follow these command to run this project

git clone https://github.com/daiyan52/Bluestock-Fintech-HQ
cd Bluestock-Fintech-HQ
cd IPO
pip install -r requirements.txt
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py createsuperuser
python3 manage.py runserver
