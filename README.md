# Digit_recoganizer_notebook
Python notebook for digit recoganizer competition on kaggle.
MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.


### *Notebooks*
[Conv2D Basics: Blueprint for Success](https://www.kaggle.com/code/lipsitac/conv2d-basics-blueprint-for-success)
[Transfer Learning Tune-Up(with grid search)](https://www.kaggle.com/code/lipsitac/transfer-learning-tune-up-with-grid-search)

### Initial discovery of the potential of Basic Conv2D 💡🧑‍🔬️: 
> To get the baseline for the digit recognizer competition we used a straightforward convolutional neural network (Conv2D), embracing simplicity with layers such as MaxPooling, flattening, dense, and an output layer. And to our surprise, we got an accuracy score of 0.9836 on our first submission which was quite good given that the model architecture was cardinal. To experiment more around the base lin notebook we tried grid search and kfold on it and the accuracy improved by 0.00579(our best score so far).


### Unlocking the hysteria of transfer learning 🛠️:
>As we got a pretty good accuracy score just by submitting our baseline notebook we thought of going an extra mile to get better results. We decided to use transfer learning, a technique that has shown great promise in improving accuracy in various image classification tasks. But what we got contrasted with what we expected. Our transfer learning base underperformed and couldn’t beat the baseline score. Later going through some references and notebooks we came to know that transfer learning acts as a great catalyst especially when the given data is smaller. But here in the digit recognizer, we had more than sufficient data that the push of transfer learning was redundant. 

### Did using just basic Conv2D layers suffice for achieving high accuracy?🧐🙆‍♀️
>Despite experimenting with all the techniques and models above we concluded that regardless of how much transfer learning has shown excellent results in other image classification tasks, we believe that further research and experimentation are necessary to determine the optimal approach for this specific problem. We could use this(transfer learning) method to understand the depth of its functionality however it would be better if we look for other ways that could give us further favorable outcomes.


**PS: Also feel free to comment your opinion on both our notebooks mentioned at the start of the discussion.**
