- 👋 Hi, I’m @suresh-vaddi-usps
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
suresh-vaddi-usps/suresh-vaddi-usps is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

## GitHub Actions Workflows

### Resend Open Workflow Notifications

This repository includes a workflow that monitors and resends notifications for open (in-progress, queued, or waiting) GitHub Actions workflows.

**Features:**
- 🔄 Automatically monitors workflow runs
- 📋 Lists all open workflows with detailed information
- ⏰ Scheduled checks every 6 hours
- 🎯 Manual triggering with filtering options
- 📊 Detailed summary reports

**How to Use:**

1. **Automatic Monitoring**: The workflow runs automatically every 6 hours to check for open workflows
2. **Manual Trigger**: Go to Actions → "Resend Open Workflow Notifications" → Run workflow
   - Optionally filter by specific workflow name
   - Optionally filter by status (all, in_progress, queued, waiting)
3. **Workflow Event Trigger**: Automatically triggered when the CI workflow runs

**What it does:**
- Scans all workflow runs in the repository
- Identifies workflows that are currently open (not completed)
- Logs detailed information about each open workflow
- Creates a summary table in the job output
- Sends notifications about the current status
