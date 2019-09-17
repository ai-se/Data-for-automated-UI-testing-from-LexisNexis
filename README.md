# Automated UI testing data from LexisNexis

Cite as:
```
@inproceedings{yu2019terminator,
 author = {Yu, Zhe and Fahid, Fahmid and Menzies, Tim and Rothermel, Gregg and Patrick, Kyle and Cherian, Snehit},
 title = {TERMINATOR: Better Automated UI Test Case Prioritization},
 booktitle = {Proceedings of the 2019 27th ACM Joint Meeting on European Software Engineering Conference and Symposium on the Foundations of Software Engineering},
 series = {ESEC/FSE 2019},
 year = {2019},
 isbn = {978-1-4503-5572-8},
 location = {Tallinn, Estonia},
 pages = {883--894},
 numpages = {12},
 url = {http://doi.acm.org/10.1145/3338906.3340448},
 doi = {10.1145/3338906.3340448},
 acmid = {3340448},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {automated UI testing, test case prioritization, total recall},
} 
```


 - Each test case has a unique "id".

 - Folder "results" contains results for 54 consecutive runs of 2661 automated UI test cases from September 27th to November 15th in 2018.
 
 - For each file in the "results" folder, if a certain id does not occur, that test case is skipped for that run.

 - File "test_feature.csv" contains the featurized test case descriptions for each test case.
