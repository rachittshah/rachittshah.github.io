# Rachitt Shah's Blog

A modern technical blog built with MkDocs Material theme, focusing on AI Engineering, RAG Systems, and Technical Notes.

## Features

- 🎨 Modern Material Design
- 🌙 Dark/Light mode support
- 🔍 Full-text search
- 📱 Mobile-friendly
- 🔄 RSS feed support
- 📊 SEO optimized
- 🏷️ Tag-based navigation
- 🔗 Social media integration
- 📝 Math equation support
- 🖼️ Responsive images
- 💻 Code syntax highlighting

## Local Development

### Prerequisites

- Python 3.10 or higher
- pip (Python package manager)

### Setup

1. Clone the repository:
```bash
git clone https://github.com/rachittshah/rachittshah.github.io.git
cd rachittshah.github.io
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

### Running the Development Server

Start the local development server:
```bash
mkdocs serve
```

The site will be available at `http://localhost:8000`

### Building the Site

To build the static site:
```bash
mkdocs build
```

The built site will be in the `site` directory.

## Project Structure

```
.
├── docs/
│   ├── index.md          # Home page
│   ├── about.md          # About page
│   ├── blog/            # Blog posts
│   │   ├── index.md     # Blog landing page
│   │   └── posts/       # Individual blog posts
│   ├── rag/             # RAG Systems section
│   ├── ai/              # AI Engineering section
│   ├── stylesheets/     # Custom CSS
│   └── javascripts/     # Custom JavaScript
├── mkdocs.yml           # MkDocs configuration
└── requirements.txt     # Python dependencies
```

## Content Management

### Adding a New Blog Post

1. Create a new markdown file in `docs/blog/posts/`
2. Add YAML frontmatter:
```yaml
---
title: Your Post Title
description: Brief description
date: YYYY-MM-DD
tags:
  - tag1
  - tag2
---
```

### Custom Styling

Custom styles can be added in `docs/stylesheets/extra.css`

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the main branch.

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

MIT License - See [LICENSE](LICENSE) for details

## Contact

- GitHub: [@rachittshah](https://github.com/rachittshah)
- Twitter: [@rachittshah](https://twitter.com/rachittshah)
- LinkedIn: [Rachitt Shah](https://www.linkedin.com/in/rachittshah)
- Email: [contact@rachittshah.com](mailto:contact@rachittshah.com) 