---
title: Custom Functions
date: '2025-02-11'
format: hugo-md
output: html_document
---


# Custom EDA Functions Documentation

This page explains the purpose and usage of custom functions developed for COVID-19 exploratory data analysis in the United States.

## 1. Data Preparation Functions

### Import Necessary Libraries:

<details class="code-fold">
<summary>Code</summary>

``` r
library(tidyverse)
```

</details>

### `renameState()`

**Purpose:** Standardizes state column naming across datasets

**Parameters:**
- `df`: Input dataframe

**Description:**  
Renames any column containing "state" in its name to "state". Ensures consistent column naming across different datasets.
