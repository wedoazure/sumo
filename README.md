![alt text][logo]

# sumo
A python command line app that will summarise your input text file using Azure OpenAI.

This is based on Microsoft Learn lab files.

# Pre-reqs 

You will need a deployment of Azure OpenAI, don't forget it is a gated service, so you need to apply for it.  

I would recommend GPT35 for this app, it works well and is cheaper than GPT4!

Locally, you will need Python installed. Once installed, you can add the rest of the requirements using the below:

pip install python-dotenv  
pip install openai  

# Customise

You will need to use the provided text file, or bring your own. Update the relative text_file variable in the sumo file.

You can modify the Temperature of the model used by modifying the creativity variable, don't forget, bigger equals more creative.

You will also need your own env file, with the following entries for your own Azure OpenAI instance.

AZURE_OAI_ENDPOINT=  
AZURE_OAI_KEY=  
AZURE_OAI_MODEL=  

Note: Model is the name you have given to your deployment.

[logo]: wdLogo.png "WeDoAzure Logo"
