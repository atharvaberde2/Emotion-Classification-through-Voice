# Business Case
My friend and I have observed that many individuals, despite appearing to live normal lives, harbor hidden problems that significantly affect their emotional well-being. These hidden griefs often manifest in subtle changes in their speech patterns, which can be difficult for others to detect. The inability to recognize these emotions through voice can lead to misunderstandings and strained relationships. To promote a friendly and empathetic community, we decided to develop a machine learning model capable of recognizing people's emotions from their voice. This tool aims to bridge the gap in emotional understanding, fostering better communication and support among individuals.

# Executive Summary
We began by gathering our training data, which included 50 different words and phrases spoken in seven different emotions. We then uploaded these audio files into a Jupyter Notebook and used a tool to transform each audio file into a representation of sound frequencies. We organized this data into a table to match the frequencies with the corresponding emotions. To clean our data, we removed any duplicates and checked for any missing values.

After ensuring our data was clean, we split it so that 75% would be used for training our model and 25% for testing it. We trained our model using a neural network, which is a type of machine learning technique, with various layers to process the audio data. Finally, we trained and tested the model, which provided us with 86% validation accuracy, meaning that it was able to correctly classify 86% of the voices it hadn't seen.

# What is next

To further enhance our model, we plan to incorporate data augmentation techniques to create a dataset that is more capable of handling variations in voice pitch and background noise. We also aim to explore advanced architectures such as Recurrent Neural Networks (RNNs) or Transformers, which may better capture temporal dependencies in voice data. Furthermore, we seek to expand the range of emotion classes to include more nuanced emotions like sarcasm, resulting in a more comprehensive emotion classification system. Most importantly, we plan to develop it into a user-driven app that can allow people to record their voices, and it will classify their emotion, allowing the model to respond accordingly.

# Tools used
Jupyter, Librosa, Python, Tensorflow, Scikit-Learn
