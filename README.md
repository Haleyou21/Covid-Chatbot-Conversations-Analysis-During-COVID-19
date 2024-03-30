# Covid Chatbot Conversations Analysis During COVID-19

## Introduction

The COVID-19 pandemic, the most significant public health emergency of the century, was accompanied by an unprecedented "infodemic." The World Health Organization (WHO) and other agencies highlighted the challenges of misinformation and disinformation spreading through digital channels. This project aims to analyze conversations with VIRA (Vaccine Information Resource Assistant), a chatbot developed by Johns Hopkins University and IBM, to understand public sentiments, concerns, and the spread of misinformation regarding COVID-19 vaccines.

## Background

VIRA serves as a digital platform for disseminating evidence-based information about COVID-19 in English and Spanish. Monitoring public attitudes through such chatbots offers a novel perspective on infoveillance, providing early signals of emerging misinformation.

## Methods

### Data Collection

We analyzed 45,877 user chat utterances collected between July 2021 and May 2023 from VIRA, focusing on English and Spanish conversations. These utterances reflect public questions and concerns about COVID-19, excluding system responses by VIRA.

### Analysis

- **Topic Modeling:** Utilizing BERTopic, an unsupervised NLP technique, we identified key topics within the conversations.
- **Sentiment Analysis:** A subset of over 3,200 queries was analyzed to gauge public sentiment, employing GPT-3's text-davinci-003 model for English and Spanish inputs.

## Results

Our analysis revealed significant insights into public sentiment and the prevalent misinformation themes during the pandemic. The volume of conversations and the emerging topics indicated public interest in vaccine information and safety, as well as trust in health institutions.

### Chat Volume Over Time

An initial surge in chatbot usage was observed with the rollout of COVID-19 vaccines, followed by fluctuations corresponding to major pandemic events.

### Topic Analysis

BERTopic modeling identified over 400 topic areas, with a substantial portion related to vaccine information and safety, and community and trust.

### Sentiment Analysis

The sentiment analysis showed a majority of neutral responses, with a notable proportion expressing negative sentiments, reflecting public concerns and mistrust.
