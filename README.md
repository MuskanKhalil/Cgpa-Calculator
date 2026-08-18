# CGPA & Percentage Calculator

A clean, single-page calculator for tracking semester grades — supports both the 4.0 GPA scale and percentage-based grading, since not every university uses the same system.

**[Live Demo](#)** ← replace with your GitHub Pages link once it's live

## Why I built this

Manually calculating CGPA every semester (adding up credit hours × grade points on a calculator or spreadsheet) got tedious, so I built a small tool to do it instantly — and made it flexible enough for universities that grade by percentage instead of GPA.

## Features

- Toggle between **GPA (4.0 scale)** and **Percentage** grading systems
- Add or remove any number of courses
- Enter credit hours (or weight %) and grade for each course
- Real-time calculation as you type — no submit button needed
- Instant remark based on your result (e.g. "Dean's list territory", "Solid standing")
- Fully responsive — works on mobile
- Clear all / reset with one click

## Built with

- HTML5
- CSS3 (custom design, no frameworks)
- Vanilla JavaScript (no libraries)

## How it works

```
GPA = Σ(grade points × credit hours) ÷ Σ(credit hours)
Percentage = Σ(marks × weight) ÷ Σ(weight)
```

## Run it locally

Just clone the repo and open `index.html` in any browser — no build step, no dependencies.

```bash
git clone https://github.com/YOUR-USERNAME/cgpa-calculator.git
cd cgpa-calculator
```

Then open `index.html` in your browser.

## License

Free to use and modify.
