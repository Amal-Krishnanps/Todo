# Todo App
A simple todo app built with django to remind something.

## Setup Instructions
**1. Clone the Repository**

    git clone https://github.com/Amal-Krishnanps/Todo.git
    
    cd mytodo

**2. Create a Virtual Environment**
   
     python -m venv venv
   
 **3. Activate the Virtual Environment**
 
      On Windows:
      venv\Scripts\activate
     
      On macOS/Linux:
      source venv/bin/activate
   
**4. Install Dependencies**

      pip install -r requirements.txt

**5. Apply Migrations**

     python manage.py migrate

**6. Create Superuser**

     python manage.py createsuperuser

**7. Run the Development Server**

     python manage.py runserver



### API Endpoint

http://127.0.0.1:8000/todo/
