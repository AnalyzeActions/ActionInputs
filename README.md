# ActionInputs

## Introduction

This repository contains the CSV files used as inputs to the ActionTraction and
WorkKnow Programs. Specifically, the majority of these CSV files contain the
list of the top 200 most critical projects, across multiple programming
languages, as reported by the
[ossf/criticality_score](https://github.com/ossf/criticality_score) tool.
Although the aforementioned project provides a
[download](https://commondatastorage.googleapis.com/ossf-criticality-score/index.html)
of these CSV files, this repository exists so as to support the replication of
experiments conducted with the
[ActionTraction](https://github.com/AnalyzeActions/ActionTraction) and
[WorkKnow](https://github.com/AnalyzeActions/WorkKnow) tools. Please note that
these CSV files were not produced by a tool available in this repository or by a
contributor to this organization. For an updated version of the tool used to
create these CSV files or the most recent version of these files as shared by
the OSSF, please refer to their respective links.

## Data Format

Although the CSV files in this repository contain a multiple columns of data
about the top-200 critical projects for various languages, the
[ActionTraction](https://github.com/AnalyzeActions/ActionTraction) and
[WorkKnow](https://github.com/AnalyzeActions/WorkKnow) tools only focus on the
`name` and `url` columns in the data files. For instance, here are the contents
of the `analyze_actions_projects.csv` file:

```csv
name,url
AnalyzeActions,https://github.com/AnalyzeActions/ActionTraction
WorkKnow,https://github.com/AnalyzeActions/WorkKnow
```
