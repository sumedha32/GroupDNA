# GroupDNA — WhatsApp Group Chat Analytics

## Project Overview

GroupDNA is a Python-based project that analyzes WhatsApp group conversations to understand messaging activity, participation patterns, frequently used words, and communication behavior.

The dataset covers the period from 1 April 2024 to 30 May 2024.

## Objectives

- Parse WhatsApp chat messages from a text file.
- Calculate message counts for each participant.
- Identify the busiest day and hour.
- Create a 6 × 24 hourly activity heatmap using NumPy.
- Identify frequently used words.
- Estimate response times and analyze silent days.
- Assign rule-based personality archetypes.
- Generate a final report summarizing the results.

## Technologies Used

- Python
- NumPy
- datetime module
- Lists, dictionaries, sets, loops, and functions
- Google Colab

## Dataset Summary

The analysis identified 3,174 parsed messages from six participants, along with 32 media entries, 15 deleted-message entries, and four system lines.

## Main Features

1. **Chat Parser:** Extracts timestamps, participant names, and message content.
2. **Group Overview:** Summarizes total messages and participant activity.
3. **Activity Analysis:** Identifies the busiest day and hour.
4. **Hourly Heatmap:** Represents participant activity across 24 hours.
5. **Word Frequency:** Counts commonly used words after basic text cleaning.
6. **Response and Silence Analysis:** Estimates response intervals and measures silent days.
7. **Personality Archetypes:** Uses rule-based thresholds to assign labels based on message patterns.
8. **Final Report:** Presents the main findings in a readable format.

## How to Run

1. Open the notebook in Google Colab.
2. Upload the `hostel_bois.txt` dataset.
3. Confirm the dataset filename matches the path used in the code.
4. Run all notebook cells from top to bottom.
5. Review the generated analyses and final report.

## Limitations

Response-time estimates may not represent direct replies. Personality archetypes are simplified labels based on messaging patterns, not definitive personality assessments. Basic word-frequency analysis may not capture context, slang, or spelling variations.

## Conclusion

GroupDNA demonstrates how Python fundamentals and NumPy can be used to analyze chat activity, identify communication patterns, and summarize group behavior.

## AI Assistance Disclosure

AI assistance was used for guidance with code structure, debugging, and documentation. The code and analysis should be reviewed and understood by the project author.
