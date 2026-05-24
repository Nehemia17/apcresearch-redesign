# APC Research — Applied Physics and Chemistry @ Nano Center Indonesia

> Official website of the **Applied Physics and Chemistry (APC)** research group at **Nano Center Indonesia**, built with Jekyll and deployed via GitHub Pages.

[![Jekyll](https://img.shields.io/badge/Jekyll-4.x-red?logo=jekyll&logoColor=white)](https://jekyllrb.com/)
[![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-blue?logo=github)](https://pages.github.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 🔬 About

The APC Research website serves as the central hub for the Applied Physics and Chemistry group at Nano Center Indonesia. It features:

- **Research publications** synced from Substack via webhook integration
- **Research subteam profiles** (Wastewater, Nanofibers, Nano-Petro, Low-Dimensional Materials)
- **Team & people** directory
- **Partnership & openings** information
- **Contact** page

---

## 🗂️ Project Structure

```
apcresearch-redesign/
├── _config.yml           # Jekyll site configuration
├── _data/
│   ├── publications.yml  # Publications data
│   └── research.yml      # Research areas data
├── _includes/            # Reusable HTML partials (header, footer, etc.)
├── _layouts/             # Page layout templates
├── _posts/               # Blog/news posts
├── _sass/                # SCSS stylesheets
├── assets/               # Static assets (images, CSS, JS)
├── pages/
│   ├── contact.html      # Contact page
│   ├── openings.html     # Job/research openings
│   ├── partnership.html  # Partnership opportunities
│   ├── people.html       # Team members
│   ├── publications.html # Research publications
│   └── research.html     # Research overview
├── 404.html              # Custom 404 error page
├── Gemfile               # Ruby dependencies
└── index.html            # Homepage (landing page)
```

---

## 🚀 Getting Started

### Prerequisites

- [Ruby](https://www.ruby-lang.org/) >= 2.7
- [Bundler](https://bundler.io/)
- [Jekyll](https://jekyllrb.com/) >= 4.x

### Installation

```bash
# Clone the repository
git clone https://github.com/Nehemia17/apcresearch-redesign.git
cd apcresearch-redesign

# Install Ruby dependencies
bundle install
```

### Running Locally

```bash
bundle exec jekyll serve
```

Then open your browser and visit: `http://localhost:4000`

### Building for Production

```bash
bundle exec jekyll build
```

The output will be generated in the `_site/` directory.

---

## 🧪 Research Subteams

| Subteam | Focus Area |
|---|---|
| 💧 **Wastewater Solutions** | Nanobubbles & advanced oxidation for industrial wastewater treatment |
| 🧵 **Nanofibers via Electrospinning** | Polymer nanofibers for biomedical and filtration applications |
| 🛢️ **Nano-Petro** | Nanofluids for enhanced oil recovery (EOR) and reservoir simulation |
| ⚛️ **Low-Dimensional Materials** | 2D materials (graphene, MoS₂) for next-gen electronics |

---

## 📄 Publishing Workflow

Researchers publish directly to our **Substack** account (`apcresearch.substack.com`), and new papers are automatically synced to this website via webhook integration — no manual deployment required.

```
Write Paper → Publish on Substack → Auto-Sync (Webhook) → Live on Website
```

---

## 🤝 Contributing

We welcome contributions! If you'd like to improve the website:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add some improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

---

## 📬 Contact

- **Email:** contact@nanocenter.id
- **Substack:** [apcresearch.substack.com](https://apcresearch.substack.com/)
- **Institution:** [Nano Center Indonesia](https://nanocenter.id)

---

## 📝 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  Made with ❤️ by the APC Research Team @ Nano Center Indonesia
</p>
