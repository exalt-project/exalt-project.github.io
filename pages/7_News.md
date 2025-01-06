---
layout: page
title: News
feature-img: "assets/img/pexels/news.jpeg"
position: 4
tags: [Page]
---

<style>
    .news-container {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        gap: 15px;
    }

    .news-item {
        display: flex;
        flex-direction: column;
        width: calc(33% - 20px); /* 3 items per row with spacing */
        margin: 15px 0;
        border: 1px solid #ddd;
        border-radius: 5px;
        overflow: hidden;
        text-align: left;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        transition: transform 0.2s ease-in-out;
    }

    .news-item:hover {
        transform: scale(1.05);
    }

    .news-image {
        width: 100%;
        height: 200px;
        object-fit: cover;
    }

    .news-content {
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
        margin-bottom: 10px;
    }

    @media (max-width: 768px) {
        .news-item {
            width: calc(50% - 20px); /* 2 items per row on smaller screens */
        }
    }

    @media (max-width: 480px) {
        .news-item {
            width: 100%; /* 1 item per row on very small screens */
        }
    }
</style>

# News

<div class="news-container">
    
<div class="news-item">
    <a href="/news/news2.html">
        <img src="/assets/img/news/Robet_Paulus_award.png" alt="Robert Paulus receiving award" class="news-image">
    </a>
    <div class="news-content">
        <a href="/news/news2.html" class="news-title">Robert Paulus Wins GeoSpatial Award 2024</a>
        <div class="news-date">December 16, 2024</div>
        <div class="news-description">
            Robert Paulus received the prestigious GeoSpatial Award 2024 for his master thesis on spatio-temporal modeling and crisis sensibility analysis using social media data. Click to read more.
        </div>
    </div>
</div>

<div class="news-item">
    <a href="/news/news1.html">
        <img src="/assets/img/news/ValPred.jpg" alt="News Image 1" class="news-image">
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
    <a href="/assets/pdf/Omalius_décembre_2024-7.pdf" target="_blank">
        <img src="/assets/img/news/omalius_decembre_2024.png" alt="Omalius Magazine featuring EXALT project" class="news-image">
    </a>
    <div class="news-content">
        <a href="/assets/pdfs/Omalius décembre 2024-7.pdf" target="_blank" class="news-title">Anna Kiriliouk’s Research Featured in Omalius Magazine</a>
        <div class="news-date">December 20, 2024</div>
        <div class="news-description">
            Anna Kiriliouk’s research and the EXALT project have been featured in Omalius, the magazine of the University of Namur. <a href="/assets/pdf/Omalius décembre 2024-7.pdf" target="_blank">Click here to read the article</a>.
        </div>
    </div>
</div>

</div>


</div>
