# Bacterial-Specific-feature-Selection-for-Enhanced-Antimicrobial-Peptide-Activity-Predictions 
## Developers: Hamid Teimouri and Angela Medvedeva

There are several classes of short peptide molecules, known as antimicrobial peptides
(AMPs), which are produced during the immune responses of living organisms against
various infections. In recent years, substantial progress has been achieved in applying
machine-learning methods to predict the activities of AMPs against bacteria. In most
investigated cases, however, the outcome is not bacterium-specific since the specific
features of bacteria, such as chemical composition and structure of membranes, are not
considered. To overcome this problem, we developed a new computational approach
that allowed us to train several supervised machine-learning models using a specific set
of data associated with peptides targeting bacteria E. coli, A. baumannii. We utilized
the Least Absolute Shrinkage and Selection Operator (LASSO) regression and Support
Vector Machine (SVM) techniques to select, among more than 1500 physio-chemical
descriptors, the most important features that can be used to classify a peptide as antimicrobial or ineffective against those species of bacteria. We then performed the
classification of active versus inactive AMPs using the Support Vector classifiers and
Logistic Regression methods. This computational study allows us to make recommendations of how to design more efficient antibacterial drug therapies.
