# Email-Categorization

Classifying emails into different labels can have a great impact on businesses and save valuable time for organizations by quickly redirecting and responding 
to customer complaints and requests. There is a lack of annotated data available for email categorization, and hence an unsupervised classifier is ideal. 
In this study, we present a semi-supervised learning approach to automatically classify emails into user defined labels. 
By using deep learning techniques, the classifier must be more flexible and reduce the administrative and maintenance work. 
The authors conduct a number of experiments to test the performance and scalability of common machine learning algorithms with different text-representations, 
word embeddings and model architectures. A Bi-directional Long-Short Term Memory Network  classifier with a custom embedding layer showed the best
classification performance with an accuracy of 60.01% on unseen data.

The repository contains two files - `Semi_Supervised_Email_Categorization.ipynb` and `emails_3000.csv`. 
The python notebook contains the source code and the csv file is the sample dataset that is used.

To reproduce the results presented, execute all the cells in the python Notebook.
