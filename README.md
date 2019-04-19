# confidence_database

This is a database of simple confidence studies. The purpose of the database is to enable easy access to the data of many different datasets. The data from each dataset is organized in an identical manner with the following fields:
- Subj_idx: the subject number
- Stimulus: stimulus identity (for most studies, 1 or 2)
- Response: subject's response (for most studies, 1 or 2)
- Confidence: subject's confidence rating
- RT_decision: the decision reaction time (RT)
- RT_confidence: the confidence reaction time (RT)
- Difficulty: the contrast, coherence, or any other measure of trial difficulty

For datasets where the stimulus is a continuous quantity (e.g., orientation), the fields stimulus and response are continuous.

For studies that collected the decision and confidence with a single button press, RT_confidence is set to 0.

For all datasets, there is either a single condition or a manipulation that only has a minimal effect on subjects' performance. Example manipulations include transcranial magnetic stimulation to different brain areas, presence or absence of trial-by-trial feedback, etc. 

Detailed descriptions of each dataset will be provided in a forthcoming paper. Datasets will be added as they become available. Currently, the database consists of 2 datasets (we expect to have 20-30 datasets by the end of May 2019). A brief description of the existing datasets is provided below:

Dataset #	Subjects	Trials/subject	Authors	    Year	Journal	Which experiment	            Conf scale
1	      175	        97	            Bang et al	2019	JEP:G	  Expt 2, fine discrimination	  1-4
2	      175	        97	            Bang et al	2019	JEP:G	  Expt 2, coarse discrimination	1-4

IMPORTANT!
We welcome new contributions! If you have data (either published or unpublished) that meets the criteria above (basically, it can be summarized in the above format), please consider sharing your data. Any entry received by May 30, 2019 will ensure that the contributor will be a co-author on the resulting paper. You can contribute your dataset by emailing it in the above format to Doby Rahnev at drahnev@gmail.com.