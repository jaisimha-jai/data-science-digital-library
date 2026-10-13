# Personal Digital Lib — Personalisation Guide

## Already updated
- Student name: Vardhi Jaisimha Kumar
- Register number: 24102A030134
- Profile photo: `images/vardhi-profile.jpg`
- Home page includes CGPA and SGPA cards. Values intentionally show `Not added` until you provide verified numbers.
- Five supplied PowerPoint modules are in `modules/`.
- The portal uses Data Science module titles from the provided presentations.

## Change your CGPA and SGPA
1. Open `dashboard.html` in VS Code.
2. Search for `Academic Snapshot`.
3. In the CGPA card, change `<h3>Not added</h3>` to your CGPA, for example `<h3>8.75</h3>`.
4. In the SGPA card, change the second `<h3>Not added</h3>` to your latest SGPA. Use your actual values only.
5. Save the file and refresh the browser.

## Change your photo
Replace `images/vardhi-profile.jpg` with your new image, keeping the same filename. For best results use a JPG or PNG portrait.

## Update modules
Replace files inside `modules/` with your updated presentations, preserving filenames `Module_01.pptx` through `Module_05.pptx`, or change the corresponding `href` values in `dashboard.html` and `module1.html`.

## Later: What I've Learned
This section has not been added yet, as requested. When ready, we can add a checklist or progress cards for topics you have completed.

## Open locally
You can open `index.html` in a browser to inspect the static pages. Some browser features may work better when served through a local web server. The Python coding lab needs internet to load Pyodide and packages.
