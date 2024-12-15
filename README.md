#   Configuration Text For AI Assistant That Reads & Documents Abusive Messages

 
This GitHub repository contains the configuration text for a large language model assistant designed to assist the user to document verbally abusive messages received through digital channels. These might be emails, WhatsApp conversations, or messages received through any other digital channel.

The configuration text was drafted with a very specific and painful use case in mind.:

Many individuals who receive hurtful and abusive messages from toxic people find that reading these communications provokes anxiety, trauma, and upset. Equally, those who receive such messages commonly find that recording them serves a few important and useful purposes. 

For one, having an objective record of the communications received can serve as a tool against the tendency of victims' abuse to engage in self-gaslighting. Those who receive messages like this can over time convince themselves that they weren't as hurtful or bad as they really were. 

Many individuals who have been on the receiving end of messages such as these are also in therapy. Given that we can't have our therapists wearing invisibility cloaks and hiding in the background when we're being abused, recording and summarising the messages received can serve as a “next best thing. “

The configuration text for this assistant was written with exactly these kind of dynamics and situations in mind. Its objective is twofold. Firstly to shield the user from reading the original message. The mechanism it uses to do this is by providing a summary of the communication, and then a trigger warning and finally white space. 

The purpose of the whitespace instruction is to provide room for the user to avoid accidentally seeing the message unless they wish to do so. Finally, the assistant is configured to copy the original message in its entirety for the purpose of documentation. The configuration instructions here were designed to cover the most common use cases, such as the user providing a copy of a text message or a screenshot of a communication exchange on WhatsApp. 

In order to be as portable as possible, the configuration text was written to not assume that the underlying model has vision capability. Given that LLMs with vision are increasingly becoming the norm and will undoubtedly be the standard in the very near future, the user may wish to remove this instruction in order to avoid confusing the model. 

The useful thing about LLM assistants is that they are relatively portable. Whether the configuration is written in natural language like this one or in JSON, they can be easily shifted around between platforms and to a good extent they're also model agnostic. This particular assistant doesn't require anything advanced such as a RAG pipeline or exposure to real-time events. Any model with good reasoning capabilities would be suitable to deploy this on top of. This assistant could be provisioned on OpenAI or on Hugging Face Chat. I have an assistant running for anyone who wishes to use it on the latter platform. 

The configuration text here is shared on an open source basis to allow anyone who wishes to tweak the configuration to better reflect the specific circumstances of their own abuse to freely do so. Some instructions, however, might be generally useful, including the instruction to the model to assume the context of abuse as an underlying dynamic, which can make the direction of the output more deterministic without needing to do things like manually configure temperature settings. 

The configuration is open-ended as to whether the end user is the victim of abuse or someone who is assisting them. The intention here is that someone might be willing to read the original message and verify that the model has correctly copied it for posterity before deleting the original communication. 


## Config (V2)



