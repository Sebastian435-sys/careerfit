# CareerFit — AI Resume Match Scorer

An AI-powered web app that analyzes your resume against tech and engineering roles and returns a match score, skills gap breakdown, and actionable recommendations.

Built with vanilla HTML/CSS/JS and the Claude API (Anthropic).

## What it does

1. Select a target role (Data Analyst, Software Engineer, ML Engineer, and 13+ others)
2. Paste your resume text
3. Claude analyzes your qualifications against real role requirements and returns:
   - Overall match score (0–100)
   - Matched vs. missing skills
   - Category breakdown (technical skills, experience, education, projects)
   - Top 4 specific actions to improve your fit
   - Honest hiring manager perspective

## Roles supported

**Data:** Data Analyst, Data Engineer, Data Scientist, BI Analyst, Analytics Engineer  
**AI/ML:** ML Engineer, AI Research Scientist  
**Engineering:** Software Engineer, Frontend Engineer, Backend Engineer, DevOps/Platform Engineer  
**Product:** Product Manager, Technical PM  
**Other:** UX/Product Designer, Cybersecurity Analyst, Cloud Architect

## Tech stack

- Vanilla HTML, CSS, JavaScript (no frameworks)
- Claude claude-sonnet-4-6 API via Anthropic
- Google Fonts (Inter + Space Grotesk)

## Setup

1. Clone the repo
```bash
git clone https://github.com/yourusername/careerfit.git
cd careerfit
```

2. The app calls the Anthropic API directly from the browser. To run locally with your own API key, add a proxy or use Anthropic's claude.ai artifact environment where the API key is handled automatically.

3. Open `index.html` in a browser or deploy to any static hosting (GitHub Pages, Vercel, Netlify).

## Deployment (GitHub Pages)

1. Push to GitHub
2. Go to repo Settings → Pages → set source to `main` branch, `/ (root)`
3. Your app will be live at `https://yourusername.github.io/careerfit`

## Project structure

```
careerfit/
└── index.html    # Full app (single file — HTML, CSS, JS)
└── README.md
```

## Built by

Sebastian Gonzalez — [linkedin.com/in/sebastian-g-ucla](https://linkedin.com/in/sebastian-g-ucla)
