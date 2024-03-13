---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Association of Selective Serotonin Reuptake Inhibitor Use With Abnormal Physical Movement Patterns as Detected Using a Piezoelectric Accelerometer and Deep Learning in a Nationally Representative Sample of Noninstitutionalized Persons in the US."
authors: ["Michael V. Heinz", "George D. Price", "Franklin Ruan", "Robert J. Klein", "Matthew Nemesure", "Aliza Lopez", "Nicholas C. Jacobson"]
date: 2022-04-07
doi: "10.1001/jamanetworkopen.2022.5403"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-05-16T21:39:54-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
#publication: "Association of Selective Serotonin Reuptake Inhibitor Use With Abnormal Physical Movement Patterns as Detected Using a Piezoelectric Accelerometer and Deep Learning in a Nationally Representative Sample of Noninstitutionalized Persons in the US."
publication_short: "Passive Detection of SSRIs using human movement and deep learning"

abstract: "Importance  Selective serotonin reuptake inhibitors (SSRIs) are a common first-line treatment for some psychiatric disorders, including depression and anxiety; although they are generally well tolerated, SSRIs have known adverse effects, including movement problems, sleep disruption, and gastrointestinal problems (eg, nausea and upset stomach). No large-scale studies using naturalistic, longitudinal, objective data have validated physical activity findings, and actigraphy data are well suited to address this task.

Objectives  To evaluate whether differences in physical movement exist among individuals treated with SSRIs compared with control participants and to identify the unique features of the movement of patients treated with SSRIs.

Design, Setting, and Participants  This cross-sectional study examines longitudinally collected wearable movement data within a cross-sectional sample of 7162 participants from the 2005-2006 National Health and Nutrition Examination Survey (NHANES), a nationally representative population-based sample of noninstitutionalized persons in the US having both medication information and passive movement data. Statistical analysis was performed from April 1, 2021, to February 1, 2022.

Exposures  The use of SSRIs (sertraline hydrochloride, escitalopram oxalate, fluoxetine hydrochloride, paroxetine hydrochloride, and citalopram hydrobromide), as reported by participants interviewed by NNHANES personnel, was the primary exposure, measured as a binary variable (taking an SSRI vs not taking an SSRI).

Main Outcomes and Measures  The primary outcome was the intensity of body movement as recorded by a piezoelectric accelerometer worn on the right hip for more than 1 week.

Results  Of the 7162 participants included in the study, the mean (SD) age was 33.7 (22.6) years, 266 (3.7%) were taking an SSRI, 3706 (51.7%) were female, 1934 (27.0%) were Black, 1823 (25.5%) were Mexican American, 210 (2.9%) were other Hispanic, 336 (4.7%) were other or multiracial, and 2859 (39.9%) were White (per the NHANES data collection protocol). A cross-validated, deep learning classifier was constructed that achieved fair performance predicting SSRI use (area under the curve, 0.67 [95% CI, 0.64-0.71] for the validation set and 0.66 [95% CI, 0.64-0.68] for the test set). To account for possible confounding by indication, we constructed a parallel model incorporating depression severity, finding only marginal performance improvement. When averaged across individuals and across 7 days, the results show less overall movement in the SSRI group (mean, 120.1 vertical acceleration counts/min [95% CI, 115.7-124.6 vertical acceleration counts/min]) compared with the non-SSRI control group (mean, 168.8 vertical acceleration counts/min [95% CI, 162.8-174.9 vertical acceleration counts/min]).

Conclusions and Relevance  This cross-sectional study found a moderate association between passive movement and SSRI use, as well as SSRI detection capacity of passive movement using time series deep learning models. The results support the use of passive sensors for exploration and characterization of psychotropic medication adverse effects."

# Summary. An optional shortened abstract.
summary: ""

tags: ["SSRI","Deep learning","passive sensing", "actigraphy", "side effects"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2790799#:~:text=COMMENTS-,Download%20PDF,-Comment
url_code:
url_dataset:
url_poster:
url_project: https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2790799
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
