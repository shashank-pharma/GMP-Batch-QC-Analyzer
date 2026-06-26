# GMP-Batch-QC-Analyzer

A Python-based Quality Control (QC) dashboard for analyzing assay results of pharmaceutical manufacturing batches. The project compares assay values against specification limits and visualizes batch compliance using color-coded charts.

---

# Project Overview

Quality Control is a critical part of pharmaceutical manufacturing. Every production batch must be evaluated to ensure it meets predefined quality specifications before release.

This project demonstrates how Python can be used to analyze assay results, identify batches outside specification limits, and generate visual summaries that support quality review.

---

# Features

### Batch Data Analysis

* Import and organize batch assay data.
* Compare assay values with specification limits.
* Identify compliant and non-compliant batches.
* Generate batch-wise QC summaries.

### Visualization

* Color-coded batch comparison chart.
* Upper specification limit (USL) indicator.
* Lower specification limit (LSL) indicator.
* Easy-to-read batch labels and assay values.

### Reporting

* Display assay results for each manufacturing batch.
* Support quick visual assessment of batch quality.
* Save generated plots for documentation or reporting.

---

# Technologies Used

* Python
* Pandas
* Matplotlib
* NumPy

---

# Workflow

### Step 1 — Load Batch Data

Import assay results for multiple manufacturing batches.

### Step 2 — Data Processing

* Store batch information.
* Organize assay values.
* Compare results with specification limits.

### Step 3 — Compliance Check

Evaluate each batch against predefined assay acceptance criteria.

### Step 4 — Visualization

Generate a color-coded bar chart showing:

* Batch ID
* Assay (%)
* Upper Specification Limit
* Lower Specification Limit

---

# Example Output

The dashboard displays:

* Individual assay values for each batch.
* Specification limits (Upper and Lower).
* Color-coded batch status for quick interpretation.

This helps visualize whether manufacturing batches remain within acceptable GMP quality specifications.

---

# Learning Outcomes

Through this project, I explored:

* Working with pharmaceutical QC datasets.
* Data organization using Pandas.
* Comparing analytical results against specification limits.
* Building simple quality control dashboards.
* Data visualization using Matplotlib.
* Applying Python concepts to pharmaceutical quality analysis.

---

# Future Improvements

* Read batch data directly from Excel.
* Automatic Pass/Fail classification.
* Batch trend analysis across multiple manufacturing campaigns.
* Statistical summaries (mean, standard deviation, RSD).
* Generate PDF QC reports.
* Interactive dashboard using Streamlit.

---

# Disclaimer

This project uses sample data created for learning purposes and is intended to demonstrate Python applications in pharmaceutical Quality Control. It should not be used for actual GMP decision-making or product release activities.

---

# Author

**Shashank Limje**

Regulatory Affairs Student | Python for Pharma & Healthcare Analytics | Continuous Learner
