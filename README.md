# DevOps, QA and Test Automation Tools Dashboard

A polished static reference site for comparing modern DevOps, CI/CD, QA automation, API testing, performance testing, container, infrastructure, and observability tools.

## What This Project Includes

- A visual dashboard in `index.html` with tool cards, delivery flow, stack recommendations, and official source links.
- A dedicated `tools.html` reference page with deeper guidance for each tool.
- A dedicated `architecture.html` page explaining the end-to-end delivery lifecycle from planning to production feedback.
- Local visual assets in `assets/`, including tool logos and a dashboard hero image.
- No build step, framework, package manager, or server dependency required.

## Pages

| Page | Purpose |
|---|---|
| `index.html` | Main dashboard and overview of the tool landscape |
| `tools.html` | Tool-by-tool catalog with use cases, strengths, and adoption guidance |
| `architecture.html` | Delivery pipeline stages, quality gates, and team stack patterns |

## Tool Coverage

| Area | Tools |
|---|---|
| CI/CD | GitHub Actions, Jenkins, GitLab CI/CD |
| Containers and Infrastructure | Docker, Kubernetes, Terraform |
| QA Automation | Playwright, Selenium, Cypress, BrowserStack |
| API and Performance Testing | Postman, Apache JMeter |
| Observability | Prometheus, Grafana |

## Recommended Use Cases

| Team Type | Recommended Stack |
|---|---|
| Lean Web Team | GitHub Actions, Docker, Playwright, Postman |
| Platform Engineering | Terraform, Kubernetes, Prometheus, Grafana, GitLab CI/CD |
| Enterprise QA | Jenkins, Selenium, Cypress, BrowserStack, Apache JMeter |

## Project Structure

```text
.
|-- README.md
|-- index.html
|-- tools.html
|-- architecture.html
`-- assets/
    |-- devops-dashboard-photo.jpg
    `-- logos/
        |-- apache-jmeter.svg
        |-- cypress.svg
        |-- docker.svg
        |-- github-actions.svg
        |-- gitlab.svg
        |-- grafana.svg
        |-- jenkins.svg
        |-- kubernetes.svg
        |-- postman.svg
        |-- prometheus.svg
        |-- selenium.svg
        `-- terraform.svg
```

## Run Locally

Open `index.html` directly in a browser, or serve the folder with a local static server:

```bash
python -m http.server 8080
```

Then visit:

```text
http://localhost:8080
```

## Deploy To GitHub Pages

1. Push the repository to GitHub.
2. Open repository **Settings**.
3. Go to **Pages**.
4. Set the source to the main branch and root folder.
5. Save the configuration.

Because this project is pure static HTML/CSS, GitHub Pages can host it directly from the repository root.

## Notes

The adoption and fit scores are dashboard heuristics for comparison and planning. They are not market-share claims.