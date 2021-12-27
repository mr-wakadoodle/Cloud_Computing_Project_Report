Install Anaconda
Create a folder <example --> myfirstbot>
cd + path to the folder
Conda create --name chatbotvenv python==3.7.6
conda activate chatbotvenv
conda install ujson==2.0.3
conda install tensorflow==2.1.0
pip install rasa==1.10.0
rasa init

# To run rasa bot use - rasa shell

I purposely did not include a requirement.txt file. Please read throught the steps and try to implement step by step. That's how I learned :)
