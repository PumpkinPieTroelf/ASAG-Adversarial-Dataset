# ASAG-Adversarial-Dataset
This repository contains the student crafted adversarial automatic short answer grading dataset described in: 

Filighera, A., Steuer, T., Rensing, C.: Fooling it - Student Attacks on Automatic ShortAnswer Grading. In: European Conference on Technology Enhanced Learning. Springer (2020, in press)

Please cite this paper when using the dataset. 

The dataset consists of 4 columns:
- the first contains the ID of the question which was answered (the questions can be found in questions.txt, the ID is implicitly encoded by the line number)
- the second is the actual answer
- the third contains the label assigned by the student that wrote the answer
- the fourth includes the labels assigned by the grading model during the exercise

NOTE: The answers and labels assigned by the students were not modified beyond removing line breaks. A version of the dataset with actual gold labels may be added to this repository at a later date.
