# Schedule

The course schedule consists of 1 afternoon (Tuesday) and 3 "full" days (Wednesday - Friday) in the first two weeks, with 1.5 days in the last week.

The "full days" run from 09:00 - 17:00, with a break from 12:00 - 13:30.

Conceptually, mornings are predominantly related to introductions, presentations and discussion of the previous days, and are afternoons reserved for independent  work on the examples and tasks.

#### Introduction, File Formats & Genome Browsers ([Michael Baudis](https://www.imls.uzh.ch/en/research/baudis/))

##### 2018-09-18 (Tue), 13-17
* general introduction into the topic ([slides](https://info.baudisgroup.org/assets/articles_and_presentations/2018-09-18___Michael_Baudis__BIO392-Introduction-Variants__slides.pdf))
* schedule adjustment
* guidance about course room and computer use (Tina Siegenthaler)
* [reading](https://baudisgroup.github.io/BIO392-Github/literature-links.html):
    - 1000 Genomes paper
    - The sequence of sequencers paper
* tasks:
    - Genome Storage Space & Cost, e.g. required for 1000 Genomes
      * WES & WGS
      * Different file formats
         * SAM
         * BAM
         * VCF
         * FASTA
      * Associated costs
      * Cost factors
      * Raw Storage costs

##### 2018-09-19 (Wed), 09-17
* reference genome resources
* [reading](https://baudisgroup.github.io/BIO392-Github/literature-links.html):
    - "Genomics made easier"
    - UCSC genome browser tutorial
* exercise: [UCSC tutorial](https://github.com/baudisgroup/BIO392-Github/blob/master/assets/UCSC_tutorial.md)
* [Answer for UCSC tutorial](https://github.com/baudisgroup/BIO392-Github/blob/master/assets/UCSC_tutorial_answers/UCSC_tutorial_Answer.md), [genelist](https://github.com/baudisgroup/BIO392-Github/blob/master/assets/UCSC_tutorial_answers/exercise_genelist_output1.txt), [genelist_canonical](https://github.com/baudisgroup/BIO392-Github/blob/master/assets/UCSC_tutorial_answers/exercise_genelist_output2.txt)
* genome editions and coordinates
* [reading](https://baudisgroup.github.io/BIO392-Github/literature-links.html):
    - segment_liftover article
* exercise: genome liftover

##### 2018-09-20 (Thu), 09-17
* Annotating genome variants
* [reading](https://baudisgroup.github.io/BIO392-Github/literature-links.html):
    - HGVS Recommendations (not for details, though)
    - dbVar "Overview of Structural Variation" ([link](https://www.ncbi.nlm.nih.gov/dbvar/content/overview/))
    - [info slides from the morning session](assets/2018-09-20-BIO392-variant-resources-formats.pdf)
* Literature review and discussion

##### 2018-09-21 (Fri), 09-17
* Associating variants with phenotypes and diseases (focus on cancer…)
    - Use of variant databases and annotation tools ([CiVIC](https://civicdb.org), [OncoKB](http://oncokb.org/#/), [ClinGen](https://www.clinicalgenome.org/), [arrayMap](http://arraymap.org)…)
* [info slides](assets/2018-09-21-BIO392-variant-resources-arraymap.pdf) from the morning session
* Hands-on analysis of genome data
    - [copy number segmentation tutorial](assets/DNAcopy_segmentation.r) [Reference publication](https://internal.baudisgroup.org/assets/articles_and_presentations/2004-10-01___Olshen___Circular_binary_segmentation_for_the_analysis_of_array_based_DNA_copy_number_data.pdf)
    - [plink tutorial](assets/PLINK_tutorial/plink_intro%2Bexercise.pdf)
    - [variant <-> disease mapping exercise](assets/variant_diseases_session.pdf)

#### Tools & Programmatic Solutions ([Izaskun Mallona](https://www.dmmd.uzh.ch/en/research/baubec/groupmembers/imallona.html))

* [SIB Swiss Institute of Bioinformatics tutorial on UNIX](https://edu.sib.swiss/pluginfile.php/2878/mod_resource/content/4/couselab-html/content.html)
* [Unix slides](assets/imallona/1_unix.pdf)
* [Genomic formats slides](assets/imallona/2_genomics.pdf)
* [Exercises](assets/imallona/3_exercises.md)

##### 2018-09-25 (Tue), 13-17
* How are UCSC Genome Browser data stored? Why?
* Genomics data management: automation
   - Computer basics: plain text files, Unix terminal
   - Reproducibility
   - Systems set up (data download and software installs)

##### 2018-09-26 (Wed), 09-17
* Unix for bioinformatics
   - Chapter 1: What is UNIX
   - Chapter 2: The UNIX filesystem
   - Chapter 3: UNIX shell - first steps
   - Chapter 4: UNIX shell - filesystem commands
   - Chapter 5: UNIX shell - working with files

##### 2018-09-27 (Thu), 09-17
* Overview of the standard genomics data formats (I)
   - FASTA
   - FASTQ
   - SAM
   - BED
* Basic file processing for bioinformatics
  - awk, cut

##### 2018-09-28 (Fri), 09-17
* Overview of the standard genomics data formats (II)
  - GFF/GTF
  - BEDgraphs
  - Wiggle files
  - VCFs
* Indexed genomic data formats
* Exercises

#### Genome Variants to Modified Proteins ([Elif Ozkirimli Olmez](http://www.biochem-caflisch.uzh.ch/members/Ozkirimli/Elif))

##### 2018-10-02 (Tue), 13-17

* [Protein Structure Slides](assets/bio392_lecture1.pdf)
  - Protein Data Bank [PDB](https://www.rcsb.org/)
* Literature
  - [Bhattacharya R, Rose PW, Burley SK, Prlić A (2017) Impact of genetic variation on three dimensional structure and function of proteins. PLOS ONE 12(3): e0171355.](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0171355)
  - [Zehir, A., Benayed, R., Shah, R. H., Syed, A., Middha, S., Kim, H. R., et al. (2017). Mutational landscape of metastatic cancer revealed from prospective clinical sequencing of 10,000 patients. Nature Medicine, 23(6), 703–713.](http://doi.org/10.1038/nm.4333)
  - [Studer, R. A., Dessailly, B. H., & Orengo, C. A. (2013). Residue mutations and their impact on protein structure and function: detecting beneficial and pathogenic changes. Biochemical Journal, 449(3), 581–594.](http://doi.org/10.1042/BJ20121221)
* [Protein Structure Analysis Task](assets/Protein_structure_activity.pdf)

##### 2018-10-03 (Wed), 09-17
* Go over the protein structure analysis task from Tuesday. All of you did a great job!
* [Uniprot slides](assets/bio392_uniprot.pdf)
    - [Uniprot](https://www.uniprot.org/)
    - [Gene Ontology, GO](http://geneontology.org/)
* [Uniprot introduction video](https://www.youtube.com/watch?v=x9GNm2DLP-U), [Uniprot Feature viewer video](https://www.youtube.com/watch?v=JjdLtoaNpf4)
* [Uniprot activity](https://github.com/baudisgroup/BIO392-Github/blob/master/Uniprot_activity.pdf)
* [Alignment slides](https://github.com/baudisgroup/BIO392-Github/blob/master/bio392_alignmentlecture.pdf)
* [Afternoon activity](https://github.com/baudisgroup/BIO392-Github/blob/master/Uniprot_activity2.pdf)

##### 2018-10-04 (Thu), 09-17
* We start at 9:30
* [Oct 4 slides](assets/bio392_oct4slides.pdf)
* [Oct 4 activity](assets/Oct4_activity.pdf)

##### 2018-10-05 (Fri), 09-17
* Morning: Presentations on *your* protein
  - Biological relevance of your protein
  - Experimental details/methods
  - 2 key findings
  - Position of mutations on protein structure (structure figure)
  - Discussion
* Afternoon: [BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi) task

#### Review, feedback & test (Michael Baudis)

* 2018-10-09 (Tue), 13-17 ([slides](assets/2018-10-09-BIO392-variant-privacy.pdf))
  - Ontologies for metadata annotations (very brief introduction)
  - Privacy, security, society - implications of availability & possible re-identification of genome data
    - long range familial identification
    - principles of Beacon-style re-identification attack
    - "ease" of field sequencing (MinIon etc.)
* 2018-10-10 (Wed), 09-14:30
  * preparation/recap time in the morning
  * Written exam (13:00 - 14:30)
    - multiple choice and free questions
