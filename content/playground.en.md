---
title: "How to use handy Hugo features" # Title of the blog post.
date: 2025-01-29T14:17:59+01:00 # Date of post creation.
description: "Article description." # Description used for search engine.
featured: false # Sets if post is a featured post, making appear on the home page side bar.
# pinFeatured: true
draft: true # Sets whether to render this page. Draft of true will not be rendered.
toc: false # Controls if a table of contents should be generated for first-level links automatically.
menu: main
usePageBundles: false # Set to true to group assets like images in the same folder as this post.
featureImage: "/images/building.png" # Sets featured image on blog post.
featureImageAlt: 'Description of image' # Alternative text for featured image.
featureImageCap: 'This is the featured image.' # Caption (optional).
thumbnail: "/images/dollar.png" # Sets thumbnail image appearing inside card on homepage.
#shareImage: "/images/path/share.png" # Designate a separate image for social media sharing.
codeMaxLines: 10 # Override global value for how many lines within a code block before auto-collapsing.
codeLineNumbers: false # Override global value for showing of line numbers within code block.
figurePositionShow: true # Override global value for showing the figure label.
categories: ["Hugo"]
tags: ["Hugo"]
series: "Housekeeping"
# comment: false # Disable comment if false.
---

**Code**
```python {hl_lines=[3]}
import datetime

today = datetime.today()
```

**Notices**
{{% notice info "Info!" %}}
Mind you!
{{% /notice %}}

