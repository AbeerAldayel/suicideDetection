# Similar Minds Post Alike: Assessment of Suicide Risk Estimation Using Behavioural Data
## clpsych shared task
In this work we are trying to build model that predicts the risk level of suicide based on users behavioural data. 
* Task B: Risk Assessment for SW posters based on their SW postings and other Reddit postings

* Link to Overleaf latex file https://www.overleaf.com/1411918554ftzbvbgrjtcs
## Main Dates
* Mar 18     Preliminary system description paragraphs due (for our overview shared task paper)
* Mar 20-22  Test set downloadable. Output (and IRB approval or determination of Exempt status) due 4 days from your download timestamp.   Submissions without documentation of IRB approval, exemption, or equivalent will not be evaluated.
* Mar 30     Final system description paragraphs due (no late submissions accepted)
* Mar 30     Short shared task papers + final system description paragraphs due (no late submissions accepted)


## Files Description:
data_sample_clpsy19: sample data
TimeFeatures.ipynb: this script computes mean time intervals from any of the two posts in text from a certain topic, topics are defined by dictionaries we created. The script also include empath features.

* dictionaries: dictionarities from different topics

* clpsych_model.py: This file contains script to train the basic ML models. 

* Features.py: This file contains script to Construct the features based on the users set provided in the basic training file [Features extraction]. 

* ExtractDictionsFromHTML.ipynb: this file extract dictions from webpages 


##Folders Description:
dictionaries: dictionarities from different topics

data_sample_clpsy19: sample data

SampleShareTask: more data for feature observations (Posts from suicide watch in Jan, 2019 and all the posts of the authors from other subreddit)

* Empath: features extracted from empath and which empath feature might be useful for our classification task

* senti_value: This file read each user post and assign the sentiment value for each file to prepare it for next step of feature construction.




