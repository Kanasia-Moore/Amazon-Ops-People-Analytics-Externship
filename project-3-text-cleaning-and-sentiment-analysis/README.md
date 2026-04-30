# Project 3: Text Cleaning & Sentiment Analysis

## Overview

This phase of the project focuses on transforming unstructured employee voice data into a format that can be analyzed and interpreted.

Using Python, this project explores how text preprocessing and sentiment analysis can be used to extract meaningful insights from employee feedback collected from platforms like Glassdoor and YouTube.

The goal is to move beyond raw feedback and begin quantifying employee sentiment while preserving the context behind employee experiences.

---

## Objectives

- Clean and standardize unstructured text data
- Remove noise such as punctuation, stop words, and inconsistencies
- Apply sentiment analysis to employee feedback
- Visualize sentiment trends and patterns
- Translate results into actionable insights

---

## Key Questions

- How can unstructured employee feedback be transformed into usable data?
- What patterns emerge once the data is cleaned and standardized?
- How does sentiment vary across different sources of employee voice data?
- What are the limitations of sentiment analysis when applied to real-world feedback?

---

## Methods

- Text preprocessing, including lowercasing and punctuation removal
- Stop word removal using NLTK
- Custom text cleaning functions
- Sentiment scoring using TextBlob
- Data structuring with Pandas
- Visualization of sentiment distribution and trends

---

## Deliverable(s)

This section will store polished project outputs connected to this phase of the analysis.

- [Findings Summary PDF](./deliverables/project-3-findings-summary.pdf) *(to be added)*

---

## Findings Summary

Analysis of employee voice data from Glassdoor and YouTube revealed clear differences in how employees communicate their experiences.

Glassdoor reviews tend to be more structured and constructive, often outlining pros, cons, and actionable feedback. This makes it easier to identify patterns and assess sentiment with clarity.

In contrast, YouTube content is more emotionally driven and less structured. While this makes themes slightly harder to extract, it provides deeper context into day-to-day operations, work pace, and work-life balance challenges.

Together, these platforms complement each other — Glassdoor offering clarity and direction, while YouTube provides depth and lived experience.

For a more detailed summary, see the [Findings Summary PDF](./deliverables/project-3-findings-summary.pdf).

---

## Insights & Interpretation

- Sentiment analysis provides direction, but not full context
- Emotional language can skew sentiment scoring if not interpreted carefully
- Structured feedback from Glassdoor is easier to quantify
- Unstructured content from YouTube provides richer storytelling and operational context
- Combining both sources creates a more complete view of employee experience

---

## Reflection

This project reinforced the importance of data preparation in the analytical process.

Cleaning and structuring text data plays a critical role in making sure insights accurately reflect the underlying message. Even small inconsistencies in text can affect the reliability of results.

It also highlighted that while tools like TextBlob are useful, they should be used alongside contextual understanding rather than treated as a standalone source of truth.

---

## Areas for Improvement

- Improve text cleaning to better handle context-specific language
- Explore more advanced sentiment models for higher accuracy
- Incorporate topic modeling to better group themes
- Strengthen the connection between sentiment results and operational recommendations

---

## Tools Used

- Python
- Pandas
- NLTK
- TextBlob

---

## Status

This project section is in progress. The findings summary PDF will be added to the `deliverables` folder once finalized.
