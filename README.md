[README.md](https://github.com/user-attachments/files/34035057/README.md)
# COS30045 Data Visualisation – Demonstration 2

A single-page website that combines Exercises 4.1, 4.3–4.7, 5 and 6 (SVG shapes, D3 bar chart, multiple chart types, and interactive charts).

**Student:** Pham Huy Phuc

## Contents

| Section | Exercise | What it shows |
|---|---|---|
| SVG house and garden | 4.1 | SVG primitives, coordinate system, `<g>` grouping and `translate` |
| TV models by brand | 4.3 – 4.7 | D3 horizontal bar chart: CSV loading, data binding, `scaleLinear` / `scaleBand`, labels |
| Three charts | 5 | Vertical bar chart with axes, line chart (points + area), donut chart |
| Interactive charts | 6 | Histogram with filters, tooltip and re-scaled axis; scatterplot with filter and tooltip |

## Project structure

```
index.html
css/style.css
js/main.js              (Ex 4.3–4.7)
js/ex5-bar-chart.js     (Ex 5)
js/ex5-line-chart.js    (Ex 5)
js/ex5-donut-chart.js   (Ex 5)
js/ex6.js               (Ex 6 + extensions)
data/                   (CSV files)
images/                 (annotated SVG image, DOM screenshot)
```

## Run locally

D3 loads the CSV files with `d3.csv()`, so the page must be served over HTTP.
Open the folder in VS Code and use the **Live Server** extension (do not open `index.html` by double-clicking).

## Technologies

HTML, CSS, JavaScript, D3.js v7, Tailwind CSS (CDN).

## Generative AI declaration

Generative AI (Claude, by Anthropic) was used in this project, mainly for **JavaScript, SVG and D3 code**, plus page layout and styling. A full, exercise-by-exercise declaration is in **`AI_Declaration`** (submitted as a separate document). Summary:

| Exercise | How AI was used |
|---|---|
| 4.1 SVG house | Drafted the SVG scene (primitives, grouped windows with `<g>` and `translate`) and the annotated coordinate image; I customised, tested and took the DOM screenshot |
| 4.3 – 4.7 Bar chart | Generated starter D3 code for CSV loading, data binding, scales and labels; I reviewed it and explored how each part works |
| 5 Multi-chart | Helped combine the three charts into one page, wrap each script to avoid name clashes, and restyle the charts |
| 6 Interactivity | Helped integrate the code and wrote the extensions (size filter, histogram tooltip, scatterplot filter, axis re-scaling) |
| Landing page | Generated the page design (HTML, Tailwind and custom CSS) and helped with Git/GitHub and hosting problems |

All AI-generated code was reviewed, tested in the browser and can be explained by me.
