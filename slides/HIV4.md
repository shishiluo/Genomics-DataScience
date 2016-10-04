# Notes to HIV 4 lecture (Oct 4)
There were no slides for this lecture. Below are my notes and links I used.

## Announcements
* Project proposal due before Oct 11 class. Look in the 'projects' directory for a sample proposal
* The reading for the personal genomics topic is http://www.nytimes.com/2009/01/11/magazine/11Genome-t.html?_r=1
	- it's long, but an entertaining and informative read
* You will receive details about a mid-semester survey in the coming week

## HIV Summary
In this part of the course we have:
* Annotated a single HIV sequence
* Compared variation in two HIV genes
* Inferred evolutionary relationships between HIV sequences using Hamming Distance

## Phylogenetic forensics
See `sample_proposal.pdf` in the 'projects' directory for the background to this case. The analysis was published in the following paper:
http://www.pnas.org/content/99/22/14292.long 

### Steps for downloading data and making trees
1. Go to www.hiv.lanl.gov and navigate to the sequence database search. 
2. Using 'Pubmed ID' 12388776, search for Pol CDS and Env CDS sequences separately. Make sure to check the box for 'Include fragments ...'
3. For the 'naive' trees, select all the sequences and click on 'Make Tree'.
	- Do not include reference sequences, click OK
	- Keep the fields at their default, click Submit
	- Take a look at the output, play around with Rainbow Tree to add some color to the tree
	- Download the Fasta alignment (before gapstripping) as you can use this for the more sophisticated tree construction
4. For the more sophisticated tree construction, navigate to 'PhyML' in the 'Tools' section of the website
	- Paste the alignment you just downloaded, or upload the file
	- Leave everything as default for the first run, you can play around with things later
	- Submit, and explore the different tree outputs.