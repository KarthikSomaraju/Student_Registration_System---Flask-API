# Student_Registration_System---Flask-API

## Open this link   
[[(https://5000-m-s-kkb-ase1a0-cuaynv9b7f3q-a.asia-east1-0.prod.colab.dev)](https://5000-m-s-kkb-ase1a0-cuaynv9b7f3q-a.asia-east1-0.prod.colab.dev)
](https://5000-m-s-usw3b8-99fubusps35p-b.us-west3.prod.r.colab.dev/)
## Features

- Register a student using an HTML form
- Input validation with friendly error messages (empty fields, invalid name, invalid roll number, invalid email, duplicate roll number)
- Result page showing the submitted details
- Page listing all registered students
- Home page showing the total number of registered students

## Routes

| Route | Method | Description |
|-------|--------|-------------|
| `/` | GET | Home page |
| `/register` | GET, POST | Show the registration form and process the submitted data |
| `/students` | GET | Show all registered students |

## Project Structure

```
my_flask_project/
    app.py
    templates/
        index.html
        register.html
        result.html
        students.html
    static/
    requirements.txt
    README.md
```

## Technologies Used

- Python
- Flask
- HTML and CSS

## How to Run

1. Create and activate a virtual environment
2. Install the requirements:
   ```
   pip install -r requirements.txt
   ```
3. Run the app:
   ```
   python app.py
   ```
## Testing

- Valid input shows the result page
- Empty fields show an error message
- A roll number with letters shows an error message
- A repeated roll number shows an error message

## Note
Students are stored in a Python list, so the data is lost when the app restarts. No database is used.

## Google Colab link
(https://colab.research.google.com/drive/1DflfgA70fo5xN1L5imuS8simXsaD7NSM?usp=sharing)
