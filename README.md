## Setup & Installation 

To run this project, perform the following tasks 


Downloading packages from ```requirements.txt``` inside ``App`` folder
```bash
cd../..

cd App

pip install -r requirements.txt

python -m spacy download en_core_web_sm

```

After installation is finished create a Database ```cv```

And change user credentials inside ```App.py```

Run the ```App.py``` file using
```bash
streamlit run App.py

```