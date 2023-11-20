# Academic-Article-Organizer-and-Analyzer

### Project Description
The "Academic-Article-Organizer-and-Analyzer" is an R-based automation tool designed for efficient management and analysis of academic research articles. It specializes in organizing, renaming, and processing large volumes of PDF documents from academic databases or personal collections. Key functions include extracting article metadata, standardizing file naming conventions, and conducting preliminary text analyses on abstracts for classification.

### Features
- **File Organization**: Automated renaming and restructuring of PDF article files.
- **Data Extraction**: Retrieves article lists with details like titles from specified directories.
- **String Manipulation**: Utilizes regular expressions and string functions to clean and format article titles.
- **Citation Analysis**: Extracts and processes bibliographic data, especially abstracts, from Mendeley for analysis.

### Requirements
Required R installation and libraries:
- RPostgreSQL, dplyr, dbplyr, data.table, lubridate, reshape2, stringr, tidyverse, readxl, knitr, ggplot2, udpipe, bib2df, lexRankr, xlsx.

### Usage
#### Setup
Load all necessary R packages and ensure correct file paths.

#### File Renaming and Organization
Execute script sections to rename and organize PDF files, involving cleaning file names and standardizing formats.

#### Citation Analysis
Process bibliographic data from `.bib` files, focusing on fields like authors, titles, and abstracts. Cleaned data is exported to Excel for further analysis.

### Output
- Organized PDF files with standardized names.
- Excel files with structured bibliographic data and abstracts.

### Note
Adjust script paths to match your file system and ensure your data format aligns with the script's expectations.

This tool is ideal for researchers, librarians, or data scientists managing large research paper collections, providing a structured approach to document management and analysis.
