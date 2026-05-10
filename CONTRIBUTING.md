# Contributing Guide

Thank you for your interest in contributing to this project.

This project is a static RTL landing page built with HTML, CSS, and Vanilla JavaScript. Contributions should keep the project lightweight, accessible, SEO-friendly, and easy to deploy on GitHub Pages.

## How to Contribute

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Test the page locally.
5. Submit a pull request.

```bash
git checkout -b feature/your-feature-name
```

## Local Development

Run a simple local server:

```bash
python -m http.server 3000
```

Open:

```txt
http://localhost:3000
```

## Branch Naming

Use clear branch names:

```txt
feature/add-contact-form
fix/mobile-spacing
docs/update-readme
style/refine-hero-section
seo/update-schema
```

## Commit Message Style

Use readable commit messages:

```txt
feat: add contact section
fix: improve mobile CTA spacing
docs: update deployment guide
style: refine pricing cards
seo: add FAQ structured data
```

Recommended prefixes:

| Prefix     | Purpose                  |
| ---------- | ------------------------ |
| `feat`     | New feature              |
| `fix`      | Bug fix                  |
| `docs`     | Documentation changes    |
| `style`    | Visual/CSS changes       |
| `refactor` | Code restructuring       |
| `seo`      | SEO-related changes      |
| `perf`     | Performance improvements |
| `chore`    | Maintenance tasks        |

## Code Guidelines

Please follow these guidelines:

- Use semantic HTML.
- Keep the page accessible.
- Keep CSS readable and organized.
- Avoid unnecessary JavaScript.
- Do not add heavy dependencies.
- Do not add build tools unless necessary.
- Keep the project GitHub Pages compatible.
- Optimize images before committing.
- Use descriptive class names.
- Maintain RTL layout compatibility.
- Test on mobile and desktop.

## SEO Guidelines

When changing page content, check:

- Page title
- Meta description
- Canonical URL
- Heading hierarchy
- Open Graph tags
- Twitter Card tags
- Structured data
- Sitemap URL
- Internal anchor links

## Accessibility Guidelines

Before submitting:

- Check keyboard navigation.
- Check focus states.
- Use meaningful link text.
- Do not rely only on color.
- Keep text readable on mobile.
- Keep good contrast between text and background.
- Use correct heading order.

## Pull Request Checklist

Before opening a pull request:

- [ ] I tested the page locally.
- [ ] I checked mobile responsiveness.
- [ ] I verified internal anchor links.
- [ ] I checked the browser console for errors.
- [ ] I avoided unnecessary dependencies.
- [ ] I updated documentation if needed.
- [ ] I kept RTL layout intact.
- [ ] I considered SEO impact.
- [ ] I considered accessibility impact.

## Reporting Issues

Use the issue templates in `.github/ISSUE_TEMPLATE`.

Please include:

- Clear description
- Steps to reproduce
- Expected behavior
- Actual behavior
- Browser/device details
- Screenshots if relevant

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
