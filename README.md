#  Business Statistics Mock Examination Portal

A fully functional, single-file web application designed to replicate a real-life Computer Based Test (CBT) environment for the **MAHE (Manipal Academy of Higher Education) Directorate of Online Education - First Semester PGCP/MSc Business Analytics**.

This portal allows faculty to upload question papers (PDF/DOCX/TXT), automatically parse them, and generate infinite uniquely shuffled mock exams for students with real-time auto-grading and analytics.

---

## 🌟 Key Features

### ‍🎓 For Students
- **🔐 Secure Login:** College ID and Password authentication.
- **📋 Real Exam Environment:** Full-screen CBT layout with a running timer and auto-submit.
- **🔀 Smart Shuffling:** Every attempt generates a completely new paper. Questions and options (A/B/C/D) are randomly shuffled from the master bank.
- **📝 Two-Part Exam:** Part A (MCQ/MSQ) locks upon submission, unlocking Part B (Descriptive).
- ** Navigation Palette:** Mark for review, clear response, and track answered/unanswered questions.
- **🛡️ Anti-Cheat:** Right-click, copy/paste, and developer tools (F12) are disabled during the exam.
- **🏆 Instant Results:** Detailed scorecard with section-wise performance, segment-wise analysis, and attempt history.
- **🖨️ Printable Scorecard:** Generate a clean, printable PDF-ready scorecard.

### 👨🏫 For Admins (Faculty)
- **📊 Live Dashboard:** View total attempts, unique students, average scores, and top performers.
- **👁️ Answer Review:** Click any submission to see the student's exact answers vs. the correct answers/model answers.
- **📎 Smart File Upload:** Drag & drop **PDF, DOCX, or TXT** files. The system automatically extracts questions, options, and answers using pattern matching.
- **📥 Bulk Import:** Import hundreds of questions at once using a simple text format or JSON.
- **📈 Analytics:** Identify the "Most Difficult Questions" based on student accuracy.
- **📤 Export Data:** Download all student submissions and scores as a CSV spreadsheet.

---

## 🚀 Deployment (GitHub Pages)

This project is a **single static HTML file**. You can host it for free in less than 2 minutes:

1. Create a new Public Repository on GitHub.
2. Upload the `index.html` file to the repository.
3. Go to **Settings** > **Pages**.
4. Under "Source", select **Branch: `main`** and **Folder: `/ (root)`**.
5. Click **Save**. Your exam portal will be live at `https://<your-username>.github.io/<repo-name>/`.

---

## 🔑 Default Credentials

| Role | College ID | Password |
| :--- | :--- | :--- |
| **Student** | `STU001` | `pass123` |
| **Admin** | `ADMIN` | `admin123` |

*(Note: You can add more students in the Admin Panel or directly in the code's `DEFAULT_USERS` object).*

---

## 📚 Pre-loaded Content

The portal comes pre-loaded with a comprehensive question bank based on the official MAHE Business Statistics syllabus:

- **Segment 1:** Descriptive Statistics (Central tendency, variation, data types)
- **Segment 2:** Probability and Uncertainty (Addition/multiplication theorem, Bayes' theorem)
- **Segment 3:** Probability Distributions (Binomial, Normal, Poisson, Exponential)
- **Segment 4:** Sampling and Estimation (CLT, Confidence intervals)
- **Segment 5:** Hypothesis Testing (Null/alternative, Type I/II errors, z-test, t-test)
- **Segment 6:** Correlation & Regression Analysis (Karl Pearson, SLR, R-square)

---

## 📎 How to Upload Question Papers (Admin Guide)

The portal features a smart parser that can read your existing model papers.

1. Login as **ADMIN**.
2. Go to the **📎 Upload PDF/Docs** tab.
3. Drag and drop your Question Paper (PDF or DOCX).
4. Select the document type (Auto-detect, MCQ, MSQ, Descriptive, or Syllabus).
5. The system will extract the text and show a **Preview**.
6. Review the extracted questions, assign them to the correct segments, and click **✅ Import All**.

*💡 **Pro Tip:** For 100% accuracy, use the **📥 Bulk Import** tab and paste questions in this simple format:*
```text
Q: What is the range that the values in a normal distribution can take?
A: Lesser than 0
B: Greater than 0
C: −∞ to +∞
D: −1 to 1
ANS: C
SEG: 3
