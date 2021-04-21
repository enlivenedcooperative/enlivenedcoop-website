---
layout: project
title: 'San Francisco Crime Map'
caption: Using Tableau to map San Francisco crime.
description: >
  Using data from the SFPD, create a visualization for crime rates by neighborhood in NE San Francisco.
date: 19 Sep 2020
image: 
  path: assets/img/projects/hydejack-site.jpg
  srcset: 
    2560w: /assets/img/projects/tableau_sf_crime.jpg
    1280w: /assets/img/projects/tableau_sf_crime@0.50x.jpg
    640w: /assets/img/projects/tableau_sf_crime@0.25x.jpg

links: 
  - title: View on Tableau Public
    url: https://public.tableau.com/views/NortheasternSanFranciscoCrime/CrimeDashboard?:language=en&:display_count=y&publish=yes&:origin=viz_share_link

accent_color: '#4fb1ba'
accent_image:
  background: 'linear-gradient(to bottom, #0a7b81 0%, #01636e 25%, #02505b 50%, #073a4a 75%, #082e39 100%)'
  background: 'linear-gradient(to bottom, #7f7053 0%, #72654b 25%, #665a42 50%, #594e3a 75%, #4c4332 100% )'
  background: 'linear-gradient(to bottom, #665a42 0%, #594e3a 25%, #4c4332 50%, #40382a 75%, #332d21 100% )'
  
  overlay:    true
sitemap: false
---

A couple years ago I joined [Nextdoor](https://nextdoor.com/) and was less than impressed
with the "lost cat" posts.  However, with a lot of people sheltering in place
during the Covid pandemic, there seemed to be an uptick in activity, and I noticed there were recently a lot of 
posts regarding neighborhood crime.  Break-ins were becoming more common.  Some of the local
neighbors even began gathering video footage of break-ins from Ring doorbell cameras, and helped
the police identify and eventually arrest a gang of thieves that were responsible for the recent
spike in crime.

The available crime statistics were kind of fuzzy, with the SFPD insisting that crime was down overall,
but neighbors disagreed.  So I thought I would create a "Crime Dashboard" that would visualize
crime by neighborhood, and track crime by month.  A really perfect use for Data Analysis.

It also helped me learn Tableau, which turned out to be an awesome tool.

I found crime data on the [San Francisco Public Safety web site](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/wg3w-h783), and population data
by neighborhood on [this site](https://www.niche.com/places-to-live/san-francisco-san-francisco-ca/).

Sure enough, the tool helped show a recent increase in burglaries, actually a three-fold increase
in my neighborhood over the last 30 days (July to August, 2020).  This was a lot more valuable than anecdotal evidence.

<iframe src="https://public.tableau.com/views/NortheasternSanFranciscoCrime/CrimeDashboard?:showVizHome=no&:embed=true" frameborder="1" style="overflow:hidden;width:100%" marginwidth="0" width = "100%" height = "800"></iframe>

Here is a live view of the dashboard hosted on [Tableau Public](https://public.tableau.com/).
{:.figcaption}