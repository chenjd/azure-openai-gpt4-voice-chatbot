# azure-openai-gpt4-voice-chatbot

In project, we’ll explore how to integrate Azure OpenAI service and Azure Speech service to create a chatbot that users can interact with via voice.

## What is the difference between Azure OpenAI and OpenAI
Azure OpenAI Service provides customers with access to advanced language AI capabilities through OpenAI’s GPT-4, GPT-3, Codex, and DALL-E models, all with the added security and enterprise support of Azure. Co-developed with OpenAI, Azure OpenAI ensures compatibility and a seamless transition between the two platforms. By using Azure OpenAI, customers can leverage the same models as OpenAI while benefiting from the security features of Microsoft Azure, such as private networking and regional availability. Additionally, Azure OpenAI promotes responsible AI by offering content filtering capabilities.

[Comparing Azure OpenAI and OpenAI](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/overview?WT.mc_id=DT-MVP-5001664#comparing-azure-openai-and-openai)

## Installation

Create a virtual environment:

```bash
python3 -m venv venv
```

This will create a new virtual environment in a subdirectory called "venv".

Use pip to install dependencies:

```bash
pip install azure-cognitiveservices-speech
pip install openai
```

## Blog post
[Integrating Azure OpenAI and Azure Speech Services to Create a Voice-Enabled Chatbot with Python and GPT-4](https://levelup.gitconnected.com/integrating-azure-openai-and-azure-speech-services-to-create-a-voice-enabled-chatbot-with-python-60a39f838367)







