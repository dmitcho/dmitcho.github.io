---
layout: post
title: "TEMPLATE FOR POST"
subtitle: "A catchy, brief summary that appears under the main title."
date: 2025-12-14 21:00:00 +0800 # (Correct for Manila!)
author: Your Name/Alias # Optional, but good for clarity
categories: [Technology, Tutorial] # Use relevant categories
tags: [jekyll, chirpy, blogging, template] # Use relevant tags
pagemap:
  image: /assets/img/my-featured-image.jpg # Optional: A custom image for search result snippets
pin: false # Set to true to pin the post to the top of the homepage
mermaid: true # Set to true to enable Mermaid diagrams in this post
---

# 🌟 Introduction

Start with a compelling introduction that hooks the reader and clearly states what the post is about. Keep it brief and focused.

---

## 🎯 Section 1: Setting the Stage (The Main Idea)

Use clear, descriptive headings (`##`) to break up your content. This improves readability significantly.

Chirpy supports standard **Markdown formatting**, including:

* **Bold text**
* *Italic text*
* `Inline code snippets`
* [Links to external resources](https://github.com/cotes2020/jekyll-theme-chirpy)

### Sub-Section A: Step-by-Step

Use ordered lists for procedures or step-by-step guides.

1. This is the first step.
2. This is the second, most important step.
3. And the final action to complete the process.

> 💡 **Note/Tip Block:**
> Use the blockquote syntax (`>`) to highlight important notes, tips, or quotes. Chirpy will often style this with a distinct background color, making it visually stand out.

## 💻 Section 2: Code and Diagrams

Showcasing code is essential for technical posts.

### Code Block with Syntax Highlighting

```python
# Use the language identifier after the backticks for proper highlighting
def calculate_area(radius):
    """Calculates the area of a circle."""
    import math
    return math.pi * radius**2

print(calculate_area(5))
