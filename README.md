# Prince Kwakye

Full-stack developer from Ghana, backend-leaning. I build production systems with .NET, Angular, and Flutter, with a strong focus on reliable APIs, databases, caching, and handling failures.

- **Core stack:** C# / .NET 8+, TypeScript / Angular, Dart / Flutter, PostgreSQL, Redis
- **Also work in:** Python, Ruby, Golang
- **Reach me:** [kwakyeprince088@gmail.com](mailto:kwakyeprince088@gmail.com)

---

## Featured work

### BizTrack — retail POS & inventory platform
[biztracksoft.com](https://biztracksoft.com) · source private

A multi-tenant point-of-sale and inventory system for Ghanaian retailers, built
as three clients against one .NET 8 API.

- **API** — ASP.NET Core with CQRS via MediatR, EF Core 9 on PostgreSQL, and
  tenant isolation enforced through global query filters. Sales commit in a
  single transaction with guarded stock deduction, so two cashiers selling the
  last unit can't oversell. SignalR notifications and cache invalidation are
  dispatched through an outbox table, so nothing is lost if the process dies
  mid-write.
- **Performance** — Redis caching over dashboard and report queries, with
  explicit invalidation on every mutation that makes a figure stale.
- **Also** — JWT auth with role-based access, endpoint rate limiting, PDF receipt
  generation (QuestPDF), Serilog, and an xUnit suite over the sale and refund
  paths.
- **Clients** — an Angular admin app (standalone components, server-side
  DataTables, ApexCharts) and a Flutter mobile app for cashiers.

### [Real-Time Satellite Data Visualizer](https://github.com/Prince-Kwakye/Real-Time-Satellite-Data-Visualizer)
Python tool that pulls live natural-event data from NASA's EONET API and plots it
on an interactive map, layered with current conditions from OpenWeatherMap. An
exercise in reconciling two independent feeds with different update cadences.

### [DemoUniReg](https://github.com/Prince-Kwakye/DemoUniReg)
ASP.NET Core REST API backing a university registration system — course
enrolment, student records, and the scheduling constraints between them.

### [Quantum Monte Carlo](https://github.com/Prince-Kwakye/Quantum-Morte-Carlo)
High-performance numerical integration using quasi-Monte Carlo methods — Sobol,
Halton, and Latin hypercube sampling — with convergence compared against
standard pseudo-random sampling.

---

## GitHub

<p align="left">
  <img height="180"
       alt="Prince Kwakye's GitHub profile summary"
       src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Prince-Kwakye&theme=github_dark" />
</p>

<p align="left">
  <img height="165"
       alt="Contribution streak"
       src="https://streak-stats.demolab.com?user=Prince-Kwakye&hide_border=true&background=00000000&stroke=8b949e&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff&sideLabels=8b949e&dates=8b949e&currStreakNum=8b949e&sideNums=8b949e" />
  <img height="165"
       alt="Repos per language"
       src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Prince-Kwakye&theme=github_dark" />
</p>

---

Open to collaboration and to talking shop — email is best.
