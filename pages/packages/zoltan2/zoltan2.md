---
title: Zoltan2
permalink: zoltan2.html
folder: packages
show_sidebar: true
contact: <a href="mailto:egboman@sandia.gov">Erik Boman</a> (<a href="https://github.com/egboman">@egboman</a>), <a href="https://github.com/orgs/trilinos/teams@zoltan2">@zoltan2</a>
package: zoltan2
doxygen: true
---

Welcome to the Zoltan2 Home

Zoltan2 is a package for load balancing and combinatorial scientific computing. It may be viewed as a successor to the popular Zoltan and Isorropia packages. Currently, Zoltan2 only supports a few partitioning and ordering methods but the package is actively developed.

Zoltan2 covers many of the same areas as Zoltan. While Zoltan was written in C, Zoltan2 is written in modern templated C++. Zoltan2 supports arbitrary index types, and can therefore solve problems with more than 2 billion elements (32-bit limit). Zoltan2 provides input adapters for Xpetra (indirectly, both Epetra and Tpetra) data types as a convenience to Trilinos users. 
Much of Zoltan2 should be considered experimental code. The feature set is currently small compared to Zoltan.
