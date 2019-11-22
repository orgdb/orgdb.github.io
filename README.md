# orgdb.github.io
Unofficial Bioconductor alike OrgDb R packages 

Bioconductor OrgDb are the Annotation packages for perticular organism. They can be easily accessed through [AnnotationDbi](https://bioconductor.org/packages/release/bioc/html/AnnotationDbi.html), which makes them very useful for certain pipelines in R.

Bioconductor provide OrgDb for [20 species](http://bioconductor.org/packages/release/BiocViews.html#___OrgDb) as of now (Nov'2019), which are model organisms.

But for non-model organism we dont have a good resouce.

Anyone can make an OrgDb R package with [AnnotationForge,](http://bioconductor.org/packages/release/bioc/html/AnnotationForge.html) but it require a downloaded NCBI database in background which is abount 12GB and yes sometime it takes a long time. 

So here is an afford to make it available through this channel, which can be easily downloaded with `remotes::install_github("orgdb/org_pkg_name")`
