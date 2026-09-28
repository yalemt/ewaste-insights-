[README.md](https://github.com/user-attachments/files/32735470/README.md)
# Ghana e-waste photos: what the data says

Interactive dashboard for the **GIZ Data Lab E-Waste Hackathon, Track 2: Data Visualization & Insights Exploration**.

**Live dashboard:** add your link here (`https://YOUR-USERNAME.github.io/YOUR-REPO/`)
**Notebook:** add your public Colab/Kaggle link here

It audits all 4,301 scrapyard photos of the open Ghana e-waste image database and analyses the labelled boxes (COCO release). The reliability of the data (label coverage, near-duplicate shots, image-quality flags) is shown next to every insight.

## What is inside
- `index.html` is the whole dashboard (one self-contained file; charts load the Plotly library from a public CDN, so an internet connection is needed).
- Seven charts, example photos drawn with their boxes (filterable by category), flagged photos, method, limits and a data dictionary.

## Key numbers
4,301 photos audited (100% readable) · 689 photos with boxes (16%) · 1,682 boxes · ACs largest category (16%), top three 46% · cooling equipment 42% of boxes · 2% near-duplicate shots · 8% flagged for review · 2,428 photos carry GPS metadata.

## Data sources
| repository | use |
|---|---|
| `GIZ/E-Waste-Database` | all photos (audit) |
| `GIZ/e-waste-dataset-COCO-labels` | boxes and categories |
| `GIZ/e-waste-dataset-yolo-labels` | cross-check only |

Data by GIZ Data Lab, licensed **CC-BY-4.0**. Please cite the repositories above.

## Limits
Labels cover about 16% of the photos, so category shares describe that subset. Quality flags and near-duplicate detection are heuristics, not ground truth. Capture time is read from file names. Boxes count visible items, not weight or material.

## Team
Yalem Tilahun and team members.
