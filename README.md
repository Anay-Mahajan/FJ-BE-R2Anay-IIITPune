<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
</head>

<body style="font-family: Arial, sans-serif; line-height: 1.6; max-width: 900px; margin: auto; padding: 20px;">

  <h1>💰 Personal Finance Tracker</h1>

  <p>
    🔗 <strong>Live Application:</strong>
    <a href="https://anay-expense-tracker.vercel.app" target="_blank">Frontend</a><br/>
    🔗 <strong>Backend API:</strong>
    <a href="https://anay-finance-tracker-backend.duckdns.org/api" target="_blank">Backend</a>
  </p>

  <p>
    A full-stack finance management app built with <strong>Django</strong> and <strong>React</strong>,
    helping users track income, expenses, and financial trends.
  </p>

  <hr />

  <h2>📌 Project Overview</h2>
  <p>
    This application allows users to securely manage personal financial records, upload receipts,
    analyze spending patterns, and generate reports. The system integrates authentication,
    RESTful APIs, cloud-hosted databases, and a responsive frontend dashboard.
  </p>

  <hr />

  <h2>🚀 Features</h2>

  <h3>🔐 Authentication</h3>
  <ul>
    <li>User registration and login</li>
    <li>Google OAuth via Django Allauth</li>
    <li>Secure profile handling</li>
  </ul>

  <h3>💸 Transactions</h3>
  <ul>
    <li>Add, edit, delete income & expenses</li>
    <li>Negative amounts supported (refunds)</li>
    <li>Decimal precision for financial accuracy</li>
  </ul>

  <h3>🧾 Receipt Upload</h3>
  <ul>
    <li>Attach receipts to transactions</li>
  </ul>

  <h3>🌍 Multi-Currency</h3>
  <ul>
    <li>Store and display transactions in multiple currencies</li>
  </ul>

  <h3>📊 Dashboard & Reports</h3>
  <ul>
    <li>Visual financial summaries</li>
    <li>Monthly and category-wise reports</li>
  </ul>

  <h3>📧 Notifications</h3>
  <ul>
    <li>Email alerts using SMTP integration</li>
  </ul>

  <p><em>⚠️ Budget feature coming in a future update.</em></p>

  <hr />

  <h2>🛠 Tech Stack</h2>
  <ul>
    <li><strong>Frontend:</strong> React (Vite)</li>
    <li><strong>Backend:</strong> Django 5 + Django REST Framework</li>
    <li><strong>Database:</strong> PostgreSQL on AWS RDS</li>
    <li><strong>Authentication:</strong> Django Allauth (Google OAuth)</li>
    <li><strong>Deployment:</strong> AWS (Backend) + Vercel (Frontend)</li>
  </ul>

  <hr />

  <h2>📁 Project Structure</h2>

  <pre><code>FJ-BE-R2Anay-IIITPune/
│
├── accounts/           # User authentication & profiles
├── dashboard/          # Dashboard and financial reports
├── transactions/       # Income & expense logic
├── finance_tracker/    # Django project settings
├── frontend/           # React frontend (Vite)
│
├── manage.py
├── requirements.txt
├── .env
└── README.md
</code></pre>

  <hr />

  <h2>⚙️ Backend Setup (Django)</h2>

  <pre><code>python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt</code></pre>

  <p>Create a <code>.env</code> file:</p>

  <pre><code>DEBUG=True
SECRET_KEY=your_secret_key
DATABASE_NAME=finance_tracker
DATABASE_USER=postgres
DATABASE_PASSWORD=your_password
DATABASE_HOST=your_rds_endpoint
DATABASE_PORT=5432
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
EMAIL_HOST_USER=your_email
EMAIL_HOST_PASSWORD=your_email_password</code></pre>

  <pre><code>python manage.py migrate
python manage.py createsuperuser
python manage.py runserver</code></pre>

  <hr />

  <h2>💻 Frontend Setup (React)</h2>

  <pre><code>cd frontend
npm install
npm run dev</code></pre>

  <hr />

  <h2>👨‍💻 Author</h2>
  <p><strong>Anay Mahajan</strong><br/>Backend Developer</p>

  <hr />

 
</body>
</html>
