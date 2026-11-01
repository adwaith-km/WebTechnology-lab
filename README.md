# Web Technology Lab Record 🎓

Hey there! 👋 

Welcome to my Web Technology Lab record. I built this portal as a way to properly organize and submit all the experiments and homework assignments I completed this semester for my MCA course at Presidency University Bangalore. 

Instead of just dumping a bunch of HTML files into a folder, I wanted to design a clean, centralized hub where my professor can easily navigate through my work, view the raw code, and see how it actually looks in a browser.

## 💡 Why I Built This
Submitting lab records can get messy. I wanted a single, clean landing page that introduces who I am, what semester I'm in, and who the record is being submitted to. From there, it's super easy to jump right into the specific experiments or homeworks. 

I made sure that when you click to view a code or an output, it opens in a new tab. That way, you don't lose your place on the main list.

## ✨ What's Inside
*   **A Clean Dashboard:** A welcoming home page with all my academic details.
*   **Easy Navigation:** Separate sections for "Lab Experiments" and "Homeworks".
*   **Tidy Tables:** Everything is laid out in neat tables showing the date, serial number, and the name of the task.
*   **Code vs. Output:** For every task, you can view the actual code I wrote (styled in a cool dark-mode box) or jump straight to a screenshot of the final output.

## 🛠️ What I Used
I kept things simple and foundational, which is exactly what we're learning in this lab:
*   **HTML5** for all the structure (tables, forms, lists, frames, etc.).
*   **CSS3** for the styling, colors, and layout. 
*   I made sure to use an **External CSS** file (`style.css`) so my HTML files stay clean and easy to read.

## 📁 How the Folder is Organized
Here is a quick look at how I set up the files:

```text
📁 Web-Technology-Lab
│
├── 🏠 index.html              # The main welcome page (starts here!)
├── 📑 experiments.html        # List of all 10 Lab Experiments
├── 📑 homeworks.html          # List of all Homework assignments
├── 🎨 style.css               # The single stylesheet for the whole site
│
├── 💻 exp1-code.html          # Experiment 1 code
├── 🖼️ exp1-output.html        # Experiment 1 output screenshot
├── ... (all other experiments and homeworks)
│
└── 📁 images                  # Where I stored all the output screenshots
