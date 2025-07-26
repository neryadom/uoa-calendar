# UoA Course Calendar 

This website is made for people who miss the simple HTML based course calendar that UOA used to offer, up until April or May 2025. Since then, there has been no new HTML version made by uni,
so this project steps in to fill in the gap temporarily.
This is a web-based set of HTML files for browsing University of Auckland course descriptions, making it easier to explore subjects and courses compared to the official PDF calendar.


## Live Site
**[uoacalendar.co.nz](https://uoacalendar.co.nz)**

## What This Project Does

This project transforms the University of Auckland's course calendar from a big PDF file into a simple, searchable, and mobile-friendly website. Students can browse subjects alphabetically, jump to specific letter sections, and easily find course information without scrolling through hundreds of pages.

## Technical Overview

- **Static HTML/CSS** - Hosted on GitHub Pages for simple access
- **Minimal dependencies** - No backend
- **Issue reporting** - Integrated with Formspree for course correction submissions
- **Google Analytics** - Basic home page usage counting

## Project Structure

```
uoacalendar/
├── index.html              # Main subjects listing page
├── issues.html             # Course issue reporting form
├── issues_thanks.html      # Form submission confirmation
├── subjects/               # Individual subject pages
│   ├── COMPSCI.html       # Computer Science major and its courses
│   ├── MATHS.html         # Mathematics major and its courses
│   ├── ENGLISH.html       # English major and its courses
│   └── ...                # 200+ other subjects
├── CNAME                  # Custom domain configuration
└── README.md              # This file
```

## Important Disclaimer

This is an **unofficial** snapshot of course information taken from the University of Auckland Calendar PDF. While every effort is made to keep it accurate:

- Information may contain errors or omissions
- Course details can change between calendar updates
- Always verify with the [official University Calendar](https://www.auckland.ac.nz/en/about-us/about-the-university/the-university/official-publications/university-calendar.html) for definitive information

## Found an Issue?

Spot an incorrect course title, points value, prerequisite, or description? You have two options:

1. **Quick Report** - [Use the issue form](https://uoacalendar.co.nz/issues.html) for a simple report
2. **Direct Contribution** - Fork the repo and submit a pull request (see Contributing section below)

## Contributing

This is a **public repository** and contributions are welcome! Here's how you can help improve the course calendar:

### Fork & Pull Request Workflow

1. **Fork the repository** - Click the "Fork" button on GitHub to create your own copy
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/uoacalendar.git
   cd uoacalendar
   ```
3. **Create a feature branch**:
   ```bash
   git checkout -b fix/course-description-typo
   # or
   git checkout -b feature/new-subject-page
   ```
4. **Make your changes** - Edit the relevant HTML files in `/subjects/` or main pages
5. **Test locally** - Open `index.html` in your browser to verify changes
6. **Commit and push**:
   ```bash
   git add .
   git commit -m "Fix COMPSCI 101 prerequisite description"
   git push origin your-branch-name
   ```
7. **Create a Pull Request** - Go to your fork on GitHub and click "New Pull Request"

###  What Contributions Are Helpful

- **Course corrections** - Fix typos, outdated prerequisites, incorrect point values
- **New subject pages** - Add missing subjects from the official calendar
- **Accessibility improvements** - Better screen reader support, keyboard navigation
- **Mobile optimizations** - Improve responsive design for smaller screens
- **Performance enhancements** - Optimize loading times, reduce file sizes
- **Documentation** - Improve this README or add inline code comments

### Contribution Guidelines

- Keep changes focused (one issue per PR)
- Test your changes in multiple browsers if possible
- Follow the existing HTML/CSS style and structure
- For course content changes, reference the official UoA Calendar PDF
- Be respectful in pull request descriptions and discussions

### Quick Edits

For simple typo fixes, you can even edit files directly on GitHub:
1. Navigate to the file on GitHub
2. Click the edit icon to edit
3. Make your change and commit with a descriptive message
4. GitHub will automatically create a fork and pull request for you

## Development

This project uses vanilla HTML, CSS, and JavaScript to maintain simplicity and fast loading times. The site is automatically deployed via GitHub Pages when changes are pushed to the main branch.

### Local Development
1. Clone the repository
2. Open `index.html` in a web browser
3. Make changes to HTML/CSS files as needed
4. Test locally before pushing

## Why This Exists

The official UoA course calendar is published as a massive PDF that's difficult to navigate on mobile devices and hard to search through. This project was created to solve that problem by providing:

- **Better accessibility** - Screen reader friendly, proper HTML structure
- **Faster searching** - Browser's built-in find function works across all courses
- **Mobile experience** - Responsive design that works on any device
- **Direct linking** - Share specific courses or subjects via URL anchors

## Usage Stats

The site tracks basic visitor counts to understand usage patterns while respecting user privacy. No personal information is collected or stored.

---

*Last updated: July 2025*
