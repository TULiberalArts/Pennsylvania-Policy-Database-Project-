---
# global predefined variables
layout: tla_faculty_test
permalink: /faculty/
published: true
# meta-data variables
title: Faculty
keywords: 'renowned research faculty, neuroscience'
description: >-
  Our faculty members are nationally recognized in their fields and continue
  to  research and publish while teaching both introductory and advanced
  courses.
# custom variables these are the paths to the includes. Look first in this repo/includes/profiles/ and then look in the Theme. The Theme is assigned to these pages in the _config YAML file in the root of this project.
faculty: profiles/faculty.html
affiliated: profiles/affiliated.html
---
Our knowledgeable and experienced faculty, staff and students conduct research for the PA Policy Database Project, Institute for Public Affairs and various centers and institutes within the university and city.


{% if site.data.profiles %}
it is there.
{% endif %}
