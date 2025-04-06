
# API Explorer Proposal for API Dash

## Personal Information

**Full Name:** Tram Ton  
**Contact Info:**  
- Email: tonnuquynhtram2004@gmail.com  
- Phone: +1 (813) 724-1905  

**Discord Handle:** tramtonne  
**GitHub Profile Link:** https://github.com/TramTonne

**LinkedIn:** [https://linkedin.com/in/tramton]([https://linkedin.com/in/tramton](https://www.linkedin.com/in/tram-ton-8a3727249/))  
**Time Zone:** Eastern Time (ET, UTC-4)  
**Resume Link:** https://docs.google.com/document/d/1i1ArsfL6FT_pReXFnsRy_jrPuRqqYYhpcv9kqPU7Edo/edit?usp=sharing

---

## University Information

**University Name:** University of South Florida  
**Program Enrolled:** Bachelor of Science in Computer Science  
**Year:** Sophomore (2nd Year)  
**Expected Graduation Date:** December 2026

---

## Motivation & Past Experience

**Have you worked on or contributed to a FOSS project before?**  
While I have not yet formally contributed to a FOSS project, I have been actively learning about open-source development practices and exploring repositories on GitHub. I am currently improving my skills by studying open issues, understanding contribution guidelines, and making small improvements on personal projects with the goal of contributing to FOSS soon. I am excited to gain real-world open-source experience through this project.

**What is your one project/achievement that you are most proud of? Why?**  
I built an "Automated Amazon Price Tracker" that scrapes Amazon product pages, monitors price drops, and sends email alerts. It was my first full project using BeautifulSoup, SMTP, and cron jobs. I'm proud because it improved my real-world web scraping and automation skills.

**What kind of problems or challenges motivate you the most to solve them?**  
I am most motivated by technical challenges that combine automation and user experience improvements, especially when they remove tedious manual work for users.

**Will you be working on GSoC full-time?**  
Yes, I will be dedicating my summer to GSoC full-time.

**Do you mind regularly syncing up with the project mentors?**  
Not at all. I would appreciate regular feedback and discussions to ensure the project stays aligned with expectations.

**What interests you the most about API Dash?**  
I love how API Dash focuses on making API testing accessible and seamless for developers, especially beginners. The curated API library would make the tool even more powerful and user-friendly.

**Can you mention some areas where the project can be improved?**  
- Enhanced search and filter functionalities for easier API discovery.
- More community engagement features like user reviews and contributions.
- Automatic syncing of API documentation updates from external sources.

---

## Project Proposal Information

**Proposal Title:** API Explorer: Curated API Library and Automation Pipeline for API Dash

### Abstract

The project aims to build a curated library of popular and publicly available APIs for API Dash. Users will be able to discover, browse, search, and directly import pre-configured API request templates into their workspace. I will develop a backend automation pipeline to parse OpenAPI/HTML files, auto-categorize APIs, enrich data, and generate templates. This project will enhance onboarding efficiency, improve user experience, and create opportunities for community contributions.

### Detailed Description

API Explorer will introduce a curated API library feature in API Dash, organized across different domains such as AI, finance, weather, and social media. It will allow users to:
- Discover new APIs easily through categorized browsing and powerful search capabilities.
- Directly import ready-to-use API requests with authentication details, payloads, and expected responses.
- Access an ever-growing database with user-contributed APIs, ratings, and reviews.

**Key Deliverables:**
- Automation Pipeline:
  - Parse OpenAPI specs and HTML documentation.
  - Extract API endpoint details, parameters, authentication, and sample requests/responses.
  - Auto-tag APIs into appropriate categories.
  - Enrich metadata (e.g., authentication methods, usage limits, etc.).
  - Create ready-to-import templates compatible with API Dash.
- Backend integration with API Dash workspace.
- User Interface Enhancements:
  - Browsable and searchable API library.
  - User rating and review system for APIs.
- Community contribution mechanism via GitHub.

**Tech Stack:**
- Languages: Dart, Flutter (for frontend)
- Backend: Dart server or cloud functions
- Parsing: YAML, JSON (OpenAPI formats), HTML parsing
- Hosting: GitHub and/or Firebase for templates

### Weekly Timeline

**Community Bonding Period:**
- Deep dive into API Dash's codebase and development practices.
- Finalize scope and requirements with mentors.
- Research existing OpenAPI parsers and libraries.

**Week 1-2:**
- Set up local development environment.
- Build a basic OpenAPI file parser.
- Create scripts for auto-categorization based on API metadata.

**Week 3-4:**
- Expand parser capabilities to handle HTML documentation.
- Design template structure compatible with API Dash.

**Week 5-6:**
- Implement backend service for API ingestion and template generation.
- Create sample templates and test import functionality into API Dash.

**Midterm Evaluation:**
- Fully functional ingestion and template generation pipeline.
- Basic UI to browse a few sample APIs.

**Week 7-8:**
- Build browsing and searching features in the API Dash UI.
- Implement user ratings and review system (backend and frontend).

**Week 9-10:**
- Integrate GitHub community contribution flow.
- Add support for automatic updates of API templates.

**Final Evaluation:**
- Fully functioning curated API Explorer.
- Documentation, deployment, and final demos.

---

**Thank you for considering my proposal! I am excited about the opportunity to contribute to API Dash through GSoC 2025.**

