This project was done to help me better understand the difference between Flask, Django and FastAPI. 
It's inspired from : https://www.youtube.com/watch?v=3vfum74ggHE 

To make it work as it is right now you can copy this code and run it (in bash) : 

```console
python3 -m venv venv
source venv/bin/activate

pip install fastapi
pip install "uvicorn[standard]"
pip install python-multipart sqlalchemy jinja2

uvicorn app:app --reload
```

I might try to make it work with docker later on.