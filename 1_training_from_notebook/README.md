# Challenge 1 - Training from a Notebook

You are working for a credit card company and are one of the few people who work on fraud detection models in this company.  
You suddenly get an email from your boss saying that one of the models is experiencing some extreme model drift and needs to be replaced. They have already tried to retrain it themselves, but something didn't work and your colleague who is in charge of this model is up in the mountains today, so it's up to you to go and try to fix it.  
You reach out to your colleague and through a weak signal get to hear that the model training script is saved in a GitHub repo.  
They also mention that they unfortunately are unable to share their Data Science Project and that you need to create one from scratch. They can't remember what image they used to train the model, but they do recall that a **small** image is enough.  
Finally, they recommend to just Google the RHODS documentation, as you have not used RHODS too much yet.  

You make a list of what you need to do and get to work:

- Create a new Data Science project to get access to a Notebook and name it "NotebookTraining-*your_name*".
- Clone this git repository: [https://github.com/rh-aiservices-bu/rhods-training/tree/main/1_training_from_notebook](https://github.com/rh-aiservices-bu/rhods-training/tree/main/1_training_from_notebook).
- Run the model training notebook (train_model.ipynb).
- Run an inference by using the model testing notebook (test_model.py).
    - Specifically, try to replace Sally's (one test customer) data with Jon's (another test data) as a sanity test. Jon's data is: 
    - distance_from_last_transaction: 0.17559150228166587
    - ratio_to_median_price: 1.2942188106198573
    - used_chip: 0.0
    - used_pin_number: 0.0
    - online_order: 0.0
- Clean up after yourself by removing the Data Science project! - *Yes, we will check if you did this or not*.
