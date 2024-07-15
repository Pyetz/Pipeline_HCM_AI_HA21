<h1><center>Pipeline HCM AI CHALLENGE <br> Event Retrieval from Visual Data</center></h1>

## Setup 
```
pip install git+https://github.com/openai/CLIP.git
pip install -r requirements.txt
```

## Run on local
```
python app.py
```

URL: http://0.0.0.0:5001/home?index=0

## Run on colab
```
!python app.py &>/content/logs.txt &
!npm install -g tunnelmole
!tmole 5001
```

then add '/home?index=0' to the end of path
