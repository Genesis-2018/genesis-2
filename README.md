# genesis-2
1. Open a terminal and run the command "git clone --branch v0.1 --recursive https://github.com/daniel-kukiela/nmt-chatbot"
2. Clone this repository or download it and uncompress it. Then move all of the documents from this repo into the nmt-chatbot repo. Ensure that requirements.txt is replaced. Download the file from https://drive.google.com/file/d/1ylntISvSmq-yBo0LXYExKbhkompgiJiH/view?usp=sharing and move it into the "nmt-chatbot/model" folder

3.  cd nmt-chatbot and run the command pip install -r requirements.txt

4. Open the model directory and find the "hparams" and "checkpoint" files. Find and replace all instances of "/home/paperspace/Desktop" with the path that you saved the nmt-chatbot folder in. Open the "best_bleu" folder and repeat for the "checkpoint" and "hparams" files in there.

5. Navigate to the "sentdex_lab" folder and move the files "modded-inference.py" and "scoring.py" to the "nmt-chatbot" folder.

6. In the terminal, ensure you are still in the "nmt-chatbot" directory and run the command "python3 modded-inference.py" to begin communicating with the chatbot.
