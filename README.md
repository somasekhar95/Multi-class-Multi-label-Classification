# Multi-class-Multi-label-Classification
Multi-class Multi-label Classification using Support vector Machines

Each data instance has three labels: Families, Genus, and Species. Each of the labels has multiple classes. We wish to solve a multi-class and multi-label problem. One of the most important approaches to multi-class classification is to train a classifier for each label. I've used SVM with gaussian kernel and Linear SVM with L1 penalty. Used SMOTE upsampling to account for class imbalance. Also used Classifier chain method. Evaluated using Exact match and hamming score
