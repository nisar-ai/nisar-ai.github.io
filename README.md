# Nisar Ahmad — Computer Systems Portfolio

Personal portfolio of Nisar Ahmad, a BS Computer Science undergraduate at COMSATS University Islamabad, Sahiwal Campus.

🔗 [Live portfolio](https://nisar-ai.github.io/)

## About

This portfolio presents my academic background, systems-oriented projects, technical skills, and research interests.

I am interested in computer networks, operating systems, cloud computing, and distributed systems. My current projects explore queueing, finite service capacity, request admission, retry behaviour, and tail latency through implementation and simulation.

I am seeking a summer 2027 undergraduate research internship in computer systems.

## Academic Background

- Degree: BS Computer Science
- Institution: COMSATS University Islamabad, Sahiwal Campus
- Current semester: Third semester, Fall 2026
- CGPA: 3.50 / 4.00
- Academic standing: Top five in a class of 50 students
- Expected graduation: July 2029

### Coursework

| Status | Courses |
| --- | --- |
| Completed | Programming Fundamentals; Object Oriented Programming (Java); Discrete Structures |
| In progress — Fall 2026 | Data Structures (C++); Database Systems (Oracle SQL); Fundamentals of Digital Logic Design |
| Planned — Spring 2027 | Computer Networks; Artificial Intelligence; Information Security |

## Selected Systems Projects

### CloudTrace Lab

A configurable discrete-event microservice simulator for exploring request arrivals, finite service capacity, queueing, simulated failures, and retries.

Features include:

- Exponential-backoff retries with jitter.
- Seeded experiments for repeatable simulation runs.
- Request- and service-level CSV trace export.
- Mean and p50/p95/p99 latency analysis.
- Success-rate, utilisation, queue-wait, and bottleneck analysis.
- Interactive visualisations.

Technologies: Python, Gradio, NumPy, Pandas, Plotly, Hugging Face Spaces.

[Source code](https://github.com/nisar-ai/cloudtrace-lab)

#### Reported Example Run

The portfolio includes the following example outputs documented in my CV:

| Metric | Reported value |
| --- | --- |
| Requests simulated | 300 |
| Successful requests | 298 / 300 (99.3%) |
| p50 latency | 3.32 seconds |
| p95 latency | 6.05 seconds |
| p99 latency | 6.26 seconds |
| Requests requiring multiple attempts | 24 |

These are single-run simulation outputs, not production measurements or a comparative performance benchmark. Latencies represent simulated request time.

The reported run does not establish an improvement over a baseline. Independent reproduction would require its exact configuration, random seed, code version, and exported traces.

### Token Bucket Rate Limiter

A serverless rate-limiting demonstration with a live traffic simulator.

Features include:

- Token refill and burst handling.
- Request admission and throttling.
- HTTP 429 responses.
- Throttling visualisation and timestamped event logs.
- Git-based continuous deployment.

Technologies: JavaScript, Netlify Functions, REST APIs.

Scope: a demonstration of rate-limiting behaviour, not a claim of globally consistent enforcement across multiple serverless instances.

## Additional Software Projects

| Project | Description | Technologies / Status |
| --- | --- | --- |
| UniBot Next | AI-assisted university admissions chatbot with server-side API handling and environment-variable secret management. | Next.js, React, Tailwind CSS, Groq API, Netlify |
| GlobalVisa Flow | Multilingual visa-planning application with document checklists and cost/timeline estimates. | Next.js, TypeScript; running locally for development and testing; public deployment in progress |
| Multilingual Translator | Translation application for English, Urdu, Arabic, and German using a pretrained model. | Python, Streamlit, NLLB-200, Hugging Face Spaces |
| NovaCalc | Scientific calculator with a controlled expression evaluator. | Mathematical expression evaluation |
| Weather Forecast App | Application displaying weather conditions and forecast information through public weather APIs. | External API integration |

## Portfolio Sections

1. Introduction — academic profile, research direction, and CV.
2. Selected Systems Projects — CloudTrace Lab and Token Bucket Rate Limiter.
3. Research Interests — networks, operating systems, cloud systems, and experimental questions.
4. Education — completed, current, and planned coursework.
5. Technical Skills — programming, systems concepts, analysis tools, and deployment.
6. Independent Development — self-directed implementation experience.
7. Additional Software Projects — supporting application-development work.
8. Honors & Activities — academic recognition and ongoing leadership development.
9. Certifications — training and available verification links.
10. Contact — personal and university email addresses.

## Built With

- HTML5 — semantic page structure.
- CSS3 — layout, styling, responsive design, and print styles.
- IBM Plex Sans and IBM Plex Mono — typography through Google Fonts.
- GitHub Pages — static website hosting.

No JavaScript frameworks, package installation, or build tools are required.

## Repository Structure

```text
.
├── index.html             # Portfolio content and page structure
├── styles.css             # Styling, responsive layout, and print styles
├── Nisar_Ahmad_CV.pdf      # CV linked from the portfolio
├── README.md              # Repository documentation
└── certs/                 # Optional certificate images retained from earlier versions
```

The current page uses certificate verification links and does not require certificate images.

## Run Locally

Clone the repository:

```bash
git clone [https://github.com/nisar-ai/nisar-ai.github.io.git](https://github.com/nisar-ai/nisar-ai.github.io.git)
cd nisar-ai.github.io
```

Open `index.html` in your browser.

Alternatively, if Python is installed, start a local static server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Update the Portfolio

- Edit `index.html` to update content, projects, coursework, and links.
- Edit `styles.css` to change the visual design.
- Replace `Nisar_Ahmad_CV.pdf` when updating the CV, keeping the filename consistent with the HTML link.
- Update the “Last updated” date after making content changes.
- Confirm that project results and status descriptions match the underlying work.

Commit and push your changes:

```bash
git add index.html styles.css README.md Nisar_Ahmad_CV.pdf
git commit -m "Update systems research portfolio"
git push origin main
```

If your repository uses a different branch, replace `main` with that branch name.

## GitHub Pages Deployment

In the repository settings:

1. Open **Settings → Pages**.
2. Select **Deploy from a branch** as the source.
3. Select the branch containing the portfolio files.
4. Select **/ (root)** as the publishing folder.
5. Save the configuration.

The portfolio is intended to be published at:

https://nisar-ai.github.io/

## Research and Reporting Scope

This portfolio distinguishes between:

- Research interests and completed experience.
- Simulation results and real-system measurements.
- Independent projects and institutional employment.
- Pretrained-model integration and model training.
- Locally running applications and publicly deployed services.
- Ongoing programmes and completed certifications.

Project descriptions are intended to reflect the work accurately, without claiming production readiness or unsupported performance improvements.

## Contact

- GitHub: [github.com/nisar-ai](https://github.com/nisar-ai)
- LinkedIn: [Nisar Ahmad](https://www.linkedin.com/in/nisar-ahmad-973a673a2/)
- Personal email: [iamnisarahmad08@gmail.com](mailto:iamnisarahmad08@gmail.com)
- University email: [fa25-bcs-092@students.cuisahiwal.edu.pk](mailto:fa25-bcs-092@students.cuisahiwal.edu.pk)

---

Last updated: October 28, 2026
