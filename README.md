This web page contains the replication package for the FSE 2015 paper:

# Query-based Configuration of Text Retrieval Solutions for Software Engineering Tasks
1. [Dataset](#dataset)
2. [Exploratory study](#exploratory)
3. [QUEST implementation](#implementation)
4. [QUEST evaluation study](#evaluation)
5. [Authors](#authors)

## <a name="dataset"></a> Dataset

| Description | Download |
| --- | --- |
| **Change requests.** Zip file containing the change requests used in both studies. Each folder in the zip file corresponds to a different software system and contains 3 files: \*\_Mapping.txt, \*\_Corpus.txt, and \*\_Queries.txt. See the README file included in the zip file for more information. | [[ZIP]](dataset.zip) |
| **Stop words.** List of stop words used to process the change request. The list includes Java keywords, English common words, and HTML keywords. | [[TXT]](stopwords-en-java-html.txt)|

## <a name="exploratory"></a> Exploratory study

| Description | Download |
| --- | --- |
| **Effectiveness.** Spreadsheet containing the TR configurations used in the study, the effectiveness achieved by each TR configuration for each query, and an analysis of the best global and local TR configuration. | [[XLSX]](study-i/effectiveness-all-configs.xlsx) |

## <a name="implementation"></a> QUEST implementation

| Description | Download |
| --- | --- |
| **Pre-retrieval properties and measures.** PDF document describing the pre-retrieval properties and measures implemented by QUEST. | [[PDF]](pre-retrieval-measures.pdf) |
| **Post-retrieval properties and measures.** PDF document describing the post-retrieval properties and measures implemented by QUEST. | [[PDF]](post-retrieval-measures.pdf) |

## <a name="study-ii"></a> QUEST evaluation study

| Description | Download |
| --- | --- |
| **QUEST results.** Spreadsheet containing the TR configuration recommended by QUEST and compared to eight baselines. The analysis includes but is not limited to effectiveness comparison between QUEST and the baselines; number (and percentage) of queries whose effectiveness was improved, preserved and deteriorated by the recommender; MRR and MAP values; etc. | [[XLSX]](study-ii/quest-results.xlsx) |

## <a name="authors"></a> Authors
* [Laura Moreno](https://www.cs.colostate.edu/~lmorenoc/) (lmorenoc at colostate dot edu)
* [Gabriele Bavota](http://www.inf.usi.ch/faculty/bavota/) (gabriele.bavota at usi dot ch)
* [Sonia Haiduc](http://www.cs.fsu.edu/~shaiduc/) (shaiduc at cs dot fsu dot edu)
* [Massimiliano Di Penta](http://www.rcost.unisannio.it/mdipenta/) (dipenta at unisannio dot it)
* [Rocco Oliveto](http://www.distat.unimol.it/people/oliveto/) (rocco.oliveto at unimol dot it)
* Barbara Russo (brusso at unibz dot it)
* [Andrian Marcus](http://www.utdallas.edu/~amarcus) (amarcus at utdallas dot edu)