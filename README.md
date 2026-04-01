# Billy Cruz - Resume Templates

## Live Preview Links
- **PCA Resume:** https://yg4president.github.io/billy-cruz-resumes/pca.html
- **Transporter Resume:** https://yg4president.github.io/billy-cruz-resumes/transporter.html

## How to Edit (No coding needed)

### Option A: Edit on GitHub (easiest)
1. Go to https://github.com/YG4PRESIDENT/billy-cruz-resumes
2. Click on `pca.html` or `transporter.html`
3. Click the pencil icon (edit) in the top right
4. Change any text you see — dates, skills, bullet points, job titles
5. Click "Commit changes" when done
6. Your live link updates automatically in ~60 seconds

### Option B: Edit on your computer
1. Download the `.html` file
2. Right-click > "Open With" > any text editor (TextEdit, Notepad, VS Code)
3. Find the text you want to change and edit it directly
4. Save the file
5. Double-click the file to preview in your browser
6. Print > Save as PDF when ready

### What you CAN safely change (just edit the text between the tags):
- **Your name, phone, email, location** — near the top after `<body>`
- **Summary text** — the paragraph after "Professional Summary"
- **Skills** — each `<li>skill name here</li>` line. Delete a line to remove a skill, copy one to add
- **Job titles** — text inside `<span class="entry-title">JOB TITLE</span>`
- **Dates** — text inside `<span class="entry-date">Jan 2025 - May 2025</span>`
- **Company/org** — text inside `<div class="entry-org">Company | City, TX</div>`
- **Bullet points** — text inside `<li>your bullet point here</li>`. Delete the whole `<li>...</li>` line to remove
- **Certifications** — same as bullet points
- **Education** — text inside the `edu-name` and `edu-detail` spans

### What NOT to touch:
- Everything above `</head>` (that's the styling — don't change it)
- The HTML tags themselves (the `<div>`, `<span>`, `<ul>`, `<li>` parts)
- Class names like `class="entry-title"`

### To add a new job entry, copy this block and paste it where you want:
```html
<div class="entry">
  <div class="entry-header">
    <span class="entry-title">Job Title Here</span>
    <span class="entry-date">Mon YYYY - Mon YYYY</span>
  </div>
  <div class="entry-org">Company Name | City, TX</div>
  <ul>
    <li>First bullet point describing what you did.</li>
    <li>Second bullet point describing what you did.</li>
  </ul>
</div>
```

### To print as PDF:
1. Open the HTML file in Chrome
2. Press Cmd+P (Mac) or Ctrl+P (Windows)
3. Click "More settings"
4. UNCHECK "Headers and footers"
5. CHECK "Background graphics"
6. Set destination to "Save as PDF"
7. Save

### To tailor for a new job:
1. Duplicate `pca.html` or `transporter.html` and rename it (e.g., `newjob.html`)
2. Change the tagline, summary, and skills to match the new job posting
3. Reorder or rewrite bullets to emphasize what the new job cares about
4. Print as PDF and submit
