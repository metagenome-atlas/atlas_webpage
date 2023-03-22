---
# Leave the homepage title empty to use the site title
title:
date: 2023-03-22
type: landing

sections:
  - block: hero
    content:
      title: Hugo Academic Theme
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://wowchemy.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-themes" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Wowchemy Website Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        {{% alert note %}}

        [Remote Atlas Tutorial](https://silask.github.io/talk/tutorial-at-the-ismb-2023/)
        {{% /alert %}}

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  # - block: about.avatar
  #   id: about
  #   content:
  #     # Choose a user profile to display (a folder name within `content/authors/`)
  #     username: admin
  #     # Override your bio text from `authors/admin/_index.md`?
  #     text:

  - block: markdown
    content:
      title: Metagenome-Atlas
      subtitle: 
      maintext: |-
          {{< figure library="true" src="atlas_scheme.png" title="Scheme of workflow" width="400px" >}}

          Metagenome-atlas is a easy-to-use metagenomic pipeline based on [snakemake](https://snakemake.github.io/). It handles all steps from QC, Assembly, Binning, to Annotation & Quantification.

          The pipline is easy to use. You can start using atlas with three commands:

          ```
              mamba install -y -c bioconda -c conda-forge metagenome-atlas
              atlas init --db-dir databases path/to/fastq/files
              atlas run all
          ```

          ![So easy a caveman could do it](img/caveman.jpg)


          Atlas has only one dependency: [conda](http://anaconda.org/). All databases and other dependencies are installed **on the fly**.
          Atlas is based on snakemake which allows to run steps of the workflow in parallel on a cluster.


          <!-- ## See metagenome atlas in action
          [Video](https://asciinema.org/a/337467)
          <script async id="asciicast-337467" src="https://asciinema.org/a/337467.js" charset="utf-8"></script>
          -->



          <!-- [![asciicast](https://asciinema.org/a/337467.svg)](https://asciinema.org/a/337467) -->



    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'



  - block: markdown
    content:
      title: Get Started
      subtitle: 
      maintext: |-
        
        

        - [Get Started](https://metagenome-atlas.readthedocs.io/en/latest/usage/getting_started.html)

        - [Join the forum](https://github.com/metagenome-atlas/atlas/discussions)

        - [{{< icon name="twitter" pack="fab" >}} Follow me on Twitter](https://twitter.com/SilasKieser)

        - [Check out the documentation](https://metagenome-atlas.readthedocs.io/en/latest/)

        - [Do the Tutorial](https://github.com/metagenome-atlas/Tutorial)


    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'



  - block: markdown
    content:
      title: Others on Metagenome-Atlas
      subtitle: 
      maintext: |-
        

        <a class="twitter-timeline" data-height="800" data-width="800" data-theme="dark" href="https://twitter.com/SilasKieser/timelines/1270049886436646912?ref_src=twsrc%5Etfw">Others on Metagenome Atlas </a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>



        [{{< icon name="twitter" pack="fab" >}} Tweet about it!](http://twitter.com/intent/tweet?text=%23metagenomeAtlas%20%3A%20Three%20commands%20to%20start%20analyzing%20your%20data%2C%20from%20%40SilasKieser%20https%3A%2F%2Fbmcbioinformatics.biomedcentral.com%2Farticles%2F10.1186%2Fs12859-020-03585-4)

        <span style="text-shadow: none;"><a class="github-button" href="https://github.com/metagenome-atlas/atlas" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star this on GitHub">Star</a><script async defer src="https://buttons.github.io/buttons.js"></script></span>








        <!-- # Article

        ATLAS: a Snakemake workflow for assembly, annotation, and genomic binning of metagenome sequence data.  
        Kieser, S., Brown, J., Zdobnov, E. M., Trajkovski, M. & McCue, L. A.  
        BMC Bioinformatics 21, 257 (2020).  
        [doi: 10.1186/s12859-020-03585-4](https://doi.org/10.1186/s12859-020-03585-4)   -->




    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'


# - block: features
#     content:
#       title: Skills
#       items:
#         - name: R
#           description: 90%
#           icon: r-project
#           icon_pack: fab
#         - name: Statistics
#           description: 100%
#           icon: chart-line
#           icon_pack: fas
#         - name: Photography
#           description: 10%
#           icon: camera-retro
#           icon_pack: fas
  

  


---
