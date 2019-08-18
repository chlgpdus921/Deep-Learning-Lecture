<h1>Lecture 1-1. Basic Machine Learning Terms and Concepts</h1>
<h2> 1.1 What is ML? </h2>

    - Machine Learning
    - Some kind of software
    - exit programming 

    ex) Spam filter: It is difficult to deal with spam because there are many rules.
    ex) Automatic driving: There are many rules.

    Let's learn automatically from certain phenomena instead of programming daily! <br>
    Programming with the ability to learn data, to learn something
<hr/>
<h2> 1.2 What is learning? </h2>
  <b> Certain data must be given in advance to learn. Depending on how you learn, there are two types of learning: </b>

    - Supervised learning
    - Unsupervised learning

<h3> 1.2.1 Supervised learning </h3>
<b> learning with labeled examples (training set already) </b>

    ex) A program that looks at an image and automatically does it whether it's a cat or a dog. 
    - To learn with a labeled cat examples  

<h3> 1.2.2 Unsupervised learning </h3>
<b> To learn by looking at data that is not to make labeled by oneself </b>

    ex) Google news is hard to decide in advance. 
<br>   

This lecture will mainly deal with supervised of two learning type. Because this is most problem.
> ex) Image labelling <br>
> ex) Spam filters <br>
> ex) Test results prediction (how many hours have been studied and what is the result) <br>
<hr/>
<h2> 1.3  Types of supervised learning </h2>
<h3> 1.3.1 What is regression?</h3>

    A program that predicts test scores according to study time.
    Score (Range 0-100) - This is called regression because it has a wide range.

<h3> 1.3.2 What is classfication? </h3>
<h3> 1.3.2.1  Binary classification </h3>

    Pass/non pass system according to study time
    This is called classification because it is to choose between the two.
    But two range, This is called Binary classification.
    
<h3> 1.3.2.2  Multi-label classification</h3>

    A system that predicts grades according to study time.
    It's one of five (A,B,C,D,F), so  classification.
    It is called Multi-label classification because there are many labeled.
<hr/>
<h2> 1.4 Supervised learning Examples </h3>
<h3> 1.4.1 Regression </h3>
   
     X (time) | 10 9 3 2
     Y (score)| 90 80 50 30
     IF X = 7 (time) , Y = 75 (score)
     
<h3> 1.4.2 Binary Classification </h3>

    X (time) | 10 9 3 2
    Y (score)| P P F F
    Pass/Non-pass
    
<h3> 1.4.3 Multi-label Classification </h3>

    X (time) | 10 9 3 2
    Y (score)| A B D F
