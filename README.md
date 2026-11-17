# HN "Who is Hiring?" Monthly Report

**🔎 Search this month's jobs live: [prostyropor-star.github.io/hn-who-is-hiring-report](https://prostyropor-star.github.io/hn-who-is-hiring-report/)** (filter by keyword, remote, salary, visa)

Numbers from the monthly **Ask HN: Who is hiring?** thread on Hacker News, parsed into structured data (company, role, remote policy, salary, tech stack). Updated monthly.

## November 2026 (245 job posts)

**Remote policy** (from each post's first line)

| Work mode | Posts | Share |
|---|---|---|
| Remote | 105 | 43% |
| Onsite | 52 | 21% |
| Hybrid | 37 | 15% |
| Remote or onsite | 15 | 6% |
| Not stated | 36 | 15% |

Remote posts restricted to a region: US 23, Europe/EU 7, worldwide 7, UK 2.

**Most mentioned tech**

| Tech | Posts |
|---|---|
| AI | 130 |
| Data | 87 |
| Python | 62 |
| TypeScript | 51 |
| React | 50 |
| AWS | 33 |
| ML | 24 |
| Rust | 21 |
| LLM | 19 |
| Postgres | 18 |
| Node | 17 |
| Kubernetes | 16 |
| Next.js | 16 |
| C++ | 14 |

**Salaries**: 55 posts state a USD range. Median midpoint: **$187,500**.

| Stack mentioned | Posts with USD range | Median midpoint |
|---|---|---|
| Python | 19 | $180,000 |
| React | 18 | $182,938 |
| TypeScript | 13 | $180,000 |
| Rust | 7 | $200,000 |
| Kubernetes | 7 | $200,000 |

**Visa sponsorship** mentioned positively in 17 posts (7%).

## Method

Posts are read through the official public Hacker News API (hn.algolia.com). The first line of each post (`Company | Role | Location | REMOTE | Salary`) is split into fields; tech tags are keyword matches over the whole post. Free-text parsing is heuristic, so treat small counts with care. No personal data (names, emails, usernames) is collected.

## Get the data yourself

The structured data behind this report (every post as a row: company, roles, work mode, remote region, location, salary min/max, visa, tech tags, apply link, link to the HN post) comes from the
**[Hacker News Who is Hiring Jobs Scraper](https://apify.com/mistlike_potato/hn-who-is-hiring-jobs-parser)** on Apify. It can also send you only *new* posts every day, filtered by keyword, remote and salary.

More job data tools: [Career Site Jobs Scraper](https://apify.com/mistlike_potato/career-site-jobs-scraper) (34,000+ company job boards) · [job-board-starter](https://github.com/prostyropor-star/job-board-starter)

---
Made by ProStyropor. Not affiliated with Hacker News or Y Combinator.
