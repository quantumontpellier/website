---
title: "A Hardware-Aware Heuristic for the Qubit Mapping Problem in the NISQ Era"
authors:
- siyuan
- adrien
- Gabriel Staffelbach
- aida
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2020-09-01T00:00:00Z"
doi: "10.1109/TQE.2020.3026544"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Quantum Engineering, vol. 1, pp. 1-14, 2020, Art no. 3101614"
publication_short: ""

abstract: Due to several physical limitations in the realization of quantum hardware, today's quantum computers are qualified as noisy intermediate-scale quantum (NISQ) hardware. NISQ hardware is characterized by a small number of qubits (50 to a few hundred) and noisy operations. Moreover, current realizations of superconducting quantum chips do not have the ideal all-to-all connectivity between qubits but rather at most a nearest-neighbor connectivity. All these hardware restrictions add supplementary low-level requirements. They need to be addressed before submitting the quantum circuit to an actual chip. Satisfying these requirements is a tedious task for the programmer. Instead, the task of adapting the quantum circuit to a given hardware is left to the compiler. In this article, we propose a hardware-aware (HA) mapping transition algorithm that takes the calibration data into account with the aim to improve the overall fidelity of the circuit. Evaluation results on IBM quantum hardware show that our HA approach can outperform the state of the art, both in terms of the number of additional gates and circuit fidelity.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["qubit mapping", "quantum", "compiler"]
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9205650
url_code: https://github.com/peachnuts/HA
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
