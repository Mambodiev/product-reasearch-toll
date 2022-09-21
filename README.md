This is a product reasearch tools website (the idea is to create something like https://app.adspy.com/)
to run it :

windows:
python -m venv env
env\Scripts\activate  
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver  


admin:
username:admin
password:9081
linux:
python3 -m venv env
source env/bin/activate 
pip3 install -r requirements.txt 
python3 manage.py migrate
python3 manage.py runserver 


http://127.0.0.1:8000/products/
http://127.0.0.1:8000/products/car-drying-towel/
