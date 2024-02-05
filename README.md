# AmbiguityChecker for natural language requirements. 
The ambiguity checker prototype automatically classifies English natural language requirements as either ambiguous or non-ambiguous.

##Context:.

Requirement engineers need to evaluate and answer customer requirements in a short time. The analysis of the requirements is extensive and time-consuming as it implies analysing hundreds of requirements per project. One of the phases of the analysis is to check for ambiguity in the given requirement text as in real-life contexts requirements can be abstract or ambiguous, i.e., they can be interpreted in more than one way.  The overall goal is to support the requirement engineer experts by automatically analysing and classifying the requirements in terms of their ambiguity. Furthermore, working towards explainable AI, the models provide the term that add to ambiguity extracted from each requirement.

##Key Features:

•	NLP Processing: utilized NLP techniques to work with textual requirements, such as TF-IDF.

•	AI and ML: binary models are trained and used to classify requirements as ambiguous or not, by providing a level of confidence and an explanation for the classification.

•	User-Friendly Interface: a web application is provided, where users can upload the requirements to check for presence of ambiguity. 

##How It Works:

•	Input: Using the web interface, the users can upload requirement written in English as either excel file or manually type the requirement to check for the presence of ambiguity.

•	Processing: the input entered is processed by employing NLP techniques.

•	Classification: ML/AI models are trained and used to classify the requirements as ambiguous or not. The models have learned from the data in the training phase and are capable of classification on new requirements (user input).

•	Output: For each requirement, the user is provided with a classification class(Ambiguous or Not Ambiguous),a confidence level of such classification, and an explanation that includes terms that add to the ambiguity. The user has the possibility to provide their own validation directly after the classification and feedback/ comments,that will be further incorporated into the model. Based on the user validation and the model outcomes metrics (True Positiove, True Negatives, False Positives, False Negatives) can be calculated to assess the model's performance.


A mock up of the tool is provided in Prototype_mockup.pdf.
