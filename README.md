# Identification of ATP Binding Residues

We have carried out a brief implementation of the paper
“Identification of ATP binding residues of a protein from
its primary sequence” and attempted to improve on the existing methods by using different machine learning techniques,
an extended dataset and optimized parameters on the models.

ATP is an important ligand that plays a critical role as a
coenzyme in the functionality of many proteins. Hence, it is
essential to develop novel methods for identifying ATP interacting residues in ATP binding proteins in order to understand
the mechanism of protein-ligands interaction. This can be done
via simple statistical methods or supervised machine learning
techniques.

The given paper discussed a Support Vector Machine
(SVM)-based method to perform classification. It compared the
amino acid composition of ATP interacting and non-interacting
regions of proteins and concluded that certain residues are
preferred for interaction with ATP. It trained and tested the
model (carried out cross validation) on 168 non-redundant
ABP chains. The SVM based model using primary sequence
of proteins obtained a maximum MCC of 0.33 with validation
accuracy of 66.25 %.

We managed to obtain an improved cross validation accuracy
of 69.58 % and MCC score 0.393 using a larger training set
and an optimized SVM model.
