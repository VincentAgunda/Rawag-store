# Rawag Store

Rawag Store is a Django-based web application designed to manage sweater production. It tracks threads (by color and quantity), finished and in-progress sweaters, shipped sweaters, sweater orders, customers, and additional products like needles.

## 🚀 Features
- **Thread Management:** Track thread color and available quantities.
- **Sweater Management:** Monitor sweater production status (in progress, finished, shipped).
- **Order Management:** Handle sweater orders, including customer information and shipping status.
- **Customer Tracking:** Manage customer lists, including received and waiting customers.
- **Product Inventory:** Manage additional products like needles.

## ⚙️ Technologies Used
- **Backend:** Django 5.1.6
- **Frontend:** HTML, CSS (with static files)
- **Database:** SQLite3

## 💾 Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/VincentAgunda/Rawag-store.git
   cd Rawag-store
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   venv\Scripts\activate  # For Windows
   source venv/bin/activate  # For Unix/macOS
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations:**
   ```bash
   python manage.py makemigrations store_management
   python manage.py migrate
   ```

5. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

6. **Access the app:**
   Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your web browser.

## 🧪 Running Tests
```bash
python manage.py test
```

## 🤝 Contributing
1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Create a pull request

## 📄 License
This project is licensed under the [MIT License](LICENSE).

## ✨ Acknowledgments
- Django Documentation
- Open-source contributors

---

💡 **For any queries or feedback, feel free to open an issue or contact the maintainer.**

