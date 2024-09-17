# Northeastern University Wireless Club: *Yagi Antenna Build* Workshop Resources
---

Welcome to the resources for the *Yagi Antenna Build* workshop presented by the Northeastern University Wireless Club (W1KBN). Below, you'll find important links and information related to our presentation and how to compile the slides yourself if you'd like.

---

### 📄 **Workshop Slides**
To view the final slides used in the workshop, visit the Google Drive link below:
```https://drive.google.com/drive/folders/1DcPeHOKzqbaV7TIICU0LNaIRyhPFN-JE?usp=drive_link```

---

### 🛠 **Build Instructions**
As a helpful guide during our workshop, please refer to the following Instructables page for step-by-step instructions on constructing the Yagi Antenna. This resource is a valuable supplement to our presentation slides:
[The Tape Measure Antenna on Instructables](https://www.instructables.com/The-Tape-Measure-Antenna/)

---

### 💻 **Compiling the Slides Yourself**
If you'd like to compile the LaTeX slides on your own, you're welcome to do so. Below are the instructions for compiling using `pdflatex` with shell escape enabled (required for fetching the Git commit hash in the footer).

#### **Requirements:**
1. TeX distribution (e.g., TeX Live, MiKTeX)
2. LaTeX packages:
   - `beamer`
   - `graphicx`
   - `hyperref`
   - `xcolor`
   - `iexec` (for Git commit hash)
   
#### **Compilation Steps:**
1. Clone this repository or download the `.tex` file.
2. Make sure you have the necessary LaTeX packages installed.
3. Run the following command to compile with shell escape enabled:
   ```bash
   pdflatex --shell-escape main.tex
   ```
   This command will allow LaTeX to execute the necessary shell commands to retrieve the current Git commit hash, which is displayed in the footer of the slides.
   
4. After compiling, you should see the `main.pdf` output file in the project directory.

---

#### **Note:**
We previously hosted the PDF directly in this repository but have since transitioned to using Google Drive to host the slides as a temporary solution. It's generally not best practice to store binary files, like PDFs, in version control systems (VCS) because they can bloat the repository and make versioning difficult. By hosting the slides on Google Drive for now, we ensure easier access for workshop participants and maintain a more efficient repository. We are actively working on finding a better and more permanent PDF-hosting solution.

---

### 📬 **Questions?**
If you have any questions or feedback, feel free to reach out to us:
- **Workshop Email:** workshops@nuwireless.org
- **Club Website:** [https://nuwireless.org](https://nuwireless.org)

---

### 🖋 **Design and Contributions**
All workshop materials, design, and this repository were created by [Muhammad Elarbi](https://melarbi.com) based on LaTeX Beamer. For any questions or further information, feel free to reach out to me at elarbi.m@northeastern.edu.
