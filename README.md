<div align="center">
  <h1>Christian Chiavelli</h1>
  <p><b>Senior Software Engineer</b> · Full stack with a front-end focus</p>
  <p>Vue.js · Nuxt · TypeScript · .NET · C# · SQL Server</p>

  <a href="https://www.linkedin.com/in/christianchiavelli">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:christian.chiavelli@outlook.com">
    <img src="https://img.shields.io/badge/Email-0078D4?style=flat-square&logo=microsoft-outlook&logoColor=white" alt="Email" />
  </a>
  <a href="https://chiavelli.dev/">
    <img src="https://img.shields.io/badge/Portfolio-14B8A6?style=flat-square&logoColor=white" alt="Portfolio" />
  </a>
</div>

<br/>

I'm a senior software engineer focused on the front end of web products, with enough .NET and SQL Server experience to take a feature from the database to the screen. I've been building web applications since 2016, and I work in English with U.S.-based teams from São Paulo, Brazil.

Most of my recent work is modernizing systems that can't stop running. Right now I'm part of a team moving a large business intelligence platform for the foodservice industry from .NET Razor views to Nuxt 4 and .NET APIs, one screen at a time, with old and new screens running side by side behind a YARP reverse proxy.

## Featured projects

Built on public data. Each one runs with a single command, needs no API key or account, and works in English and Brazilian Portuguese.

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/christianchiavelli/larder"><img src="https://raw.githubusercontent.com/christianchiavelli/larder/main/docs/screenshots/directory-light.png" alt="Larder's product directory, with faceted filters and Nutri-Score grading" /></a>
      <h3><a href="https://github.com/christianchiavelli/larder">Larder</a></h3>
      <p>Food product analytics on the Open Food Facts catalogue, roughly 3.5 million packaged products, handled honestly where the data is incomplete.</p>
      <p><sub>Nuxt 4 · Vue 3.5 · Tailwind 4 · Nitro BFF · Storybook</sub></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/christianchiavelli/deckle"><img src="https://raw.githubusercontent.com/christianchiavelli/deckle/main/docs/screenshots/work-light.png" alt="Deckle's page for Melencolia I, offering only the paper sizes its scan can hold" /></a>
      <h3><a href="https://github.com/christianchiavelli/deckle">Deckle</a></h3>
      <p>A headless print shop on The Met's public-domain collection, with numbered drops that never oversell.</p>
      <p><sub>Next.js 16 · NestJS GraphQL · Vendure · Payload · Postgres 18</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/christianchiavelli/faultline"><img src="https://raw.githubusercontent.com/christianchiavelli/faultline/main/docs/screenshots/live-paper.png" alt="Faultline's 24-hour helicorder with the day's largest earthquakes labelled" /></a>
      <h3><a href="https://github.com/christianchiavelli/faultline">Faultline</a></h3>
      <p>A live seismograph of the planet on USGS earthquake data, drawn the way a drum seismograph records a day.</p>
      <p><sub>Angular 22 · SSR with incremental hydration · Express BFF</sub></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/christianchiavelli/spillway"><img src="https://raw.githubusercontent.com/christianchiavelli/spillway/main/docs/screenshots/overview.png" alt="Spillway's overview of a day of curtailed wind and solar energy, hour by hour" /></a>
      <h3><a href="https://github.com/christianchiavelli/spillway">Spillway</a></h3>
      <p>Alerts on the wind and solar energy Brazil's grid operator keeps from being generated, from the ONS's open data.</p>
      <p><sub>SvelteKit 3 · Go 1.27 · Postgres 18 · OpenAPI 3.1</sub></p>
    </td>
  </tr>
</table>

Also: [modular-monolith-ticketing](https://github.com/christianchiavelli/modular-monolith-ticketing), the architecture report from my postgraduate program in Software Architecture at Infnet. It designs an online ticketing system as a modular monolith, with an admission pipeline, domain events, ADRs and the C4 model.

## What I work with

**Front end:** Vue 3, Nuxt, TypeScript, Pinia, Tailwind CSS, Storybook, React, Next.js, Angular  
**Back end:** C#, ASP.NET Core, Entity Framework Core, Dapper, Node.js (NestJS, Express), Go  
**Data:** SQL Server, PostgreSQL, MongoDB  
**Quality and delivery:** Vitest, Vue Test Utils, Playwright, axe, GitHub Actions, Azure DevOps, Docker

## Experience

<details>
<summary><b>Chiavelli Dev</b> · Senior Software Engineer · Apr 2024 – present · Remote</summary>
<br/>

Contract software engineering through my own company. Current engagement: modernizing a large business intelligence platform for the foodservice industry, from .NET Razor views to a Nuxt 4 front end and .NET APIs, screen by screen.

- Legacy and new screens run side by side behind a YARP reverse proxy (Strangler Fig), so each screen ships on its own and users never face a big-bang cutover
- Own product areas end to end: analytics dashboards with Highcharts, choropleth maps, and URL-driven filter state that keeps legacy deep links working
- Recover business rules buried in legacy controllers and stored procedures, so every rewritten screen matches production
- Build ASP.NET Core (.NET 9) endpoints with Entity Framework Core and Dapper on SQL Server, consumed through typed TypeScript clients
- Contributed to the migration of 40+ routes to the new front end so far

</details>

<details>
<summary><b>HCosta</b> · Senior Full Stack Developer · Sep 2024 – Dec 2025 · Bauru, Brazil</summary>
<br/>

- Led the front end of new web applications built from scratch, defining the Nuxt 3, Vue 3 and TypeScript architecture
- Created a private npm package of shared UI components, so the applications reused one component set
- Designed and built REST APIs in .NET Core with Entity Framework and SQL Server, including JWT authentication
- Took ownership of legacy Django and MongoDB services, consolidating data under a single access layer

</details>

<details>
<summary><b>Valtech</b> · Full Stack Developer · Mar 2022 – Sep 2024 · Remote</summary>
<br/>

- Built Vue 3 and TypeScript interfaces on Optimizely CMS with a .NET back end for Valtech's global clients
- Modernized legacy client applications through incremental migrations to Vue 3, with zero-downtime releases
- Standardized a UI component library documented in Storybook, and added unit and end-to-end tests with Vitest and Cypress

</details>

<details>
<summary><b>Linx</b> · Developer Analyst · Jan 2021 – Feb 2022 · Bauru, Brazil</summary>
<br/>

- Worked on a foodservice product that consolidated sales from delivery platforms into a single view for operators
- Built back-end services in .NET Core with Entity Framework, Dapper and SQL Server, and dashboards with AG Grid and Vue 2
- Implemented real-time updates with SignalR and JWT-based authentication

</details>

<details>
<summary><b>NeoAssist</b> · Front-End Developer · Jan 2020 – Jan 2021 · Bauru, Brazil</summary>
<br/>

- Front-end work on an omnichannel customer service platform built in Vue 2 and Vuex
- Customized the platform as a white-label product for new clients, adapting it to each client's brand

</details>

Earlier: web developer at Zeon Solutions (2018–2019), customer success with code-level fixes in PHP and Symfony at Arca Solutions (2017–2018), and web developer intern at MStech (2016).

## Education

**Postgraduate in Software Architecture** · Infnet · in progress  
**Bachelor's in Information Systems** · Instituição Toledo de Ensino · 2015 – 2019  
**Systems Analysis and Development** · Instituição Toledo de Ensino · 2023
