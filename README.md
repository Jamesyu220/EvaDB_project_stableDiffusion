# EvaDB_project_stableDiffusion   
### Install EvaDB
Please refer to the website of EvaDB to setup the environment.  
https://evadb.readthedocs.io/en/stable/source/overview/getting-started.html  

### Install stable diffusion python tools  
Please run these codes to install the python tools for image generation:  
```
pip install replicate
pip install openai
```  
### Play with the Text-to-Image transformation
Please go to the directory apps/text-to-image and run:  
```
python text-to-image.py
```  
After entering your prompts, you can choose which tool you want, either Replicate, DALL-E, or both.  
Then you need to enter the API key for the tool.  
For Replicate, sign in to Replicate by your Github account and get the API key.  
For DALL-E, sign in to your OpenAI account and select API, click your icon on the right up side, and click "View API keys" then create a new secret key.  
If the environment set up successfully, the program will show image URLs on the terminal.