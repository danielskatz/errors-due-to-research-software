# Errors due to research software

This repo is a list of papers and articles that discuss errors in research due to software errors.

Please feel free to make additions, **keeping the lists in chronologic order (by year)**, and formatting entries similarly to exisiting ones (title, author, publisher, year. DOI/URL). If you want to add a comment as well, feel free, but please indent it as shown in "A Scientist's Nightmare" entry.  See the [contributing guidelines](https://github.com/danielskatz/errors-due-to-research-software/edit/main/README.md#contributing) below.

## Papers / articles related to research software

* A Scientist's Nightmare: Software Problem Leads to Five Retractions, Greg Miller, Science, 2006. https://doi.org/10.1126/science.314.5807.1856
  + A comment on this story by crystallographer [Brian Matthews](https://en.wikipedia.org/wiki/Brian_Matthews_(biochemist)), entitled [Five retracted structure reports: Inverted or incorrect?](http://doi.org/10.1110/ps.072888607), questions the explanation given by the authors of the retracted papers. It is a reminder of the importance of publishing research code. The supposedly faulty code behind this story was never made public.
* Retraction: "Structure of MsbA from E. coli: A homolog of the multidrug resistance ATP binding cassette (ABC) transporters", "Structure of the ABC transporter MsbA in complex with ADP·vanadate and lipopolysaccharide", "X-ray structure of the EmrE multidrug transporter in complex with a substrate", Geoffrey Chang, Christopher B. Roth, Christopher L. Reyes, Owen Pornillos, Yen-Ju Chen, and Andy P. Chen, Science, 2006. https://doi.org/10.1126/science.314.5807.1875b
* Retraction: Measures of Clade Confidence Do Not Correlate with Accuracy of Phylogenetic Trees, Barry G Hall, Stephen J Salipante, PLOS Computational Biology, 2007. https://doi.org/10.1371/journal.pcbi.0030158
* BLOSUM62 miscalculations improve search performance, Mark P Styczynski, Kyle L Jensen, Isidore Rigoutsos, and Gregory Stephanopoulos, Nature Biotechnology, 2008. https://doi.org/10.1038/nbt0308-274
* _Retracted_: Prediction of posttranslational modification sites from sequences with kernel methods, Xiaobo Wang, Yongcui Wang, Yingjie Tian, Xiaojian Shao, Ling-Yun Wu, and Naiyang Deng, Wiley Periodicals, 2010. https://doi.org/10.1002/jcc.21526
  + "retracted by agreement between the authors, the journal's editors, and Wiley ... because a computational error produced results that led the authors to overstate the level of performance of their computing model."
* The Effects of FreeSurfer Version, Workstation Type, and Macintosh Operating System Version on Anatomical Volume and Cortical Thickness Measurements, Ed H. B. M. Gronenschild, Petra Habets, Heidi I. L. Jacobs, Ron Mengelers, Nico Rozendaal, Jim van Os, and Machteld Marcelis, PLOS One, 2012. https://doi.org/10.1371/journal.pone.0038234
* Retraction: Comparative expression profile of miRNA and mRNA in primary peripheral blood mononuclear cells infected with human immunodeficiency virus (HIV-1). Ankit Gupta, Pruthvi Nagilla, Hai-Son Le, Coulton Bunney, Courtney Zych, Anbupalam Thalamuthu, Ziv Bar-Joseph, Sinnakaruppan Mathavan, Velpandi Ayyavoo, PLoS One, 2012. https://doi.org/10.1371/annotation/d28d38b2-41a3-42a6-b421-68f9460a676d
  + "During the initial analysis, we eliminated miRNAs if they showed an expression CT of value 35 in over 75% of the samples. This decision was based on the instructions from the software during the initial data feed process for the selection of particular miRNAs (row) for exclusion. Unfortunately, the software included the excluded miRNAs as controls along with the endogenous controls and analyzed the data."
* Retraction: Implications of new hypertension guidelines in the United States. Monica L Bertoia, Molly E Waring, Priya S Gupta, Mary B Roberts, Charles B Eaton, Hypertension, 2012. https://doi.org/10.1161/HYP.0b013e318269bc7a
  + "...the authors discovered an error in the code for analyzing the data. The National Health and Nutrition Examination Survey (NHANES) medication data file had multiple observations per participant and was merged incorrectly with the demographic and other data files. Consequently, the sample size was twice as large as it should have been (24989 instead of 10198)."
* Retraction: Vitamin D Levels do not Predict Cardiovascular Events in Statin-treated Patients with Stable Coronary Disease. Vera Bittner, Nanette K Wenger, David D Waters, David A DeMicco, Michael Messig, John C LaRosa, American Heart Journal, 2013. https://doi.org/10.1016/j.ahj.2013.06.001
  + "Further investigation revealed that the code created to manually anonymize the data was accidentally run twice. During the first run, anonymized subject identifiers were successfully assigned to both biosamples and clinical data. However, after this first run had passed quality control checks, the anonymization code was re-run inadvertently, replacing the first correct set of identifiers with a random and incorrect set. We do not understand how or why the code was re-run."
* Retraction notice to "Plasma PCSK9 levels and clinical outcomes in the TNT (Treating to New Targets) Trial" [J Am Coll Cardiol 2012;59:1778–1784]. Roeland Huijgen, S Matthijs Boekholdt, Benoit J Arsenault, Weihang Bao, Jean-Michel Davaine, Fatiha Tabet, Francine Petrides, Kerry-Anne Rye, David A DeMicco, Philip J Barter, John J P Kastelein, Gilles Lambert, Journal of the American College of Cardiology (JACC), 2013. https://doi.org/10.1016/j.jacc.2013.04.002
  + "Further investigation revealed that the code created to manually anonymize the data was accidentally run twice. During the first run, anonymized subject identifiers were successfully assigned to both biosamples and clinical data. However, after this first run had passed quality control checks, the anonymization code was re-run inadvertently, replacing the first correct set of identifiers with a random and incorrect set."
* Author-Initiated Retraction: Anderson et al, Induced Alpha Rhythms Track the Content and Quality of Visual Working Memory Representations with High Temporal Precision. David E Anderson, John T Serences, Edward K Vogel, Edward Awh, The Journal of Neuroscience : The Official Journal of the Society for Neuroscience, 2015. https://doi.org/10.1523/JNEUROSCI.0074-15.2015
  + "We regret that there was an error in the analytic code used to compute oscillatory power in our article. Specifically, there was a matrix transposition error in the code"
* Retraction: Inferring the Effects of Cancer Treatment: Divergent Results From Early Breast Cancer Trialists’ Collaborative Group Meta-Analyses of Randomized Trials and Observational Data From SEER Registries, Katherine E. Henson, Reshma Jagsi, David Cutter, Paul McGale, Carolyn Taylor, and Sarah C. Darby, Journal of Clinical Oncology, 2016. https://doi.org/10.1200/jco.2016.69.0875
* Cluster failure: Why fMRI inferences for spatial extent have inflated false-positive rates, Anders Eklunda, Thomas E. Nichols, and Hans Knutssona, Proceedings of the National Academy of Sciences, 2016. https://doi.org/10.1073/pnas.1602413113
  + "a 15-year-old bug was found in 3dClustSim while testing the three software packages (the bug was fixed by the AFNI group as of May 2015, during preparation of this manuscript). The bug essentially reduced the size of the image searched for clusters, underestimating the severity of the multiplicity correction and overestimating significance"
* Retraction: The Neural Basis of Temporal Individuation and its Capacity Limits in the Human Brain. Claire K Naughtin, Benjamin J Tamber-Rosenau, Paul E Dux, Journal of Neurophysiology, 2016. https://doi.org/10.1152/jn.z9k-3963-retr.2016
  + "We regretfully retract this publication due to a computer programming error in a portion of the multi-voxel pattern analyses (MVPA) code. Specifically, we employed a mean-centering procedure (page 503) to control for overall regional differences in signal amplitude between conditions prior to MVPA."
* Retraction notice to “Increased Risk of Stomach and Esophageal Malignancies in People With AIDS”: Gastroenterology 2012;143:943–950.e2. E Christina Persson, Meredith S Shiels, Sanford M Dawsey, Kishor Bhatia, Lesley A Anderson, Eric A Engels, Gastroenterology, 2016. https://doi.org/10.1053/j.gastro.2016.02.069
  + "The authors recently discovered two programming errors that affected the results in their article on the epidemiology of esophageal and stomach cancers in human immunodeficiency virus infected people. As a result of these errors, the standardized incidence ratios (SIRs) were too high."
* Withdrawal: Aberrant Cross-Brain Network Interaction in Children With Attention-Deficit/Hyperactivity Disorder and Its Relation to Attention Deficits: A Multisite and CrossSite Replication Study. Weidong Cai, Tianwen Chen, Luca Szegletes, Kaustubh Supekar, Vinod Menon, Biological Psychiatry, 2016. https://doi.org/10.1016/j.biopsych.2016.11.001
  + "During the course of analysis of data from a different study, the authors discovered a single coding error in the MATLAB script used in this study that transforms output of FSL independent component analysis to a MATLAB compatible format for subsequent analysis. Specifically, there was an error in the way the MATLAB function “reshape” was used, which resulted in some parts of the data being incorrectly structured."
* Retraction: How birds outperform humans in multi-component behavior, Sara Letzner, Onur Güntürkün, and Christian Beste, Current Biology Magazine, 2017. https://doi.org/10.1016/j.cub.2017.07.056
* Retraction: A Case-Cohort Study of Cadmium Body Burden and Gestational Diabetes Mellitus in American Women.. Megan E Romano, Daniel A Enquobahrie, Christopher D Simpson, Harvey Checkoway, Michelle A Williams, Environmental Health Perspectives, 2017. https://pmc.ncbi.nlm.nih.gov/articles/PMC5381973/ (_Note: Original DOI link for the retraction is not working: https://doi.org/10.1289/EHP1818_)
  + "This article is being retracted at the request of the authors because of inadvertent errors in the statistical code that resulted in the exclusion of 12 gestational diabetes mellitus cases with urinary cadmium below the limit of detection. The coding errors do not impact any other published studies of this population."
* Retraction Note to: Risk factors for increased left ventricular hypertrophy in patients with chronic kidney disease. Kosaku Nitta, Stoshi Iimuro, Enyu Imai, Seiichi Matsuo, Hirofumi Makino, Tadao Akizawa, Tsuyoshi Watanabe, Yasuo Ohashi, Akira Hishida, Clinical and Experimental Nephrology, 2017. https://doi.org/10.1007/s10157-017-1466-x
  + "Upon carrying out further analyses, the authors discovered that the program used in merging their data set was not working correctly, which may have made the conclusion stated in their article questionable."
* The war over supercooled water, Ashley G. Smart, Physics Today, 2018, https://doi.org/10.1063/PT.6.1.20180822a
  + This story is announced as a "hidden coding error", but a careful reading shows that it was really a case of an unjustified assumption, which hadn't been written down anywhere else but in the code.
* Retraction: Association between the probability of autism spectrum disorder and normative sex-related phenotypic diversity in brain structure. Christine Ecker, Derek S Andrews, Christina M Gudbrandsen, Andre F Marquand, Cedric E Ginestet, Eileen M Daly, Clodagh M Murphy, Meng Chuan Lai, Michael V Lombardo, Amber N V Ruigrok, Edward T Bullmore, John Suckling, Steven C R Williams, Simon Baron-Cohen, Michael C Craig, Declan G M Murphy,  Medical Research Council Autism Imaging Multicentr, JAMA Psychiatry, 2018. https://doi.org/10.1001/jamapsychiatry.2018.4296
  + "During these replication attempts, we identified a problem with the script that was used for the prediction of biological sex in male and female individuals with ASD based on their respective neuroanatomy in our original sample... we discovered that the gaussian process classification function called within the analysis scripts operates in 2 different modes depending on whether test labels are supplied. If test labels are supplied, the function returns the probabilities of belonging to the correct class as defined by the test labels (ie, +1 or −1 for male and female individuals, respectively). If test labels are not supplied, the function outputs the probabilities for a "default" class (eg, the first class). "
* Characterization of Leptazolines A–D, Polar Oxazolines from the Cyanobacterium Leptolyngbya sp., Reveals a Glitch with the “Willoughby–Hoye” Scripts for Calculating NMR Chemical Shifts, Jayanti Bhandari Neupane, Ram P. Neupane, Yuheng Luo, Wesley Y. Yoshida, Rui Sun, and Philip G. Williams, Organic Letters, 2019. https://doi.org/10.1021/acs.orglett.9b03216
  + Story about this: Researchers find bug in Python script may have affected hundreds of studies, Sean Gallagher, Ars Technicha, 2019. https://arstechnica.com/information-technology/2019/10/chemists-discover-cross-platform-python-scripts-not-so-cross-platform
  + In short, the code assumed the list of files in a directory is sorted, which it is on Windows but not on Linux or MacOS (see text describing Figure 2 in Neupane). This is an example of a portability bug.
* Notice of Retraction. Aboumatar et al. Effect of a Program Combining Transitional Care and Long-term Self-management Support on Outcomes of Hospitalized Patients With Chronic Obstructive Pulmonary Disease: A Randomized Clinical Trial. JAMA. 2018;320(22):2335-2343, Hanan Aboumatar and Robert A. Wise, JAMA. 2019. https://doi.org/10.1001/jama.2019.11954
* Retraction Note: Limited individual attention and online virality of low-quality information, Xiaoyan Qiu, Diego F. M. Oliveira, Alireza Sahami Shirazi, Alessandro Flammini, and Filippo Menczer, Nature Human Behavior, 2019. https://doi.org/10.1038/s41562-018-0507-0
  + "a software bug led to an incorrect value"
* Retraction Note: Limited individual attention and online virality of low-quality information. Xiaoyan Qiu, Diego F M Oliveira, Alireza Sahami Shirazi, Alessandro Flammini, Filippo Menczer, Nature Human Behavior, 2019. https://doi.org/10.1038/s41562-018-0507-0
  + "In Fig. 4d, a software bug led to an incorrect value of the discriminative power represented by the blue bar."
* Notice of Retraction and Replacement. Dyrbye et al. Association of Clinical Specialty With Symptoms of Burnout and Career Choice Regret Among US Resident Physicians. JAMA. 2018;320(11):1114-1130. Liselotte N Dyrbye, Sara E Burke, Rachel R Hardeman, Jeph Herrin, Natalie M Wittlin, Mark Yeazel, John F Dovidio, Brooke Cunningham, Richard O White, Sean M Phelan, Daniel V Satele, Tait D Shanafelt, Michelle van Ryn, JAMA: Journal of the American Medical Association, 2019. https://doi.org/10.1001/jama.2019.0167
  + "These were generated by the commercial software package Stata (StataCorp): specifically, we used a command to generate the marginal probabilities for categorical variables using the results of a logistic regression model. We used this command to generate the predicted probabilities and CIs for each respondent category and outcome, and then took ratios of these to produce relative risks (RRs). However, we did not realize that the command we used can produce, for predicted probabilities, CIs that extend below 0."
* A case for open communication of bugs in climate models, made with ICON version 2024.01, Proske, U., Brüggemann, N., Gärtner, J. P., Gutjahr, O., Haak, H., Putrasahan, D., and Wieners, K.-H., EGUsphere, 2024.  https://doi.org/10.5194/egusphere-2024-3493

## Papers / articles related to general software as used in research (eg, Excel-related errors)

* Mistaken identifiers: gene name errors can be introduced inadvertently when using Excel in bioinformatics, Zeeberg BR, Riss J, Kane DW, Bussey KJ, Uchio E, Linehan WM, Barrett JC, and Weinstein JN, BMC Bioinformatics. 2004. https://doi.org/10.1186/1471-2105-5-80
* Does high public debt consistently stifle economic growth? A critique of Reinhart and Rogoff, Thomas Herndon, Michael Ash and Robert Pollin, Cambridge Journal of Economics, 2014, https://doi.org/10.1093/cje/bet075
  + "RR [Reinhart and Rogoff] calculated both means and medians of cells in lines 30–44 instead of lines 30–49. In their analysis with the 1790–2009 dataset, RR calculated both means and medians for cells in lines 5–19 instead of lines 5–24. As such, Australia, Austria, Belgium, Canada and Denmark were excluded entirely from their calculations with both the 1946–2009 and 1790–2009 data samples. Reinhart and Rogoff acknowledge the error in a [New York Times column](https://archive.nytimes.com/www.nytimes.com/interactive/2013/04/17/business/17economix-response.html), while maintaining the validity of their conclusion.
  + The paper Growth in a Time of Debt by Reinhart and Rogoff, as an NBER working paper, last revised in Dec 2011 <https://doi.org/10.3386/w15639>, was cited as a motivation for public policy changes by American, EU, and British politicians, so this error may have had an outsized impact.
* Gene name errors are widespread in the scientific literature, Ziemann M, Eren Y, and El-Osta A, Genome Biololgy, 2016. https://doi.org/10.1186/s13059-016-1044-7
* A journey of reproducibility from Excel to Pandas, Simon Hettrick, Software Sustainability Institute's blog, 2017. https://www.software.ac.uk/blog/journey-reproducibility-excel-pandas
  + "Everything looks rosy until you get to question 9... This mistake occurred because I was using a SEARCH() function to differentiate between possible answers. I had searched for 'taught', which is not unique across the potential answers, rather than 'a taught' which is. Here lies one of the biggest problems with Excel: a mistake can throw out a tiny part of the overall analysis, which is hard to detect. By contrast, programming forces you to abstract your analysis so that it can be applied more generally, and this means that mistakes generally have wide-ranging effects, which makes them easier to detect.
  + "Even something as simple as listing the steps in the original analysis became invaluable when trying to fathom the logic in the original spreadsheet. On that front, I can conclusively say that whilst it’s not impossible to reconstruct the logic behind '40 columns of arcane transformations', it is so, so much simpler to review a couple of lines of well-commented code."
* Covid: how Excel may have caused loss of 16,000 test results in England, Alex Hern, The Guardian, 2020. https://www.theguardian.com/politics/2020/oct/05/how-excel-may-have-caused-loss-of-16000-covid-tests-in-england
* Guidelines for human gene nomenclature, Elspeth A. Bruford, Bryony Braschi, Paul Denny, Tamsin E. M. Jones, Ruth L. Seal, and Susan Tweedie, Nature Genetics, 2020. https://doi.org/10.1038/s41588-020-0669-3
  + includes "symbols that affect data handling and retrieval, e.g. all symbols that auto-converted to dates in Microsoft Excel have been changed (SEPT1 is now SEPTIN1; MARCH1 is now MARCHF1 etc); tRNA synthetase symbols that were also common words have been changed (WARS is now WARS1, CARS is now CARS1, etc.)."
* Microsoft Finally Fixes Excel Glitch That Caused Major Headaches for Scientists, Josh Hendrickson, PC Mag, 2023. https://www.pcmag.com/news/microsoft-finally-fixes-excel-glitch-that-caused-major-headaches-for-scientists
  + includes "Years after introducing Excel's automatic conversion features, Microsoft rolls out an update to prevent it from changing gene symbols to dates."

## Papers / articles that collect multiple failure examples

* Computational science: ...Error, Zeeya Merali, Nature, 2010, https://doi.org/10.1038/467775a
* Bits and Bugs: A Scientific and Historical Review on Software Failures in Computational Science, Thomas Huckle and Tobias Neckel, SIAM, 2019. https://doi.org/10.1137/1.9781611975567
* EuSPRIG Spreadsheet Horror Stories, European Spreadsheet Productivity & Risks Interest Group. https://eusprig.org/research-info/horror-stories/
* Baldridge AS, Bellinger GC, Fleming OM, Rasmussen LV, Whitley EW, Welty LJ. The epidemiology of errors in data capture, management, and analysis: A scoping review of retracted articles and retraction notices in clinical and translational research. Journal of Clinical and Translational Science. 2024;8(1):e110. https://doi.org/10.1017/cts.2024.533


## About this repository

### Code of Conduct

This project/repository follows the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/). By participating in this project you agree to abide by its terms. Please report any violations or concerns to Daniel S. Katz at d.katz@ieee.org

### Contributing

Thanks for considering contributing to this project. Your help is essential for keeping it great.

Contributions to this project are released to the public under the [project's open source license](LICENSE). Whenever you add Content to a repository containing notice of a license, you license that Content under the same terms, and you agree that you have the right to license that Content under those terms. If you have a separate agreement to license that Content under different terms, such as a contributor license agreement, that agreement will supersede.

### Authors and credit

If you contribute to this work, such as by a pull request (PR), please also add yourself to the [`AUTHORS.md`](./AUTHORS.md) file in the same PR, ideally with your real name, your GitHub username, and your [ORCID](https://orcid.org)

If you use this work, please credit/cite it and the [authors](./AUTHORS.md).

### Submitting a pull request

1. [Fork](https://github.com/danielskatz/errors-due-to-research-software/fork) and clone the repository
2. Create a new branch: `git checkout -b my-branch-name`
3. Make your change
4. Optionally add yourself to the `AUTHORS.md` file
5. Push to your fork and [submit a pull request](https://github.com/danielskatz/errors-due-to-research-software/compare)
6. Pat yourself on the back and wait for your pull request to be reviewed and merged.

### BibTeX File

A [BibTeX][bibtex] files of citation that have [DOIs][doi] is included in this repository, see `references.bib`. It is
currently manually generated using the included [Bash][bash] script `doi2bibtex` which can parse the `README.md`.

If you are adding an entry to this `README.md` note the formatting suggested at the start of this `README.md` and please
try and use the URL format for the [DOI][doi] (prepend the DOI with `https://doi.org/`
e.g. `https://doi.org/10.1186/1471-2105-5-80`). You can then regenerate `references.bib` using the following.

``` shell
./doi2bibtex > references.bib
```

See `doi2bibtex -h` for help on usage. Remember to include the changes to `references.bib` in your commit.

This script uses the following free software.

- [gawk][gawk]
- [Bash][bash]
- [cURL][curl]

[gawk]: https://www.gnu.org/software/gawk/
[bash]: https://www.gnu.org/software/bash/
[bibtex]: https://www.ctan.org/pkg/bibtex
[curl]: https://curl.se
[doi]: https://www.doi.org/
