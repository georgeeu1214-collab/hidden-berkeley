# Hidden Berkeley: HW2 starter

Create your own public website from this starter, then use a Jupyter notebook to edit the data it displays.

**Start here:** on the [HW2 template repository](https://github.com/macss-berkeley/hw2-hidden-berkeley-template), choose **Use this template → Create a new repository**. Name your copy `hidden-berkeley` and make it public. Clone your copy with GitHub Desktop and open its folder in VS Code. Follow [hw2_hidden_berkeley.ipynb](hw2_hidden_berkeley.ipynb).

## What is in this repository?

| File | What it does |
| --- | --- |
| `hw2_hidden_berkeley.ipynb` | Your instructions, data edits, and submission evidence. |
| `docs/_data/locations.csv` | The resource data. The notebook edits this file; the website reads it. |
| `docs/index.md` | The page heading, introduction, and supplied loop that displays the CSV rows. |
| `docs/_config.yml` and `docs/_layouts/default.html` | Supplied website settings and layout. |

GitHub Pages builds the website from `main` and `/docs`. After you push a changed CSV, GitHub rebuilds the page using the new data. Jupyter only edits and saves the data; it does not build the website. The `_data` folder name is required by the website builder.

## Purpose and sources

This guide is for new Berkeley students who want a quick starting list of useful places and services beyond the main campus landmarks. The first eight resources were supplied by COMPSS 211A. I added [Moffitt Library](https://www.lib.berkeley.edu/visit/moffitt) and checked its name, location, and access details on that official library page.


## Website checks

Live website: https://georgeeu1214-collab.github.io/hidden-berkeley/

I improved the existing Morrison Library entry (HB03) by adding an access note about its location in Doe Library and a link to its official page. I added Moffitt Library as a new resource. On the published site, I checked that my new heading and introduction appear, that the Morrison entry shows the updated access note, that the Moffitt entry shows all five fields (name, category, area, access note, and source link), and that both official links work. The displayed values match my CSV, and the Morrison and Moffitt links open the correct UC Berkeley Library pages.
