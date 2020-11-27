---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "DAN+: Danish Nested Named Entities and Lexical Normalization"
authors: ["Barbara Plank", "Kristian Nørgaard Jensen", "Rob van der Goot"]
date: 2020-12-10
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-27T16:33:14+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 28th International Conference on Computational Linguistics"
publication_short: "COLING 2020"

abstract: "This paper introduces DAN+, a multi-domain resource for nested named entities (NEs) and lexical normalization for Danish, a less-resourced language. We empirically assess three strategies to model the two-layer NE annotations, cross-lingual cross-domain transfer from German versus in-language annotation, language-specific versus multilingual BERT, and the effect of lexical normalization on Danish NE. Our results show that the most robust strategy is multi-task learning which is rivaled by multi-label decoding, transfer is successful also for zero-shot, and in-language BERT and lexical normalization works the best on the least canonical data. However, our results also show that out-of-domain remains challenging, while performance on news plateaus quickly. This highlights the importance of cross-domain evaluation of cross-lingual transfer."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code: "https://github.com/bplank/DaNplus"
url_dataset:
url_poster: "poster.pdf"
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
