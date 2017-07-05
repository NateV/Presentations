---
layout: deck
title: A Data Pipeline for CLS
description: Building a TREF Data-Analysis pipeline
theme: moon
---

{% include cover_slide.html deck_title=page.title deck_author="Nate Vogel" %}

<section>
  <h2> Transparent, Reproducible, Easy-to-use, Fancier analysis </h2>
</section>

<section>
  <h2> Separate <i> logic </i> from <i> presentation </i> </h2>
</section>

<section>
  <h2> Logic: Sets </h2>
  <div>
    <p> C is the set of all cases. So "Cases Handled" in a year is: </p>
    <p class="math">
      $$\{c \in C: c_{date.opened} >= Y_{start}, c_{date.opened} <= Y_{end}\}$$
    </p>
  </div>
</section>
<section>
  <h2> Logic: Functions </h2>
  <div>
    <p> Functions are testable methods for learning something about the cases in a set. </p>
  </div>
</section>
<section>
  <h2> Logic: Functions </h2>
  <div>
    <p> For example, if <code> cases_handled </code> is the set of cases handled in a year, then we can write a function that calculates the number of cases for each race/ethnicity category. </p>
    <p> The function is defined as, "Given a set of cases, return a dictionary mapping each race/ethnicity category to the number of cases with that race/ethnicity." </p>
  </div>
</section>
<section>
  <h2> Logic: Functions </h2>
  <div>
    <p> Once defined, a function could be implemented anywhere, including in Excel; but implementing in programming languages, such as R and python, is probably more straightforward. </p>
  </div>
</section>
<section>
  <div>
    <h2> Presentation </h2>
    <p> We can use the functions we've defined in a variety of display formats </p>
    <ul>
      <li> Web-based</li>
      <li> Rmarkdown reports </li>
    </ul>
  </div>
</section>
<section>
  <h2> Caveat </h2>
  <div>
    Our access to the raw data is still restricted by the report web interface. We can define datasets, but have to access them by building reports by clicking through data fields and filter options. Cf. "SELECT caseid, race from cases WHERE DateOpened >= yrStart AND DateOpened <= yrEnd"
  </div>
</section>
<section>
  <h2> CLS by the numbers </h2>
</section>
<section>
  <h2> Intake Trends </h2>
</section>
<section>
  <h2> Cases Closed </h2>
</section>
