# Machine Learning Patient Classification in Emergency Department

This project uses machine learning to classify patients in the Emergency Department (ED) based on their medical data. It helps in early identification and prioritization for better patient care.

## 📂 Project Structure

- `admin/` – Django admin settings
- `migrations/` – Database migration files
- `models.py` – ML model code
- `views.py` – Web view logic
- `templates/` – HTML templates for the frontend
- `static/` – Static files (CSS, JS)
- `dataset.csv` – Input medical data (if included)

## ⚙️ Features

- Classifies patients based on medical data
- Web-based user interface using Django
- Model training and evaluation
- Handles real-world emergency data

## 🛠️ Technologies Used

- Python
- Django
- Scikit-learn
- Pandas, NumPy
- HTML/CSS

## 🚀 How to Run the Project

```bash
# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the server
python manage.py runserver
