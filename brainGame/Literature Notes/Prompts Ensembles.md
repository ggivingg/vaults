
**The Prompt-Model Ensemble**
* prompts are model specific (prompts are tied to models)
	* a prompt that works perfectly for one model wont necessarily work for another model
* **Measurement**: how do you measure the fidelity of the prompt-model ensemble? 
	* is it the same experiment if you slightly change the prompt per model? 
* **Model Reliability**: when you have a stable model, there is the possibility that your model has a poisoned back door (modern security practice requires you to presume this is the current case). You update your model to a now presumed safe semantic upgrade. You now run the series possibility of having a no longer functioning prompt. 
* **ML SDLC for Prompts**: The PM Ensemble requires a robust machine learning SDLC. 
	* is this metaflow, mlflow, vertexAi? or an agent for metrics