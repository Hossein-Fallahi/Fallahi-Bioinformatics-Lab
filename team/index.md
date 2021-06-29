---
title: Team
nav:
  order: 5
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

My team members mostley include graduate students with a background in cell and molecular biology. I am helping them to do their thesis.
They will be here with their thesis title soon.
please check it later. 

{% include section.html %}

{% include section.html background="images/BioinfoLab.jpg" dark=true%}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}  

{:.center}
## Current researchers and students:  
{:.center}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
%}  
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}  
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}  
{:.center}
### Previous students who did their bioinformatics analysis in my lab:  
{:.center}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: alumni"
%}

{:.center}

{% include section.html %}

{% include section.html background="images/banner.jpg" dark=true%}

There is no position available at the moment. Please chek here later.

{%
  include link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
  style="button"
%}
{:.center}

{% include section.html %}

## Funding

At the moment, we only recive a limited research funding from Razi University Research Council for each Master and PhD student to counduct their thesis.
{:.center}


{%
  style="square"
  include link.html
  image1="images/razi.jpg"
  link1="https://www.razi.ac.ir/en/"
  tooltip1="Razi University"
  
%}
