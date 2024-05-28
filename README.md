# Summarization-and-Key-point-extraction-using-LangChain
Summarization and Key point extraction using LangChain


In this section, I have created a sample input data (basically conversation between a financial agent and customer). He need to invest some amount retirement amount. He is seeking some advice from the agent about low risk profile for the investment.

I have used Langchain to extract the folloing things from the transcript:
1. Summary of the conversation.
2. Key pointextraction.

We know that sometime model halucinate their result, so inorder to verify the model doesn't halucinate and providing the correct result, I am validating result across the transcript. Basically the result will contain from which part of the transcript the model have picked the key points.

I have also compared the result with 
1. Legacy models like GPT3.5 Turbo
2. Very recent and much efficient model like GPT4o model.
