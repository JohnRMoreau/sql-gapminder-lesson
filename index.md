---
layout: lesson
root: .
lastupdated: April 4, 2016
contributors: ["Tracy Teal", "John Moreau", "et al"]
maintainers: ["TBD"]
domain: "Economics and Business"
topic: SQL
software: SQL
dataurl: https://github.com/JohnRMoreau/2016-04-07-FederalReserveBoard/raw/gh-pages/data/gapminder-sql-data.zip
status: Under Development
---

<!-- USING THIS LESSON TEMPLATE -->
<!-- Lesson specific information is taken from the YAML header at the top of the page -->

<!-- THE LESSON INFORMATION -->


# Data Carpentry {{ page.topic }} for {{ page.domain }}

Data Carpentry's aim is to teach researchers basic concepts, skills,
and tools for working more effectively with data.
The lessons below were designed for those interested
in working with {{page.domain %}} data in {{page.topic %}}.


**Content Contributors: {{page.contributors | join: ', ' %}}**


**Lesson Maintainers: {{page.maintainers | join: ', ' %}}**


**Lesson status: {{ page.status }}**

<!--
  [Information on Lesson Status Categories]()
-->

<!-- ###### INDEX OF LESSONS ON THIS TOPIC ###### -->

## Lessons:


1. [SQL Introduction](00-SQLIntro-00.html)
2. [SQL Cheat Sheet](sql_cheat_sheet.html)


## Data
<!--
Data files for the lesson are available here: ({{page.dataurl %}})[{{page.dataurl %}}]
-->
Data files for the lesson are available here: (https://github.com/JohnRMoreau/2016-04-07-FederalReserveBoard/raw/gh-pages/data/gapminder-sql-data.zip)[https://github.com/JohnRMoreau/2016-04-07-FederalReserveBoard/raw/gh-pages/data/gapminder-sql-data.zip]

### Requirements

Data Carpentry's teaching is hands-on, so participants are encouraged to use
their own computers to insure the proper setup of tools for an efficient workflow.
*These lessons assume no prior knowledge of the skills or tools*, but working
through this lesson requires working copies of the software described below.
To most effectively use these materials, please make sure to install everything
*before* working through this lesson.




{% if page.software == "Python" %}
{% include pythonSetup.html %}
{% elsif page.software == "Spreadsheets" %}
{% include spreadsheetSetup.html %}
{% elsif page.software == "R" %}
{% include rSetup.html %}
{% else %}
{% include anySetup.html %}
{% endif %}

<p><strong>Twitter</strong>: @datacarpentry
