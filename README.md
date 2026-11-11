<p align="center">
  <img src="assets/header.svg" alt="Artem Sereda — Python Backend Developer. FastAPI, PostgreSQL, React and TypeScript. Business workflows, data integrity and full-stack development." width="100%" />
</p>

<p align="center">
  <a href="mailto:seredartem44@gmail.com"><img src="https://img.shields.io/badge/Email-Contact_me-142330?style=flat-square&amp;logo=gmail&amp;logoColor=5eead4" alt="Email Artem" /></a>
  <a href="https://www.linkedin.com/in/artem-sereda-911580318/"><img src="https://img.shields.io/badge/LinkedIn-Let%27s_connect-142330?style=flat-square&amp;logo=linkedin&amp;logoColor=38bdf8" alt="Connect on LinkedIn" /></a>
  <a href="https://github.com/seredartem?tab=repositories"><img src="https://img.shields.io/badge/GitHub-Explore_my_work-142330?style=flat-square&amp;logo=github&amp;logoColor=e2e8f0" alt="Explore my repositories" /></a>
</p>

<p align="center"><strong>Open to Python backend roles and internships</strong></p>

## About me

I build Python backends for applications with real business rules: booking capacity, membership balances, access permissions, and auditable state changes. My featured project, **SPLASH**, connects a React and TypeScript interface to an asynchronous FastAPI backend and PostgreSQL database.

My work spans API design, relational data modelling, transactional workflows, database migrations, and regression tests, alongside the client and owner interfaces that use them. I also build API integrations, asynchronous data-collection tools, and web scrapers.

Based in **Warsaw, Poland** · Studying **Computer Networks at Społeczna Akademia Nauk**.

## Technical toolkit

| Area | Technologies & practices |
| :--- | :--- |
| **Backend & API design** | `Python` · `FastAPI` · `Flask` · `Pydantic` · `REST / OpenAPI` · service layers |
| **Databases** | `PostgreSQL` · `SQLAlchemy 2 async` · `Alembic` · `SQL` · `MySQL` |
| **Data consistency** | transactions · row-level locking · idempotent operations · entry ledgers |
| **Authentication & access** | `JWT` · `bcrypt` · role-based permissions · server-side validation |
| **Frontend integration** | `React` · `TypeScript` · `Vite` · typed API clients · responsive PL/UA interfaces |
| **Testing & quality** | `Pytest` · `Node.js test runner` · TypeScript checks · `Ruff` |
| **Async & integrations** | `asyncio` · `aiohttp` · `httpx` · `Requests` |
| **Scraping & automation** | `BeautifulSoup` · `Playwright` |
| **Development** | `Git` · `GitHub` · `Postman` · `OOP` |

## Selected projects

<table>
  <tr>
    <td colspan="2" valign="top">
      <h3>01 / SPLASH — Dance &amp; Fitness Platform</h3>
      <p><strong>Full-stack website · React frontend + FastAPI backend</strong></p>
      <p>A dance and fitness studio platform covering the client booking journey and daily owner operations, with business rules enforced by an asynchronous Python service layer.</p>
      <ul>
        <li>Transactional booking and membership workflows with row locks, idempotent retries, and protection against duplicate entry deductions</li>
        <li>JWT authentication, role-based API permissions, Pydantic validation, and Alembic database migrations</li>
        <li>Owner CRM for client records, attendance, membership ledgers, booking history, and operational analytics</li>
        <li>Typed React API integration with authenticated requests, error handling, and expired-session recovery</li>
        <li>Responsive Polish/Ukrainian UI with Warsaw-local booking windows and precise monetary formatting</li>
        <li>Pytest regression tests for permissions, cancellation cutoffs, retries, and stale updates; frontend regression checks for date and account-access rules</li>
      </ul>
      <p><code>Python</code> <code>FastAPI</code> <code>PostgreSQL</code> <code>SQLAlchemy</code> <code>Alembic</code> <code>Pydantic</code> <code>Pytest</code> <code>React</code> <code>TypeScript</code> <code>Vite</code></p>
      <p><sub>Source code is private.</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>02 / Weather API</h3>
      <p>A Flask backend combining user accounts, protected weather endpoints, and persistent data storage.</p>
      <ul>
        <li>JWT authentication and password hashing</li>
        <li>OpenWeather API integration</li>
        <li>Request quotas, user balances, and request history</li>
      </ul>
      <p><code>Python</code> <code>Flask</code> <code>MySQL</code> <code>JWT</code></p>
      <p><a href="https://github.com/seredartem/Weather_sell"><strong>Explore the backend →</strong></a></p>
    </td>
    <td width="50%" valign="top">
      <h3>03 / Async Crypto Monitor</h3>
      <p>An asynchronous client that collects cryptocurrency prices from the CoinGecko API and produces structured reports.</p>
      <ul>
        <li>Concurrent HTTP requests with aiohttp and asyncio</li>
        <li>Retries for API rate-limit responses</li>
        <li>JSON output with prices, statuses, and timestamps</li>
      </ul>
      <p><code>Python</code> <code>asyncio</code> <code>aiohttp</code> <code>JSON</code></p>
      <p><a href="https://github.com/seredartem/Asynchronous-cryptocurrency-parsing"><strong>Explore the async client →</strong></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>04 / Vinted Data Scraper</h3>
      <p>A web scraping project for extracting product information from marketplace listings.</p>
      <ul>
        <li>HTML parsing with CSS selectors and pagination</li>
        <li>Product titles, prices, sizes, and listing links</li>
        <li>Listing image downloads</li>
      </ul>
      <p><code>Python</code> <code>Requests</code> <code>BeautifulSoup</code></p>
      <p><a href="https://github.com/seredartem/Web-scrapping-Vinted"><strong>Explore the scraper →</strong></a></p>
    </td>
    <td width="50%" valign="top">
      <h3>05 / Pixabay Image Downloader</h3>
      <p>A small command-line learning project for searching Pixabay and downloading an image through its API.</p>
      <ul>
        <li>Search queries and image retrieval</li>
        <li>JSON-based settings</li>
        <li>Object-oriented Python structure</li>
      </ul>
      <p><code>Python</code> <code>Requests</code> <code>REST API</code> <code>JSON</code></p>
      <p><a href="https://github.com/seredartem/api_pixabay"><strong>Explore the downloader →</strong></a></p>
    </td>
  </tr>
</table>

## Education & languages

**Społeczna Akademia Nauk** · Computer Networks · 2024–2028, expected graduation

Additional Python training: **Genius Space** online courses and private Python lessons.

| English | Polish | Ukrainian | Russian |
| :--- | :--- | :--- | :--- |
| Intermediate | Intermediate | Native | Native |

---

<p align="center">
  Have a backend opportunity or a project to discuss?<br />
  <a href="mailto:seredartem44@gmail.com"><strong>seredartem44@gmail.com</strong></a> · <a href="https://www.linkedin.com/in/artem-sereda-911580318/">LinkedIn</a>
</p>

<a href="mailto:seredartem44@gmail.com"><img src="assets/footer.svg" alt="Let's build something useful. Python, APIs and automation." width="100%" /></a>
