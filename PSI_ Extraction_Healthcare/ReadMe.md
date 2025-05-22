## Dataset Overview

- **Dataset Name:** Appenzeller-Herzog_2020  
- **Total Records:** 3,453  
- **Source:** Systematic review on  
  *"Comparative effectiveness of common therapies for Wilson disease: A systematic review and meta-analysis of controlled studies"* (2019)

The dataset was compiled using studies identified through a systematic search centered on the keyword **"Wilson disease"**.
Each record in the dataset includes:

1. `record_id` – Unique identifier for each entry  
2. `title` – Title of the paper  
3. `abstract` – Abstract of the paper  
4. `keywords` – Relevant keywords (if available)  
5. `authors` – Author(s) of the paper  
6. `year` – Year of publication  
7. `date` – Full date of publication  
8. `doi` – Digital Object Identifier  
9. `label_included` – Final label indicating if the paper was included  
10. `label_abstract_screening` – Label after abstract-level screening  
11. `duplicate_record_id` – Reference to a duplicate entry, if applicable


## Goal

The goal of this project is to **train a model capable of automatically selecting relevant papers** from a collection of academic articles. This can support systematic reviewers by accelerating the screening process in evidence synthesis workflows.
