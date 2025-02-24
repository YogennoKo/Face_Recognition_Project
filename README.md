# Face Recognition Project паролвд
This project implements the face recognition pipeline very crookedly in three stages: 
1) Detection using MTCNN
2) Alignment using Xception(I do not know why it is so designated, although everywhere it is essentially just getting facial nodes)
3) And the recognition itself, which unfortunately I could not get to work. Even with no understanding of what needs to be done. 

I trained it on triplet loss and measured 
the ID rate metric, also tried to use SVM to achieve at least some 
separation on the plane, it seemed to give some results, but this is not what I would like
```
Look at Face_recognition_experiments.ipynb file
```
