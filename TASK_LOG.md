# TASK 4 — Execution Log
- Created repo with dockerized sample app.
- Branched: main, dev, feature/update-homepage.
- PR: feature -> dev (merged), PR: dev -> main (merged).
- Tag: v1.0 pushed.
cd "C:\Users\harsh\Downloads\Terraform Labs\Dockerized_Webapp"

# paste your two PR URLs here ↓↓↓
$pr1 = "https://github.com/SuryanshGarg04/devops-task4-git-workflow/pull/1"
$pr2 = "https://github.com/SuryanshGarg04/devops-task4-git-workflow/pull/2"

@"
## PR Links
- feature → dev: $pr1
- dev → main: $pr2
"@ | Add-Content -Encoding UTF8 .\TASK_LOG.md
