# DoiHunter

**DoiHunter** is a Python package that helps you download research papers using DOIs or paper titles through Sci-Hub. Whether you're conducting research or need specific papers quickly, DoiHunter simplifies the process by automating downloads.

## Features

- **Batch Download**: Download multiple research papers in one go using a list of DOIs or titles.
- **DOI to PDF**: Automatically fetches papers from Sci-Hub using the provided DOI.
- **Title to DOI**: Retrieves DOIs using paper titles through the CrossRef API and downloads the corresponding papers.
- **Custom File Naming**: Automatically names files based on paper titles for easy identification.
- **Error Handling**: Logs failed downloads and provides detailed summaries after processing.

## Installation

1. First, ensure you have Python installed on your system.
2. Install the `doi_hunter` package using pip:

```bash
pip install doi_hunter
````

## Setup & Usage

### Step 1: Create a Directory and Paper Title List
-Create a directory with any name.
- Inside that directory, create a file called paper_titles.txt.
- This file should contain a list of paper titles or DOIs, each on a new line.

Example content for paper_titles.txt:
-
AI Ethics: Balancing Innovation with Privacy and Security in the Digital Age
10.1002/er.6529
Prediction of daily global solar radiation using different machine learning algorithms: Evaluation and comparison

