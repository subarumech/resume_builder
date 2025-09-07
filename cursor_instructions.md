
# CURSOR AI RESUME CUSTOMIZATION INSTRUCTIONS

## Job Target Analysis
- **Company/Role**: Senior Manufacturing Engineer - Medical Device Company
- **Experience Level**: senior
- **Key Technical Terms**: api, solidworks, manufacturing, lean, six sigma, quality, iso, fda, medical device, cleanroom, project management, leadership, team, automation
- **Management/Soft Skills**: project management, team lead, leadership, mentor, manage, cross-functional

## Custom Instructions
Focus on medical device experience and regulatory compliance

## Your Task
Please customize the LaTeX resume in `templates/base_resume.tex` based on the following:

### 1. Experience Selection & Ordering
From the job experiences in `data/job_experiences.json`, select and prioritize the most relevant experiences that match the job requirements. Consider:
- Technical skill alignment with: api, solidworks, manufacturing, lean, six sigma, quality, iso, fda, medical device, cleanroom, project management, leadership, team, automation
- Management experience relevance: project management, team lead, leadership, mentor, manage, cross-functional
- Industry/domain fit
- Experience level progression

### 2. Achievement Bullet Optimization
For each selected experience, rewrite the achievement bullets to:
- Emphasize skills that match the job requirements
- Use relevant keywords from the job description
- Quantify results where possible
- Highlight transferable skills
- Keep bullets concise (1-2 lines each)
- Stay extremely truthful to the original achievements

### 3. Skills Section Customization  
From the skills in `data/job_experiences.json`, select and prioritize skills that are most relevant to this role:
- Prioritize technical skills that match job requirements
- Include relevant management/leadership skills
- Organize by relevance to the target role

### 4. Profile/Summary Customization
Update the profile section to align with the target role and emphasize relevant experience.

## Important Guidelines
- Stay truthful to the original data - don't fabricate experiences
- Use the exact LaTeX formatting from the original template
- Focus on the most relevant 3-4 job experiences
- Maintain professional tone and formatting
- Ensure all LaTeX syntax is correct

## Job Description for Reference
```
Senior Manufacturing Engineer - Medical Device Company

We are seeking a Senior Manufacturing Engineer to join our dynamic team developing cutting-edge medical devices. The ideal candidate will have experience in manufacturing processes, quality systems, and cross-functional team leadership.

Key Responsibilities:
- Lead manufacturing process development and optimization for medical device assembly
- Implement lean manufacturing principles to improve efficiency and reduce waste
- Develop and maintain work instructions, process documentation, and quality procedures
- Collaborate with R&D, Quality, and Production teams on new product introductions
- Manage capital equipment projects and facility improvements
- Ensure compliance with FDA regulations and ISO 13485 quality standards
- Mentor junior engineers and technicians

Required Qualifications:
- Bachelor's degree in Mechanical, Manufacturing, or Industrial Engineering
- 5+ years of experience in medical device or highly regulated manufacturing
- Strong knowledge of lean manufacturing, Six Sigma, and process improvement methodologies
- Experience with CAD software (SolidWorks preferred)
- Familiarity with statistical process control and data analysis
- Understanding of FDA regulations and medical device quality systems
- Excellent project management and leadership skills

Preferred Qualifications:
- Experience with cleanroom manufacturing environments
- Knowledge of automation and robotics in manufacturing
- Previous experience with facility design and construction projects
- Certification in Six Sigma (Green Belt or higher)
- Experience with ERP systems and manufacturing execution systems (MES)

This role offers the opportunity to work on life-saving medical devices in a fast-paced, innovative environment where you can make a real impact on patient outcomes.

```

Please analyze the job requirements and customize the resume accordingly.


---

# AVAILABLE DATA REFERENCE

## Personal Information
```json
{
  "name": "Mike Moran",
  "phone": "941-894-8801",
  "email": "mikeymoran714@gmail.com",
  "linkedin": "https://www.linkedin.com/in/michael-moran-fl/",
  "linkedin_handle": "michael-moran-fl",
  "location": "Orlando, FL"
}
```

## Profile/Summary
Project Manager, Mechanical Engineer, and Facility Coordinator. Proven ability to lead teams and subordinates effectively on complex technical challenges. Four years of experience in the world's most advanced manufacturing and construction environments; from launch vehicles to medical devices. Looking for a role where I can contribute to cutting-edge projects that require all members to "wear many hats."

## Education
```json
[
  {
    "institution": "University of Florida",
    "degree": "B.S. in Mechanical Engineering",
    "graduation_date": "Dec 2021",
    "start_date": "Aug 2017",
    "location": "Gainesville, FL"
  }
]
```

## Skills by Category
```json
{
  "management": [
    "Project planning and scheduling",
    "lab management",
    "employee leadership and mentorship",
    "budget and cost control",
    "risk management",
    "production planning",
    "production control",
    "ERP systems"
  ],
  "mechanical_engineering": [
    "Rapid tooling and process design",
    "advanced RCA resolution",
    "FEA",
    "agile manufacturing design",
    "product development",
    "thermal management systems",
    "design for manufacturing",
    "assembly work instructions"
  ],
  "facilities_construction": [
    "Facility management/leadership",
    "high-pressure gas systems",
    "project management",
    "cleanroom standards",
    "OSHA safety protocols",
    "HVAC",
    "clean water systems",
    "architectural design reviews",
    "construction coordination and facilitation"
  ],
  "manufacturing": [
    "Sensitive electronics assembly",
    "cleanroom experience",
    "authoring work instructions",
    "CNC mills/lathes",
    "microfabrication equipment",
    "cryogenics",
    "hydraulics",
    "lean manufacturing",
    "production planning",
    "heavy machinery",
    "hand tools",
    "lean six sigma",
    "production control",
    "MRP"
  ],
  "software": [
    "SolidWorks",
    "Microsoft Project",
    "Microsoft Office (including Excel)",
    "Jira",
    "Revit",
    "Siemens NX",
    "ERP systems",
    "Python",
    "Google Workspace"
  ]
}
```

## All Job Experiences
```json
[
  {
    "company": "CURIS System",
    "position": "Project Manager",
    "start_date": "March 2025",
    "end_date": "Present",
    "location": "Orlando, FL",
    "achievements": [
      "Managed engineering teams in scaling design and manufacturing operations, implementing lean manufacturing techniques and utilizing ERP systems for project management",
      "Directed multi-million dollar facility bio-decontamination system integrations and in-house R&D for next-generation product development"
    ],
    "key_terms": [
      "ERP systems",
      "lean manufacturing",
      "project management",
      "R&D",
      "engineering teams",
      "manufacturing operations",
      "facility integration",
      "bio-decontamination"
    ]
  },
  {
    "company": "MTronPTI",
    "position": "Manufacturing Engineer",
    "start_date": "Feb 2025",
    "end_date": "March 2025",
    "location": "Orlando, FL",
    "achievements": [
      "Enhanced manufacturing processes for DoD suppliers, creating detailed assembly work instructions and technical drawings, and applying lean manufacturing principles",
      "Voluntarily left to pursue a significantly improved offer from a prior interview"
    ],
    "key_terms": [
      "lean manufacturing",
      "technical drawings",
      "assembly work instructions",
      "manufacturing processes",
      "DoD suppliers"
    ]
  },
  {
    "company": "Neuralink",
    "position": "Production Facility Coordinator",
    "start_date": "March 2023",
    "end_date": "June 2024",
    "location": "Austin, TX",
    "achievements": [
      "Directed the construction and facilitization of a new manufacturing facility and lab, managing budgets, schedules, and lean initiatives to achieve a 10x increase in N1 brain implant production capacity",
      "Managed construction schedules, upgrade installations, and project budgets; including three full-scale production lines, cleanroom HVAC and power installations, medical-grade water systems, and dozens of other major improvements to pass regulatory compliance audits",
      "Designed and implemented mechanical assemblies, lab documentation, and facility upgrades using tools like SolidWorks, Revit, and Google Workspace tools"
    ],
    "key_terms": [
      "SolidWorks",
      "Revit",
      "Google Workspace",
      "cleanroom HVAC",
      "medical-grade water systems",
      "facility construction",
      "manufacturing facility",
      "production capacity",
      "cleanroom",
      "HVAC",
      "regulatory compliance",
      "mechanical assemblies",
      "project budgets",
      "lean initiatives"
    ]
  },
  {
    "company": "Neuralink",
    "position": "Manufacturing Technician",
    "start_date": "March 2022",
    "end_date": "March 2023",
    "location": "Austin, TX",
    "achievements": [
      "Acted as a Manufacturing Engineer, optimizing processes with SolidWorks and RCA, and implementing lean manufacturing to reduce deviations by up to 30%",
      "Personally designed, built, and programmed a custom, auto-failover, high-pressure gas system for the clean room gas supplies",
      "Authored work instructions, validations, process maps, and maintenance protocols for N1 brain implant assembly",
      "Built N1 devices, tooling, and the manufacturing line itself. Utilized every tool imaginable, from microfab and probe stations to forklifts and lathes"
    ],
    "key_terms": [
      "SolidWorks",
      "RCA",
      "lean manufacturing",
      "high-pressure gas systems",
      "microfab",
      "probe stations",
      "CNC lathes",
      "manufacturing engineer",
      "process optimization",
      "work instructions",
      "brain implant assembly",
      "microfabrication",
      "tooling"
    ]
  },
  {
    "company": "SpaceX",
    "position": "Starship Integration Technician",
    "start_date": "June 2020",
    "end_date": "October 2020",
    "location": "Boca Chica, TX",
    "achievements": [
      "Installed cryogenic fuel systems, avionics, and hydraulics for Starship second stage vehicles SN5\u2013SN12, utilizing technical schematics and diagrams",
      "Used Siemens NX to improve manufacturing steps with build engineers, speeding up LOX downcomer installation by several hours"
    ],
    "key_terms": [
      "Siemens NX",
      "cryogenic systems",
      "avionics",
      "hydraulics",
      "technical schematics",
      "Starship",
      "cryogenic fuel systems",
      "manufacturing optimization",
      "LOX downcomer"
    ]
  },
  {
    "company": "Altavian",
    "position": "Mechanical Engineering Intern",
    "start_date": "Sep 2018",
    "end_date": "July 2019",
    "location": "Gainesville, FL",
    "achievements": [
      "Designed and validated thermal management systems for military drone systems, reducing internal peak temperatures by 8%, and created detailed technical documentation and work instructions",
      "Developed MIL-SPEC cable harness molds for the drone system's base station / controller assembly",
      "Automated BOM documentation for the DoD using SolidWorks macros, reducing manual intervention from engineers"
    ],
    "key_terms": [
      "SolidWorks",
      "thermal management systems",
      "MIL-SPEC",
      "SolidWorks macros",
      "thermal management",
      "military drone systems",
      "cable harness",
      "technical documentation",
      "BOM automation",
      "DoD"
    ]
  }
]
```

---

# WORKFLOW

1. Read this analysis and the job description above
2. Review the available data (experiences, skills, etc.)
3. Select the most relevant 3-4 job experiences for this role
4. Customize the LaTeX resume in `templates/base_resume.tex`
5. Focus on matching keywords and requirements from the job description
6. Ensure all LaTeX formatting is preserved

The goal is to create a targeted resume that highlights your most relevant experience for this specific role while staying truthful to your actual background.
