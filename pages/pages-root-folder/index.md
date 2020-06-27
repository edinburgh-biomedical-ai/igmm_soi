---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: simple_header.jpg
widget1:
  title: "Wet Lab"
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: widget-1-302x182.jpg
  text: 'We design experiments in molecular cancer biology to model the process of cancer initiation (<em>oncogenesis</em>). Our aim is to trace DNA and RNA trajectories at cellular resolution and quantify necessary and sufficient early conditions for cancer to occur.
  We closely collaborate with experimental biologists on both designing and performing the experiments, throughtout the data generation process.'
widget2:
  title: "Dry Lab"
  url: 'http://phlow.github.io/feeling-responsive/info/'
  image: widget-1-302x182.jpg
  text: '1. <strong><u>Cancer biology</u></strong>: We design and/or apply computational methods to analyse and predict (i) mutational (DNA) interactions, and (ii) transcriptional (RNA) trajectories, during cancer initiation <br/>2. <strong><u>Population biology</u></strong>: We develop causal stastitical (non-)parametric and machine learning techniques for applications to large-scale biomedical data, such as scRNA-seq and the UK Biobank.'
widget3:
  title: "Teaching"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: '1. <strong>Causality in Biomedicine</strong>: Aimed at biologists, computer scientists and more broadly researchers from quantitative backgrounds. Two main topics of (i) Causal Effect Estimation and (ii) Causal Discovery are covered, together with biomedical applications. <br/> 2. <strong>PhD projects</strong> (<a href="https://edinburgh-biomedical-ai.github.io/igmm_soi/contact/">contact</a>) <br/>3. <strong>MSc projects</strong> <br/> 4.<strong> BSc summer projects</strong> <br/>'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

