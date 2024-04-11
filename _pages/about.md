---
permalink: /
title: "👋Salut! Bine ai venit pe pagina mea!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
❓Cine sunt

Elev la C.N.N.T, in timpul liber ma implic in proiecte legate de securitate cibernetica (laboratorare de analiza malware/inginerie inversa, masini virtuale, analiza prin XDR-uri si EDR-uri, probleme de tip CTF, etc.). Sunt un indivit captivat de acest domeniu prin prisma complexitatii sale. Aspectul care imi place cel mai mult e absenta conceptului "one size fits all" ce poate fi intalnit aproapre oriunde altundeva in industria IT. In ultimele luni am luat subiectul acesta in serios si sunt recunoscator pentru lucrul asta, deoarece am devenit mult mai informat in legatura cu orice fel de pericol digital.

🤔Ce te-a facut sa te implici in domeniu
======
In urma cu un an am incercat sa piratez un joc. Dupa cum majoritatea lumii stie, unele lucruri sunt prea buna sa fie adevarate. Era vorba despre un titlu aparut recent, iar cum eu nu aveam banii sa-l cumpar am decis ca pirateria era a doua cea mai buna varianta. In momentul in care am dat click pe "Download" antivirus-ul meu a inceput sa-mi afiseze zeci de avertizari despre un troian (vezi ce este un [troian aici](https://us.norton.com/blog/malware/what-is-a-trojan)). Era putin spus faptul ca m-am panicat. Pe langa asta, toate datele mele erau mai mult ca probabil compromise, iar antivirus-ul meu nu a fost suficient ca sa scap de el. A trebuit sa resetez Windows-ul si am pierdut tot din calculator. Din seara aceea am inceput sa caut feluri in care sa nu mai pot lua virusi, dar aveam o curiozitate aparte pentru ei. Am aflat cum reusesc sa intre in sisteme, tipurile de virusi, cum actioneaza (etc). Pe urma am aflat faptul ca nimic nu poate fi ***100% sigur***, iar de altfel tot ce este online poate fi compormis. Astfel, o seara aparent proasta mi-a dat ragaz sa aflu totul despre [vulnerabilitati](https://www.upguard.com/blog/vulnerability) si [exploatari](https://www.cisco.com/c/en/us/products/security/advanced-malware-protection/what-is-exploit.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
