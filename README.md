# AIE314 Tutorial 1: Preprocessing Unstructured Data for LLM Applications

## Team Members
- Abdallah lasheen (ID: 22101137)
- Nourhan Abdelhamid (ID: 22100665)
- Noura adel (ID: 22100933)
- Remonda rezq (ID: 22101332)
- Raghad Mohamed (ID: 

## Project Description
This project focuses on building a robust preprocessing pipeline to handle and normalize unstructured data from multiple formats (PDF, DOCX, and Excel) for use in Large Language Model (LLM) applications and RAG systems. 

The pipeline processes data covering the following areas:
* **Computer Science Fundamentals**: Concepts including computation, information, and automation.
* **Algorithms & Data Structures**: Procedures for problem-solving and organizing data using arrays, linked lists, trees, and graphs.
* **Modern Technologies**: Insights into Programming Languages (Python, Java, Go) , Operating Systems (Windows, Linux, macOS) , and Artificial Intelligence.
* **Student Records**: Structured information for 15 students, including academic data for students like Liam Anderson (GPA: 3.85) and Emma Davis (GPA: 4.0).



## Project Structure
- `output/`: Contains the normalized JSON files for each document.
    - `computer_science_overview_docx.json`
    - `computer_science_overview_pdf.json`
    - `ExcelSample_xlsx.json`
- `preprocessing.ipynb`: The Python script containing the extraction and normalization logic.
- `README.md`: Project documentation.

## How to Run the Code
1. **Prerequisites**: Ensure you have Python installed.
2. **Install Dependencies**:
   ```bash
   pip install pandas python-docx PyPDF2 openpyxl
