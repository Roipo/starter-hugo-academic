---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Designing actuation systems for animatronic figures via globally optimal discrete
  search
authors:
- Simon Huber
- Roi Poranne
- Stelian Coros
date: '2021-01-01'
doi: ""
project_name: MotorMatchingAnimatronics
# Schedule page publish date (NOT publication's date).
publishDate: '2021-08-03T23:17:27.095239Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: '2'

# Publication name and optional abbreviated publication name.
publication: '*ACM Transactions on Graphics (TOG)*'
publication_short: ""

abstract: "We present an algorithmic approach to designing animatronic figures – expressive robotic characters whose movements are driven by a large number of actuators. The input to our design system provides a high-level specification of the space of motions the character should be able to perform. The output consists of a fully functional mechatronic blueprint. We cast the design task as a search problem in a vast combinatorial space of possible solutions. To find an optimal design in this space, we propose an efficient best-first search algorithm that is guided by an admissible heuristic. The objectives guiding the search process demand that the design remains free of singularities and self-collisions at any point in the high-dimensional space of motions the character is expected to be able to execute. To identify worst-case self-collision scenarios for multi degree-of-freedom closed-loop
mechanisms, we additionally develop an elegant technique inspired by the concept of adversarial attacks. We demonstrate the efficacy of our approach by creating designs for several animatronic figures of varying complexity."

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
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://www.youtube.com/watch?v=fBYlgEhnKgk

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
{{< youtube fBYlgEhnKgk >}}