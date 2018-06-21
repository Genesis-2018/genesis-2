# genesis-2
To begin, open a terminal and run the command "git clone --branch v0.1 --recursive https://github.com/daniel-kukiela/nmt-chatbot"

Next, clone this repository or download it and uncompress it. Then move all of the documents from this repo into the nmt-chatbot repo. Ensure that requirements.txt is replaced.

Then, cd nmt-chatbot and run the command pip install -r requirements.txt

After, open the model directory and find the "hparams" and "checkpoint" files. Find and replace all instances of "/home/paperspace/Desktop" with the path that you saved the nmt-chatbot folder in. Open the "best_bleu" folder and repeat for the "checkpoint" and "hparams" files in there.

Navigate to the "sentdex_lab" folder and move the files "modded-inference.py" and "scoring.py" to the "nmt-chatbot" folder.

In the terminal, ensure you are still in the "nmt-chatbot" directory and run the command "python3 modded-inference.py" to begin communicating with the chatbot.
