**🩸 Blood Bank Management System**
A web-based Blood Bank Management System built using Flask and SQLite. This system allows users to register, donate/request blood, and view donation/request history. Admins can manage and monitor blood-related activities through a secure dashboard.


**🚀 Features**
👤 User Features
User registration & secure login/logout

Donate blood with donor details

Request blood for a patient

View personal donation & request history

Reset password via username/email


**🔐 Admin Features**
Admin login/logout

Admin dashboard with statistics (extendable)

View all blood requests & donations

**🛠️ Tech Stack**
Backend: Python, Flask

Frontend: HTML, CSS, Jinja2 Templates

Database: SQLite

Security: Password hashing with Werkzeug


**🗃️ Database Structure**
The project uses three SQLite databases:

user_data.db: Stores user info

donar_data.db: Stores donation records

request_data.db: Stores blood request records


**⚙️ Setup Instructions**
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/Shanub11/Blood-Bank-Management-System.git
cd Blood-Bank-Management-System
2. Create a Virtual Environment (optional but recommended)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
(If requirements.txt is missing, use pip freeze > requirements.txt after installing Flask and dependencies.)

4. Run the App
bash
Copy
Edit
python app.py
Visit http://127.0.0.1:5000/ in your browser.


**🔑 Admin Credentials**
Set environment variables before running:

bash
Copy
Edit
export ADMIN_USERNAME=Admin
export ADMIN_PASSWORD=Admin123
export SECRET_KEY=your_secret_key
Or modify default values in app.py during development.




