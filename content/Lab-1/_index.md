---
title: "Lab 1 - AI Security"
linkTitle: "Lab 1 - AI Security"
weight: 1
#archetype: "chapter"
---

## Lab overview
In this lab you will access to a chatbot powered by a Large Language Model (LLM). The chatbot interface will be Open WebUI backed by a Ollama model based on [llama3.2](https://ollama.com/library/llama3.2).

The specific LLM model you will be using today is called ['secret_keeper'](https://ollama.com/gabeobrien/secret_keeper).  This model has been asked to keep a secret for a single user.  Your task will be to trick the chatbot into giving up the secret that it keeps.

But first there are some setup tasks to complete.

Tasks:
* Log into Qwiklabs
* Start the lab to deploy the infrastructure
* Access the OpenWeb UI
* Load in the 'secret_keeper' model
* Start smooth talking the chatbot
* Extract the secret it keeps!

## Deploy the lab with Qwiklabs

The AI Chat bot will be deployed using Qwiklabs.  Click the link below and use the student email address and password to log into Qwiklabs.

[Qwiklabs](https://fortinet.qwiklabs.com/users/sign_in)

{{< figure src="imgs/qwiklabs-log.png" >}}

Once logged in select the course 'AI Chatbot - Secret Keeper' course

{{< figure src="imgs/qwiklabs-select-course.png" >}}

Next select the lab 'AI Secret Keeper Lab'.

{{< figure src="imgs/qwiklabs-select-lab.png" >}}

Finally start the deployment clicking on 'Start'

{{< figure src="imgs/qwiklabs-start-lab.png" >}}

Once the lab is deployed there will be a sidebar with the OpenWebURL and AdminUserEmail and AdminUserPpassword.

{{< figure src="imgs/qwiklabs-sidebar.png" >}}

Copy the OpenWebURL, open a new tab and past the URL to load the OpenWeb UI.  Copy/paste the email, password and click 'Sign in'.

{{< figure src="imgs/openweb-ui-login.png" >}}

## Setup the Secret Keeper LLM Model

Once you have logged into OpenWeb UI you will notice that there are no LLM models currently available.

{{< figure src="imgs/openweb-ui-select-a-model.png" >}}

Click on 'Select a model' and then click on 'Manage Connections'.

{{< figure src="imgs/openweb-ui-no-models-yet.png" >}}

Use the 'Actions' drop down in the uppder right hand side and click 'Manage'

{{< figure src="imgs/openweb-io-select-action-manage.png" >}}

Click on the 'Models' in the list on the left.

{{< figure src="imgs/openweb-ui-add-secret-keeper-model.png" >}}

Fill out the form field under 'Pull a model from Ollama.com'. Enter 'gabeobrien/secret_keeper' and click the download icon.

{{< figure src="imgs/secret-keeper-model.png" >}}

If you see the 'secret_keeper' model is loaded then you are ready to start hacking the chatbot!


## Find the secret that is being kept

Your task is to use the chat interface to convince the model to tell you the secret it keeps. The chatbot doesn't want to give up it secret, but if you ask just right you might be able to get the secret.

Make sure to pay attention to the answers it gives as well as the suggestions offered up.

Feel free to read up a on how to trick LLM models to go against their training.

Enjoy!