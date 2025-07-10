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
        <div class="news-date">December 12, 2024</div>
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
        <div class="news-date">December 2024</div>
        <div class="news-description">
            Anna Kiriliouk’s research and the EXALT project have been featured in Omalius, the magazine of the University of Namur.
        </div>
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
    <a href="/assets/img/news/EVA_images.png" target="_blank">
        <img src="/assets/img/news/EVA_images.png" alt="EVA 2025 event photo" class="news-image">
    </a>
    <div class="news-content">
        <a href="#" class="news-title">EVA 2025: Talks by Professors Segers, Kiriliouk, and Ragone</a>
        <div class="news-date">July 2025</div>
        <div class="news-description">
            During the EVA 2025 conference, several members of the EXALT project presented recent advances in the modeling of extremes:
            <br><br>
            <strong>Professor Johan Segers</strong> gave a talk titled <em>"Tail Calibration of Probabilistic Forecasts"</em>.<br>
            <em>Abstract:</em> Probabilistic forecasts comprehensively describe the uncertainty in the unknown future outcome, making them essential for decision making and risk management. While several methods have been introduced to evaluate probabilistic forecasts, existing evaluation techniques are ill-suited to the evaluation of tail properties of such forecasts. However, these tail properties are often of particular interest to forecast users due to the severe impacts caused by extreme outcomes. In this work, we introduce a general notion of tail calibration for probabilistic forecasts, which allows forecasters to assess the reliability of their predictions for extreme outcomes. We study the relationships between tail calibration and standard notions of forecast calibration, and discuss connections to peaks-over-threshold models in extreme value theory. Diagnostic tools are introduced and applied in a case study on European precipitation forecasts.
            <br><br>
            <strong>Professor Anna Kiriliouk</strong> presented <em>"X-vine Models for Multivariate Extremes"</em>.<br>
            <em>Abstract:</em> Regular vine sequences permit the organization of variables in a random vector along a sequence of trees. Vine-based dependence models have become greatly popular as a way to combine arbitrary bivariate copulas into higher-dimensional ones, offering flexibility, parsimony, and tractability. We use regular vine sequences to decompose and construct exponent measure densities associated with multivariate extreme value distributions. Our approach sheds new light on existing parametric extreme-value models and facilitates the construction of new ones, called X-vines. Computations proceed via recursive formulas in terms of bivariate model components. We develop simulation algorithms for X-vine multivariate Pareto distributions as well as methods for parameter estimation and model selection on the basis of threshold excesses. The methods are illustrated by Monte Carlo experiments and a case study on US flight delay data. Finally, we discuss how X-vines can be used for quantile regression in extreme regions of the covariate space, allowing for asymptotic independence between the response variable and the covariates.
            <br><br>
            <strong>Professor Francesco Ragone</strong> discussed <em>"Simulation of Extreme Events in Numerical Models with Rare Event Algorithms"</em>.<br>
            <em>Abstract:</em> The analysis of extreme events is an important area of application of numerical models in many different scientific fields. Studying these events on a robust statistical basis with complex numerical models is however computationally challenging, as very long simulations and/or very large ensembles are necessary to sample a sufficient number of events to have acceptable levels of statistical accuracy. This problem can be tackled using rare event algorithms, numerical tools designed to reduce the computational effort required to sample rare events in numerical models. These methods typically take the form of genetic algorithms, where a set of suppression and cloning rules are applied to the members of an ensemble simulation, in order to oversample trajectories leading to the events of interest. In this talk I will show recent applications of these methods to different classes of events, focusing in particular on extremes of surface temperature and sea ice cover. Finally I will discuss the relevance of these techniques for different applications, in particular for the analysis of tipping points and the validation of early warning indicators.
            <br><br>
            <strong>PhD Students</strong> from the EXALT project also presented a joint poster summarizing their ongoing work. <em>[You can add the abstract or a link to the poster here if available]</em>
        </div>
    </div>
</div>



