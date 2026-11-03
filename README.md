# Province Athens report for lodges

A lightweight static web form for preparing and saving lodge visit reports for the Provincial Grand Lodge of Athens.

## What this project does

This project provides a browser-based report template for recording:

- lodge identity and visit date
- visiting officer details
- attendance and participation data
- ritual and operational observations
- financial and administrative notes
- brief conclusions and recommendations
- a digital signature area

The resulting form can be printed or saved as a PDF and emailed as a draft.

## Files

- `index.html` – the full HTML, CSS, and JavaScript application

## How to use

1. Open `index.html` in a browser, or serve the folder locally.
2. Fill in the required lodge visit details.
3. Use the signature pad to add the representative signature.
4. Click "Αποθήκευση προσχεδίου" to save the report on the current device.
5. Click "Εκτύπωση / PDF" to print or export to PDF.
6. Click "Προετοιμασία email" to open a pre-filled email draft.

## Run locally

From the project folder:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## GitHub Pages

This site is suitable for GitHub Pages deployment as a static website.

1. Push the repository to GitHub.
2. Open the repository's Settings.
3. Go to Pages.
4. Select the branch and folder for deployment.
5. Save the configuration.

## Notes

- Data is stored locally in the browser using `localStorage`.
- The form is intended for use on a personal or trusted device.
- No backend or database is required.

## License

No explicit license has been provided for this repository.
