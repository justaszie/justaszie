## Portfolio - Justas Zieminykas
Hi, I'm Justas - a full-stack software engineer with **strong backend foundation (Python, FastAPI, SQL, data processing, networks, REST APIs)**, and **solid frontend skills in HTML/CSS, Javascript, Typescript, and React**. I build clean, maintainable and well-tested [full-stack web apps](#projects) and deploy them through **CI/CD pipelines**.


Before software engineering, I worked in product management, which gave me strong product intuition and attention to user value - experience that helps me make technical tradeoff decisions. I can bring value to software teams through my technical depth, product experience, ownership mindset, and passion for designing elegant software. Backend is my strength but I am comfortable working across the stack.

Below you'll find [examples of my work](#projects) and how to [get in touch](#get-in-touch).

--- 

### Get in touch
- [Linkedin](https://www.linkedin.com/in/justas-%C5%BEieminykas-01423988/)
- [justas.zieminykas@gmail.com](mailto:justas.zieminykas@gmail.com)

---

## Projects
### 1. Google Fit Weight Tracker
A full-stack web application that allows users to enter their body weight or get it from external sources (Google Fit API) and presents analytical insights in a modern web UI. It demonstrates end-to-end skills: full-stack development, OAuth 2.0, 3rd-party API integration with data normalization, modular backend architecture, automated testing, and CI/CD.

**Tech Stack**
- **Backend**: FastAPI (Python 3.12), PostgreSQL, JWT Auth (Supabase), Google Auth, Google Web REST APIs, modular architecture.
- **Frontend**: React + TypeScript, Vite, custom CSS ([BEM](https://getbem.com/) style), responsive UI
- **CI / CD**
  - Backend unit + integration tests (~85% coverage with pytest)
  - mypy + formatter + linter, Github Actions, Git/PR hygiene
  - Deployed on Koyeb (backend) + Cloudflare Pages (frontend)

**Links**
- [Codebase / Documentation](https://github.com/justaszie/weight-tracker)
- [Live Demo](https://tracker.justas.tech/). Sign up or use these demo credentials<sup style="color:red;">*</sup> :
  - Email: `wtdemo@justas.tech`
  - Pwd: `demo1`
- [API Docs](https://api.tracker.justas.tech/docs)

><sup style="color:red;">*</sup> The credentials above give access to demo mode where you can try the features using a mock data source instead of real Google Fit API data. The app is currently in the testing phase on Google’s platform, so only the testing group users can access their Google Fit data using this app. Contact me  to add you to the testing group (please mention your gmail address)


**Screenshots**
![Main View](/img/wt-screenshot-1.png)
![No Data View](/img/wt-screenshot-2.png)

---

### 2. Events Manager
[Codebase / Documentation](https://github.com/justaszie/event-manager)

Built as a project assessment, it's an application that allows management of nightlife event listings.
- Sign up, log in and CRUD features for events and associated venues
- Python (Flask), server side rendering (Jinja2 Templates)
- Session management, form validation, paginated data access
- PostgreSQL: database with 2 tables and a 1-N relationship
- Bash script for quick setup 

---
