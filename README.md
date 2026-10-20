# SurfaceGuard AI: Industrial Surface Anomaly Segmentation (tentative title)

**Course:** Deep Learning & Generative AI Project (BSDA2001P), IIT Madras BS Data Science
**Term:** T3 2026
**Name:** Aman Sharma
**Roll No / ID:** 23f2003437

## Problem
Pixel-level segmentation of surface anomalies in industrial images across four
categories (defect_a to defect_d). The Kaggle metric combines Foreground Dice (70%),
a False Positive score (20%) and Empty Prediction Accuracy (10%). Predictions are
submitted as column-major run-length-encoded (RLE) masks.

## Links
- Kaggle competition: SurfaceGuard AI (https://www.kaggle.com/t/498bacc37b6d416e9dc1995899b3fa61)
- Kaggle notebook: DL-23f2003437-notebook-t32026
- W&B project: 23f2003437-t32026

## Repository structure
- notebooks/: milestone and final notebooks (EDA, training, inference)
- src/: train.py, inference.py, utils.py
- reports/: milestone and final reports (PDF)
- models/: small checkpoints / pointers (large weights live on Kaggle Hub)
- requirements.txt
- README.md

## Git workflow
- main always holds the latest stable version.
- One branch per milestone: milestone-1 ... milestone-5. Branches are never deleted.
- Milestone work is committed on its branch, then merged into main.

## Milestone status
| Milestone | Branch | Status |
|---|---|---|
| M0 Setup | main | in progress |
| M1 Data understanding and metrics | milestone-1 | pending |
| M2 Segmentation pipeline and first submission | milestone-2 | pending |
| M3 Transfer learning | milestone-3 | pending |
| M4 Training improvements | milestone-4 | pending |
| M5 Post-processing and ensembling | milestone-5 | pending |

## Setup
Run: pip install -r requirements.txt
