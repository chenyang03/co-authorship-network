# Co-authorship network of 402.39K authors on Google Scholar

Building and Analyzing a Global Co-Authorship Network Using Google Scholar Data (full citation below)

Licensed under [Creative Commons Attribution Share Alike 4.0](http://choosealicense.com/licenses/cc-by-sa-4.0/).

## Description

A global co-authorship network with 402.39K nodes and 1.23 million edges

## Files

* ``nodes.txt``: all the node IDs used in the dataset

* ``edges.txt``: the co-authorship network among the authors. For example, "1, 3" means author 1 and author 3 are co-authors.

* ``gs_info.txt``: the information of each node within the network. Each line in this file represents one node. The elements within each line: node_ID, total_number_of_citations, h-index, g-index, academic title(3-professors/2-postdocs/1-students/0-unknown), computer_science_author?(1-yes,0-no), biology_author?(1-yes,0-no), sociology_author?(1-yes,0-no)

## BibTex Entry
```
@inproceedings{Chen_BigScholar17,
 author = {Yang Chen and Cong Ding and Jiyao Hu and Ruichuan Chen and Pan Hui and Xiaoming Fu},
 title = {{Building and Analyzing a Global Co-Authorship Network Using Google Scholar Data}},
 booktitle = {Proc. of 26th International World Wide Web Conference (WWW 2017) Companion},
 year = {2017},
}
```
