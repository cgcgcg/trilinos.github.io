---
title: Stratimikos Doxygen
permalink: stratimikos_doxygen.html
folder: packages
show_sidebar: true
contact: <a href="mailto:rabartl@sandia.gov">Ross Bartlett</a> (<a href="https://github.com/bartlettroscoe">@bartlettroscoe</a>), <a href="https://github.com/orgs/trilinos/teams/stratimikos">@stratimikos</a>
package: stratimikos
doxygen: true
---

Development Doxygen for Stratimikos is available [Here](http://trilinos.org/docs/dev/packages/stratimikos/doc/html/index.html)  
Links to all available Trilinos release Doxygen collections for Stratimikos are listed below.  
Trilinos Version:

{% for trilinos_version in site.trilinos_versions %}
[{{ trilinos_version }}]({{ "http://trilinos.org/docs/r" | append: trilinos_version | append: "/packages/" | append: page.package | append: "/doc/html/index.html" }}),{% endfor %}
