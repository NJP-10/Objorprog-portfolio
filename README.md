# Objorprog-portfolio

Step 1: Clone the Repository

git clone https://github.com/yourusername/your-django-project.git cd your-django-project


Step 2: Create a Virtual Environment

On macOS/Linux:
python3 -m venv env source env/bin/activate

On Windows:
python -m venv env.\env\Scripts\activate


Step 3: Install Dependencies

pip install -r requirements.txt


Step 4: Set Up the Database

python manage.py migrate


Step 5: Create a Superuser (Optional)

python manage.py createsuperuser


Step 6: Run the Development Server

python manage.py runserver


Step 7: Access the Admin Interface

http://127.0.0.1:8000/admin/
