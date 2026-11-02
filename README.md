# 📝 My Blog (Django Web Application)

[ 🇬🇧 English Version ](#english) | [ 🇦🇲 Հայերեն Տարբերակ ](#armenian)

---

<span id="english"></span>
## 🇬🇧 English

> A full-featured, responsive blog web application built with Python and the Django framework. It provides a complete content management workflow including article publishing, many-to-many tagging, interactive comment forms, and session-based bookmarks.

### 📌 About the Project

**My Blog** is a comprehensive blogging platform built to demonstrate core and advanced Django architectural patterns. The application showcases full-scale relational modeling (connecting Posts, Authors, Tags, and Comments), dynamic URL routing with slugs, server-side form validations, and user session management for saving favorite posts.

### ✨ Key Features

- **Post Publishing & Detail Pages:** Clean feed of latest posts and full-detail article pages powered by SEO-friendly dynamic slugs.
- **Many-to-Many Tagging System:** Flexible categorization of articles using reusable tags (e.g., tech, lifestyle, tutorials).
- **Interactive Comment System:** Direct user feedback and discussion on posts using validated Django ModelForms.
- **"Read Later" / Bookmarks:** User ability to save articles for later reading stored in client browser sessions without mandatory user registration.
- **Media Asset Pipeline:** Automated management and display of featured blog post cover images.
- **Django Admin Customization:** Back-office dashboard for managing authors, drafting posts, organizing tags, and moderating comments.
- **Modern Responsive UI:** Clean modular layouts built with Django Template Language (DTL) inheritance and custom CSS styling.

### 🛠 Tech Stack

- **Backend:** Python 3.x, Django
- **Database:** SQLite3 (Django ORM)
- **Frontend:** HTML5, CSS3, Django Templates
- **Image Processing:** Pillow (Django Media pipeline)

### 📂 Project Structure

```text
my_blog/
│
├── blog/                   # Core blog application (Models, Views, Forms)
│   ├── models.py           # Schemas (Post, Author, Tag, Comment)
│   ├── forms.py            # Comment ModelForm definition
│   ├── views.py            # Class-Based and Function-Based views
│   ├── urls.py             # Route definitions
│   └── admin.py            # Admin panel configuration
│
├── templates/              # HTML templates (base.html, post lists, details)
├── static/                 # Static files (CSS styles, icons)
├── manage.py               # Django management script
├── requirements.txt        # Project dependencies
└── .gitignore              # Git ignored files
```


🚀 Installation & Setup


Clone the repository:
git clone https://github.com/MarkosyanShooshan/my-blog.git
cd my-blog

Create and activate a virtual environment:
python -m venv venv
venv\Scripts\activate

macOS / Linux:
python3 -m venv venv
source venv/bin/activate

Install dependencies:
pip install -r requirements.txt

Apply database migrations:
python manage.py migrate

Create an admin superuser:
python manage.py createsuperuser

Run the development server:
python manage.py runserver
Open http://127.0.0.1:8000/ in your browser.


<span id="armenian"></span>
🇦🇲 Հայերեն


Բազմաֆունկցիոնալ և ժամանակակից բլոգ վեբ-հավելված՝ ստեղծված Python-ով և Django ֆրեյմվորքով։ Նախագիծն ընդգրկում է հոդվածների հրապարակում, Many-to-Many թեգերի համակարգ, մեկնաբանություններ և սեսիաների միջոցով հոդվածների պահպանում («Կարդալ ավելի ուշ»)։


📌 Նախագծի մասին

My Blog նախագիծը ներկայացնում է Django-ի հնարավորությունների ամբողջական համադրությունը։ Հավելվածում իրականացված է տվյալների բազայի բազմակողմանի մոդելավորում (Հեղինակներ, Հոդվածներ, Թեգեր և Մեկնաբանություններ), slug-երով ավտոմատ գեներացվող հասցեներ, ձևաթղթերի ստուգում (ModelForms) և օգտատիրոջ սեսիաների (Sessions) արդյունավետ կիրառում։


✨ Հիմնական հնարավորությունները

Հոդվածների Կատալոգ և Դետալային Էջեր — Վերջին հոդվածների գլխավոր էջ և ընթերցման առանձին էջեր՝ slug-երի հիման վրա։
Թեգերի Համակարգ (Many-to-Many) — Հոդվածների բազմակի խմբավորում ըստ թեմաների (օր.՝ ծրագրավորում, ճամփորդություն և այլն)։
Մեկնաբանությունների Համակարգ — Օգտատերերի կարծիքների ընդունում և ստուգում Django ModelForms-ի միջոցով։
«Կարդալ Ավելի Ուշ» (Read Later) — Հոդվածները նախընտրելիների ցանկում պահպանելու հնարավորություն՝ բրաուզերի սեսիայում (առանց գրանցվելու պարտադրանքի)։
Մեդիա Նկարների Կառավարում — Հոդվածների գլխավոր լուսանկարների անվտանգ ներբեռնում և արտապատկերում։
Հզոր Django Admin Վահանակ — Հոդվածների, հեղինակների, թեգերի և մեկնաբանությունների լիարժեք կառավարում ադմինիստրատորի կողմից։
Մոդուլային Շաբլոններ — Կոկիկ և ժամանակակից դիզայն՝ Django Template Language-ի շաբլոնների ժառանգմամբ։

- **Shooshan Markosyan** — [GitHub Profile](https://github.com/MarkosyanShooshan)