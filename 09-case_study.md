# Case Study

We now assess three/four (or perhaps just one!) case study areas and assess their data documenting, providing targeted feedback on how they could improve, and discuss the strengths.


# Ranking data on the DARECO

Some examples of data documentation are now discussed, and ranked on the DARECO.

## Academia

## EML

The Ecological Metadata Language (EML) [@EML-about] is:

> ...an open source, community oriented project dedicated to providing a high-quality metadata specification for describing data relevant to the ecological discipline. EML provides a very highly structured approach to documenting data.

EML provides ways to describe the heterogenous data common in ecology, which range from the gene level to the biosphere level [@Jones2006]. The EML standard has a [documented standard](https://knb.ecoinformatics.org/#external//emlparser/docs/index.html)
), available on its website, and is widely used in ecology. There is an R package to interface into the EML package, called [`EML`](https://github.com/ropensci/EML), which allows for reading and creating EML files. Creating an EML document is time consuming, but the format is robust, so EML lives at the top right quadrant of DARECO.


## Journal "Data papers"

To provide more information and context around the data used in research,  journals are now adding "data papers", specifically designed for publishing and sharing data. One example of this is **Elsevier's Data In Brief**, which aims to provide an outlet where researchers can easily share and reuse data by publishing articles about the data to improve reproducibility, enhance discoverability by taking it out of the supplementary materials, increase traffic and citations to both the research articles and the data, pave the way for collaborations. Data In Brief welcome data from all research areas.

The requirements of Data In Brief are similar to research articles, requiring a title, author list, afiliations, abstract, and references. They also require several clear bullet points explaining why the data is useful to others, a direct link to the data, a complete description of the design, materials, and methods, and a specifications table. Of particular interest are the sections **Completed specifications table** and **complete description of the experimental design and materials and methods**

The completed specifications table details information on subject area, data type (image, table, text file, graph),the data format (raw, filtered, analysed), how the data was acquired, related articles, data accessibility (it is in a public repo etc), and features of the experimental factors and features, and related research article.

Whilst this is useful, the structure it provides is very flexible, and doesn't tell the researcher/analyst how to actually structure the data and folders. It doesn't tell them how to do it, just provides some good ideas on what they should include. This is a useful step towards improving data resuse, but it _lacks some minimal structure that allows a researcher to have a predictable way to access and interpret the data_.

For example, it does not provide the same resolution of information as a Data Dictionary. As another example, Elsevier's guidelines on "a complete description of the experimental design and materials and methods", state that:

> Offer a complete description of the experimental design and methods used to acquire the data and, where applicable, to perform the analysis. Include any relevant figures and tables needed to understand the data fully. Please also provide, where applicable, any code files used for base-level analysis or filtering of the data

- This is a good standard, but it does not provide explicit instructions.

It is also unclear what the _license_ for data in brief is, as it appears to be CC-BY, but upon acceptance of an article, authors are asked to complete an 'Exclusive License Agreement' [more information](https://www.elsevier.com/about/our-business/policies/copyright), and that third party reuse of open access articles is determined by the author's choice of [user license](https://www.elsevier.com/about/our-business/policies/open-access-licenses). Finally, to provide open access, this journal has an open access fee, which further limits the impact of the paper.

## journal: "data"

http://www.mdpi.com/journal/data

> a peer-reviewed open access journal on data in science, with the aim of enhancing data transparency and reusability. The journal publishes in two sections: a section on the collection, treatment and analysis methods of data in science; a section publishing descriptions of scientific and scholarly datasets (one dataset per paper).

> One of the current hot topics in science is data: how can datasets be used in scientific and scholarly research in a more reliable, citable and accountable way? Data is of paramount importance to scientific progress, yet most research data remains private. Enhancing the transparency of the processes applied to collect, treat and analyze data will help to render scientific research results reproducible and thus more accountable. The datasets itself should also be accessible to other researchers, so that research publications, dataset descriptions, and the actual datasets can be linked. The journal Data provides a forum to publish methodical papers on processes applied to data collection, treatment and analysis, as well as for data descriptors publishing descriptions of a linked dataset.

> Data (ISSN 2306-5729) is a unique international, scientific open access journal on ʻdata in scienceʼ. It provides a forum for data scientists as well as for scientists working with data. The journal publishes two sections:

> Methods: the Methods section publishes research articles, review papers and technical notes on methods for collecting, processing (treating), managing, storing and analyzing scientific and scholarly data. Related source code, if available, can be deposited as supplementary material.

> Data Descriptors: the Data Descriptors section publishes descriptions of scientific and scholarly datasets (one dataset per paper). Described datasets need to be publicly deposited prior to publication, preferably under an open license, thus allowing others to re-use the dataset. Small datasets might also be published as supplementary material to the dataset paper in the journal Data. The link to the publicly hosted version of the dataset must be given in the paper. Data descriptors therefore provide easy citability, traceability and accountability of datasets used in scientific research. Research articles published elsewhere based on the data can link back to the data descriptors via a standard reference and DOI number. Data descriptors are published under a CC BY license, thus allowing the reuse of the descriptions in other research papers without copyright infringement.

## Industry

???

## Media

A media article, such as The Pudding, which has some interesting examples of how they curate data: [pudding data](https://github.com/the-pudding/data)

## Civic bodies

Governments/civic bodies are documenting data:

- [brisbane](https://www.data.brisbane.qld.gov.au/data/dataset)
- [ands - Australian National Data Service](http://www.ands.org.au/working-with-data/publishing-and-reusing-data/data-journals)
- [code for America](https://www.codeforamerica.org/)
- [code for Australia](https://codeforaustralia.org/)