# Sample GitHub page created from Jupyter Notebook using Quarto

This is just an example of a static web page created from a collection
of Jupyter notebooks to be hosted on GitHub pages. See [index file](index.md).


---

# Getting started to do this locally

### Install requirements:

```bash
pip install -r requirements.txt
```

or, if you prefer

### Clone my environment:

```bash
conda env create -f environment.yml
```

You can change `name` from "data-science" to anything you like in the `environment.yml` file
if you already have an Anaconda environment with this name or you simply want to use a different name for whatever reason.

---

# Step By Step instructions

After you have all requirements or environment up and running you should

### 1. Create your notebooks

However many you want. Use an old project. Just get some notebooks.

### 2. Create a "_quarto.yml" file
Addapt the structure of [this file](_quarto.yml) according to your notebooks.

### 3. Create an "index.md" fiel
It will be your page's index.
Addapt the structure of [this file](index.md) according to your notebooks.

### 4. install Quarto (if you haven't already done it)
```bash
pip install quarto-cli
```

### 5. Render the site locally
```bash
quarto render
```

### 7. Commit
```bash
git add .
git commit -m "some message"
git push origin
```

### 6. Publish the site
```bash
quarto publish gh-pages
```

---
