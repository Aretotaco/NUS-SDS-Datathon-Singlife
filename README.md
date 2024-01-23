# NUS-SDS-Datathon-Singlife

# Submission Instructions

1. Rename the submission notebook as "NUS_DATATHON_SINGLIFE_\<TEAM NAME\>.ipynb". For example, if your team name is "NUS 1", your submission notebook should be named as "NUS_DATATHON_SINGLIFE_NUS 1.ipynb". \
The notebook already contains a template function, named `testing_hidden_data`, to take in the test data and output the predictions. You are to fill in the function with your model and any preprocessing function that you may have. \
Note: Each team should only submit one notebook and the notebook should be in the `master` branch.

2. You can save your model and upload it in the GitHub repository provided that it does not exceed the file size limit on GitHub (see Section 3 on instructions for large models). You are to provide a script the load the model. Please name the loading function as `load_model`. \
If the model is not saved, we will assume that the model is trained using the training function and the output of the training model is a model that can be is trained using the template function, `testing_hidden_data`, provided in the notebook. Please name the training function as `train_model`.

3. If your model is too large to be uploaded to GitHub, you can upload it to Google Drive and share the link with us. Please ensure that the link is accessible by anyone with the link. Please provide a `LOAD_MODEL_INSTRUCTIONS.md` file in the GitHub repository to explain how to load the model. Note that you are strongly discouraged to use such large models. 