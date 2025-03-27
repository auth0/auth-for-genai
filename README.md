# Auth for GenAI

[Auth for GenAI](http://auth0.com/ai) provides a robust security framework designed specifically for GenAI applications. It ensures both secure user authentication and fine-grained access control for AI agents, granting them access to only authorized data.

Auth for GenAI secures your AI agent workflows:

* Seamless implementation and integration with your existing architecture.  
* Comprehensive security controls for both human users and AI agents.  
* Enterprise-grade protection that builds user trust and confidence.  
* Ecosystem compatibility with leading GenAI frameworks and tools

## Core Functionalities

* **Authentication for AI agents**  
  Implement secure authentication flows for your GenAI applications. This feature integrates the Universal Login you already know and love into your GenAI apps.  
* **Call APIs on the User's Behalf**  
  Securely connect AI agents to external tools, functions, and services. Expand your GenAI application capabilities by integrating with other specialized tools through secure APIs.  
* **Asynchronous User Confirmation**  
  Enable secure human-in-the-loop workflows. Asynchronously connect with the user and prompt for authentication and authorization.  
* **Fine-Grained Authorization for RAGs**  
  Enable your RAG to account for access control policies. Only let your RAG use documents your user can access to provide answers.

## Get started

Read the [Auth for GenAI documentation](http://auth0.com/ai/docs) to learn how to implement secure authentication and authorization in your Generative AI applications. The docs cover what Auth for GenAI is, quickstarts to get you up and running, key use cases, guides, and best practices to help you seamlessly secure AI agents, enforce fine-grained access control, and connect to external APIs with confidence.

### SDKs

* Start building with the Auth0 SDKs which have been updated to include AI capabilities such as Federated Connections and Async User confirmation:  
  * [Next.js SDK](https://github.com/auth0/nextjs-auth0)  
  * Fastify SDK  
  * FastAPI SDK  
    

* Management SDKs:

  * [Python SDK](https://github.com/auth0/auth0-python)  
  * [Node.js](https://github.com/auth0/node-auth0)  


* To help you build with your LLM framework we have built these SDKs:  
> [!WARNING]
> These are currently under development and are not intended to be used in production, and therefore has no official support:
   
  * [Auth0 AI for Javascript](https://github.com/auth0-lab/auth0-ai-js)  
    * [auth0/ai](https://github.com/auth0-lab/auth0-ai-js/tree/main/packages/ai): Base abstractions for authentication and authorization in AI applications.  
    * [auth0/ai-vercel](https://github.com/auth0-lab/auth0-ai-js/tree/main/packages/ai-vercel): Integration with [Vercel AI](https://sdk.vercel.ai/) framework.

  RAG specific SDKs

    * [auth0/ai-genkit](https://github.com/auth0-lab/auth0-ai-js/tree/main/packages/ai-genkit): Integration with [Genkit](https://firebase.google.com/docs/genkit) framework  
    * [auth0/ai-llamaindex](https://github.com/auth0-lab/auth0-ai-js/tree/main/packages/ai-llamaindex): Integration with [LlamaIndex.TS](https://ts.llamaindex.ai/) framework  
    * [auth0/ai-langchain](https://github.com/auth0-lab/auth0-ai-js/tree/main/packages/ai-langchain): Integration with [LangchainJS](https://js.langchain.com/docs/introduction/) framework.  
  * [Auth0 AI for Python](https://github.com/auth0-lab/auth0-ai-python)  
    * [llama-index-auth0-ai](https://github.com/auth0-lab/auth0-ai-python/blob/main/packages/llama-index-auth0-ai): Integration with [LlamaIndex](https://docs.llamaindex.ai/en/stable/) framework.  
    * [langchain-auth0-ai](https://github.com/auth0-lab/auth0-ai-python/blob/main/packages/langchain-auth0-ai): Integration with [LangChain](https://python.langchain.com/docs/tutorials/) framework.

## Contribute

We want to hear from you\! To request new features, fix bugs, or improve documentation, read our [Contributor's guide](https://github.com/auth0/open-source-template/blob/master/GENERAL-CONTRIBUTING.md).  
Have questions or feedback? Join the [Auth0 community](https://community.auth0.com/).  
