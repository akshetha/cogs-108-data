# Macroeconomic Indicators and Media Sentiment as a Prediction Measure for Tech Layoffs

## Abstract

This study investigates how macroeconomic conditions and media sentiment together predict the scale of tech-sector layoffs, with a particular focus on whether AI-focused companies respond differently from traditional tech firms. Between 2020 and 2026, the tech industry experienced dramatic swings in employment, including a COVID-era hiring boom followed by a wave of mass layoffs starting in 2022. Pursuing our curiosity about AI's role in reshaping the labor market, we build on Shekhar and Saurombe's (2026) work on "algorithmic anxiety" by quantifying surface-level media sentiment via VADER scores and testing whether AI companies are more sensitive to shifts in public perception than to macroeconomic signals, compared to traditional tech.

To investigate this, we merged three datasets: a layoff events dataset (1,590 cleaned events from 2020–2026), VADER-based news sentiment scores from 306 articles, and monthly Federal Funds Rate data from the Federal Reserve. After cleaning for missingness and joining on date-based keys, we conducted exploratory data analysis and a preliminary multiple regression predicting log-transformed layoff count using FFR, sentiment score, and an AI-sector indicator on a merged sample of 73 events.

Our EDA revealed that layoff activity peaked sharply in early 2023 for both sectors simultaneously, suggesting macroeconomic shocks affect AI and traditional tech companies at the same time rather than independently. News sentiment averaged slightly negative (mean VADER score: -0.047), consistent with underlying anxiety about job displacement. Our preliminary regression on the merged sample (n=73) found that FFR and sentiment explain limited variance in layoff scale, and the AI-sector interaction term was not strongly significant, though the small merged sample constrains our conclusions.

## Team

Akshetha Vishnu Prasad Dhivya · Annika Gangrade · Yitong Sun · William Wu · Giselle Villalobos
