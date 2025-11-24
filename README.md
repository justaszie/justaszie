## Portfolio - Justas Zieminykas
Hi, I'm Justas - a full-stack software engineer with **strong backend foundation (Python, FastAPI, SQL, data processing, networks, REST APIs)**, and **solid frontend skills in HTML/CSS, Javascript, Typescript, and React**. I build clean, testable, maintainable [full-stack web apps](#projects) and deploy them through **CI/CD pipelines**.


Before software engineering, I worked in product management, which gave me strong product intuition and attention to user value - experience that helps me make technical tradeoff decisions. I can bring value to software teams through my technical depth, product experience, ownership mindset, and passion for designing elegant software. Backend is my strength but I am comfortable working across the stack.

Below you'll find [examples of my work](#projects) and how to [get in touch](#get-in-touch).


### Get in touch
- [Linkedin](https://www.linkedin.com/in/justas-%C5%BEieminykas-01423988/)
- CV
- Email: [justas.zieminykas@gmail.com](mailto:justas.zieminykas@gmail.com)


## Projects
### 1. Google Fit Weight Tracker
A full-stack web app that integrates Google OAuth, gets Google Fit data from their REST API, and provides a dashboard view with weekly body weight metrics and trends.

**Tech Stack**
- **Backend**: FastAPI (Python 3.12), PostgreSQL, JWT Auth (Supabase), Google Auth, Google Web REST APIs, modular architecture.
- **Frontend**: React + TypeScript, Vite, custom CSS ([BEM](https://getbem.com/) style), responsive UI
- **CI / CD**
  - Backend unit + integration tests (85% coverage with pytest)
  - mypy + formatter + linter, Github Actions, Git/PR hygiene
  - Deployed on Koyeb (backend) + Cloudflare Pages (frontend)

**Links**
- [Codebase / Documentation](https://github.com/justaszie/weight-tracker)
- [Live Demo](https://tracker.justas.tech/). Use demo credentials<sup style="color:red;">*</sup> :
  - Email: `wtdemo@justas.tech`
  - Pwd: `demo1`
- API Docs: [Swagger](https://api.tracker.justas.tech/docs) | [Redoc](https://api.tracker.justas.tech/redoc)

<sup style="color:red;">*</sup> The demo account uses mock data source instead of Google Fit APIs. This is because the production integration requires verification by Google. Developers who want to test the real Google Fit integration can be added to the testing group upon request.

**Screenshots**
![Main View](/img/wt-screenshot-1.png)
![No Data View](/img/wt-screenshot-2.png)
