---
title: 'Calculation and optimization of correlation function in distillation method of lattice quantum chromodynamcis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhang Ren-Qiang
  - Jiang Xiang-Yu
  - Yu Jiong-Chi
  - Zeng Chong
  - Gong Ming
  - Xu Shun

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021-07-01T00:00:00Z'
doi: '10.7498/aps.70.20210030'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Acta Physica Sinica*
# publication_short: In *ICW*

abstract: Lattice quantum chromodynamics (lattice QCD) is a theory based on quantum chromodynamics, which is widely used in strong interaction related calculations. As a research method that can give accurate and reliable theoretical results, with the improvement of computer ability, Lattice QCD is playing an increasingly important role in recent years. Distillation method is an important numerical method to calculate hadron correlation function in lattice QCD, and can improve the signal-to-noise ratio of calculated physical quantities. Distillation is a method to approximately compute full propagator via replace the laplacian operator with it's outerproduct of laplace eigenvectors. In this way, the construction of operators is independent of the inversion of propagator which is costful. The eigenvector system and perambulator can be used in different physical projects and we don't need to compute these data repeatedly. It's also convinent for computing disconnected part of correlation function. However, it also faces to the problem of large amount of data in constructing correlation function because the difficulty of compuation is proportional to the cubic of the number of eigenvectors, so it is necessary to further improve its computational efficiency. A program is developed in this work to construct correlation function of quark bilinear with distillation method, and solved the bottleneck of computing performance by using MPI(Message Passing Interface, https://www.open-mpi.org), OpenMP(Open Multi-Processing) and SIMD(Single Instruction Multiple Data) multi-level optimization technology. And this program distribute timeslices to different MPI processes because the computation of each timeslice is independent. In order to show the efficiency of our program some tests result are presented. After various tests of the program, it shows that our design can support large-scale computation. Under the strong scalability test, the parallel computing efficiency of 512 processes can still achieve about 70%. The ability of calculating correlation function is greatly improved. The correction of results also has been checked via compute pseudo-scalar correlators of charmonium. Three different 0−+ operators were adopted for variational analysis and there effecitive mass plateau were compared with the effective mass obtained from the tradional method with point source. The results of distillation method are consistent with traditional method. After variational analysis, three state is obtained, which means the variational analysis take effects and the correlation functions obtained from distillation method is reasonable.


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
