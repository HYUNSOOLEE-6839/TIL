# Today I Learned
<br>

## Day-01
- Study and Summary of Python's Basic Grammar and Calculations.

## Day-02
- **Studied and Summarized**
1. Array programming through the *Numpy-Package*
2. Data_Analysis through the *Pandas-Package*

## Day-03
- **Studied and Summarized**
1. Data-Visualization with *Matplotlib*
2. Prediction of Iris Variety by Basic-Machine-Learning Techniques

## Day-04
- **Studied and Summarize**
1. Found missing data through the *Basic-package(MissingNo)* of data preprocessing
2. learned about the document preprocessing capabilities through the basic methods of *scikit-learn*
3. studied Tokenizer to Wordcloud through the *NLTK* natural language preprocessing package.

### From today,
I am planning to study from the beginning thorugh a new lecture instead of reviewing what I have learned before. 😁😁
- **Basic_Concepts_01** : The study of Python's *basic concepts* and strings, lists and tuples and dictionaries.
- **Basic_Concepts_02** : Studying *Conditional* and *Repeated Statements*.

## Day-05
- **Basic_Concepts_03** : Definition and use of *Functions*, and study of parameters, *Lambda Functions*
- **Basic_Concepts_04** : Studied various functions implemented within *Module* and studied *class, object and method.* Among them, I studied *Class Inheritance, method override, etc.* in detail.
- **Basic_Concepts_05** : I studied the *Regular Expression*, and found the pattern through various methods such as meta-character and minimum-matching.

## Day-06
- Used *BeautifulSoup4* to crawling the web such as the title and date of the Internet news article.

## Day-07
- Studied Web-Page crawl using *Selenium* and crawled on several pages including Automative-Login and Automative-Searching.
- The operating system that I used to study crawling was Window OS, and I felt that there was a small difference when I used MAC OS this time, and it was a good opportunity to fix the code one by one, not by searching.

## Day-08
- I studied how to handle *multi-dimensional* data usingn the Numpy and how to change or slicing these data into different dimensions. In particular, the concept of the axis was clearly established, and it was realized that it could be used in various fields or in various fields, and that it was simpler and more convenient to operate a computer by aligning shapes with broadcasting functions.
- Furthermore, using the basic *Matplotlib*, I was able to graph my defined fuctions or results as desired, and I was able to draw graphs more neatly and easily recognizable through styling each graph.

## Day-09
- Through the *Pandas* module, I study how to leverage Series and DataFrame to organize, reconstruct, and classify the given data easily.
- Future learning plans will be used in Machine-Learning based on what has been learned and reviewed so far, and I have established a basic concept of what is in Machine-Learning.

## Day-10
- I looked at the types of machine learning, and we also looked at what role each model plays, and what kinds of deep learning exist.
What was impressive was that **"the fourth industrial revolution that is happening now"** by looking at various techniques such as improving the picture quality or changing the day and night of the background through Deep Learning's "GAN" model.
- It studied the conformity assessment and experimental design process of the model, and established the concept of 'overfitting'.

## Day-11
- I studied the basis of 'statistics' that will be used in whether it is machine learning or deep learning, which were statistical probabilities and distribution, statistical reasoning, and tests.  which were difficult to understand, but I was able to establish concepts by applying them in real life as an example.

## Day-12
- I studied the mathematical concepts of differentiation and matrix, simple regression analysis. Among them,  Tested and estimated the regression coefficient, and practiced simple linear regression with Boston's house price as an example.

## Day-13
- Using Boston housing price data as an example, we studied multiple linear regression analysis, including crime rate, number of rooms per house, and ratio of lower classes in the population through three variables.
- As a result, the overall model had the smallest residuals, each variable had a low p-value, and the rate of variation of y described as three variables overlapped.
In other words, we show that the regression model I used is not bad to use even though it is multi-communication.

## Day-14
- Multilinear regression analysis was conducted through data from Toyota car prices and Boston house prices, and the contents included how to diagnose multicollinearity, regression diagnosis, regression model determination, and variable selection methods.
- The contents are organized while studying multi-linear regression analysis. 
<br>
1) Data is pre-processed. <br>
2) Train the model. <br>
3) The p-value of the R-square or variable shows that 'this model has some performance'. <br>
4) Based on domain knowledge, determine which variables to remove after checking the variables. <br>
5) While checking multicollinearity through coordination matrix or VIF, recognize that 'this variable also needs to be erased'. If there are one or two variables to erase, you can erase them daily, but if there are many, use variable selection method. <br>
6) While checking the response, check that the model is well-suited to a certain extent. <br>
7) Be sure to check the performance for validation_data and select a model. 


<br>

- Practiced *logistic regression* through Personal Loan dataset.

## Day-15
- I studied how to reduce the regression coefficient through *Ridge and Lasso*, and studied dimension reduction through *PCA*.
- After studying *regression analysis*, I started to study machine learning in earnest. In its contents, we study *Naive-Bayes* models and study *KNN*. While studying KNN, we considered solving the overfitting problem through Cross-Validation, and we were able to establish the concept through various materials. Furthermore, while practicing on KNNs, we experienced in-house increasing the performance of KNNs in certain situations through methods that give less weight even if they are in the same Neighbor, and gave us an opportunity to consider how to improve accuracy through multiple techniques.

## Day-16
- Until today, I have completed basic studies of basic machine learning models, including *LDA, QDA, SVM, neural network models, and decision trees*.
- The Iris data were classified through decision trees based on Sepal_length and Sepal_width, and the difference in accuracy was determined by giving different Depths for each classification.
- While studying machine learning, there was a change in accuracy or significance depending on how each variable or parameter was designated, and it was possible to pick out data discretization or wrong data through coding without direct calculation, and these processes were able to learn the technology to be honest and accurate.
- From tomorrow, I will study *'ensemble'* which uses a mix of these techniques.

## Day-17
- Today, we studied *'ensemble'*, a concept that utilizes several basic models to create one new model.
- Using single tree-based models, I changed the number of sampling, and verified with post-fitting evaluation data for decision tree models, showing better accuracy.
- The most interesting study, "Random Forest," showed that performance, like any other model, did not improve any more, and coding showed that it could achieve 100% accuracy with proper sampling and depth.
- The question here was, **'Why not use a more complex model of deep learning to predict it would be more accurate?'**, and the answer was to coding myself, but machine learning, a relatively simple technique, was more accurate. We realized that simple models have high accuracy even with simple techniques, and complex techniques can produce poor results.'
- In other words, it can be easily likened to **'using grenades to catch mice?'**
- While studying machine learning and ensembles, the most important thing in improving accuracy is Feature_selection, which laid the foundation for thinking about what techniques and models should be used for each data and type.

## Day-18
- In the morning, I studied clustering as an example of 'Boston house price' and visualized and compared the results of K-Means and DBSCAN.
  > It is generally known that K-Means lag behind DBSCAN.

- This example, which does not produce good results of DBSCAN, which has the characteristics of clusters between things at a close distance, is a special example, and will be demonstrated through other examples later.

- In the afternoon, I studied "Credit Card Fraud Detection Data" as an example, drew a graph for each variable for the target variable, and defined the variables with differences through the graph.
- In addition, I wanted to get results using modules such as LightGBM and XGBoost, but this module did not work on my Mac M1 operating system, so I will study them more deeply through other computers later.

## Day-19
- I started studying Deep-Learning from today, and I learned Mnist handwriting data through Tensorflow and saw the results.
- The results showed a high accuracy of 97.32%, and I felt that a single line of code adding the module could produce tremendous results.
- I have since studied several active functions, loss functions, and neural network architectures, and have also implemented Perceptron.

## Day-20
- Today, I studied optimization theory, and while studying indiscriminate substituting methods, the question was raised, 
   > "Can't I find the answer after putting it in less?"
- In that way, the results of this algorithm were visualized using Gradient Descent and the results were obtained to answer the questions raised.
- Later, I also studied Back Propagation, and conducted a hands-on study on deep neural network learning using numerical differentiation.
<br>

#### This is the summary of deep neural network learning using numerical differentiation.
1) In order to obtain a numerical gradient, the standard loss must be obtained. <br>
2) Move as much as epsilon each scalar what you want to learn to obtain a new loss function. <br>
3) Calculate the difference between the loss function and the standard loss function. <br>
4) As much as epsilon has been moved, divide it into epsilon and obtain it according to the Numinal Gradient definition, and store the Gradient in the corresponding Scalar location.

## Day-21
- I studied several neural networks today, including CNN, RNN, and TNN.
- One of the most impressive was CNN, which was particularly useful in finding patterns to recognize images.
- In the course of studying this, I learned about the need for Padding and how to handle a useful technique called Zero-Padding.
- While studying about the pooling layer, I wonder
  > "Wouldn't making a lot of pooling layers produce results quickly and compactly?" 
- through the characteristics of "passing the pooling layer reduces the size of the images and aggregates information."
- The practice proved my question wrong.
- And then studied underfitting, overfitting, and drop-out, and practiced how to prevent overfitting. 
- To improve this, several techniques such as Early Stopping Callback and Drop-out were used, and since these techniques did not prevent overfitting, the number of neurons in "Dense 4" could be increased to prevent overfitting.
- Although it did not improve dramatically, Early Stopper prevented it from climbing indefinitely.

## Day-22
- Today, I studied about MNN.
- In this process, several learning modules were conceptually explored, and the study of transfer learning and Fine-Tuning was focused. 
- The reason for using transfer learning is,
1) Addressing the shortage of datasets. <br>
2) Cost reduction.<br>
3) Less manpower required for learning. <br>
A total of three things can be summarized.
- To summarize while studying Fine-Tuning,
  > 'In general, layers that have been Knowledge Transfer do not learn after Freeze, but only new layers.' <br>
  
  > "However, if the learning data set is large enough, it is okay to learn all layers.'
- It can be arranged as above.

- The interesting thing was that my computer had never overheated before when I was doing machine learning or other tasks, but as I was practicing Transfer Learning learning, learning was interrupted by a large amount of RAM consumption compared to specifications, reducing batch_size of data from 32 to 8 and using GPUs via Google's Colab.
- Although the speed was slow and it took a while, the accuracy was close to 100%, showing satisfactory results.
- Until today, I have finished studying Python's main grammar, machine learning, and deep learning techniques, and from now on, I am going to do various projects using what I have learned so far.
- For example, data analysis using advertising data or data analysis using shopping mall order data.
- It is planning to proceed from projects using Pandas to projects using deep learning step by step.

## Day-23
- Today, I visualized sales (all, country, month, day of the week, hour by hour) through the virtual shopping mall customer order data, and made data-based decisions through customer cohort analysis and monthly repurchase rate analysis.
#### The agenda was, "When should I send a push message when I send a coupon?"
- It is meaningless to send a push message without considering the time when the order is made, and there will be no basis for judgment in the future when the same event occurs.
- In the current state, I thought it was the most intuitive judgment to do at the time when the most orders were made.
The process is,
1. Data identification
2. Propose a hypothesis
3. Hypothesis verification
 There are 3 different types of results obtained 1 to 3 times.
  > Since consumption patterns may vary from user to user, the solution was to find the most purchased time zone and send coupons at that time.
  > In other words, it is efficient to target customers individually by time zone.
