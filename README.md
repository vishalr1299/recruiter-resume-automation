# Recruiter Resume Automation

Automation project for standardizing candidate resumes into a recruiter-defined Word format.

## Project Goal

Take a raw candidate resume and produce a consistently formatted `.docx` while preserving the candidate's content.

## Current Formatting Specification

- Narrow document margins
- No extra paragraph spacing
- Verdana 11 pt
- Remove existing headers and footers
- Rebuild candidate contact information at the top in the standard order: full name, email, contact number, LinkedIn
- Section order: Professional Summary, Technical Skills, other applicable sections, Education, Certifications (if present), Professional Experience
- Section headings are bold and underlined
- Normal content is not bold/highlighted
- Summary bullets remain bullets and are left aligned
- Professional Experience is the largest section
- Experience is organized as Company/Client, tenure in `MMM YYYY - Present` style, designation, and responsibilities when present
- Company/designation/responsibility labels are bold where applicable; responsibility content is left-aligned bullet points

## Development Approach

The first version will use deterministic Python document processing before introducing AI.

## Planned Phases

1. Word document formatting MVP
2. Resume content extraction
3. Intelligent section detection
4. JD/resume matching
5. Skill matrix generation
6. Recruiter screening assistant
7. Web application
8. Database and users
9. Deployment
10. Freelance-ready productization
