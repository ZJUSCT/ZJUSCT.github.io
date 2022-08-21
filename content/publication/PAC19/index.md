---
title: 'Parallel Computing Feature Analysis of Grid Numerical Simulation Software
for Lattice Quantum Chromodynamics'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - BI Yu-Jiang
  - ZHOU Chao
  - WU Yu-Fei
  - LI Rui-Xiang
  - LIU Zhao-Feng
  - CHEN Jian-Hai
  - XU Shun

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2020-07-01T00:00:00Z'
doi: '10.15888/j.cnki.csa.007498'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Computer Systems & Applications*
# publication_short: In *ICW*

abstract: Lattice Quantum Chromodynamics (QCD) is a non-perturbative method for solving QCD based on the first principles. By simulating the interaction between gluon field and fermion field on super-cubic lattice, the calculated results are considered to be a reliable description of the phenomenon of strong interaction. Lattice calculation is of great significance to the study of QCD theory. However, the lattice QCD computing has a very large degree of freedom, which makes it difficult to improve the computational efficiency. Usually, the domain decomposition method is used to realize the scalability of parallel computing, but how to improve the efficiency of data parallel computing is still the core problem. In this work, taking Grid, a typical lattice QCD software, as an example, the data parallel computing pattern in lattice QCD computing is studied. Focusing on the complex tensor computing in lattice QCD and improving the efficiency of large-scale parallel computing, the theoretical analysis of data parallel computing features in lattice QCD method is carried out, and then the performance test and analysis are carried out for the specific data parallel computing methods such as SIMD and OpenMP of Grid software. Finally, the significance of data parallel computing pattern to the application of lattice QCD computing is explained.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
