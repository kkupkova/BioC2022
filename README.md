# GenomicDistributions demo - BioC2022

### Description

During this workshop participants will be introduced to _GenomicDistributions_
package. At first, we will go over a general introduction to 
_GenomicDistributions_, where we will learn about the purpose, design, and 
advantages of _GenomicDistributions_. Followed by instructor-led demo,
we will go through all of the functions included in 
_GenomicDistributions_, where participants will be able to try the functions
on provided example datasets. The participants will learn, 
how to calculate and plot summary statistics extracted from the example 
datasets and how to further customize plots generated with 
_GenomicDistributions_. Some of the _GenomicDistributions_ functions require
genome annotations (for _hg19_, _hg38_, and _mm10_ these are all included in 
the _GenomicDistributionsData_ package and passed to a subset of functions 
ending with the suffix _“Ref”_), the participants will be taught how to easily 
create and use these annotations. At the end of the workshop, all participants 
will be able to extract following summary statistics about their regions of 
interest: distribution over chromosomes, distances from genomic features 
(e.g., TSSs), distribution over annotation classes, signal summary in regions,
region widths, distances to the nearest neighbor, GC content, and dinucleotide
frequencies.


### Pre-requisites

Helpful but not required:

* Basic knowledge of R syntax
* Familiarity with the GenomicRanges class

Anyone interested in getting familiar with _GenomicDistributions_ before the
workshop is welcome to that that by reading the _GenomicDistributions_ 
publication or vignettes provided with the package: 

* [publication](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-022-08467-y)
* [vignettes](http://code.databio.org/GenomicDistributions/articles/index.html)

### Participation

Participants will be able to test all of the functions provided in
_GenomicDistributions_ on example datasets, learn how to customize plots 
and create genome annotations required by some of the functions.

### _R_ / _Bioconductor_ packages used

* _GenomicDistributions_
* _GenomicDistributionsData_

### Time outline

| Activity                     | Time |
|------------------------------|------|
| Introduction                 | 10m  |
| Package demo                 | 25m  |
| Questions                    | 10m  |

