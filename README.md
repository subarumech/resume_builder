# Simple AI Resume Builder

A dead-simple system for customizing your LaTeX resume using Cursor AI.

## How It Works

1. **Update the job posting** in `job_posting.md`
2. **Ask Cursor AI** to read `ai_instructions.md` and customize your resume
3. **Compile the generated LaTeX** to PDF

That's it!

## Files

```
resume_builder/
├── templates/
│   └── base_resume.tex      # Your LaTeX resume template
├── my_achievements.md       # All your experiences and skills
├── job_posting.md          # Paste job descriptions here
├── ai_instructions.md      # Instructions for Cursor AI
└── README.md              # This file
```

## Usage

### Step 1: Update the Job Posting
Edit `job_posting.md` and paste in the job description you're applying for.

### Step 2: Ask Cursor AI
Simply ask Cursor AI:

> *"Please read ai_instructions.md and create a customized resume"*

### Step 3: Compile to PDF
```bash
pdflatex customized_resume.tex
```

## What Cursor AI Will Do

- Read your achievements from `my_achievements.md`
- Read the job requirements from `job_posting.md`
- Select your most relevant 3-4 job experiences
- Rewrite achievement bullets to match the job requirements
- Choose relevant skills that align with what the employer wants
- Create a new `customized_resume.tex` file based on your template
- Keep everything truthful to your actual experience

## Benefits

- ✅ **Ultra simple** - Just 3 files to manage
- ✅ **No setup** - No Python, no dependencies, no API keys
- ✅ **Full transparency** - See exactly what changes are made
- ✅ **Easy to modify** - Edit your achievements anytime
- ✅ **Reusable** - Just update the job posting for each application

## Installation

Only requirement: LaTeX for PDF compilation
- **macOS**: `brew install --cask mactex`
- **Windows**: Download MiKTeX from https://miktex.org/
- **Linux**: `sudo apt-get install texlive-full`