---
layout: page
title: News
feature-img: "assets/img/pexels/news.jpg"
position: 4
tags: [Page]
---

<style>
    .news-item {
        display: inline-block;
        width: 300px;
        margin: 15px;
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
    }
</style>

# News

<div style="display: flex; flex-wrap: wrap; justify-content: space-evenly;">

<div class="news-item">
    <img src="/assets/img/news/news1.jpg" alt="News Image 1" class="news-image">
    <div class="news-content">
        <div class="news-title">Exciting Discovery in Climate Research</div>
        <div class="news-date">December 20, 2024</div>
        <div class="news-description">
            Our team has made a breakthrough in understanding climate variability. Read more about the implications for future studies.
        </div>
    </div>
</div>

<div class="news-item">
    <img src="/assets/img/news/news2.jpg" alt="News Image 2" class="news-image">
    <div class="news-content">
        <div class="news-title">Workshop on Extreme Value Analysis</div>
        <div class="news-date">November 15, 2024</div>
        <div class="news-description">
            We hosted a successful workshop on extreme value analysis with renowned speakers from around the world.
        </div>
    </div>
</div>

<div class="news-item">
    <img src="/assets/img/news/news3.jpg" alt="News Image 3" class="news-image">
    <div class="news-content">
        <div class="news-title">Collaboration with Local Universities</div>
        <div class="news-date">October 10, 2024</div>
        <div class="news-description">
            Partnering with local institutions, we aim to foster innovation in climate science.
        </div>
    </div>
</div>

</div>
