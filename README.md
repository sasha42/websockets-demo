# Websockets example

This is a sample project that demonstrates a connection between *javascript* running in the browser, and *python* running in the backend. You can send messages back and forth between the frontend and the backend over websockets, using SocketIO.

## Setup
You will need python3 in order to run this code.

```
pip install -r requirements.txt
python app.py
```

Open up your browser at [localhost:5000](localhost:5000) and try sending messages between your browser and python. Any keyboard presses you make in the python app will be sent to the frontend.
