---

> ## Challenge Advisor: Update & Finalize Your Project Overview
>
> > 💡 **These grey text instructions are just for you, the team's Challenge Advisor; please delete them once you have completed the steps below.**
>
> We've pre-populated this Challenge Project Overview page — which is what will be shared with your Break Through Tech student team in August — using the details from your submission form. In order for your project to be finalized and assigned to a team, please:
>
> 1. **Send us your GitHub username** so we can add you as a Collaborator to this repo, which will enable you to make edits. If you don't have a username, you can create a free account [here](https://github.com/signup). Once you are ready to share your username, simply reply to the email that sent you to this repo. Once we receive your GitHub username, you will get an email inviting you to join this repo as a Collaborator and can begin making edits. 
> 2. **Review all sections below** and update or expand any content as needed, making sure to address the SME Feedback in the section immediately below. Look for square brackets to find the places below that require additional inputs from you (e.g., "About [Company / Org Name]").
> 3. **Add your dataset** to the [data folder](data) in this repo.
> 4. **Close the Issue assigned to you in this repo** to let us know that you have made your edits and the overview page is ready for final review. You can do this by going to the _Issues_ tab in the top left section of the menu above, add a comment that says "CA review complete", and click the button to Close the Issue. 
>
> If you're unfamiliar with how to edit a page like this in GitHub, check out [this tutorial](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/handson/edit-readme.html) for a quick overview (start with step 2 and only edit this page), and [this guide](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/markdown.html) on how to use Markdown to compose text. 
> 
> ---
>
> ### 🔍 SME Feedback from the BTT Evaluation Team
>
> *Please address the following by editing this page:*
>
> - See advisor feedback section below for detailed technical adjustments.
> - [Additional feedback item]
> - [Additional feedback item]
>
> ---
>

---

# Multi-Document Deal Comparison & Consistency Agent

**Company / Org:** PIMCO  
**Challenge Advisor:** N/A  
**Program:** Break Through Tech AI Studio - Fall 2026

---

## 🏢 About PIMCO

PIMCO is a global investment management firm, specializing in fixed income and alternative investments, with a strong focus on providing innovative solutions to institutional and individual investors. Our team is dedicated to leveraging advanced technologies to enhance investment strategies and drive value.

---

## 🎯 The Challenge

### Project Summary
Build a multi-document reasoning agent using LangChain and LangGraph that ingests two or more publicly available ABS deal documents (e.g., two prospectuses from the same issuer across different vintages, or a term sheet vs. a final indenture), cross-references them across predefined comparison dimensions, identifies inconsistencies, structural differences, and missing terms, and produces a side-by-side comparison report.

### Success Criteria
The agent should accurately identify inconsistencies, structural differences, and missing terms between documents, acting like a senior analyst performing a redline review. It should produce a side-by-side comparison report and score the materiality of differences (Critical, Notable, Minor).

### Project Milestones

Use these milestones to guide your work. Your team will create a **GitHub Projects board** to track tasks within each milestone.

| Month     | Milestone                     | Key Activities                                                |
|-----------|-------------------------------|--------------------------------------------------------------|
| **September** | Data Understanding            | Explore dataset, handle missing values, document findings    |
| **October**   | Model Development             | Train baseline model, experiment with approaches, iterate    |
| **November**  | Evaluation & Presentation     | Finalize model, prepare presentation, document results       |

> **Note for the team:** Please create a GitHub Projects board in this repository to break these milestones into weekly tasks. Go to the **Projects** tab → **New project** → Choose **Board** → Add columns for each month.

---

## 📊 Dataset

**Name and Source:** Publicly available ABS deal documents from SEC EDGAR (424B filings)  
**Format:** PDF  
**Size:** under 1GB  
**Location:** [Link to dataset or instructions for accessing it]

### Key Details
- Publicly available ABS deal documents from SEC EDGAR (424B filings), including multiple vintages from issuers such as Toyota, Verizon, and Sallie Mae.
- [Any known limitations or preprocessing needed]
- [Link to data dictionary or documentation, if available]

---

## 🛠️ Suggested Approach

**ML Problem Type:** NLP  

**Recommended Libraries:**
- LangChain
- LangGraph
- OpenAI (LLM + embeddings)
- FAISS (faiss-cpu)
- pdfplumber
- sec-edgar-downloader
- Pydantic
- Pandas
- Plotly
- Streamlit
- fpdf2

**Evaluation Metrics:**
- Accuracy in identifying discrepancies, materiality scoring of differences.

---

## 📚 Resources to Get Started

The following resources will help your team understand the problem space and potential technical approaches for this project:

**Background Reading:**
- [Link to an article or blog post about the problem domain]
- [Link to an industry report or case study]

**Technical Tutorials:**
- [Link to a free tutorial on the ML technique(s) involved]
- [Link to documentation for a key library or tool]

**Code Examples:**
- [Link to a relevant GitHub repo]
- [Link to a sample implementation or starter code]

**Other:**
- [Links to any additional resources — e.g., papers, videos, podcasts, etc.]

*Feel free to explore beyond these, and share anything interesting you find with me!*

---

## 🤝 How We'll Work Together

**Check-ins:** During our biweekly 60-min AI Studio Lab Section meeting block (2nd and 4th week of every month)  
**Communication:** Slack (Break Through Tech workspace)  
**Response time:** Within 48 hours on weekdays  

**Recommended Tools:**
- **Coding:** Google Colab, VS Code
- **Collaboration:** GitHub, Notion
- **Virtual Meetings:** Zoom, Google Meet

---

## 🚀 Getting Started

1. **Review this overview document** and note any questions for our first meeting
2. **Begin reviewing the dataset** using the link above
3. **Read the GitHub Projects documentation** [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)

I'm excited to work with you!

---

## ❓ Questions?

Please bring any questions to our first meeting during the week of August 24th (Break Through Tech's Bridge to Studio - Session B).


---

## 📋 BTT Internal Evaluation Notes
*(This section is for BTT staff only — remove before sharing with students)*

| Check | Status | Notes |
|-------|--------|-------|
| Python Compatibility | GREEN | The tech stack is heavily based on Python libraries (LangChain, Pandas, etc.), ensuring compatibility with the student skill set. |
| Data Readiness | GREEN | The data consists of publicly available ABS deal documents and is estimated at under 1GB, indicating it is manageable and ready to use without extensive cleaning. |
| Resource Check | GREEN | No specialized hardware or proprietary software is mentioned, making it accessible for students. |

**Student Fit Score:** 8/10  
**Technical Depth Score:** 7/10  
**Overall Recommendation:** REVISE

**Advisor Feedback Draft:**
The project leverages relevant technologies in a meaningful way, allowing students to apply both ML and software engineering principles. To enhance clarity for the fellows, it may be beneficial to provide more context on the specific comparison dimensions and to outline potential challenges concerning the reasoning agent. Lastly, ensure the expected deliverables are clearly defined and feasible within the semester timeline.

---
