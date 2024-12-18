# **Multilingual Narrative Characterization and Extraction**

This repository contains the implementation for the **SemEval Task on Multilingual Characterization and Extraction of Narratives from Online News**. The task aims to identify manipulative or misleading content in news articles across two domains: **Climate Change** and **Ukraine-Russia War**. It is divided into the following subtasks:

## **Subtasks**
1. **Entity Framing (Subtask 1)**  
   Classify entities into main roles (e.g., Protagonist, Antagonist) and fine-grained roles using a predefined taxonomy.  
   Code available in the [`entity-framing`](https://github.com/Taleef7/semeval-2025-task10-PFWT10/tree/entity-framing) branch.

2. **Narrative Classification (Subtask 2)**  
   Assign appropriate narrative and subnarrative labels to articles based on their content.  
   Code available in the [`narrative-classification`](https://github.com/Taleef7/semeval-2025-task10-PFWT10/tree/narrative-classification) branch.

3. **Narrative Extraction (Subtask 3)**  
   Generate a concise, grounded explanation for the dominant narrative and subnarrative in an article.  
   Code available in the [`narrative-extraction`](https://github.com/Taleef7/semeval-2025-task10-PFWT10/tree/narrative-extraction) branch.

## **How to Use**
- Clone the repository:  
  ```bash
  git clone https://github.com/Taleef7/semeval-2025-task10-PFWT10.git

## **Acknowledgements**
This project was developed as part of the SemEval 2025 Task 10. For more details on the task, visit the [`SemEval Task 10 official website`](https://propaganda.math.unipd.it/semeval2025task10/).

Special thanks to [`Professor Jonathan Rusert`](https://www.linkedin.com/in/jon-rusert/) for his assistance and guidance with all subtasks.