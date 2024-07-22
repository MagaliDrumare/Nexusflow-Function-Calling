# Athene-Llama3-70B Released: An Open-Weight LLM Trained through RLHF based on Llama-3-70B-Instruct - July 2024 
Nexusflow has released Athene-Llama3-70B, an open-weight chat model fine-tuned from Meta AI’s Llama-3-70B. Athene-70B has achieved an Arena-Hard-Auto score of 77.8%, rivaling proprietary models like GPT-4o and Claude-3.5-Sonnet. 
- https://www.marktechpost.com/2024/07/21/athene-llama3-70b-released-an-open-weight-llm-trained-through-rlhf-based-on-llama-3-70b-instruct/


# Nexusflow-Function-Calling with LLM 

We are thrilled to open source NexusRaven-V2, a 13B LLM outperforming GPT-4 in zero-shot function calling, the capability to turn natural language instructions into executable code to use tools. The function calling capability lies at the core of the OpenAI Assistants API, and serves as the key to enabling copilots and agents to use software tools. With the goal of advancing open source models for copilots and agents, NexusRaven-V2 marks an exciting step in collaboration with the community to expand the open model ecosystem for technological and societal impacts. The highlights of this release include:

- State-of-the-art & Generalizable Capability. NexusRaven-V2 surpasses GPT-4 by up to 7% in function calling success rates in human-generated use cases involving nested and composite functions. NexusRaven-V2 has never been trained on the functions used in evaluation.
- Open-source and Commercially Permissive. NexusRaven-V2 is further instruction-tuned on Meta's CodeLlama-13B-instruct, leveraging curated data generated through Nexusflow's pipeline, exclusively sourced from open-code corpora without using proprietary LLMs. It is commercially permissive for both community developers and enterprises.
- Ease of Integration. We release open-source utility artifacts that enable users to seamlessly replace mainstream proprietary function calling APIs with NexusRaven-V2 in their software workflow. We also provide online demos and Colab notebooks for onboarding and integration demonstration.
- Function Calling Benchmark and Leaderboard. We open source our evaluation benchmark Nexus-Function-Calling and establish a Huggingface leaderboard which includes an extensive collection of real-life human-curated function-calling examples, covering a diverse range of function-calling use cases and difficulties. These hundreds of examples, across 9 tasks, have been curated with input from domain experts, and their ground truth has been meticulously checked. We open source 8 out of the 9 benchmarks, leaving one as an internal benchmark for testing new models.

### Nexusflow 
- https://nexusflow.ai/

### Function-Calling and Data Extraction with LLMs
- https://www.deeplearning.ai/short-courses/function-calling-and-data-extraction-with-llms

