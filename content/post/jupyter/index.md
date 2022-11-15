---
title: Display Jupyter Notebooks with Academic
subtitle: Learn how to blog in Academic using Jupyter notebooks
summary: Learn how to blog in Academic using Jupyter notebooks
authors:
  - admin
tags: []
categories: []
projects: []
date: '2019-02-05T00:00:00Z'
lastMod: '2019-09-05T00:00:00Z'
image:
  caption: ''
  focal_point: ''
---

<!--Insert Python Code Block-->
```python
from IPython.core.display import Image
Image('https://www.python.org/static/community_logos/python-logo-master-v3-TM-flattened.png')
```
<!--Display image located in <current_folder>/index_1_0.png -->
![png](./index_1_0.png)

## Create or upload a Jupyter notebook
<!-- Text in `` are colored with programming red-->
Run the following commands in your Terminal, substituting `<MY-WEBSITE-FOLDER>` and `<SHORT-POST-TITLE>` with the file path to your Academic website folder and a short title for your blog post (use hyphens instead of spaces), respectively:

<!--Insert bash code-->
```bash
mkdir -p <MY-WEBSITE-FOLDER>/content/post/<SHORT-POST-TITLE>/
cd <MY-WEBSITE-FOLDER>/content/post/<SHORT-POST-TITLE>/
jupyter lab index.ipynb
```

<!--Insert Yaml code-->
```
---
title: My post's title
date: 2019-09-01

# Put any other Academic metadata here...
---
```
