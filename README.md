# Auth for GenAI

Auth for GenAI provides a robust security framework designed specifically for GenAI applications. It ensures both secure user authentication and fine-grained access control for AI agents, granting them access to only authorized data.

Auth for GenAI secures your AI agent workflows:

- Seamless implementation and integration with your existing architecture.
- Comprehensive security controls for both human users and AI agents.
- Enterprise-grade protection that builds user trust and confidence.

## Get started

- Read the [Auth for GenAI documentation](https://sko-labs-poc.vercel.app/ai/docs) to learn about use cases and features. 
- Start building with Auth0 SDKs:
    - [Next.js SDK](https://github.com/auth0/nextjs-auth0)
    - [Python SDK](https://github.com/auth0/auth0-python)
    - [Node.js](https://github.com/auth0/node-auth0)
    - [Auth0 AI for Javascript](https://github.com/auth0-lab/auth0-ai-js)
    - [Auth0 AI for Python](https://github.com/auth0-lab/auth0-ai-python)

## Project structure

- [nextjs-auth0](https://github.com/auth0/nextjs-auth0): Next.js SDK
- [auth0-python](https://github.com/auth0/auth0-python): Python SDK
- [node-auth0](https://github.com/auth0/node-auth0): Node.js SDK
- [auth0-ai-js](https://github.com/auth0-lab/auth0-ai-js): Auth0 AI for Javascript
	- [auth0/ai](https://github.com/auth0-lab/auth0-ai-js/tree/main/packages/ai): Base abstractions for authentication and authorization in AI applications.
	- [auth0/ai-genkit](https://github.com/auth0-lab/auth0-ai-js/tree/main/packages/ai-genkit): Integration with [Genkit](https://firebase.google.com/docs/genkit) framework
	- [auth0/ai-llamaindex](https://github.com/auth0-lab/auth0-ai-js/tree/main/packages/ai-llamaindex): Integration with [LlamaIndex.TS](https://ts.llamaindex.ai/) framework
	- [auth0/ai-langchain](https://github.com/auth0-lab/auth0-ai-js/tree/main/packages/ai-langchain): Integration with [LangchainJS](https://js.langchain.com/docs/introduction/) framework.
	- [auth0/ai-vercel](https://github.com/auth0-lab/auth0-ai-js/tree/main/packages/ai-vercel): Integration with [Vercel AI](https://sdk.vercel.ai/) framework.
- [auth0-ai-python](https://github.com/auth0-lab/auth0-ai-python): Auth0 AI for Python
	- [llama-index-auth0-ai](https://github.com/auth0-lab/auth0-ai-python/blob/main/packages/llama-index-auth0-ai): Integration with [LlamaIndex](https://docs.llamaindex.ai/en/stable/) framework.
	- [langchain-auth0-ai](https://github.com/auth0-lab/auth0-ai-python/blob/main/packages/langchain-auth0-ai): Integration with [LangChain](https://python.langchain.com/docs/tutorials/) framework.

## Contribute

We want to hear from you! To request new features, fix bugs, or improve documentation, read our [Contributor's guide](https://github.com/auth0/open-source-template/blob/master/GENERAL-CONTRIBUTING.md).

Have questions or feedback? Join the [Auth0 community](https://community.auth0.com/).