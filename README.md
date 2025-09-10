# Arico Viejo Workshop on Scanning Probe Magnetism

This repository hosts the **public website** for the *Arico Viejo Workshop on Scanning Probe Magnetism* (26–30 January 2026).

👉 Published site (via GitHub Pages): https://<username>.github.io/<repository>/

---

## How to update content

### 1. Edit the website
The website is a single file: `index.html`.

- To update **attendees**: search for `<ul class="attendees">` and add/remove `<li>` entries.
- To update the **program**: search for `<!-- === PROGRAM BY DAY === -->` and edit times, speakers, and sessions.
- To update **abstracts**: search for `<section id="abstracts">` and duplicate a `<details>` block. Replace the `summary` (title + speaker) and the text inside `<p>`.

### 2. Commit changes
1. In GitHub, open `index.html` and click the ✏️ pencil (edit).
2. Make edits directly in the browser.
3. Scroll down, write a short commit message, and click **Commit changes**.

### 3. Changes go live
- GitHub Pages automatically rebuilds the site in 1–2 minutes.
- Refresh the public URL to see updates.

---

## Optional: Add more files
- PDFs of abstracts or the full program can be added to the repository.  
- To link them: upload the file (e.g., `abstract_lorente.pdf`) and add a link in `index.html`, e.g.:  
  ```html
  <a href="abstract_lorente.pdf" target="_blank">Download PDF</a>
  ```

---

## Contact
For questions or edits, contact the organizers: **arico.spm.workshop@gmail.com**
