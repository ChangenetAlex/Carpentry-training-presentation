# 🪚 Carpentry Course Presentation Template

This repository provides a **template for Carpentry training presentations**.  
It’s designed to be reused and customized for different workshops.  
Before using it, make sure to update key information such as the **workshop image**, **date**, and **helper(s)**.

---

## 📋 What to Update

Before each workshop:
- 🖼️ **Workshop Image**: Replace the image(s) in the `img/` folder with visuals relevant to your workshop.
- 📅 **Workshop Date**: Update the date on the title slide in the presentation file.
- 🧑‍🤝‍🧑 **Helper(s)**: Update the name(s) of helpers in the presentation header or introduction slide.

---

## 📁 Repository Structure

Carpentry-training-presentation/
├── presentation.qmd # Quarto source file for slides
├── presentation.html # Rendered HTML presentation
├── img/ # Folder for images (replace as needed)
├── .gitignore # Git ignore file
└── presentation_start.Rproj # RStudio project file

---

## 🚀 How to Use This Template

1. **Clone or download** this repository:

```bash
git clone https://github.com/ChangenetAlex/Carpentry-training-presentation.git
```

2. Open the project in RStudio or VS Code with Quarto.
3. Edit presentation.qmd:

* Update the workshop date.
* Add or remove helper names.
* Replace placeholder text and images.

4. Render the presentation to HTML using:

```bash
quarto render presentation.qmd
```

The generated presentation.html will appear in your project folder, ready to share or present.


