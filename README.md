# Gendered-Tropes-in-Movies

An analysis of gendered language patterns in film scripts using natural language processing and log odds ratios to identify how male and female characters are portrayed differently through action words and descriptions.
Inspiration: This project was inspired by The Pudding's "She Giggles, He Gallops" article, which analyzed gender tropes across 2,000 film scripts.

This analysis examines bigrams (two-word sequences) in film scripts to discover which action words are more strongly associated with "she" vs "he" in screen directions. For example:

Words associated with "she": giggles, sobs, smiles, gasps
Words associated with "he": shoots, gallops, grins, kills

The analysis uses log odds ratios to quantify these associations, revealing underlying gender stereotypes in how screenwriters portray male and female characters.

Bigram Extraction: Identifies pronoun + action word pairs (e.g., "she smiles", "he runs")
Log Odds Ratio Analysis: Quantifies which words are more strongly associated with each gender
Statistical Smoothing: Implements Laplace smoothing to handle rare words
Visualization: Creates bar charts showing the most gendered words
Stop Word Filtering: Removes common words to focus on meaningful actions

Credits
Original Research: Julia Silge, Russell Samora, Amber Thomas, Hanah Anderson (The Pudding)
