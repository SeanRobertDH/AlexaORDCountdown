# AlexaORDCountdown
Simple ask Alexa how many days to your ORD date

to use:
 01 create an acount on 'https://developer.amazon.com/alexa'
 02 head over to 'https://developer.amazon.com/alexa/console/ask' and create a new skill
 03 name the skill anything you want
 04 set default language to the same as your Alexa (UK and US are different)
 05 select 'custom model' and 'alexa-hosted' backend resources.
 06 click 'Create skill' and wait untill it's done
 07 set 'how many days' as invocation skill name
 08 navigate to 'HelloWorldIntent' and delete all sample utterances.
 09 add in the utterances 'order', 'audi', 'oh r. dee', 'oh are dee' and 'o. r. d.'.
 10 click on 'Save Model' and 'Build Model'
 11 navigate to 'Code' in the toolbar above.
 12 replace 'index.js' code with the code in the git 'index.js'
 13 Replace date with your own ORD date
 14 click on 'Save' and 'Deploy'
 15 run in test enviroment to see that it works
 16 Make sure you don't have any conflicting skills with the invocation name 'how many days'.
 17 say 'Ask how many days to ORD'

note* The command cannot be shortened to 'how many days to ORD' due to skill invocation structure.
