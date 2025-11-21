## Portfolio - Justas Zieminykas
Hi, I'm Justas, a Full-stack engineer. My specialty is a **strong foundation in Backend programming using Python, FastAPI, SQL, Networks, REST APIs and data processing**. I also have **solid Web Frontend skills in Javascript, Typescript, and basics of React**. Finally, I can handle **basic CI/CD workflows and deploy apps to production**. Combining these skillsets, I am able to build and maintain [full stack apps](#projects). I am particularly passionate about designing elegant software and optimizing flows.

After spending 8+ years in Product Management, I realized that I was more passionate about building, than managing, and pivoted into Software Engineering. I aim to bring value to a new team on Day 1 so in preparation I've obtained strong Full Stack fundamentals in an intense ~18 months course on [Launch School](https://launchschool.com/courses). After that I've practiced building and deploying [projects](#projects) from scratch.


### Get in touch
You can find me on:
- [Linkedin](https://www.linkedin.com/in/justas-%C5%BEieminykas-01423988/)
- CV
- Email: [justas.zieminykas@gmail.com](mailto:justas.zieminykas@gmail.com)


## Projects
### 1. Google Fit Weight Tracker
Full Stack app that fetches your weight from Google Fit API and provides metrics to help you track your weight goals. It's built as an SPA with **React TS** Frontend and **Python (FastAPI)** Backend with **PostgreSQL DB**. It includes integrations with **Google Fit Web API** and **Supabase** for auth. It's deployed on free services: Koyeb (Backend), Cloudflare Pages (Frontend), and Supabase (Auth and Postgres DB)

**Tech Stack**
- **Backend**:
  - Python / Fast API (REST APIs)
  - PostgreSQL DB (Manged by Supabase)
  - JWT Auth (Managed by Supabase)
- **Frontend**:
  - React (TypeScript)
  - [BEM](https://getbem.com/) style CSS
- **CI / CD**
  - Pytest for backend unit and integration tests
  - Pre-commmit hooks (quick tests, code quality)
  - Github Workflows (full tests, code quality)
  - PR hygiene and main branch protection
  - Cloud hosting on Koyeb and Cloudflare Pages

**Links**
- [Github Codebase](https://github.com/justaszie/weight-tracker)
- [Live Demo](https://tracker.justas.tech/). Use demo credentials<sup style="color:red;">*</sup> :
  - Email: `wtdemo@justas.tech`
  - Pwd: `demo1`
- API Docs:
  - [Swagger](https://api.tracker.justas.tech/docs)
  - [Redoc](https://api.tracker.justas.tech/redoc)

<sup style="color:red;">*</sup> In Production, the Google API integration is in testing state due to strict verification by Google. Using demo credentials, a mock data source is used instead of real Google Fit integration. Please reach out to me [justas.zieminykas@gmail.com](mailto:justas.zieminykas@gmail.com) to try connecting to your own Google Fit data.

**Screenshots**
![Main View](/img/wt-screenshot-1.png)
![No Data View](/img/wt-screenshot-2.png)
