---
title: "Lab 1 - AI Security"
linkTitle: "Lab 1 - AI Security"
weight: 1
#archetype: "chapter"
---

## Lab overview
In this lab you will access to a chatbot powered by a Large Language Model (LLM). The chatbot interface will be Open WebUI backed by a Ollama model based on [llama3.2](https://ollama.com/library/llama3.2).

The specific LLM model you will be using today is called ['secret_keeper'](https://ollama.com/gabeobrien/secret_keeper).  This model has been asked to keep a secret for a single user.

## Access Open WebUI

Use the credentials below to access the Open WebUI to start hacking on the chatbot.

{{< figure src="imgs/openweb-ui-login.png" >}}

> Username: user@user.com <br>
> Password: ThisIsHowYouLogIn <br>

Ask you teacher for the URL to the OpenWeb UI site.
<!--
> [Open WebUI](http:///) <br>
-->
Ensure that the model select is the 'gabeobrien/secret_keeper' model.

{{< figure src="imgs/secret-keeper-model.png" >}}

<!--
## First load the 'secretkeeper' model

Select a model -> Manage Connections

Models -> Actions -> Manage

Pull a model from Ollama.com -> gabeobrien/secret_keeper -> Download button

Close out all the dialogues.

Confirm that gabeobrien/secret_keeper is the selected model
-->

## Find the secret that is being kept

Your task is to use the chat interface to convince the model to tell you the secret it keeps. The chatbot doesn't want to give up it secret, but if you ask just right you might be able to get the secret.

Make sure to pay attention to the answers it gives as well as the suggestions offered up.

Feel free to read up a on how to trick LLM models to go against their training.

Enjoy!