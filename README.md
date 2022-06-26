# BiomechanicalFeaturesofOrthoPatients

Predicting biomechancial features of orthopedic patients. This is introductory practice with pandas, numpy, and scikit learn.

About Dataset
Context
The data have been organized in two different but related classification tasks.

column3Cweka.csv (file with three class labels)

The first task consists in classifying patients as belonging to one out of three categories: Normal (100 patients), Disk Hernia (60 patients) or Spondylolisthesis (150 patients).
column2Cweka.csv (file with two class labels)

For the second task, the categories Disk Hernia and Spondylolisthesis were merged into a single category labelled as 'abnormal'. Thus, the second task consists in classifying patients as belonging to one out of two categories: Normal (100 patients) or Abnormal (210 patients).
Content
Field Descriptions:

Each patient is represented in the data set by six biomechanical attributes derived from the shape and orientation of the pelvis and lumbar spine (each one is a column):

pelvic incidence
pelvic tilt
lumbar lordosis angle
sacral slope
pelvic radius
grade of spondylolisthesis
Acknowledgements
The original dataset was downloaded from UCI ML repository:

Lichman, M. (2013). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science

Files were converted to CSV

Inspiration
Use these biomechanical features to classify patients according to their labels
