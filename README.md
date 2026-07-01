# 🎬 IMDB Movie Analysis — Power BI Dashboard

## 📌 Overview
A 4-page interactive Power BI dashboard analyzing 999 IMDB movies to uncover trends in revenue, ratings, genres, runtime, and top-performing titles/directors. Built to help studios and analysts understand which genres, directors, and release years drive the strongest box office performance.

## ❓ Problem Statement
Which movie genres, directors, and release years generate the highest revenue, and how do factors like rating, runtime, and votes correlate with box office success?

## 📊 Dataset
- **Source:** IMDB Movies dataset (Kaggle) — *add your exact link here*
- **Size:** 999 movies across 13 genres, spanning 2006–2016
- **Key fields:** Title, Genre, Year, Runtime, Rating, Metascore, Votes, Revenue, Director

## 🛠️ Tools & Techniques
- **Power BI Desktop** — 4-page interactive dashboard design
- **Power Query** — data cleaning and transformation
- **DAX** — custom measures for genre metrics, rating bands, and top-N rankings
- **Visuals used:** bar/column charts, scatter plots, funnel chart, donut chart, ribbon/Sankey chart, KPI cards, sortable tables

## 🔑 Key Insights
- **Action dominates volume and revenue** — Action leads with ~290 movies and the highest total revenue (~35K million), roughly 5x the next closest genre
- **Animation has the highest average Metascore (70)**, despite Action having the most movies but a lower average Metascore (54)
- **2016 was the peak year** for movie releases (~290 titles) and also drove the sharpest rise in total revenue, which trended upward steadily from 2010–2016
- **Star Wars: Episode VII – The Force Awakens** was the top-grossing movie at 936.63M revenue with an 8.10 rating
- **The Dark Knight** had the highest vote count (1,791,916 votes) and one of the highest ratings (9.00) among top revenue-earners
- **J.J. Abrams** ranks as the top director by total revenue across his filmography in the dataset
- Average movie in the dataset: 6.72 rating, 113.17-minute runtime, 82.96M revenue, and a Metascore of 59
- Revenue shows a **general positive relationship with rating and votes**, though with high variance — a few high-rated outliers pull well above the trend

[LinkedIn](https://linkedin.com/in/sindhu-sri-chattu-a9005a2b4) | [GitHub](https://github.com/SindhusriChattu)
