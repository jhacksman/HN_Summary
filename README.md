# HN_Summary

This repository contains daily summaries of the top 10 articles from Hacker News, formatted for a podcast script. Each day's summaries are stored in a folder named with the current date (YYYY_MM_DD). The folder contains two documents: one for the podcast description with links to each Hacker News article, and one for the script.

## Repository Structure

- `YYYY_MM_DD/`
  - `podcast_description.md`: Contains the podcast episode description with links to each of the 10 articles reviewed.
  - `script.md`: Contains the podcast script with summaries and comments for each article.

## Instructions to Re-run the Job

To generate new summaries for subsequent days, follow these steps:

1. Navigate to the Hacker News website and identify the top 10 articles.
2. Summarize the top 10 articles from Hacker News, including key points and notable comments.
3. Create podcast script segments for each article, incorporating the summaries and comments.
4. Create a folder for the current date (YYYY_MM_DD) in the repository.
5. Write the podcast episode description, including links to each of the 10 articles reviewed.
6. Compile the script and episode description into separate documents and place them in the folder for the current date.
7. Commit and push the changes to the repository.

## Prompt to Re-run the Job

To re-run this job and generate new summaries for a future date, use the following prompt:

```
You are crafting a podcast script based on the top 10 articles from Hacker News, with a focus on summarizing the articles and comments in a CoT format, starting from the 10th most popular article and working up to the 1st. Additionally, you are preparing a separate document with the podcast episode description and links to each of the 10 articles reviewed. The user has also requested the creation of a GitHub repository named HN_Summary with a folder for the current date containing two documents: one for the podcast description with links to each Hacker News article, and one for the script.
```

## Example

For example, to generate summaries for July 5, 2024, create a folder named `2024_07_05` and follow the steps outlined above to create the podcast description and script documents.

## Contact

If you have any questions or need further assistance, please contact the repository maintainer.
