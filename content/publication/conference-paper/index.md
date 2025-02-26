---
title: 'Enhancing Home Energy Management: A Day-Ahead Machine Learning Approach Using EMHASS for Predictive Temperature Control'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - M. Draou
  - A. Brakez

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2025-02-02T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-02-02T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Trends in Environmental Sustainability and Green Energy*
publication_short: In *CGEEE 2024*

abstract: This paper presents a comprehensive study on the implementation of a day-ahead machine learning algorithm in residential settings for energy saving purposes. The core of our methodology involves the utilization of the K-Nearest Neighbors (KNN) algorithm for temperature predictions, contributing to the realization of an adaptive and efficient energy management framework. The system collects temperature data at 5-min intervals through temperature sensors, processes it through EMHASS, and trains the KNN model. To address weather-induced variations in thermal energy systems, an automation script checks for foggy conditions, triggering the `tune' endpoint to adapt the KNN model dynamically. Over the month of November, the model has been evaluated on two renewable energy systems, a hot water system and a space heating system. The findings highlight the effectiveness of our approach in predicting thermal energy system's temperature with a coefficient of determination R2 evaluated at 91{\%} for water heating and 68{\%} for space heating. Marking a significant stride in the domain of smart home energy management

# Summary. An optional shortened abstract.
summary:

tags:
  - Machine learning
  - KNN
  - Thermal modeling
  - EMHASS
  - HEMS

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '10.1007/978-3-031-81560-7_15'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://link.springer.com/chapter/10.1007/978-3-031-81560-7_15#citeas'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'EMHASS KNN Logic'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
