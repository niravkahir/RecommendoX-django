# 🎬 RecommendoX — Movie & Web Series Recommendation System

RecommendoX is a Django-based web application for discovering movies and web series. It provides content browsing, search, watchlists, ratings, reviews, personalized recommendations, OTT platform integration, and role-based features for users, content creators, industry professionals, and administrators.

## 📸 Screenshots

Explore the application's interface and its key features below.

### 🏠 User Features

**Browse, search, rate, review, and save movies or series to your watchlist.**

<img width="1352" height="1079" alt="Screenshot 2026-10-27 200018" src="https://github.com/user-attachments/assets/d15c7448-daef-454c-8519-b4fe16585a4a" />

### 👑 Golden User Dashboard

<img width="1731" height="2616" alt="Screenshot_27-10-2026_193525_127 0 0 1" src="https://github.com/user-attachments/assets/6f780850-26be-45a9-a5a6-5037c00765c7" />


![Golden User Dashboard](screenshots/golden-user-dashboard.png)

### 🎬 Content Creator Dashboard

<!-- TODO: Upload your Content Creator dashboard screenshot here -->

![Content Creator Dashboard](screenshots/content-creator-dashboard.png)

### 🛡️ Admin Dashboard

<!-- TODO: Upload your Admin dashboard screenshot here -->

![Admin Dashboard](screenshots/admin-dashboard.png)

### 📺 OTT Platform Integration

<!-- TODO: Upload your OTT platform screenshot here -->

![OTT Platform Integration](screenshots/ott-platforms.png)

---

## ✨ Features

### 👤 User Features
- **Registration & Login:** User authentication.
- **Browse Content:** Filter movies and series by genre, language, and content type.
- **Search:** Search by title, director, cast, or description.
- **Watchlist:** Save content to watch later.
- **Ratings:** Rate content from 1 to 5 stars.
- **Reviews:** Write and manage reviews with admin moderation.

### 👑 Special User Roles

#### 🥇 Golden User — Industry Professional
- Create a professional profile.
- Access content analytics dashboards.
- View rating distributions.
- Explore audience feedback insights.
- Check OTT platform availability.
- Apply for admin verification.

#### 🎥 Content Creator
- Add new movies and series.
- Edit and delete existing content.
- Access a creator dashboard with statistics.

#### ✍️ Reviewer
- Submit reviews with automatic approval, according to reviewer permissions.
- Display a verified reviewer badge.
- Participate in the trusted rating system.

### 🛡️ Admin Features
- Manage users, including blocking, unblocking, and deletion.
- Add, edit, and delete content.
- Approve or reject reviews.
- Verify Golden User applications.
- Access analytics dashboards.
- Manage OTT platform information.

### 📺 OTT Platform Integration
- Browse content by streaming platform, such as Netflix, Prime Video, and Disney+.
- Filter free content.
- Access direct watch links.
- View platform availability.

### 🎯 Recommendation System
- Discover relevant movies and web series through the recommendation functionality.

## 🛠️ Tech Stack

| Technology      | Purpose                  |
|-----------------|--------------------------|
| Python          | Programming language     |
| Django 6.0.2    | Backend web framework    |
| SQLite / MySQL  | Database options         |
| HTML5           | Page structure           |
| CSS3            | Styling                  |
| Bootstrap 5     | Responsive UI components |
| Font Awesome 6  | Icons                    |

## ⚙️ Prerequisites

- Python 3.10 or a compatible version supported by your Django installation.
- pip
- Git
- A virtual environment
- XAMPP, if using its MySQL server

## 🚀 Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/niravkahir/RecommendoX-django.git
cd RecommendoX-django
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows PowerShell:**

```powershell
.\venv\Scripts\Activate.ps1
```

**Windows Command Prompt:**

```cmd
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure environment variables

Configure the environment variables required by your project in the `.env` file, if applicable.

Do not commit passwords, secret keys, or other sensitive credentials to GitHub.

### 6. Apply database migrations

```bash
python manage.py migrate
```

### 7. Start the development server

```bash
python manage.py runserver
```

Open the application in your browser:

http://127.0.0.1:8000/
---

If you find this project useful, consider giving the repository a ⭐ on GitHub!
