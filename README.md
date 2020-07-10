                                
# Project 1 -Fact Extraction and Automated Claim Verification
* Verify textual claims against textual sources by retrieving relevant evidence from Wikipedia pages.
* Dataset: FEVER (Fact Extraction and VERification) dataset
* Contains 185,445 claims manually verified against introductory section of Wikipedia pages
* Each claim annotated as SUPPORTED, REFUTED and NOTENOUGHINFO
* For the first two classes, evidence provided to support or refute the claim.


# Task:
* Find and retrieve Wikipedia pages which are most relevant to the claim.
* Extract a set of sentences from the retrieved Wikipedia pages that support or refute the claims. These set of sentences form the evidence for the claim.
* Using this evidence, classify the claim as Supportedand Refuted.
* If there isn’t sufficient evidence to support or refute a particular claim, label the claim as NotEnoughInfo.

* Evaluation:
* Classification Task: Accuracy
* Evidence extraction: Precision, Recall and F1 score

# My contribution
* To facilitate the fake news validation developed an Automatic Fact Check Claim Verification web app with the 2017 Wikipedia dump where Python’s Flask library was used for the model deployment on web.
* Used Python’s NLP’s RAKE and textblob library to extract keywords from the claim to retrieve the most relevant Wikipedia documents and used Python’s Spacy and TF-IDF that improved evaluation of sentence similarity between corresponding Wikipedia document’s sentences and the given claim.


