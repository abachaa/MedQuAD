-------------------------------------------
MedQuAD: Medical Question Answering Dataset  
-------------------------------------------

MedQuAD includes 47,457 medical question-answer pairs created from 12 NIH websites (e.g. cancer.gov, niddk.nih.gov, GARD, MedlinePlus Health Topics). The collection covers 37 question types (e.g. Treatment, Diagnosis, Side Effects) associated with diseases, drugs and other medical entities such as tests.  

We included additional annotations in the XML files, that could be used for diverse IR and NLP tasks, such as the question type, the question focus, its syonyms, its UMLS Concept Unique Identifier (CUI) and Semantic Type. 
We  added the category of the question focus (Disease, Drug or Other) in the 4 MedlinePlus collections. All other collections are about diseases.  
 
The paper cited below describes the collection, the construction method as well as its use and evaluation within a medical question answering system.   

N.B. We removed the answers from 3 subsets to respect the MedlinePlus copyright (https://medlineplus.gov/copyright.html):  
(1) A.D.A.M. Medical Encyclopedia, (2) MedlinePlus Drug information, and (3) MedlinePlus Herbal medicine and supplement information. 
-- We kept all the other information including the URLs in case you want to crawl the answers. Please contact me if you have any questions.  
 
-------------------
QA Test Collection  
-------------------

We used the test questions of the TREC-2017 LiveQA medical task:  https://github.com/abachaa/LiveQA_MedicalTask_TREC2017/tree/master/TestDataset. 

As described in our BMC paper, we have manually judged the answers retrieved by the IR and QA systems from the MedQuAD collection. 
We used the same judgment scores as the LiveQA Track: 1-Incorrect, 2-Related, 3-Incomplete, and 4-Excellent. 
-- Format of the qrels file: Question_ID judgment Answer_ID 

The QA test collection contains 2,479 judged answers that can be used to evaluate the performance of IR & QA systems on the LiveQA-Med test questions:  https://github.com/abachaa/MedQuAD/blob/master/QA-TestSet-LiveQA-Med-Qrels-2479-Answers.zip

----------
Reference  
---------- 

If you use the MedQuAD dataset and/or the collection of 2,479 judged answers, please cite the following paper: "A Question-Entailment Approach to Question Answering". Asma Ben Abacha and Dina Demner-Fushman. BMC Bioinformatics, 2019.    

	@ARTICLE{BenAbacha-BMC-2019,    
		  author    = {Asma {Ben Abacha} and Dina Demner{-}Fushman},
		  title     = {A Question-Entailment Approach to Question Answering},
		  journal = {{BMC} Bioinform.}, 
		  volume    = {20},
  		  number    = {1},
     		  pages     = {511:1--511:23},
  		  year      = {2019},
  	url       = {https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-3119-4}
		   }     
		   
License
- The MedQuAD dataset is published under a Creative Commons Attribution 4.0 International Licence (CC BY). https://creativecommons.org/licenses/by/4.0/

Contact
-  Asma Ben abacha (abenabacha at microsoft dot com)
