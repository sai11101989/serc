# serc
Replace https://serc.iiit.ac.in/static/images/ with localstorage/images/filename.jpg while you use it in your local machine.
https://github.com/sai11101989/serc/blob/main/testingrawbib.bib
https://github.com/sai11101989/serc/blob/main/test.bib

https://raw.githubusercontent.com/sai11101989/serc/testingrawbib.bib
https://raw.githubusercontent.com/sai11101989/serc/test.bib

Final File to reflect:
https://raw.githubusercontent.com/sai11101989/serc/main/test.bib

Rules for Updating bib file correctly,

1. Go to Internet and Search for the updated BIB
2. Remove abstract{}, keywords{}, doi{}, address{}, numpages{}
3. Replace the BookTitle{} with journal{}
4. The journal{} tag should have journal proceeding book name + conference code (Ex: ICSE, ISEC) + pages + ISBN number + Publisher (ACM Publication/IEEE Publication}
5. Get the DOI as url{}
6. Ensure that you have Each Bib has new empty new line
7. The final bib should contain author{}, title{}, year{}, url{}, journal{} tags only
8. Update the such finalized bib in test.bib file the above repo.



**Before - :**

@inproceedings{sripada2015support,
  title={In support of peer code review and inspection in an undergraduate software engineering course},
  author={Sripada, Saikrishna and Reddy, Y Raghu and Sureka, Ashish},
  booktitle={2015 IEEE 28th conference on software engineering education and training},
  pages={3--6},
  year={2015},
  organization={IEEE}
}

**BIB form ACM Site:**

@inproceedings{10.1109/CSEET.2015.8,
author = {Sripada, Saikrishna and Reddy, Y. Raghu and Sureka, Ashish},
title = {In Support of Peer Code Review and Inspection in an Undergraduate Software Engineering Course},
year = {2015},
isbn = {9781467367011},
publisher = {IEEE Computer Society},
address = {USA},
url = {https://doi.org/10.1109/CSEET.2015.8},
doi = {10.1109/CSEET.2015.8},
abstract = {Peer code review and inspection is a quality improvementsoftware engineering activity consisting of systematicexamination of source code. While peer code review is commonlyused in industrial and open-source software projects, it is seldomtaught or practiced in undergraduate level Software Engineeringcourses. We conduct a study on the use of peer code reviewin a sophomore level introductory Software Engineering courseconsisting of more than 200 students and present our experiences,findings and challenges. We use Bitbucket's (a free code distributedversion control system hosting site for Git and Mercurial)in-built code-review system and web-based hosting service. Weextract the peer code review comments using Bitbucket API fordetecting coding standard or compliance violation and identificationof defects (number and type) by reviewers. We also conducta survey on the benefit of peer code review activity on peercohesion and communication. Our experiments and survey revealthat employing peer code review in an undergraduate class hasseveral learning benefits such as improvement in coding skills,program comprehension abilities, knowledge of coding standard,and compliance and peer communication},
booktitle = {Proceedings of the 2015 IEEE 28th Conference on Software Engineering Education and Training},
pages = {3–6},
numpages = {4},
keywords = {Inspections, Static code Analysis, Code Reviews, Defects},
series = {CSEET '15}
}

**Final Edited Version:**

@inproceedings{10.1109/CSEET.2015.8,
author = {Sripada, Saikrishna and Reddy, Y. Raghu and Sureka, Ashish},
title = {In Support of Peer Code Review and Inspection in an Undergraduate Software Engineering Course},
year = {2015},
url = {https://doi.org/10.1109/CSEET.2015.8},
journal = {Proceedings of the 2015 IEEE 28th Conference on Software Engineering Education and Training (CSEET '15), pp:3–6, IEEE Computer Society Publication, ISBN: 9781467367011},
}
