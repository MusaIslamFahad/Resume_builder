# 📝 Interactive Resume Builder (Terminal-based)

Create a professional resume directly from your terminal with this Python-powered **interactive resume builder**. Designed for simplicity and flexibility, this tool lets users input and manage personal details, work experience, education, skills, projects, certifications, and achievements—then generates a polished PDF resume in seconds.

---

## 🚀 Features

- 📋 **User-Friendly Terminal UI** using `prompt_toolkit`  
- ✍️ **Dynamic Resume Sections**:
  - Contact Info  
  - Work Experience  
  - Education  
  - Skills  
  - Projects  
  - Certifications  
  - Achievements  
- 📄 **Automatic PDF Generation** using `fpdf`  
- 🖨️ **Multi-line and formatted entries** for responsibilities, project descriptions, and more  
- 🔁 **Edit, Add, and Update** entries easily before exporting  
- 🧑‍💻 **Cross-platform support** (Windows, macOS, Linux)

---

## 📦 Requirements

- Python 3.x  
- [`prompt_toolkit`](https://python-prompt-toolkit.readthedocs.io/en/master/)  
- [`fpdf`](https://pyfpdf.github.io/fpdf2/)

Install dependencies using:

```bash
pip install prompt_toolkit fpdf
```
---

## 🏃 How to Run

1.  **Clone the Repository (or create the files manually):**

    If you have Git installed, you can clone the repository to your local machine:

    ```bash
    git clone [https://github.com/yourusername/resume-builder.git](https://github.com/yourusername/resume-builder.git)
    cd resume-builder
    ```

    *Replace `https://github.com/yourusername/resume-builder.git` with the actual URL of your project's GitHub repository once you've created it.*

    Alternatively, if you prefer to set up the project manually, you can create the necessary Python files (`resume_builder.py`, etc.) in a new directory and then navigate into it.

2.  **Install Dependencies:**

    ```bash
    pip install prompt_toolkit fpdf
    ```

3.  **Run the Application:**

    ```bash
    python resume_builder.py
    ```

    *(Assuming your main Python script is named `resume_builder.py`.)*


    ---

## 💻 Usage

When you run the script, you'll see an **interactive terminal interface** that guides you through building your resume. You'll be prompted to enter information for each section.

### Interactive Prompts:

The application will walk you through these sections:

* **Contact Info:** Your name, email, phone number, LinkedIn profile, GitHub link, and other relevant contact details.
* **Work Experience:** Enter your job title, company name, employment period, location, and **multi-line responsibilities** for each role. You can add as many work experiences as you need.
* **Education:** Provide details about your degree, university, graduation year, and field of study. Feel free to add multiple educational entries.
* **Skills:** Categorize your skills, such as programming languages, development tools, and soft skills.
* **Projects:** Include project titles, detailed **multi-line descriptions**, and optional links to your projects.
* **Certifications:** List the name of your certification, the issuing body, and the date it was obtained.
* **Achievements:** Highlight your notable accomplishments or awards, with support for **multi-line entries**.

### Editing and Review:

Before generating the PDF, the tool gives you full control to refine your resume:

* **Review** all the information you've entered, section by section.
* **Edit** any existing entry if you need to correct a mistake or improve the wording.
* **Add** new entries to sections like Work Experience or Education effortlessly.
* **Remove** entries that are no longer relevant to your resume.

### PDF Generation:

Once you're happy with your input, the application will automatically generate a polished **PDF resume**. It will be saved in your current directory, or you can specify a different output path.

---

## 🤝 Contributing

We love contributions! If you have ideas for new features, ways to improve the tool, or bug fixes, here's how you can help:

1.  **Fork the repository.**
2.  **Create your feature branch:** `git checkout -b feature/AmazingFeature`
3.  **Commit your changes:** `git commit -m 'Add some AmazingFeature'`
4.  **Push to the branch:** `git push origin feature/AmazingFeature`
5.  **Open a Pull Request.**

---

## ⭐ Show Your Support

If you found this project helpful and it made building your resume easier, please consider giving it a ⭐ **star on GitHub**!

Your support helps others discover this tool and encourages further development. Don't forget to **share it with your network** too!





