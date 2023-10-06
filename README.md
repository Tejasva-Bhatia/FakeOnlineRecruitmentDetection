# FakeOnlineRecruitmentDetection
Detection of Fake Online Job Postings Using Machine Learning Techniques

There are a numerous amount of job postings on the internet and sometime these vacancy postings turns out to be fake. Even on the reputed and trusted job advertising platforms, people fall prey to these fake job advertisements. After selection in the job, hiring people start demanding for money and details of bank account. Good number of candidates gets duped and lose loads of money and sometimes even their current jobs. So it would be very helpful to identify if the job listed on the website is real or fake. In this project, I have used machine learning to detect fraud job vacancy postings.

The data set availaible on the internet was highly imbalanced. So I used two data balancing techniques namely “Adaptive Sympathetic” and “Synthetic Minority Oversampling Technique” in combination with “Term Frequency-Inverse Document Frequency” which is a feature extraction method. Some projects have used “Bag of Words” for extraction of features which could just count the no. of times of the word appeared whereas the technique used in this research work (i.e TF-IDF) also provides the importance of words. The public “Employment Scam Aegean Dataset” (EMSCAD) was used which contained around 18000 job listings out of which about 800 are fraud listings. We have used two machine-learning models such as Random Forest and k-nearest classifiers in combination with above two data set balancing techniques to detect whether the online job is fake or real. 


Dataset Link:- https://www.kaggle.com/datasets/amruthjithrajvr/recruitment-scam

If you want to read in detail about this project, here, is a link to my paper :- https://ieeexplore.ieee.org/document/10074276
