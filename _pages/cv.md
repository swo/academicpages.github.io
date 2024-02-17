---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Experience

- **Team Lead**, CDC Center for Forecasting & Outbreak Analytics (2023--)
- **Senior Quantitative Epidemiologist/Modeler**, Leidos (2022--2023)
    - Supported CDC Center for Forecasting & Outbreak Analytics
    - Cataloged and analyzed models contributing to the Covid-19 Forecast Hub
    - Developed statistical analysis methods for traveler-based genomic screening data
    - Led sprint planning and project management for team-wide software refactor project
- **Group Lead, Epidemiology** (*previously Computational Epidemiologist*), [Biobot Analytics](https://www.biobot.io/) (2020--2022)
    - Served as leading wastewater epidemiology company’s most senior public health subject matter expert
    - Built and led a team of 5 infectious disease and substance use epidemiologists
    - Established paradigm for public health content in customer experience and training/technical assistance
    - Oversaw development of 3 new wastewater data interpretation features
    - Led drafting of first-ever company Code of Wastewater Monitoring Ethics
    - Developed mathematical model of waster epidemiology's predictive value for Covid-19 activity
    - Established data-driven thresholds of Covid-19 risk based on SARS-CoV-2 wastewater concentrations
- **Associate Research Scientist** (*previously Postdoctoral Fellow*), Harvard Chan School (2021)
    - Discovered quantitative evidence of antibiotic resistance “spillover” between US states
    - Made first quantification of US nationwide racial/ethnic disparities in antibiotic use
    - Created comprehensive "landscape" of antibiotic use & resistance across 72 pathogen-drug combinations
    - Differentiated role of repeated, intensive antibiotic use versus "broad" use in selecting for resistance
    - Found evidence that market factors, not medical guidelines, drive trends in antibiotic prescribing
    - Demonstrated that use of azithromycin for respiratory infections affects resistance among *N. gonorrhoeae*
- **Research Analyst**, Institute for Public Research, [CNA](https://www.cna.org/) (2020--2021)
    - Implemented a [Vaccine Vulnerability Index](https://www.cna.org/centers/ipr/phpr/vaccination-tool) for DHS [CISA](https://en.wikipedia.org/wiki/Cybersecurity_and_Infrastructure_Security_Agency)
    - Executed an infectious disease threat assessment for the Greater Houston Region
    - Conceptualized portions of New York City Emergency Management's Urban Risk Index
    - Supported COVID-19 after-action reviews for Virginia's Departments of Health and Emergency Management
- **COVID-19 Epidemiology Consultant** (2020)
    - National Basketball Association
        - Built epidemiological model of COVID-19 transmission in a "bubble"
        - Advised on design of Orlando "bubble" system used for the 2020 playoffs
    - [Epic Games](https://www.epicgames.com/)
        - Built model of COVID-19 infection and absenteeism among employees
        - Advised on company’s strategic response to COVID-19 pandemic
- **Scientific Director** (*later Consultant*), [OpenBiome](https://www.openbiome.org/) (2019--2021)
    - Acted as lead scientist for 70-person gut microbiota therapeutics nonprofit
    - Managed 2 dedicated research staff and multiple cross-departmental staff on internal research projects
    - Charted organization-wide 5-year research goals
    - Restructured 12-person research staff into thematic program areas
    - Planned and facilitated company-wide 2019 strategic planning process

## Education

- Postdoctoral Fellowship, Harvard Chan School (2016--2018)
    - Advisor: [Yonatan Grad](https://www.hsph.harvard.edu/yonatan-grad/)
- **PhD**, Biological Engineering, MIT (2016)
    - Thesis: *Quantitative modeling for microbial ecology and clinical trials* ([MIT Dspace](https://dspace.mit.edu/handle/1721.1/107277))
    - Advisor: [Eric Alm](https://be.mit.edu/directory/eric-alm)
- **MPhil**, Chemistry, University of Cambridge (2012)
    - Thesis: *Coarse-grained models of chiral assemblies* ([pdf](/files/olesen-2012-thesis.pdf))
    - Advisor: [David Wales](https://en.wikipedia.org/wiki/David_J._Wales)
- **MASt**, Applied Mathematics & Theoretical Physics, University of Cambridge (2011)
- **BA** *magna cum laude* with Highest Honors, Physics, Williams College (2010)

## Awards

- Emerging Leaders in Biosecurity Fellowship, Johns Hopkins Center for Health Security (2023)
- Kocaeli International Travel Award, Harvard Chan School (2017)
    - Funds one-week exchange program with Kocaeli University, Turkey
- NSF Graduate Research Fellowship (2013--2016)
- Presidential Fellow, MIT (2012--2013)
    - Fully funds first year of graduate student for 120 students
- Herchel Smith Fellowship, Williams College (2010--2012)
    - Fully funds 2 years of graduate study at the University of Cambridge
- Howard P. Stabler Prize in Physics, Williams College (2010)
- Barry M. Goldwater Scholarship (2009)

## White papers

- M Santiago, **SW Olesen**. Pathogen biomarkers in wastewater, stool, and
  urine: an informal literature survey. [Biobot Analytics](http://biobot.io/wp-content/uploads/2022/05/2022-04-28-Pathogen-lit-survey-combined.pdf) (Apr 2022).
- A Young, **SW Olesen**. Interpreting Covid-19 wastewater data from buildings. [Biobot Analytics](http://biobot.io/wp-content/uploads/2022/04/Brief-Interpreting-Covid-19-wastewater-data-from-buildings-1.pdf) (May 2022).
- **SW Olesen**. Effective concentration: a future-proof approach to characterizing pathogen concentrations in wastewater. [Biobot Analytics](http://biobot.io/wp-content/uploads/2022/02/2022-01-White-paper-Effective-concentration.pdf) (Feb 2022).
- **SW Olesen**. Polio and the early history of wastewater epidemiology. [Biobot Analytics](https://biobot.io/polio-and-the-early-history-of-wastewater-epidemiology/) (Oct 2021). [pdf]()

## Publications

{% for pub in site.data.publications %}
  - {{ pub.citation }}{% if pub.doi %} doi: <a href="http://doi.org/{{ pub.doi }}">{{ pub.doi }}</a>{% endif %}{% if pub.pmid %} pubmed: <a href="http://ncbi.nlm.nih.gov/pubmed/{{ pub.pmid }}">{{ pub.pmid }}</a>{% endif %} {% if pub.url %} <a href="{{ pub.url }}">link</a>{% endif %}
{% endfor %}

## Talks & posters

{% for talk in site.data.talks %}
  - {{ talk.type }}: "{{ talk.title }}". {% if talk.authors %}{{ talk.authors }}.{% endif %} {{ talk.place }} ({{ talk.date }})
{% endfor %}

## Teaching

{% for x in site.data.teaching %}
  - {{ x.title }}. {{ x.venue }}. {% if x.inviter %}Invited by {{ x.inviter }}.{% endif %} ({{ x.date }})
{% endfor %}

## Service, leadership, and community

- **President**, [Postdoctoral Association](https://www.hsph.harvard.edu/pda/) (PDA), Harvard Chan School (2018)
    - Led a consolidation of PDA council for >15 officers to 4
    - Initiated a Training Evaluation Initiative to create a common administrator-trainee language for negotiations
- **Member**, Dean's Advisory Committee on Diversity and Inclusion, Harvard Chan School (2016--2018)
- **Communication Fellow**, MIT [Biological Engineering Communication Lab](https://mitcommlab.mit.edu/be/) (2013--2016)
    - Co-founding Fellow and mentor to junior Fellows
    - Coached >100 undergraduate, graduate, and postdoc clients
    - Co-led creation of the [CommKit](https://mitcommlab.mit.edu/be/use-the-commkit/): online, content-specific communication guide
- **Diversity Co-Chair**, Graduate Student Board, MIT Biological Engineering (2013--2016)
    - Developed new programming for events exploring student diversity
    - Co-designed and conducted first departmental diversity climate survey
- **Discussion leader & participant**, MIT [Science Policy Initiative](https://mitspi.squarespace.com/) (2012--2016)
    - Team member for visits to executive agencies and Congressional offices
    - Engaged in 30-hour Science Policy Bootcamp
