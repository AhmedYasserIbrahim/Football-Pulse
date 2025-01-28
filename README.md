# Football Pulse – Automated News Posting System

## Overview

**Football Pulse** is an automated system built on **Make.com** that scrapes football news, extracts key information, generates engaging articles or tweets, and posts them on various social media platforms. This automation eliminates the need for manual content creation, allowing seamless and consistent news updates.

The final step of this system is **automatically posting news updates** on platforms such as **X (Twitter), Facebook, Reddit, and Medium**.

## How It Works

This project consists of multiple modules that work together to fetch, process, and post news:

1. **Web Scraping (ScrapingBee)**  
   - Captures football news articles from [LiveScore](https://www.livescore.com/en/news/) using **ScrapingBee**.  
   - A full-page screenshot is taken for processing.

2. **Text Extraction (EdenAI OCR)**  
   - Extracts text from the screenshot using **EdenAI OCR**, leveraging services like Google Vision and Amazon Textract.

3. **Text Generation (EdenAI NLP)**  
   - Generates a short news summary or tweet using AI-based **text generation models** such as OpenAI and Anthropic.

4. **Automated Posting (Make.com Modules)**  
   - Posts the generated content on **Blogger**, **X (Twitter), Facebook, Reddit, Medium, and WordPress** automatically.

## How to import the scenario on your account

1. **Create an account on Make.com.**
2. **Download the provided JSON file** [here](https://github.com/AhmedYasserIbrahim/Football-Pulse/blob/main/blueprint%20(9).json).
3. **Import the provided JSON file** into Make.com to restore the scenario as shown below:
   
   ![image](https://github.com/user-attachments/assets/bef915a0-72ee-4d5f-ba7f-c068f1a9142e)

   ![image](https://github.com/user-attachments/assets/408478e2-da03-4616-9e81-489e27b3553b)


5. **Set up API keys** for ScrapingBee and EdenAI.  
6. **Run the automation** to fetch the latest news, process it, and post it on your chosen platforms.  
7. **Customize the workflow** to target additional social media sites.

## Project Files

- **blueprint.json** (Included in this repository) – The complete workflow that can be imported into Make.com.

## Event Information

This project was developed as part of the **Automated Systems Workshop**, hosted by:

- **Ahmed Yasser & Syed Fawaz**  
- Special thanks to **Nadine (President), Jana (Vice President), and Miss Jalila (Club Head).**

---

## Thank you and feel free to send us questions or feedback!
