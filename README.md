# INF515: Comparative Genomics

Instructor: Marc Tollis (marc.tollis@nau.edu)<br/>
MoWeFr 12:40-1:30PM<br/>
Office Hours: MoWeFri 2:00-2:30PM<br/>
Please go to http://bblearn.nau.edu for weekly quizzes and to submit assignments

## Course Description
The purpose of this course is to familiarize students with methods, theories, and applications behind comparative genomics. Biology is now a big-data science that is genomic in scale, and the growing availability of genome sequence data from across the tree of life challenges researchers to provide evolutionary explanations for this diversity. This course focuses on the analysis of genomic sequences, including sequencing technologies, genome assembly, functional and structural predictions, and comparisons at macroevolutionary timescales in a phylogenetic context. 

Special emphasis is on building practical skills in computational biology. Classes will consist of lectures, student led discussions of primary literature, and computational labs.

The course is modeled after other genomics courses being taught by [Mike Schatz @ Cold Spring Habor](https://github.com/schatzlab/appliedgenomics2017) and [Casey Dunn @ Yale University](https://github.com/Yale-EEB723/syllabus). Some publicly available material has been repurposed.

## Prerequisites
* The course is open to any NAU graduate student, although certain components are meant to benefit CS/Informatics, Biology, and Forestry students working on a thesis project.<br/>
* Students will complete a research project as part of their grade, you may use your own data or publicly available data. Projects will be explained in detail during class.

## Resources
* Materials for the course are available at this repository. Go to the green "Code" button, and download the repository.<br/>
* [Syllabus and policies](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/INF515_F22_syllabus.pdf)
* [NAU BBLearn](https://bblearn.nau.edu/) - this will be primarily how you submit assignments and quizzes.

## Course Schedule
This is a tentative outline and topics may vary according to student needs. The course will be delivered in person but can be done remotely if quarantines are required. Attendance is strongly encouraged as there will be live coding demonstrations. It is important to be flexible in response to the changes the COVID-19 pandemic has made to the rhythm of our lives.
* All assignments for a given week are due on Sunday 11:59 PM. No late work is accepted. The two lowest quiz grades will be dropped.
* Email me questions with "INF515 F22" in the subject line. Please do not expect rapid responses over weekends (my advice is to START YOUR ASSIGMENTS EARLY IN THE WEEK).

| Week | Module | Topics | Monday | Wednesday  | Friday  | Assignment (see BBLearn) |
| ---| ------------ | ------ | -------------- | ------- | ---------- | --------------- |
| Aug 29 | 1 and 2 | Course Introductions + Sequencing Technologies | [Course Intro](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/lectures/01%20Introduction.pdf) | [Sequencing Technologies](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/lectures/02%20GenomeSequencing.pdf) | [Shendure et al. 2017](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/scientific_papers/Shendure%20et%20al.%20-%202017%20-%20DNA%20sequencing%20at%2040%20past%2C%20present%20and%20future.pdf)  | * Quiz 1</br>* [Sign up for discussion leadership](https://docs.google.com/spreadsheets/d/1GyAeELaSWa6coEp4Pg2Q51WWSvmaIjkTS5MxE3HUE00/edit?usp=sharing)</br>* [Software carpentry](https://swcarpentry.github.io/shell-novice/) (optional:Depending on your experience with computing, you should complete at least lesson 1 - 3 and 7 (that's about two hours of tutorial work - all chapters are about 4 hours). I may assign this to you based on your survey answers.)</br>* Computing survey |
| Sept 5 | 3 | Computing in Genomics | NO CLASS: LABOR DAY | [Command line workshop](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/labs/tollis_lab_UNIX_tutorial.txt) | Introduction to Monsoon at NAU |  |  |
| Sept 12 | 4 | Genome Assembly | [Genome assembly lecture](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/lectures/03%20GenomeAssembly.pdf) | [Sedlazeck et al. 2018](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/scientific_papers/Sedlazeck%20et%20al.%20-%202018%20-%20Piercing%20the%20dark%20matter%20bioinformatics%20of%20long-r.pdf); [Bradnam et al. 2013](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/scientific_papers/Gigascience%202013%20Bradnam-1.pdf) | [Lab 1: Assembling a Genome](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/tree/main/labs/lab%201) | Quiz 2 |
| Sept 19 | 5 | Genome Annotation 1 | [Genome annotation lecture 1](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/lectures/04%20GenomeAnotation.pdf) | [Yandell and Ence 2012](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/scientific_papers/Yandell%20and%20Ence%202012.pdf) |  [Lab 2: repeatmasking](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/tree/main/labs/lab%202) | Quiz 3 |
| Sept 26 | 6 | Genome Annotation 2 | [Genome annotation lecture 2](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/lectures/05%20GenomeAnnotation2.pdf) | [Aken et al. 2016](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/scientific_papers/Database%20(Oxford)%202016%20Aken.pdf);</br>[Holt and Yandell 2011](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/scientific_papers/Holt%20and%20Yandell%202011.pdf)  | Work on labs | Quiz 4; Lab 1; Lab 2 |
| Oct 3 | 7 | Orthology | [Orthology lecture](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/lectures/06%20Orthology.pdf) | [Kriventseva et al. 2019](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/scientific_papers/OrthoDB.pdf) |  [Lab 3: BLAST](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/tree/main/labs/lab%203) | Quiz 5; project proposal |
| Oct 10 | 8 | Phylogenomics 1 | [Phylogenomics 1 lecture](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/lectures/07%20Phylogenetics.pdf);</br> 2 minute oral description of your project | [Gable et al. 2022](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/scientific_papers/Gable%20et%20al.%20-%202022%20-%20A%20Genomic%20Perspective%20on%20the%20Evolutionary%20Diversif.pdf) | [Lab 4: Tree building](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/tree/main/labs/lab%204) | Quiz 6 |
| Oct 17 | 9 | Phylogenomics 2 | [Phylogenomics 2 lecture](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/lectures/08%20Phylogenetics%202.pdf) | [Donoghue and Benton 2007](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/scientific_papers/Trends%20Ecol.%20Evol.%202007%20Donoghue.pdf) | [Lab 5: Divergence time estimation](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/tree/main/labs/lab%205) | Quiz 7 |
| Oct 24 | 10 | Comparative Methods | [Comparative methods lecture](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/lectures/09%20ComparativeMethods.pdf) | Harmon chapters [3](https://lukejharmon.github.io/pcm/chapter3_bmintro/) and [7](https://lukejharmon.github.io/pcm/chapter7_introdiscrete/) | Work on labs | Quiz 8; Lab 3; Lab 4; Lab 5 |
| Oct 31 | 11 | Tests for Selection | [Selection lecture 1](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/lectures/10%20TestsForSelection.pdf) | [Sackton et al. 2020](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/scientific_papers/Sackton%20-%202020%20-%20Studying%20Natural%20Selection%20in%20the%20Era%20of%20Ubiquitou.pdf) | [Lab 6: codon models](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/tree/main/labs/lab%206) | Quiz 9 |
| Nov 7 | 12 | Population Genomics and Selective Sweeps | [Selection lecture 2](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/lectures/11%20LinkedSelection.pdf);</br>[Population structure](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/lectures/12%20PopGenomicsStructure.pdf) | [Kern and Hahn 2018](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/scientific_papers/Kern%20and%20Hahn%202018.pdf);</br>[Jensen et al. 2019](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/scientific_papers/Jensen%20et%20al%202018.pdf) | NO CLASS Fri 11/11: Veteran's Day | Quiz 10 |
| Nov 14 | 13 | Evolutionary Conservation | [Conservation lecture](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/lectures/13%20EvolutionaryConservation.pdf) | [Sackton et al. 2019](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/scientific_papers/Sackton%20et%20al.%20-%202019%20-%20Convergent%20regulatory%20evolution%20and%20loss%20of%20flight.pdf) | [Lab 7: UCSC Genome Browser](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/tree/main/labs/lab%207) | Quiz 11 |
| Nov 21 | 14 | Ancient DNA and Paleogenomics, Species Conservation | [Bergstrom et al. 2020](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/scientific_papers/Bergstro%CC%88m%20et%20al.%20-%202020%20-%20Origins%20and%20genetic%20legacy%20of%20prehistoric%20dogs.pdf) | [Robinson et al. 2018](https://github.com/marctollis/INF515-Comparative-Genomics_fall22/blob/main/scientific_papers/Robinson%20et%20al.%20-%202018%20-%20Purging%20of%20Strongly%20Deleterious%20Mutations%20Explains.pdf) | NO CLASS Fri 11/25: Thanksgiving |  |
| Nov 28 |  | Projects, discussion | Projects, discussion | Projects, discussion | Projects, discussion | Quiz 12; Lab 6 |
| Dec 5 |  | Projects, discussion | Projects, discussion | Projects, discussion | Projects, discussion | Lab 7; final projects reports |
