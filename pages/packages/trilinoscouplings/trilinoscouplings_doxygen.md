---
title: Trilinos Couplings Doxygen
permalink: trilinoscouplings_doxygen.html
folder: packages
show_sidebar: true
contact: <a href="mailto:mperego@sandia.gov">Mauro Perego</a> (<a href="https://github.com/mperego">@mperego</a>), <a href="https://github.com/orgs/trilinos/teams/trilinoscouplings">@trilinoscouplings</a>
package: trilinoscouplings
doxygen: true
---

Development Doxygen for TrilinosCouplings is available [Here](http://trilinos.org/docs/dev/packages/trilinoscouplings/doc/html/index.html)  
Links to all available Trilinos release Doxygen collections for TrilinosCouplings are listed below.  
Trilinos Version: 

{% for trilinos_version in site.trilinos_versions %}
[{{ trilinos_version }}]({{ "http://trilinos.org/docs/r" | append: trilinos_version | append: "/packages/" | append: page.package | append: "/doc/html/index.html" }}),{% endfor %}
