# Machine Learning Projects using AWS Sagemaker Service

### Sentiment Analysis using XGBoost In Built Algorithm provided by AWS Sagemaker

***Following steps are followed -***
1. Download or otherwise retrieve the data.
2. Process / Prepare the data.
3. Upload the processed data to S3.
4. Train a chosen model using Jupyter Notebook instance
5. Test the trained model (typically using a batch transform job).
6. Deploy the trained model.
7. Use the deployed model.

***In addition, the XGBoost model comprises three objects -***<br />
Model Artifacts- Stored on s3 <br />
Training Code - Using Inbuilt XGBoost container <br />
Inference Code - Using Inbuilt XGBoost container <br />

### Sentiment Analysis using PyTorch (LSTM Model) with custom code using AWS Sagemaker
Same approach followed as above. 
In addition, for PyTorch training and inference code, we added custom code. For this reason, we provided seperate code for - <br />

**train** - Code provided includes custom model code, requirements file for additional libraries required with pytorch and train file to train the model. <br />
**serve** - Code provided includes custom model code, requirements file for additional libraries required with pytorch and predict file for preprocessing inputs and 
model predictions <br />

The model follows the below mentioned approach for Deployment -

![ModelDeployment](https://github.com/shlbatra/AWS_Sagemaker_Projects/blob/main/Web%20App%20Diagram.svg)
