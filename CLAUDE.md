Workspace for job application process

on claude machine:
user: claude
password: password

## Context

resumes/Hannah_Kim/Hannah_Kim_Resume.docx
resumes/Hannah_Kim/Hannah_Kim_Resume.pdf
APPLICATION_EXTRAS.md
applied/index.md

## Applying
use playwright mcp, linkedin, company websites and the starter list provided:

Washington DC Area:

https://careers.medstarhealth.org/global/en/job/MEHEGLOBALREQ43479ENGLOBAL/Clinical-Research-Coordinator-II-Oncology
https://jobs.iqvia.com/en
https://www.indeed.com/q-epic-ehr-l-washington,-dc-jobs.html
https://careers.deloitte.com/teams/health
https://careers.hjf.org

New York City:
6. https://jobs.nyulangone.org/job/21623399/clinical-research-coordinator-new-york-ny/
7. https://builtinnyc.com/company/oscar-health/jobs
8. https://careers.mountsinai.org/jobs/3024865
Seattle:
9. https://www.fredhutch.org/en/about/careers.html
10. https://www.path.org/who-we-are/careers/
Additional Opportunities:
11. https://careers.iconplc.com/jobs
12. https://commercialcareers.syneoshealth.com

continue to search based on the content of the starter list.

## Procedure
1. open site (ensure we haven't applied already based on index.md contents)
2. think about the job, and the experience outlined in the resume+APPLICATIONS_EXTRAS.md and decide on how to fill out given page
3. if unsure on if to proceed for a particular link, create a summary of why and bin it in a file of the "job_examplename.md" explaining what other info was needed or follow up questions you couldn't readily come up with
    3a. check APPLICATION_EXTRAS.md for cached answers 
4. store answers provided in the APPLICATION_EXTRAS.md file to act as a sort of cache 
5. after applying store the related info in the way described (jobs.docx, and jobs.markdown, and the sql database)
6. write a summary in the applied/ folder with job_title_at_place.md for reviewing what the job entails in case we receive follow up and need a refresher 


## Tracking Job Applications
- in docx table (for quick review)
- in markdown table (for quick review)
- also in a database using sql such that the schema allows for easy visualization for a website that tracks progress of applciations or atleast a list
- store password used for sit in the job applied file

## Style
- no emojis
- use bun for typscript
- use uv for python (uv python subagent)
- commit messages should exclude "🤖 Generated with [Claude Code](https://claude.ai/code)Co-Authored-By: Claude <noreply@anthropic.com>"
