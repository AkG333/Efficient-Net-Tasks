Worked on one of the datasets available at Kaggle to identify whether a vehicle is an ambulance or a normal vehicle. To tackle the given task I used EfficientNetB2 model. 
I already have an experience working with EfficientNet in an ML challange held at my University where we were given a multi classification task where there were 397 labels and 62000 images each belongs to one of the labels.
Here I'll be providing both of my notebooks you can have a look and can find the similarity in the pipeline.
EfficientNet stands out because it improves accuracy and efficiency at the same time—something older CNN models struggled with.

🔑 Key Idea: Compound Scaling

Instead of scaling just one aspect of a neural network (like depth or width), EfficientNet scales three dimensions together:

Depth → more layers
Width → more neurons per layer
Resolution → larger input images

This method is called compound scaling, and it ensures balanced growth of the model.
Im sorry that I dont have that 62k images dataset for now but here is the ambulance dataset link have a binary classified dataset
https://www.kaggle.com/datasets/mahmoudshaheen1134/ambulance-dataset
