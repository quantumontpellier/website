---
title: "Practical Quantum Computing: Solving the Wave Equation Using a Quantum Approach"
authors:
- adrien
- Gabriel Staffelbach
- Henri Calendra
date: "2021-02-10T00:00:00Z"
doi: "10.1145/3430030"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "ACM Transactions on Quantum Computing, Volume 2, Issue 1n March 2021, Article No.: 2, pp 1–35"
publication_short: ""

abstract: "In the last few years, several quantum algorithms that try to address the problem of partial differential equation solving have been devised: on the one hand, “direct” quantum algorithms that aim at encoding the solution of the PDE by executing one large quantum circuit; on the other hand, variational algorithms that approximate the solution of the PDE by executing several small quantum circuits and making profit of classical optimisers. In this work, we propose an experimental study of the costs (in terms of gate number and execution time on a idealised hardware created from realistic gate data) associated with one of the “direct” quantum algorithm: the wave equation solver devised in [Costa, P.C., Jordan, S. and Ostrander, A., 2019. Quantum algorithm for simulating the wave equation. Physical Review A, 99(1), p.012323.]. We show that our implementation of the quantum wave equation solver agrees with the theoretical big-O complexity of the algorithm. We also explain in great detail the implementation steps and discuss some possibilities of improvements. Finally, our implementation proves experimentally that some PDE can be solved on a quantum computer, even if the direct quantum algorithm chosen will require error-corrected quantum chips, which are not believed to be available in the short-term."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["wave equation", "quantum", "pde", "solver", "implementation"]
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://adrien.suau.me/publication/practical_quantum_computing_solving_the_wave_equation_using_a_quantum_approach/
url_code: https://gitlab.com/cerfacs/qaths
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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
