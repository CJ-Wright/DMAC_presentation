% IOOS Binstar Channel
% Filipe Fernandes, Rich Signell, and Vembu Subramanian
% Silver Springs, May 27-29

---

# What is a Binstar Channel?

> - Binstar is a service that allows us to create and manage package repositories for conda
> - From their own webpage: "Package Everything!"
> - "And share your repositories with clients or colleagues."

# The IOOS Channel

> - 108 packages
> - Linux, Windows and OSX
> - Some really hard to compile like `iris`, `nco` and `gridgen`...
> - ...are now available via just `conda install -c ioos iris`


# How to use it?

```bash

conda config --add channels ioos

wget http://bit.ly/ioos_req

conda create --yes -n IOOS --file ioos_req.txt python=2.7
```

. . .

That is it!


# IOOS requirements file

------- ---------- ----------------
iris    mpld3      pyoos
pandas  folium     rdflib
geojson requests   ipython-notebook
xlrd    mplleaflet oceans
qrcode  utilities
------- ---------- ----------------

# Downloads

![](images/total_downloads.svg)

# Packages per OS

## Linux: 108
## OSX: 106
## Windows: 102

# How we do it?

> - Conda recipes are hosted on GitHub
> - AppVeyor &#10139; Windows
> - Travis-CI &#10139; OSX
> - Centos (docker container) &#10139; Linux

# How to contribute?

> - Improve the [Wiki](https://github.com/ioos/conda-recipes/wiki)
> - Report problems in our [Issues page](https://github.com/ioos/conda-recipes/issues)
> - Requests packages
> - Pull Requests are even better ;-)

# PRs

![](images/github_pr.png)

# Issues

![](images/github_issues.png)

# Thanks!
 
### [https://binstar.org/ioos](https://binstar.org/ioos)

![http://xkcd.com/303/](images/compiling.png)

Acknowledgements:

*We would like to thank SECOORA for the funding support. We  would also like to thank the contributions of members of NOAA/IOOS, and Principal investigators.*


---

![](images/total_downloads0.svg)

---

![](images/total_downloads1.svg)

---

![](images/total_downloads2.svg)

---

![](images/total_downloads3.svg)

---

![](images/total_downloads4.svg)