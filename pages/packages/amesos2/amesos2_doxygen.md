---
title: Amesos2 Doxygen
permalink: amesos2_doxygen.html
folder: packages
show_sidebar: true
contact: <a href="mailto:iyamaza@sandia.gov">Ichitaro Yamazaki</a> (<a href="https://github.com/iyamazaki">@iyamazaki</a>), <a href="https://github.com/orgs/trilinos/teams/amesos2">@amesos2</a>
package: amesos2
doxygen: true
---

Development Doxygen for Amesos2 is available [here](http://trilinos.org/docs/dev/packages/amesos2/doc/html/index.html)  
Links to all available Trilinos release Doxygen collections for Amesos2 are listed below.  
Trilinos Version:
 
{% for trilinos_version in site.trilinos_versions %}
[{{ trilinos_version }}]({{ "http://trilinos.org/docs/r" | append: trilinos_version | append: "/packages/" | append: page.package | append: "/doc/html/index.html" }}),{% endfor %}
