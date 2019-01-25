-------------------------------------------
MedQuAD: Medical Question Answering Dataset  
-------------------------------------------

MedQuAD includes 47,457 medical question-answer pairs created from 12 NIH websites (e.g. cancer.gov, niddk.nih.gov, GARD, MedlinePlus Health Topics). The collection covers 37 question types (e.g. Treatment, Diagnosis, Side Effects) associated with diseases, drugs and other medical entities such as tests.  

We included additional annotations in the XML files, that could be used for diverse IR and NLP tasks, such as the question type, the question focus, its syonyms, its UMLS Concept Unique Identifier (CUI) and Semantic Type. 
We  added the category of the question focus (Disease, Drug or Other) in the 4 MedlinePlus collections. All other collections are about diseases.  
 
The paper cited below describes the collection, the construction method as well as its use and evaluation within a medical question answering system.   

N.B. We removed the answers from 3 subsets to respect the MedlinePlus copyright (https://medlineplus.gov/copyright.html):  
(1) A.D.A.M. Medical Encyclopedia, (2) MedlinePlus Drug information, and (3) MedlinePlus Herbal medicine and supplement information. 
-- We kept all the other information including the URLs in case you want to crawl the answers.  
 

If you use the MedQuAD dataset, please cite the following paper: "A Question-Entailment Approach to Question Answering". Asma Ben Abacha and Dina Demner-Fushman. arXiv:1901.08079 [cs.CL], January 2019.   

	@ARTICLE{019arXiv190108079A,    
		   author    = {Asma {Ben Abacha} and Dina Demner{-}Fushman},
		   title     = {A Question-Entailment Approach to Question Answering},
		   journal = {arXiv e-prints}, 
		   year      = {2019}, 
		   month = {January},
		   archivePrefix = {arXiv},
                   eprint = {1901.08079},
 		   primaryClass = {cs.CL},
		   url = {https://arxiv.org/abs/1901.08079}
		   }     


Contact Information
-------------------
- Asma Ben Abacha: asma.benabacha@nih.gov
- Dina Demner-Fushman: ddemner@mail.nih.gov 
