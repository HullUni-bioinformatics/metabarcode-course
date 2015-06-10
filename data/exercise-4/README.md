## Exercise 4 - Cumbrian lakes eDNA ##

In this exercise we will use [metaBEAT](https://github.com/HullUni-bioinformatics/metaBEAT), a tool tailored towards reproducible and efficient analyses of metabarcoding data that we have developed in-house. It is still under active development and will likely be extended further in the future. The pipeline is available in a Docker [container](https://registry.hub.docker.com/u/chrishah/metabeat2/) with all necessary dependencies. The Docker image is building on [ReproPhylo](https://registry.hub.docker.com/u/szitenberg/reprophylo/).

The data we will be analyzing are CytB sequences amplified from eDNA samples collected from 3 Cumbrian lakes in the Lake district - Lake Windermere, Derwent water and Basenthwaite lake. The experiment was designed to assess the potential of the eDNA approach to assess fish community compositions. A manuscript (Haenfling et al.) is in preparation. For the purpose of the exercise we will attempt BLAST based taxonomic assignment. The metaBEAT tool is designed as a wrapper around a complete analysis from raw data, performing (optionally) de-multiplexing, quality filtering, clustering along the way, to OTU tables in biom format. It currently supports BLAST and phylogenetic placement (pplacer). The plan is to include further approaches in the future and to allow for efficient and standardized comparative assessments of all approaches.
We will be analyzing a total of 79 individual samples sequenced on the Illumina MiSeq platform.

Back to Google [doc](https://goo.gl/z1MTTf)
