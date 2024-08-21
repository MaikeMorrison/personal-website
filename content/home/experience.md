+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

title = "Projects"
subtitle = ""

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background image.
   image = "projects_background_4.jpg"  # Name of image in `static/img/`.
   image_darken = 0.06  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
   image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
   image_position = "center"  # Options include `left`, `center` (default), or `right`.
   image_parallax = false  # Use a fun parallax-like fixed background effect? true/false

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.

  [[experience]]
  title = "How do carcinogen exposure and cancer incidence shape mutational signature diversity in cancer tumors?"
  company = ""
  company_url = ""
  location = "International Agency for Research on Cancer"
  date_start = "2023-02-01"
  date_end = ""
  description = """
  I spent much of 2023 as a visiting scientist with Dr. Nicolas Alcala in the [Rare Cancer Genomics Group](https://rarecancersgenomics.com/) at [IARC](https://www.iarc.who.int/). During my visit, we developed signature variability analysis, a framework to quantify the diversity of mutational signatures within tumors and the heterogeneity of signatures across tumors in a population. We found that carcinogen exposure increases the diversity of mutational signatures present in a tumor---even in cases when carcinogens were thought not to have genomic effects! 

  **This work is now available as a [preprint on medRxiv!](https://doi.org/10.1101/2023.11.23.23298821)**
  """
 

[[experience]]
  title = "How can we quantify compositional variability across many microbiome samples?"
  company = ""
  company_url = ""
  location = "Stanford University Department of Biology"
  date_start = "2022-09-01"
  date_end = ""
  description = """
  With Drs. Noah Rosenberg and [Katherine Xue](https://katherinesxue.com/), I developed FAVA, an Fst-based Assessment of Variability across vectors of relative Abundances. We used FAVA to quantify the temporal stability of microbiomes following an antibiotic perturbation and the heterogeneity of microbiomes across ruminant host species at different regions of the gastrointestinal tract. 

  **Check out our [R package on GitHub](https://github.com/maikemorrison/FAVA) and [preprint on bioRxiv](https://doi.org/10.1101/2023.11.23.23298821)!**

  """  

[[experience]]
  title = "How is Shannon diversity constrained by the abundance of the ith most abundant taxon in a community?"
  company = ""
  company_url = ""
  location = "Stanford University Department of Biology"
  date_start = "2021-07-01"
  date_end = "2023-10-23"
  description = """
  Dr. Noah Rosenberg and I derived the upper and lower bounds on the popular biodiversity statistic Shannon entropy when the abundance of the ith most abundant community member is fixed. This project extends previous work which established these bounds conditional on only the first most abundant taxon.

  **Check out our [paper in *Journal of Mathematical Biology*](https://doi.org/10.1007/s00285-023-01997-3)!**
  """

[[experience]]
  title = "How can we quantify ancestry variability using the output of population structure inference software?"
  company = ""
  company_url = ""
  location = "Stanford University Department of Biology"
  date_start = "2020-09-01"
  date_end = "2022-05-21"
  description = """
  With Drs. Noah Rosenberg and Nicolas Alcala, I developed an $F_{ST}$-based tool, called FSTruct, for quantifying the variability of a population's estimated ancestry. 

  **Check out our [R package on GitHub](https://github.com/maikemorrison/fstruct) and [paper in *Molecular Ecology Resources*](https://doi.org/10.1111/1755-0998.13647)!**
  """


[[experience]]
  title = "How many ecotypes make up the world's most abundant photosynthetic organism?"
  company = ""
  company_url = ""
  location = "UT Austin Department of Integrative Biology"
  date_start = "2017-12-01"
  date_end = "2020-08-31"
  description = """
  Under Dr. Mark Kirkpatrick, I evaluated the performance of Bayesian Phylogenetics and Phylogeography (an MCMC program for analyzing DNA alignments under the multispecies coalescent model) when applied to prokaryotic genomic data. 

  I have used this tool to identify independently evolving lineages, or ecotypes, within a superabundant marine cyanobacteria responsible for 5% of global oxygen production, *Prochlorococcus marinus*.

  **You can access my poster from the 2019 Evolution Meeting [here!](files/poster-Evolution_2019.pdf)**
  """

[[experience]]
  title = "What are the drivers of rising vaccination exemptions in Texas schools?"
  company = ""
  company_url = ""
  location = "UT Austin Department of Integrative Biology"
  date_start = "2017-08-01"
  date_end = "2020-03-10"
  description = """
  With the guidance Dr. Lauren Ancel Meyers and Dr. Lauren Castro, I analyzed the Texas counties and school districts most at risk of an outbreak due to high conscientious vaccination exemption rates and fit an array of models to identify sociodemographic predictors of these exemptions.

  **This work is now published in *PLOS Medicine*! You can find the open-access paper [here.](https://doi.org/10.1371/journal.pmed.1003049)**
  """


[[experience]]
  title = "How many isolation beds are needed to protect people experiencing homelessness in Austin from COVID-19?"
  company = ""
  company_url = ""
  location = "UT Austin Department of Integrative Biology"
  date_start = "2020-04-01"
  date_end = "2021-05-13"
  description = """
  Dr. Lauren Ancel Meyers, Dr. Spencer Fox, Tanvi Ingle, and I modeled demand for COVID-19 isolation beds for the Austin homeless population based on epidemic projections. This work was done in collaboration with public health leaders from the City of Austin.

  **This project is now published in *PLOS One*! See [this link](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0251153) for the open-access paper.**
  """

[[experience]]
  title = "Mathematical Statistics in Epidemiology: A Discussion of the Mathematical Concepts Employed in Regression Analyses and Studies of Disease Spread."
  company = ""
  company_url = ""
  location = "UT Austin Mathematics Department"
  date_start = "2019-08-01"
  date_end = "2020-05-01"
  description = """
  I wrote an honors mathematics thesis with the supervision of Dr. Stephen Walker as part of my degree through the Dean's Scholars Honors Program.

  **You can view an abridged copy of my thesis [here!](files/undergrad_thesis.pdf)**
  """

[[experience]]
  title = "What is the genetic basis of how strongly our immune system responds to infectious diseases?"
  company = ""
  company_url = ""
  location = "University of California, San Francisco Department of Biostatistics & Epidemiology"
  date_start = "2019-05-01"
  date_end = "2019-07-01"
  description = """
  As part of the [UCSF Summer Research Training Program](https://graduate.ucsf.edu/srtp) and the [Amgen Scholars Program](https://amgenscholars.com/), I worked with Dr. John Witte, Dr. Linda Kachuri, and Dr. Sara Rashkin to conduct genome-wide association studies of immune response strength to 22 distinct antigens.

  We identified many interesting and novel single-nucleotide polymorphisms that are implicated in immune response variability.

  **This work is now published in *Genome Medicine*! You can find the open-access paper [here](https://doi.org/10.1186/s13073-020-00790-x) and my poster [here!](files/poster-UCSF_2019.pdf)**
  """

[[experience]]
  title = "How does terrain patchiness influence spatial infectious disease spread?"
  company = ""
  company_url = ""
  location = "Penn State University Department of Statistics"
  date_start = "2018-06-01"
  date_end = "2018-08-01"
  description = """
  As part of [The Mathematical Biosciences Institute NSF REU Program](https://mbi.osu.edu/education/summer-reu-program), I worked with Dr. Ephraim Hanks and Emily Strong to explore the dynamics of disease spread over patchy terrain through an extensive simulation study.
  
  We found that terrain heterogeneity (i.e. resource selection) can cause population dispersal to be heavy tailed, creating accelerating epidemic waves.

  **You can view our poster [here](files/poster-MBI_2018.pdf) and a recording of our final presentation [here!](https://archive.mbi.ohio-state.edu/video?view=speakers&id=18129&item=Maike%20Morrison)**
  """

+++
