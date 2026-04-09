---
layout: post
feedback: true
hide: true
title: Open Coding Society
description: Redirect to Gamified Home Pilot.
permalink: /
---


<div class="portal-container">
    <h1 class="portal-title">Select Your Path</h1>
    
    <div class="options-grid">
        <a href="{{ site.baseurl }}/home3-gamified-mvp" class="portal-card standard">
            <div class="card-content">
                <h2>World of CS</h2>
                <p>Traditional course catalog and syllabus overview.</p>
                <span class="btn-primary">View List</span>
            </div>
        </a>

        <a href="{{ site.baseurl }}/home2-gamified-mvp" class="portal-card gamified">
            <div class="card-content">
                <h2>Gamified Experience</h2>
                <p>Explore the islands of OCS in an interactive world map.</p>
                <span class="btn-glow">Enter World</span>
            </div>
        </a>
    </div>
</div>

<style>
.portal-container {
    text-align: center;
    padding: 40px 20px;
    background: #040d14;
    min-height: 80vh;
    color: white;
}

.portal-title {
    font-size: 2.5em;
    margin-bottom: 40px;
    color: #00ffcc;
    text-transform: uppercase;
    letter-spacing: 2px;
}

.options-grid {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
}

.portal-card {
    text-decoration: none !important;
    color: white;
    width: 350px;
    height: 450px;
    border-radius: 20px;
    display: flex;
    align-items: flex-end;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    overflow: hidden;
    position: relative;
    border: 2px solid #00ffcc33;
}

/* Backgrounds - replace with your actual image paths if you have them */
.standard {
    background: linear-gradient(to top, rgba(0,0,0,0.9), transparent), 
                url('https://images.unsplash.com/photo-1517694712202-14dd9538aa97?q=80&w=1000');
    background-size: cover;
}

.gamified {
    background: linear-gradient(to top, rgba(0,0,0,0.9), transparent), 
                url('{{ site.baseurl }}/images/ocs_world_map.avif');
    background-size: cover;
}

.portal-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 0 30px rgba(0, 255, 204, 0.4);
    border-color: #00ffcc;
}

.card-content {
    padding: 30px;
    text-align: left;
}

.card-content h2 {
    margin-bottom: 10px;
    font-size: 1.8em;
}

.btn-primary, .btn-glow {
    display: inline-block;
    margin-top: 15px;
    padding: 10px 20px;
    border-radius: 5px;
    background: #00ffcc;
    color: #040d14;
    font-weight: bold;
}

.btn-glow {
    box-shadow: 0 0 15px #00ffcc;
}
</style>