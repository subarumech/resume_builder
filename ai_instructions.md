# AI Resume Customization Instructions

## Your Primary Mission
Create a resume that passes ATS (Applicant Tracking System) filters by maximizing keyword matches while staying 100% truthful to my actual achievements.

## Step-by-Step Process

### 1. ATS Keyword Analysis
Read `job_posting.md` and identify:
- **Technical keywords** (software, tools, methodologies, certifications)
- **Industry terms** (regulatory standards, processes, equipment)
- **Action verbs** commonly used in engineering/PM roles
- **Quantifiable metrics** they're looking for
- **Required qualifications** that must appear verbatim

Focus on terms that ATS systems commonly filter for in engineering and project management positions.

### 2. Achievement Deep-Dive
Review `my_achievements.md` and for each relevant experience:
- Identify which ATS keywords I can legitimately claim
- Look for opportunities to add technical specificity
- Find quantifiable results that weren't explicitly stated
- **ASK ME QUESTIONS** if you need clarification to maximize keyword inclusion

Example questions you could ask:
- "What specific software versions did you use at Neuralink?"
- "What was the budget range for those facility projects?"
- "Which regulatory standards did you work with?"
- "What manufacturing methodologies did you implement?"

### 3. Professional Rewriting Rules
- **Concise and data-driven**: Every bullet should have metrics when possible
- **Engineering-focused language**: Use precise technical terminology
- **ATS optimization**: Work in as many relevant keywords as naturally possible
- **Professional tone**: Formal but not overly verbose
- **Action-result format**: "Did X which resulted in Y" structure
- **Avoid repetitive phrases**: Don't end multiple sentences with the same phrase (e.g., "in manufacturing environment") - vary sentence structure and integrate keywords naturally

### 4. Resume Creation Guidelines
- **Include ALL positions** from my_achievements.md in every resume
- **CRITICAL BULLET POINT LIMITS**: 
  - **Maximum 4 bullets** for the 2 most important/relevant positions
  - **Maximum 3 bullets** for all other positions
  - **NEVER exceed these limits** - quality over quantity
- Rewrite achievement bullets to maximize ATS keyword density
- Prioritize skills that match job requirements exactly
- Use the same terminology as the job posting when describing my experience
- **Make a LaTeX file based on the layout of base_resume.tex**

## Critical Rules
1. **NEVER fabricate** - Only use achievements I actually accomplished
2. **ASK QUESTIONS** - If unsure about details that could add keywords, ask me
3. **Stay truthful** - Enhance presentation but never invent experience
4. **Maximize keywords** - Work in every legitimate keyword possible
5. **Be specific** - Use exact tool names, standards, methodologies I actually used

## Output Requirements
- Create `customized_resume.tex` that compiles cleanly
- Maximize ATS keyword matches from the job posting
- Maintain professional engineering/PM language
- Include quantified achievements wherever possible
- Ask clarifying questions to extract maximum keyword potential
- **File Organization**: Place finished resumes in folders organized by employer name, with files named using the standard format: `[JobID]_[PositionTitle].tex` (e.g., `12345_Senior_Software_Engineer.tex` or `Senior_Project_Manager.tex` if no Job ID is available). If a folder for the specific employer does not exist, create one to organize the resume properly.
- **PDF Title**: The LaTeX `\pdftitle{}` should match the .tex filename (e.g., for `696298BR_Manufacturing_Engineer.tex`, use `\pdftitle{696298BR_Manufacturing_Engineer}`).

## Resume Formatting Rules

### Contact Information
- **Email**: Always use `michaelanthonymoranjr@gmail.com` for all resumes
- **Spacing**: Use `\vspace{0.25 cm}` between contact information and Professional Summary section (reduced from 0.40 cm)

### Job Entry Formatting
- **Two-column layout**: Dates and location in right column, job title and company in left column
- **Right column**: Dates on first line, location on second line
- **Left column**: Job Title on first line, Company Name on second line
- **CRITICAL: Right column must be double width** - Use `\setcolumnwidth{\fill, 9.0 cm}` instead of the default 4.5cm
- **Structure**:
  ```
  \begin{twocolentry}{
  \textit{Dates}
  
  \textit{Location}}
      \textbf{Job Title}
      
      \textit{Company Name}
  \end{twocolentry}
  ```

### Content Guidelines
- **Include ALL positions** from my_achievements.md in every resume
- **CRITICAL BULLET POINT LIMITS**: 
  - **Maximum 4 bullets** for the 2 most important/relevant positions
  - **Maximum 3 bullets** for all other positions
  - **NEVER exceed these limits** - quality over quantity
- **ATS optimization**: Work in as many relevant keywords as naturally possible
- **Professional tone**: Formal but not overly verbose
- **Action-result format**: "Did X which resulted in Y" structure
- **Avoid repetitive phrases**: Don't end multiple sentences with the same phrase - vary sentence structure and integrate keywords naturally

## Remember
Your goal is to help me get past the ATS filter by presenting my real achievements in the most keyword-rich, professionally optimized way possible. Every word should serve the purpose of either demonstrating my qualifications or matching ATS search terms.

---

*Start by reading the job posting, then ask me any questions needed to maximize keyword inclusion before creating the resume. Use the answers I give you to those questions to update my achievements as well for future use.*