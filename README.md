# IBM-Watson
I using IBM watson assistant website to create a chatbot,The website : https://www.ibm.com/sa-en/cloud/watson-assistant Before you start must be create an account.

#  Create an assistant 
1. Click the Create assistant.
2. Name the assistant.
3. Click Create assistant. 

![image](https://user-images.githubusercontent.com/86571348/126044458-707a0344-d0eb-4551-8163-7cc38452b7b9.png)

# Create a dialog skill 
1. Click the My first assistant tile to open the assistant.
2. Click Add dialog skill.
3. Name the skills.
4. Click Create dialog skill.
5. Click to open the skill you just created.

![image](https://user-images.githubusercontent.com/86571348/126044538-759ec473-296d-4dbf-9a71-65692b2aa782.png)

#  Add intents from a content catalog 
When you open the skill, you land on the Intents page.

![image](https://user-images.githubusercontent.com/86571348/126044825-c754d3c8-0fcf-4a57-aef5-808160f9a6d6.png)
Add training data that was built by IBM to your skill by adding intents from a content catalog. In particular, you will give your assistant access to the General content catalog so your dialog can greet users, and end conversations with them.
1. From the skill menu, click Content Catalog.
2. Find General in the list, and then click Add to skill.
3. Open the Intents tab to review the intents and associated example utterances that were added to your training data. You can recognize them because each intent name begins with the prefix #General  You will add the #General_Greetings and #General_Ending intents to your dialog.
![image](https://user-images.githubusercontent.com/86571348/126044904-2458d034-a452-440c-ad05-e791c60c1ad0.png)
 
#  Build a dialog

1. From the Skills menu, click Dialog.
2. Two nodes were added to the dialog for you:

Welcome: Contains a greeting that is displayed to your users when they first engage with the assistant.

Anything else: Contains phrases that are used to reply to users when their input is not addressed by any of the existing dialog nodes.

3. Click the Welcome node to open it in the edit view.
4. Replace the default response with the text, Like "Welcome to the Watson Assistant". 
5. Click Close to close the edit view.
you can add node, start to type #General_Greetings. Then, select the #General_Greetings option, Add the response text, Good day to you!
then try it !!
![image](https://user-images.githubusercontent.com/86571348/126045082-3fb3eb40-aaef-4118-a8da-b3822f05c230.png)

# Integrate the assistant 

![image](https://user-images.githubusercontent.com/86571348/126045164-e65f532e-c502-4018-b470-22a07f239327.png)

From the Integrations section, click the Preview link, Then click the URL that is displayed on the page. 

![image](https://user-images.githubusercontent.com/86571348/126045202-5f004998-906e-4e56-9c43-2b0d949a61a8.png)



