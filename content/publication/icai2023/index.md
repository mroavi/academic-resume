---
title: "Scaling Probabilistic Inference through Message Contraction Optimization"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Jin-Guo Liu
- Patrick Wijnings
- Sander Stuijk 
- Henk Corporaal

date: "2023-07-26:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In the *2023 World Congress in Computer Science, Computer Engineering, & Applied Computing (CSCE'23)*
publication_short: In CSCE'23

abstract: Within the realm of probabilistic graphical models, message-passing algorithms offer a powerful framework for efficient inference. When dealing with discrete variables, these algorithms essentially amount to the addition and multiplication of multidimensional arrays with labeled dimensions, known as factors. The complexity of these algorithms is dictated by the highest-dimensional factor appearing across all computations, a metric known as the \emph{induced tree width}. Although state-of-the-art methods aimed at minimizing this metric have expanded the feasibility of exact inference, many real-world problems continue to be intractable. In this paper, we introduce a novel method for adding and multiplying factors that results in a substantial improvement in the inference performance, especially for increasingly complex models. Our approach aligns well with existing state-of-the-art methods designed to minimize the induced tree width, thereby further expanding the tractability spectrum of exact inference for more complex models. To demonstrate the efficacy of our method, we conduct a comparative evaluation against two other open-source libraries for probabilistic inference. Our approach exhibits an average speedup of 23 times for the UAI 2014 benchmark set. For the 10 most complex problems, the average speedup increases to 64 times, demonstrating its scalability.



# Summary. An optional shortened abstract.
summary:


tags: [probabilistic inference, message-passing algorithms, probabilistic graphical models, Bayesian networks]

# Display this page in the Featured widget?
featured: true

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
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
