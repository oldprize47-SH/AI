# Introduction to AI Coursework

This repository holds weekly notebooks by Sangheon Park from an introductory AI course. Each notebook contains the exercise, code and any output saved during the course. Some cells and companion files were provided as teaching material.

The root notebooks are organised by week, including [Week 2](21800275_SangheonPark_Week2.ipynb), [Week 6](21800275_SangheonPark_Week6.ipynb) [Week 11](21800275_SangheonPark_Week11.ipynb) and [Week 13](21800275_SangheonPark_Week13.ipynb). The [Exercise](Exercise) directory contains companion versions, which may overlap with the root files.

Week 13 was added from the local coursework copy on 28 September 2026. Its stored outputs and execution counters were cleared; its code has not been rerun.

## Project goal

Learn how preprocessing, features and models turn raw data into interpretable analysis through separate notebook exercises.

![Project goal: ai-coursework](docs/goals/project-focus-v1.png)

AI-generated concept illustration. Device appearance, interface layout and example graphics are illustrative, not project photographs or measured results.

## Where it could be used

These exercises can support early experiments with data preparation, classification and clustering: inspect a small dataset, choose a baseline method and examine its output before building a larger application. Their main use is learning and testing an analysis workflow. A model for a new dataset would need its own training and evaluation; the notebooks do not establish a ready-to-deploy general-purpose system.

## At a glance

![AI coursework: notebook workflow](docs/flowcharts/ai.png)

Each row describes an independent exercise or workflow; the repository is not one connected application. [SVG](docs/flowcharts/ai.svg)

## How to read the notebooks

The notebooks are coursework records rather than a single application with one entry point. Open a week, read the exercise and imports, then follow the cells in their original order. Variables created in an earlier cell may be required later, so a cell copied out of context may not run by itself. The `Exercise` copies should not be counted as separate projects simply because the filenames overlap.

[Week 13](21800275_SangheonPark_Week13.ipynb) includes text-processing and classification code using scikit-learn and NLTK. It is a useful recent entry point for seeing how text is turned into features before a classifier is applied. Check its file references and library imports before attempting a full run; the presence of a notebook does not guarantee that every external dataset or language resource is included.

## Running your own copy

Use a Jupyter-compatible environment and inspect the selected notebook's imports and data paths first. Install the packages required by that notebook, start a clean kernel and execute the cells in order. There is no validated repository-wide environment lock or one-command test for every week.

Saved cell output can help explain what a course exercise did, but it can outlive the code or environment that produced it. Week 13 intentionally has no stored output, so there are no newly reproduced scores to report for that addition. The archive distinguishes coursework submissions, supplied exercise material and later portfolio maintenance.

You can read the notebooks directly on GitHub. Their version-4 notebook structure was checked on 28 September 2026, but the cells were not rerun. Saved outputs reflect the original environment and should not be treated as newly reproduced results.

[Original repository](https://github.com/oldprize47/Introduction_AI). Original history and attribution are retained.
