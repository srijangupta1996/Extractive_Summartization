# Extractive_Summartization

India has a common law system that prioritizes the doctrine of legal precedent over statutory law, and where legal documents are often written in an unstructured way. These legal judgements are often quite long, and typically taking long man hours to go through it.

A solution to this problem is to develop summary for these judgements. The gist of judgement documents should encode important experience and viewpoints of the Supreme Court, and provides instrumental and educational information for judges, lawyers, practitioners, and students. But, summarization of such judgements requires specialized law professionals that are not only expensive, but very less in number.

To tackle this problem, what we propose is a Text Summarization mechanism. Text summarization is an extraction of important text from the original document. The objective of any automatic text summarization system, especially in legal domain, is to produce a summary which is close to human-generated summaries. Based on our observation of the existing gist statements, we can treat the generation of the gist as a sentence classification problem. This is a demonstration of developing extractive summarization of Indian Supreme Court (Legal) judgements.

# Acknowledgements

First of all I would like to thank Prof. Saptarshi Ghosh and Prof. Pawan Goyal, part of Department of Computer Science at IIT Kharagpur, for providing us the project topic to work on. We are really grateful to their class room teachings for this course which provide us good foundation to start our work on this project.

I seek to express my deep and sincere gratitude to Ms. Paheli Bhattacharya, who took time to hear, guide and always available over a phone call or email, whenever we ran into any trouble or question about the project. She consistently steered us in the right direction throughout the project journey.

Last but not least I express deepest gratitude to my team mates, Kowshik Moyya, Anadi Vashisht, and Suman Basak, who supported each other during difficult times of the project.

# Problem Statement

With this project, we intend to develop a mechanism for summarization of legal documents as binary classification problem where fitness of the solution is derived using Extractive Summarization Technique, based on the statistical features of each sentence such as length of the sentence, type of entity, degree of similarity, term frequency–inverse sentence frequency and keywords to generate summary of the document.

Let R denote the statements of the full text section, our goal is to build a service, V, that is able to select some statements S, from R, that can serve as the summary statements, G.

V(R) → S

We treat this task of sentence selection as a classification problem. In addition to considering some relevant features based on knowledge and observations of linguistic and legal perspectives, we also employ different types of word vectors. We realized the service V with classifiers that were designed based the concepts of logistic regression, gradient boosting, neural networks, and some other methods.
