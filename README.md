<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B6B,35:FFA94D,70:4DABF7,100:845EF7&height=200&section=header&text=Yashoda%20First%20Aid%20Center&fontSize=44&fontColor=ffffff&fontAlignY=36&animation=fadeIn&desc=Clinic%20website%20with%20online%20appointment%20booking&descSize=16&descAlignY=58" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=845EF7&center=true&vCenter=true&width=700&lines=First+aid+clinic+website+in+Django;Book+appointments+online;Admin+dashboard+for+bookings" alt="Typing SVG"/>

<br/>

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>

<br/>

<img src="https://img.shields.io/badge/Status-Completed-20C997?style=for-the-badge"/>
<img src="https://img.shields.io/github/stars/Annepuuday111/Yashoda-First-Aid-Center?style=for-the-badge&color=845EF7"/>
<img src="https://img.shields.io/github/last-commit/Annepuuday111/Yashoda-First-Aid-Center?style=for-the-badge&color=4DABF7"/>
<img src="https://img.shields.io/github/repo-size/Annepuuday111/Yashoda-First-Aid-Center?style=for-the-badge&color=FF6B6B"/>

<br/><br/>

[About](#-about) • [Features](#-features) • [Tech Stack](#️-tech-stack) • [Project Structure](#-project-structure) • [Getting Started](#-getting-started) • [Author](#-author)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## 📖 About

**Yashoda First Aid Center** is a Django website for a local first aid clinic. Patients can read about the clinic and its services, find it on an embedded Google Map and book an appointment online. Bookings are stored in PostgreSQL and listed on an admin dashboard.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## ✨ Features

- 🏠 **Clinic pages** – Home, About, Services and Contact (with an embedded Google Map)
- 🩹 **Services** – First aid for minor and major injuries, medical consultation and health checkups
- 📅 **Appointment booking** – `AppointmentForm` captures full name, email, phone number, date and message, validated and saved through a Django `ModelForm`
- 💬 **Feedback messages** – Success / failure message shown after submitting a booking
- 🛡️ **Admin dashboard** – Table of all appointments (name, email, phone, date, message)
- 🔑 **Admin login page** – Simple client-side login that opens the admin home

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,django,postgres,html,css,js&theme=light"/>

</div>

| Layer | Technology |
| :--- | :--- |
| Backend | Python, Django 5.0 |
| Database | PostgreSQL (`psycopg2`) |
| Frontend | Django templates, HTML5, CSS3, JavaScript, Font Awesome |

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## 📂 Project Structure

```text
Yashoda-First-Aid-Center/
└── YashodaFirstaidCenter/
    ├── YashodaFirstaidCenter/   # settings.py, urls.py, wsgi.py, asgi.py
    ├── adminapp/                # Appointment model, form, views, urls, migrations
    ├── static/
    │   ├── css/styles.css
    │   └── images/
    ├── templates/               # index, about, services, contact, booking,
    │                            # login, adminhome, admindashboard
    └── manage.py
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## 🚀 Getting Started

### Prerequisites

- Python 3.10+
- PostgreSQL running locally

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Annepuuday111/Yashoda-First-Aid-Center.git
   cd Yashoda-First-Aid-Center/YashodaFirstaidCenter
   ```
2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate      # Windows: venv\Scripts\activate
   ```
3. **Install dependencies**
   ```bash
   pip install "Django>=5.0,<5.1" psycopg2-binary
   ```
4. **Create the database** and update `DATABASES` in `YashodaFirstaidCenter/settings.py` with your own credentials
   ```sql
   CREATE DATABASE "YashodaFirstaidCenter";
   ```
5. **Apply migrations and run**
   ```bash
   python manage.py migrate
   python manage.py runserver
   ```
   Open http://127.0.0.1:8000 and book an appointment at `/booking/`. Bookings appear at `/admindashboard/`.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## 🗺️ Roadmap

- [ ] Server-side admin authentication to protect the dashboard
- [ ] Save contact form messages
- [ ] Add a `requirements.txt`

## 🤝 Contributing

Contributions are welcome. Fork the repo, create a branch (`git checkout -b feature/my-change`), commit your work and open a pull request.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## 👨‍💻 Author

<div align="center">

### Annepu Uday Kumar

<a href="https://github.com/Annepuuday111"><img src="https://img.shields.io/badge/GitHub-Annepuuday111-845EF7?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://annepuudaykumar.netlify.app"><img src="https://img.shields.io/badge/Portfolio-annepuudaykumar-FF6B6B?style=for-the-badge&logo=netlify&logoColor=white"/></a>

</div>

<br/>

<div align="center">⭐ If you like this project, give it a star!</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:845EF7,35:4DABF7,70:FFA94D,100:FF6B6B&height=120&section=footer" width="100%"/>
