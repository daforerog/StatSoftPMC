Statistical Software Detector for PubMed Central Articles
This R Shiny application scans full-text open-access articles from PubMed Central (PMC) for mentions of common statistical software packages. It uses regex-based pattern detection to identify both the software name and, when possible, the version used in each article.

Features
Input PMCIDs (with or without the "PMC" prefix) for batch analysis (up to 20 at a time)

Automatically fetches full-text XML content via the tidypmc package

Uses regular expressions to detect statistical software mentions

Summarizes results visually and in a detailed data table

Displays real-time processing logs and error messages

Supported Statistical Software
The app currently detects the following software:

R, SPSS, SAS, Stata

Python and its libraries: NumPy, Pandas, scikit-learn, Matplotlib, etc.

MATLAB, Minitab, JMP, GraphPad Prism

Jamovi, JASP, RevMan

Installation & Requirements
R Packages
Ensure the following R packages are installed:


install.packages(c(
  "shiny", "shinyjs", "tidypmc", "xml2", "dplyr", 
  "DT", "stringr", "purrr", "ggplot2"
))

Running the App
Save the code in a file named app.R or split it into ui.R and server.R. Then run:

shiny::runApp("path_to_app_directory")

Or if the app is saved in a single file:
source("app.R")

Usage Instructions
Input PMCIDs (e.g., PMC1234567 or just 1234567) separated by commas or line breaks.

Click "Analyze Articles".

View the summary statistics, detailed results table, and software frequency chart.

Click "Clear Results" to reset the app.

Only open-access articles can be analyzed due to API limitations.

Output Example:
Total Articles Analyzed
Full Text Availability
Detected Software
Processing Time
Software Frequency Chart

Limitations
Articles must be open-access in PMC.

Detection is based on regular expressions and may miss or falsely detect software in rare edge cases.

License
MIT License

Credits:
Vibe Coder: Diego A. Forero, MD, PhD, 2025
Initial R Code Generation: Gemini (Google); R Code Refinement: Claude (Anthropic) 2025

Reference:
Forero DA, Nieminen P. Reporting of Biostatistical Software in Different Study Types in Health and Biomedical Sciences Research: An AI-Powered Approach. Submitted.

