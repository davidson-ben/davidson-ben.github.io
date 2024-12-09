---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-12-04
type: landing

design:
  # Default section spacing
  spacing: "6rem"


sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Davidson_CV.pdf
    design:
      css_class: dark
      background:
        color: ''
        image:
          # Add your image background to `assets/media/`.
          filename: beach.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  
  - block: markdown
    content:
      title: Marine Debris in Coastal Environments
      subtitle: ''
      text: 
        '
        Around the globe, over 350 million tons of plastic waste are generated each year (Geyer et al., 2017, _Sci. Adv._).  While plastic has significantly enhanced the human experience—reducing infection in the medical field and reducing vehicle emissions, for example—it also poses a major environmental challenge.  Plastic waste easily contaminates natural environments, particularly our lakes, rivers, and oceans.
        

        In marine environments, there is a discrepancy between the estimated amount of plastic entering the oceans and the amount currently accounted for.  We are working to understand the problem of [missing plastic](https://www.science.org/content/article/ninety-nine-percent-ocean-plastic-has-gone-missing) by studying how plastic debris interacts with shoreline environments.

        ### Field Experiments

        I have previously conducted experiments on the beaches of Lake Superior, focusing on the accumulation and burial of microplasitcs in beach sediments.  Our [2022 study](publication/1-davidson-microplastic-2022/) showed that individual characteristics of a beach were not strong predictors of microplastic pollution.  Instead, the individual beaches sampled (with a combination of characteristics) significantly influence the prediction of microplastic pollution.  Due to the many competing factors in a field study, we decided to pivot to laboratory and modeling studies to gain foundational understanding of plastic/shoreline interactions.  I plan to return to field experiments in the future to achieve a holeistic understanding of microplastic pollution.

        ### Laboratory Experiments

        We&rsquo;ve also used laboratory wave flume and basin experiments to consider a more focused impact of specific characteristics on particle beaching.  Our 39 meter long wave flume at the Water Science and Engineering Lab at the University of Wisconsin-Madison has a custom built [beach](project/Beach/) which we have used in several beaching experiments, including those published [in Flow, in 2023](publication/1-davidson-microplastic-2022/).


        We have also conducted experiments in large scale wave basins at the Queen&rsquo;s University Coastal Engineering Laboratory and the Oregon State University Hinsdale Wave Research Laboratory.  In these large scale experiments, we have been able to explore the impact of wave directionality on plastic particle beaching.

        ### Computational Modeling

        MATLAB and cite


        '

    design:
      background:
        color: ''
          
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
      background:
        color: ''
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 4
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
      background:
        color: ''
---
