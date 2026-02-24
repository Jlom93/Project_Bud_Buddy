# Bud Buddy - Simple Strain Recommender

**Goal**  
One-page site.  
User picks up to 5 favorite strains → recommends 3 similar ones by terpenes.  
Beginner HTML/CSS/JS project. No frameworks.

**Folder**  
Project_Bud_buddy

**Files**  
- index.html  
- styles.css  
- script.js  

**Disclaimer text for page**  
Helper tool only. Not medical advice. Effects vary. Ask your doctor.

## Tasks (one at a time)

1. Create files in Project_Bud_buddy folder

2. Build basic HTML in index.html  
   - <h1>Bud Buddy</h1>  
   - Red disclaimer  
   - 5 <input> with <datalist> autocomplete  
   - <button>Find similar</button>  
   - <div id="results"></div>

3. Add strain data in script.js  
   Array of ~15 strains  
   ```js
   const strains = [
     { name: "Black Amber T32", terps: ["myrcene", "limonene", "caryophyllene"] },
     // add more
   ];

Autocomplete inputs
Use <datalist id="strainList">
Button logic
On click: get 5 strains → count shared terps → show top 3 matches
Basic CSS
Center page, style inputs/button/results
Test in browser
(Later) Deploy to GitHub Pages