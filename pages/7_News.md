---
layout: page
title: News
feature-img: "assets/img/news/news-banner.jpg"
position: 3
tags: [Page]
---

<style>
    header#main {
        position: relative;
        overflow: hidden;
        background-image: none !important;
    }

    header#main::before {
        content: "";
        position: absolute;
        inset: -8px;
        background: url('/assets/img/news/news-banner.jpg') center/cover no-repeat;
        filter: blur(1px);
        transform: scale(1.00);
        z-index: 0;
    }

    header#main .title-padder {
        position: relative;
        z-index: 1;
    }

    .news-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
        gap: 20px;
        align-items: stretch;
    }

    .news-item {
        display: flex;
        flex-direction: column;
        height: 100%;
        border: 1px solid #ddd;
        border-radius: 8px;
        overflow: hidden;
        text-align: left;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        transition: transform 0.2s ease-in-out, box-shadow 0.2s ease-in-out;
    }

    .news-item:hover {
        transform: translateY(-3px);
        box-shadow: 0 8px 18px rgba(0, 0, 0, 0.12);
    }

    .news-image {
        width: 100%;
        height: 200px;
        object-fit: cover;
    }

    .news-content {
        display: flex;
        flex-direction: column;
        flex: 1;
        padding: 15px;
    }

    .news-title {
        font-size: 18px;
        font-weight: bold;
        margin: 10px 0;
    }

    .news-date {
        font-size: 12px;
        color: #888;
        margin-bottom: 10px;
    }

    .news-description {
        font-size: 14px;
        line-height: 1.5;
        margin-bottom: 0;
    }
</style>

# News

<div class="news-container">
    <div class="news-item">
        <a href="/news/workshop-2026.html">
            <img src="/assets/img/workshop/WorkshopMain.png" alt="Workshop 2026 poster" class="news-image">
        </a>
        <div class="news-content">
            <a href="/news/workshop-2026.html" class="news-title">EXALT Workshop 2026 Announced</a>
            <div class="news-date">March 2026</div>
            <div class="news-description">
                We are pleased to announce the workshop "Learning Spatio-Temporal Climate Extremes" on May 27, 2026 at Universite catholique de Louvain. Click to see the invited speakers, confirmed titles, and registration details.
            </div>
        </div>
    </div>

    <div class="news-item">
        <a href="/news/eva2025.html">
            <img src="/assets/img/news/EVA_images.png" alt="EVA 2025 event photo" class="news-image">
        </a>
        <div class="news-content">
            <a href="/news/eva2025.html" class="news-title">EVA 2025: EXALT Project Participation</a>
            <div class="news-date">July 2025</div>
            <div class="news-description">
                Several EXALT team members presented talks and a poster at the EVA 2025 conference. Click to read more.
            </div>
        </div>
    </div>

    <div class="news-item">
        <a href="https://dailyscience.be/05/02/2025/evenements-climatiques-extremes-anticiper-linattendu/" target="_blank">
            <img src="/assets/img/news/severe_weather.jpg" alt="Extreme weather event" class="news-image">
        </a>
        <div class="news-content">
            <a href="https://dailyscience.be/05/02/2025/evenements-climatiques-extremes-anticiper-linattendu/" target="_blank" class="news-title">
                Extreme Climate Events: Anticipating the Unexpected
            </a>
            <div class="news-date">February 5, 2025</div>
            <div class="news-description">
                The EXALT project, led by Prof. Anna Kiriliouk, is featured in <em>Daily Science</em> for its groundbreaking work on modeling extreme climate events using extreme value theory. Combining statistics and climatology, the project aims to improve prediction and attribution of rare events such as floods, heatwaves, and Antarctic ice melt.
            </div>
        </div>
    </div>

    <div class="news-item">
        <a href="/news/news1.html">
            <img src="/assets/img/news/ValPred.jpg" alt="VALPRED workshop" class="news-image">
        </a>
        <div class="news-content">
            <a href="/news/news1.html" class="news-title">VALPRED Workshop in Aussois</a>
            <div class="news-date">December 16, 2024</div>
            <div class="news-description">
                Professor Segers and a PhD student attended the VALPRED workshop in Aussois, focused on forecasting validation and related topics. Click to read more.
            </div>
        </div>
    </div>

    <div class="news-item">
        <a href="/news/news2.html">
            <img src="/assets/img/news/Robet_Paulus_award.png" alt="Robert Paulus receiving award" class="news-image">
        </a>
        <div class="news-content">
            <a href="/news/news2.html" class="news-title">Robert Paulus Wins GeoSpatial Award 2024</a>
            <div class="news-date">December 12, 2024</div>
            <div class="news-description">
                Robert Paulus received the prestigious GeoSpatial Award 2024 for his master thesis on spatio-temporal modeling and crisis sensibility analysis using social media data. Click to read more.
            </div>
        </div>
    </div>

    <div class="news-item">
        <a href="/assets/pdfs/Omalius%20d%C3%A9cembre%202024-7.pdf" target="_blank">
            <img src="/assets/img/news/omalius_decembre_2024.png" alt="Omalius Magazine featuring EXALT project" class="news-image">
        </a>
        <div class="news-content">
            <a href="/assets/pdfs/Omalius%20d%C3%A9cembre%202024-7.pdf" target="_blank" class="news-title">Anna Kiriliouk's Research Featured in Omalius Magazine</a>
            <div class="news-date">December 2024</div>
            <div class="news-description">
                Anna Kiriliouk's research and the EXALT project have been featured in Omalius, the magazine of the University of Namur.
            </div>
        </div>
    </div>
</div>
