Bootstrap: docker
From: zamora/r-devtools

%post
R --version

R --slave -e 'install.packages("mRMRe",repos="https://cran.rstudio.com/")'
R --slave -e 'install.packages("optparse",repos="https://cran.rstudio.com/")'

