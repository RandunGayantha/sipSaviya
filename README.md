# 🇱🇰 Sip Saviya - A/L Study Relief Portal

**Created by Sri Lankans, to help Sri Lankans.**

This is an open-source initiative to collect and share study materials (Notes, Past Papers, Short Notes) for A/L students affected by recent disasters. We need **YOUR** help to add more links to this collection.

🌐 **Website:** [View the Live Website](https://randungayantha.github.io/sipSaviya/)

---

## 🤝 How to Contribute (Step-by-Step Guide)

We store all the links in a simple text file. You do **not** need to be a programmer to help. Just follow these 6 steps.

### Step 1: Open the Data File
1. Look at the list of files at the top of this page.
2. Click on the file named **`data.json`**.

### Step 2: Click the "Edit" Button
1. Look at the top-right corner of the file content.
2. Click the **Pencil Icon** ✏️ (It says "Edit this file" when you hover over it).
   * *Note: If you are not a project owner, GitHub will create a copy for you to edit. This is normal!*

### Step 3: Scroll to the Bottom
1. Scroll down to the very end of the text.
2. You will see a square bracket `]` at the very end.
3. You must add your new notes **before** that last `]`.

### Step 4: Add the Code
Copy the code block below and paste it at the bottom of the list:

```json
  ,
  { 
    "category": "Science", 
    "subject": "Maths", 
    "title": "New Lesson Note", 
    "link": "https://drive.google.com/..." 
  }
```

> **⚠️ CRITICAL RULE:** Look at the item *above* the one you just pasted. Does it have a **comma (`,`)** at the end? If not, add a comma to the end of the previous line!

### Step 5: Fill in the Details

Change the text inside the quotes `""`.

  * **"category"**: Must be exactly one of these:
      * `"Science"` (For Maths, Bio, Chem, Physics)
      * `"Commerce"` (For Econ, BS, Acct)
      * `"Technology"` (For SFT, ET, BST, ICT)
      * `"Arts"` (For Languages, History, Geography, Media, etc.)
  * **"subject"**: The name of the subject (e.g., "Combined Maths", "Sinhala").
  * **"title"**: A short description (e.g., "2024 Model Paper").
  * **"link"**: The Google Drive link (Ensure the link is Public).

### Step 6: Submit Your Changes

1. Scroll up to the top right of the page.
2. Click the green button that says **"Commit changes..."** or **"Propose changes"**.
3. A box will appear. Write a short message (e.g., "Added Sinhala Notes").
4. Click the green button **"Propose changes"**.
5. Finally, click **"Create Pull Request"**.

🎉 **That's it!** The website admins will review your link and approve it.

---


## 💻 For Developers

This is a lightweight static site using HTML, TailwindCSS (via CDN), and Vanilla JS.

**To run locally:**

1. Clone or Download the repository.
2. Open `index.html` in your browser.


**Thank you for contributing! 🇱🇰**
