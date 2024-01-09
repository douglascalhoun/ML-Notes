# ML Notes

Data science: any profession dealing with data (including AI & ML). An interdisciplinary field that uses scientific methods, processes, algorithms and systems to extract knowledge and insights from noisy, structured and unstructured data, and apply knowledge and actionable insights from data across a broad range of application domains.

Artificial intelligence: computer systems able to perform tasks that normally require human intelligence
  - visual perception
  - speech recognition
  - decision-making
  - language translation

Sub-disciplines
  - Reasoning, problem solving
  - Knowledge representation
  - Planning
  - Learning
  - Natural language processing
  - Perception
  - Motion and manipulaion
  - Social intelligence
  - General intelligence

Applications:
  - Autonomous vehicles (drones, self-driving cars)
  - Medical diagnosis
  - Creating art (visual, poetry)
  - Proving mathematical theorems
  - Playing games (Chess, Go, Starcraft)
  - Search engines
  - Online assistants
  - Image recognition
  - Spam filtering
  - Prediction of judicial decisions
  - Targeting online advertisements

Machine Learning: algorithms trained on data to learn patterns to make predictions. The use and development of computer systems that are able to learn and adapt without following explicit instructions, by using algorithms and statistical models to analyze and draw inferences from patterns in data.

Learning (ML): 3-step process
  - Infer / Predict
  - Error / Loss
  - Train / Learn


Supervised learning
  - Vision (CNN)
  - Speech (RNN)

Unsupervised
  - Market segmentation

Reinforcement & Semi-Supervised
  - Planning (DQN)
  - Games (chess, Mario)
  - Robot movement

Deep Learning and Neural Networks
Stack our logisitic regression units into a multi-layer perceptron (MLP)
Stacked shallow learning: Logistic regression = lego, Neural Network = castle

Feature learning identifies and optimizes features from raw data

Artificial neural network (ANN): a machine learning model based on the human brain's neural structure. Interconnected nodes (neurons) organized into layers.

Multi-layer perceptrons (MLP) are fully connected feed-forward artificial neural networks with an input, output and hidden layers

Convolutional neural network (CNN): An artificial neural network that specializes in processing data with a grid-like topology, such as recognizing patterns an image.


Deep Q-Networks (DQN) use a reinforcement learning algorithm to learn how to make decisions.

Recurrent Neural Networks (RNN): 
  - supervised deep learning algorithm
  - sequential / time series data
  - uses past information to improve the performance for future inputs. 

MLP: Perceptron vs LogReg / sigmoid activation
Architecture
(Feed forward) Input => Hidden Layers => Hypothesis fn
"Feed forward" vs recursive (RNNs, later)
(Loss function) Cross entropy
(Learn) Back Propagation
Price ~ smoking + obesity + age^2
1-layer MLP
Face? ~ pixels
Extra layer = hierarchical breakdown
Inputs => Employees => Supervisors => Boss
Backprop / Gradient descent
Optimizers: adagrad, adam, gradient descent
Silver bullet, but don't abuse
linear (housing market)
features don't combine
expensive: like hiring a company when the boss h(x) does all the work
Brian comparison (dentrites, axons); early pioneers as neuroscientists / cogsci
Different types
vs brain
Activation fns
Activation units / neurons (hidden layer)
Relu, TanH, Sigmoid
