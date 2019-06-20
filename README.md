# AlexaORDCountdown
Simple ask Alexa how many days to your ORD date  
  
to use:  
 01 Create an acount on 'https://developer.amazon.com/alexa'.  
 02 Head over to 'https://developer.amazon.com/alexa/console/ask' and create a new skill.  
 03 Name the skill anything you want.  
 04 Set default language to the same as your Alexa (UK and US are different).  
 05 Select 'custom model' and 'alexa-hosted' backend resources.  
 06 Click 'Create skill' and wait untill it's done.  
 07 Set 'how many days' as invocation skill name.  
 08 Navigate to 'HelloWorldIntent' and delete all sample utterances.  
 09 Add in the utterances 'order', 'audi', 'oh r. dee', 'oh are dee' and 'o. r. d.'.  
 10 Click on 'Save Model' and 'Build Model'.  
 11 Navigate to 'Code' in the toolbar above.  
 12 Replace 'index.js' code with the code in the git 'index.js'.  
 13 Replace '31 December 2099' on line 15 with your own ORD date.  
 14 Click on 'Save' and 'Deploy'.  
 15 Run in test enviroment to see that it works.  
 16 Make sure you don't have any conflicting skills with the invocation name 'how many days'.  
 17 Say 'Alexa, ask how many days to ORD'.  
  
note* The command cannot be shortened to 'how many days to ORD' due to skill invocation structure.  
