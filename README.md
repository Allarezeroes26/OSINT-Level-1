# OSINT Level 1 - Foundations: Write-Up & Methodology

This repository contains my methodology and key takeaways from completing the [OSINT Level 1 - Foundations](https://www.f1ndx.com/slides/osint-level-1-foundation-1) course by F1NDX. 

> ⚠️ **Spoiler-Free Policy:** To respect the integrity of the course and its creators, this write-up **does not** contain direct answers, flags, or solutions to the case investigations. Instead, it focuses on the techniques, investigative mindset, and workflows used to solve the challenges.

---

## 🛠️ Course Objectives & Skills Covered
* **Advanced Search Operators:** Leveraging Google Dorking to find exposed documents and index leaks.
* **Metadata Extraction:** Analyzing hidden data in images and documents to locate critical tracking info.
* **SOCMINT Footprinting:** Safely pivoting through public social media data to map target footprints.
* **Structured Intelligence Gathering:** Applying a repeatable, logical workflow to build out a solid case file.

---

## 🔍 Investigation Breakdown & Methodology

### 1. Google Dorking Basics
* **The Goal:** Finding hidden web data using specific search parameters.
* **My Approach:** Instead of generic searching, I utilized operators like `site:`, `filetype:`, and `intext:` to cut through the noise. 
* **Key Takeaway:** Filtering out irrelevant domains early saves hours of manual searching.

### 2. Hidden Data Analysis
* **The Goal:** Extracting data from task files and images.
* **My Approach:** I utilized command-line and web-based metadata extraction tools to look beyond the surface of the files. I paid close attention to timestamps, camera models, and author names.
* **Key Takeaway:** Data that seems deleted or invisible on a standard preview is often completely preserved in the file's background layers.

### 3. Social Media Intelligence (SOCMINT)
* **The Goal:** Tracking public social media footprints.
* **My Approach:** I mapped out connections by identifying unique usernames, analyzing cross-platform handles, and tracing public interaction clues without directly interacting with the targets.
* **Key Takeaway:** People often reuse usernames across different platforms, creating a visible digital trail.

### 4. Case Investigation & Evidence Collection
* **The Goal:** Piecing together Evidence #1 and Evidence #2 to complete the final investigation.
* **My Workflow:** 1. **Initial Assessment:** Documented every known variable from the starting prompt.
  2. **Pivoting:** Used the metadata found in the initial files to query search engines for associated accounts.
  3. **Verification:** Double-checked dates and location details to ensure the intelligence was accurate and not a false positive.
  4. **Reporting:** Logged the intelligence logically to reach the final conclusion.

---

## 🚀 Key Tools Utilized
* **Advanced Search:** Google Advanced Operators
* **Metadata Extraction:** Exiftool / Online Metadata Viewers
* **Username Enumeration:** OSINT framework search strategies

---

## 💡 Final Reflections
This course was an excellent deep dive into the fundamentals of structured open-source intelligence. It taught me that OSINT isn't just about using fancy tools, it's about asking the right questions, maintaining a strict workflow, and knowing how to pivot when you hit a dead end.
