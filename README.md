# Text Classification Competition - Twitter Scarcasm Detection
This task is to detect sarcasm from contextual tweets and beat the baseline performance of F1 = 0.723.

## Voiced Presentation (Demo) Link
https://mediaspace.illinois.edu/media/t/1_685r9kih

## Setup for prediction generation on test dataset
- Please open the Twitter_Scarcasm_Detection_Source_Code.ipynb file from Google Colab. ([Link directly to Colab](https://colab.research.google.com/drive/1zdFscVYnBDxvAE3_vmEyTzYV_cYO7WkX?usp=sharing))
- Go to *Runtime* -> *Change runtime type*, and make sure it has **GPU** selected as Hardware accelerator and **High-RAM** as Runtime shape.
- Go to *Runtime* -> *Run all*. It takes approximately 5 minutes to complete.
- Before you download the answer.txt, you can also look at the validation F1 score, which is usually ~0.83. You can use the *Table of contents* toolbar on the left to navigate to section 7. Evaluation.
- Use the *Files* toolbar on the left, go to *outputs* -> *Twitter_Sarcasm_Detection*, and you should be able to see answer.txt.

## Final Result on test dataset
F1 = 0.7626858

## More Details
Please review the project documentation file, which includes all models I have tried and three different methods I used for Context text string. It also covers model performance comparison and different method comparison specification for this task.
