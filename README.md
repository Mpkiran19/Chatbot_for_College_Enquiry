## Initial Setup:

versions:

python-3.9.12-amd64

Miniconda3-py39_24.5.0-0-Windows-x86_64

This repo currently contains the starter files.

Clone repo and create a virtual environment
```
$ git clone https://github.com/Mpkiran19/College_Enquiry_Chatbot.git
$ cd chatbot-deployment
$ python3 -m venv venv
$ .\venv\Scripts\activate
```
Install dependencies
```
$ (venv) pip install Flask torch torchvision nltk
```
Install nltk package
```
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
```
Modify `intents.json` with different intents and responses for your Chatbot

Run
```
$ (venv) python train.py
```
This will dump data.pth file. And then run
the following command to test it in the console.
```
$ (venv) python chat.py
```

## OUTPUT:
![Screenshot (112)](https://github.com/user-attachments/assets/7939125f-c536-47c2-a349-35bd3cf93802)
![Screenshot (113)](https://github.com/user-attachments/assets/cd1fd01c-6a66-4f52-a635-aa07854a43da)
![Screenshot (114)](https://github.com/user-attachments/assets/2f38383b-9db6-4d2b-a964-724bb76116ac)
![Screenshot (115)](https://github.com/user-attachments/assets/2961cd85-d472-4d09-8376-6138a4a50a5a)
![Screenshot (116)](https://github.com/user-attachments/assets/c5fa003a-09d3-4bff-9dfc-25668a8930ca)
![Screenshot (117)](https://github.com/user-attachments/assets/9114169e-3158-451d-beac-51de1c2158f6)
![Screenshot (118)](https://github.com/user-attachments/assets/613f2b82-8282-4b16-87b8-7fa76233d900)
![Screenshot (119)](https://github.com/user-attachments/assets/91aea431-38e2-4d0d-9932-4ce04f0b0524)
![Screenshot (120)](https://github.com/user-attachments/assets/0301fab4-f09d-48bb-904a-5953d079474b)
