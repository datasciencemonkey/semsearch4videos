This repo holds the code for the blogpost 
[Turbocharge Deep-Discovery with LLMs for Videos and Podcasts](https://dsmonk.medium.com/simplify-deep-discovery-using-a-i-for-your-videos-and-podcasts-using-databricks-langchain-661e22d10489)

Couple of useful titbits:
1. The code was developed in Databricks MLR 13.0
2. The model can be deployed straight into [Databricks Model Serving](https://learn.microsoft.com/en-us/azure/databricks/machine-learning/model-serving/) as an Endpoint.
3. While it's not shown in the notebook here, the process can be set to run on a schedule and the index can be upgraded using [Databricks Workflows](https://learn.microsoft.com/en-us/azure/databricks/workflows/)