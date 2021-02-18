# SureStart21

### Responses

*Reflection ~ 02/08*  
In this program I hope to learn to apply machine learning concepts in the real world and use the skills I learn to build cool projects that can be implemented in daily life. I also hope to meet and connect with a diverse group of people who have gone through different experiences in the computer science realm so I could learn from them and get advice from them that could help me as I get deeper into the computer science realm myself. Along with this, I hope to work on my career skills by developing my resume and Github to set myself up for applying to internships and jobs in the future.

*Reflection ~ 02/09*  
The difference between supervised and unsupervised learning is that in unsupervised learning, the model has to find patterns and relationships in the data on its own, but in supervised lerning, the data is pre-defined so the model can check how accurate it is in comparision to the actual values.
The statement that Scikit-Learn has the power to visualize data without a Graphviz, Pandas, or other data analysis libraries is false because Scikit-Learn has to use these libraries in order to create visualizations for data. It works with these different libraries and implements code from them in order to create data visuals, without them, the visuals wouldn't work.

*Reflection ~ 02/10*  
Tensors are basically mathematical representations of physical objects that can be characterized by magnitude and multiple directions (such as in the x, y, and z planes). In Machine Learning, tensors are used to represent an array of numbers in 3-dimensional space.  
In the interactive models in the TensorFlow tutorial, I noticed that many of the components had to be created first as placeholders, and then were later filled and adjusted by the specific data we were working with.

*Reflection ~ 02/11*  
This is a dataset I found with characteristics related to depression: https://www.kaggle.com/arashnic/the-depression-dataset  
It could be used to detect depression states in people based on patterns between these characteristics. I would likely use a convolutional neural network to develop this. A CNN could look at groups of characteristics related to depression, and then combine the results from the groups to output a final answer of which depression state was detected.

*Reflection ~ 02/12*  
Tried this model, worked fine. Didn't create my own (not quite sure how to do that...), just played around with this one. I'm going to continue to try to figure out creating my own though.

*Reflection ~ 02/15*  
I extended the training dataset in th Kaggle tutorial notebook by uplaoding the full training data from the MNIST database. The model with the full training dataset performed better than the model in the original Kaggle notebook. The confusion matrix in my version showed more labels correctly predicted than the one in the original notebook, this probably happened because the model in my version had more data to extract patterns and parameters from, so it was able to better understand the data and make predictions from it than the model in the original model was.

*Reflection ~ 02/16*  
I think ML concepts were utilized in the design of this game to create the automated hiring process based on my initial hiring pattern. ML was used to find patterns in how I selected applicants for hiring and how Google selected applicants for hiring, and then followed those patterns to hire applicants on its own. A real-world example of a biased machine learning model is the model used for facial recognition on iPhones. The facial recognition model does a better job at recognizing white males more than any other demographic because that's what it's training dataset mostly consisted of. This could be made more inclusive by training the model on a more diverse dataset so that it is able to recognize features on all types of faces and skin tones rather than just white males. This is an important biased model to address because many people use it in their daily lives when they're on their phones and it wastes time in people's days unnecessarily. It also limits Apple's audience to an extent because people will find the facial recognition inconvenient and might choose to switch to another phone so that they aren't wasting time in their day just trying to unlock their phones.

*Reflection ~ 02/17*  
Some differences between a CNN and a FCNN are that a CNN has multiple different types of layers while a FCNN only has fully connected layers, and a FCNN has lots of parameters and weights while a CNN doesn't have as many. In a CNN, there's first a convolutional layer that breaks apart the image into sections and classifies each section, and then there's a pooling layer that simplifies the information and retains only important details. These two layers repeat multiple times in a CNN before finally getting to the fully connected layer where all the information is put into a single vector and then given labels. Lastly, a CNN has a fully connected output layer which looks at all the labels given to the image components thus far, and then provides the one with the most weight as the output. A FCNN only has fully connected layers, so it looks at the entire image at once and all the pixels get analyzed individually. This means there are many more weights since each pixel is treated individually. CNNs are generally better to use with images because they take up less processing space with weights and they are also better at genrealizing since they classify sections of the image rather than specific pixels, so they do a better job at preventing overfitting than FCNNs do.
