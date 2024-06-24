# FTK-digital-forensics
# Image-Bit-Stream File Analysis Using AccessData FTK

## Overview

This project involves using AccessData FTK (Forensic Toolkit) to perform forensic analysis on an image-bit-stream file. The objective is to acquire the image file and systematically document the investigation process and findings.

## Prerequisites

Before starting, ensure you have the following:

- AccessData FTK installed on your system.
- The image-bit-stream file to be analyzed.

## Steps for Analysis

### Step 1: Acquire the Image File

1. **Launch AccessData FTK**: Open AccessData FTK on your computer.
2. **Create a New Case**:
    - Go to `File` > `New Case`.
    - Enter the case information (e.g., Case Number, Examiner Name, Description).
    - Specify the case folder location and click `Next`.
3. **Add the Image File**:
    - In the `Evidence` tab, click `Add Evidence`.
    - Select `Image File` as the evidence type.
    - Browse and select the image-bit-stream file.
    - Click `Next` and follow the prompts to add the image file to the case.

### Step 2: Initial Analysis

1. **File System Overview**:
    - Once the image is added, FTK will display the file system structure.
    - Explore the directories and files within the image.
2. **Metadata Examination**:
    - Right-click on files to view properties and metadata.
    - Note details such as creation dates, modification dates, and file types.

### Step 3: Content Analysis

1. **Keyword Search**:
    - Use the `Search` feature to perform keyword searches within the image.
    - Document any significant findings related to the keywords.
2. **File Carving**:
    - Use FTK's file carving capabilities to recover deleted files.
    - Analyze recovered files for relevant information.
3. **Email Analysis**:
    - If the image contains email files, use the `Email` tab to analyze email content.
    - Document any significant email findings.

### Step 4: Reporting

1. **Generate Reports**:
    - Use the `Report` feature in FTK to generate a comprehensive report of your findings.
    - Customize the report to include relevant sections such as file listings, keyword hits, and metadata analysis.
2. **Document Findings**:
    - Write a detailed report documenting your investigation process, findings, and conclusions.
    - Include screenshots and descriptions of significant artifacts.

## Deliverables

- **Case Report**: A detailed report documenting the investigation process and findings.
- **FTK Report**: The generated report from AccessData FTK.

## Conclusion

This project aims to provide hands-on experience with forensic analysis using AccessData FTK. By following the steps outlined above, you will gain valuable insights into the forensic investigation process and the capabilities of FTK.

---

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

