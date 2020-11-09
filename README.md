# covid19-faq-bot
Covid19 FAQ Bot is a chatbot and live chat solution for COVID-19 related FAQ's.

## Requirements

rasa

python3


## How to run 

Train a unified NLU and dialogue model by running the below command:

$ rasa train

Once the model is trained, you can load it and talk to your assistant by running:

$ rasa shell

The command above will load your assistant for you to test. If, for example, you want to test only the NLU model, you can use:

$ rasa shell nlu

Launch the Rasa X UI. In your project directory run the command below:

$ rasa x
