Files of Project
Data Curation.ipynb 			- Contain code of using API to obtain data from TMDB

Data Cleaning.ipynb			- Contain code of cleaning the data obtain from json file 

Exploratory Analysis.ipynb		- Contain code of doing Exploratory Analysis and Insights

Model Training and Conclusion.ipynb	- Contain code of model training, model evaluation, model improvement and Conclusion 

decision_tree1.png - This is the image download from the Model Training and Conclusion.ipynb [In. 106]

decision_tree2.png - This is the image download from the Model Training and Conclusion.ipynb [In. 102]

decision_tree3.png - This is the image download from the Model Training and Conclusion.ipynb [In. 100]

* The reason we submit the 3 png files because the image was a bit large and may not be clear if just by looking into the jupyter notebook.


US Age Rating Meaning
NR    - No rating Information 
G     - All ages admitted. There is no content that would be objectionable to most parents. 

PG    - Some material may not be suitable for children under 10. These films may contain some mild language, 
        crude/suggestive humor, scary moments and/or violence. No drug content is present. There are a few 
        exceptions to this rule. A few racial insults may also be heard. 

PG-13 - Some material may be inappropriate for children under 13. Films given this rating may contain sexual content, 
        brief or partial nudity, some strong language and innuendo, humor, mature themes, political themes, terror and/or 
        intense action violence. However, bloodshed is rarely present. This is the minimum rating at which drug content is present.

R     - Under 17 requires accompanying parent or adult guardian 21 or older. The parent/guardian is required to stay with the 
        child under 17 through the entire movie, even if the parent gives the child/teenager permission to see the film alone. 
        These films may contain strong profanity, graphic sexuality, nudity, strong violence, horror, gore, and strong drug use. 
        A movie rated R for profanity often has more severe or frequent language than the PG-13 rating would permit. 
        An R-rated movie may have more blood, gore, drug use, nudity, or graphic sexuality than a PG-13 movie would admit. 

NC-17 - These films contain excessive graphic violence, intense or explicit sex, depraved, abhorrent behavior, explicit drug abuse,
        strong language, explicit nudity, or any other elements which, at present, most parents would consider too strong and therefore 
        off-limits for viewing by their children and teens. NC-17 does not necessarily mean obscene or pornographic in the oft-accepted 
        or legal meaning of those words. 


Meaning of each Classification report
Report A:
Classification report taken from fitting random forest with max_depth = 20
without optimising the hyperparameter max_depth

Report B:
Classification report taken from fitting random forest with max_depth = 81 after optimising the hyperparameter max_depth

Report C:
Classification report taken from fitting random forest with max_depth = 81 with additional NC-17 data

Report D:
Classification report taken from fitting random forest with max_depth = 81 with additional NC-17 data and drop features that have no significance to the Age Rating