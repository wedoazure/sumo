![alt text][logo]

# sumo
A python command line app that will summarise your input text file using Azure OpenAI.
This is based on Microsoft Learn lab files.

# pre-reqs 

You will need a deployment of Azure OpenAI, don't forget it is a gated service.

I would recommend GPT35 for this app, it works well and is cheaper than GPT4.

# customise

You will need to use the provided text file, or bring your own. Update the relative text_file variable in the sumo file.

You will also need your own env file, with the following entries for your own Azure OpenAI instance.

AZURE_OAI_ENDPOINT=
AZURE_OAI_KEY=
AZURE_OAI_MODEL=

Note: Model is the name you have given to your deployment.

[logo]: wdLogo.png "WeDoAzure Logo"
