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
    <a href="/news/news1.html">
        <img src="/assets/img/news/news1.jpg" alt="News Image 1" class="news-image">
    </a>
    <div class="news-content">
        <a href="/news/news1.html" class="news-title">Exciting Discovery in Climate Research</a>
        <div class="news-date">December 20, 2024</div>
        <div class="news-description">
            Our team has made a breakthrough in understanding climate variability. Click to read more about the implications for future studies.
        </div>
    </div>
</div>

<div class="news-item">
    <a href="/news/news2.html">
        <img src="/assets/img/news/news2.jpg" alt="News Image 2" class="news-image">
    </a>
    <div class="news-content">
        <a href="/news/news2.html" class="news-title">Workshop on Extreme Value Analysis</a>
        <div class="news-date">November 15, 2024</div>
        <div class="news-description">
            We hosted a successful workshop on extreme value analysis with renowned speakers. Click to read the details.
        </div>
    </div>
</div>

<div class="news-item">
    <a href="/news/news3.html">
        <img src="/assets/img/news/news3.jpg" alt="News Image 3" class="news-image">
    </a>
    <div class="news-content">
        <a href="/news/news3.html" class="news-title">Collaboration with Local Universities</a>
        <div class="news-date">October 10, 2024</div>
        <div class="news-description">
            Partnering with local institutions, we aim to foster innovation in climate science. Click to read more.
        </div>
    </div>
</div>

</div>
