## HACKNU hackaton 16-17 March, 2019: Google Task

> The essense of this task is as follows:
> You are given a set of 6 different pictures and input text (sentence) related to one the below six pictures. 
> Task is to find which picture belongs to that text
> Output is written in the output file

**For example:**

<img src="https://github.com/qasymjomart/hackNU_GoogleTask/blob/master/images/21/1.jpg" width="250" height="250">

<img src="https://github.com/qasymjomart/hackNU_GoogleTask/blob/master/images/21/2.jpg" width="200" height="250">

<img src="https://github.com/qasymjomart/hackNU_GoogleTask/blob/master/images/21/3.jpg" width="250" height="250">

<img src="https://github.com/qasymjomart/hackNU_GoogleTask/blob/master/images/21/4.jpg" width="250" height="250">

<img src="https://github.com/qasymjomart/hackNU_GoogleTask/blob/master/images/21/5.jpg" width="200" height="250">

<img src="https://github.com/qasymjomart/hackNU_GoogleTask/blob/master/images/21/6.jpg" width="250" height="250">

**Input text:**
A few animals might find it funny to see a goat being fed.

**Answer:** 1 (1st image)


## Text images matching solution for problem from Google in HackNU international hackathon.

First we used PyTorch image captioning model to caption images. After that, we used NLP to process the caotion text (cleaning, categorizing) and finally we utilized cosine correlation between input text and processed caption text.

## As a result, the accuracy over 70 datasets was 50% (35)

> Weights of the model are not present in the repository and can be downladed from 
https://drive.google.com/drive/folders/189VY65I_n4RTpQnmLGj7IzVnOF6dmePC for Show, Attend and Tell image captioning. 

> Weights for encoder are available using the link
https://drive.google.com/drive/folders/1DboEcIMtX6uRHQsedXM1c0oAgN4kyRRB?usp=sharing.

The following solution for image captioning was used:
https://github.com/sgrvinod/a-PyTorch-Tutorial-to-Image-Captioning
