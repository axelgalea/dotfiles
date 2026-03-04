## Skills
npx skills add https://github.com/vercel-labs/skills --skill find-skills

### GIT
npx skills add https://github.com/obra/superpowers --skill using-git-worktrees

### Frontend
npx skills add https://github.com/anthropics/skills --skill frontend-design

### Tanstack Query
npx skills add https://github.com/jezweb/claude-skills --skill tanstack-query

### Better Auth
npx skills add https://github.com/better-auth/skills --skill better-auth-best-practices

### React
npx skills add vercel-labs/agent-skills

### React Native
npx skills add expo/skills

### Office
npx skills add https://github.com/anthropics/skills --skill xlsx
npx skills add https://github.com/anthropics/skills --skill docx

### Emails
npx skills add https://github.com/resend/email-best-practices --skill email-best-practices

### ~/.bashrc
Function that will eventually become a ralph loop 
ralph() {
  if [ -z "$1" ]; then
    echo "Usage: oc <directory>"
    return 1
  fi
 opencode run "@PRD.md @progress.txt \
1. Read the PRD and progress file. \
2. Find the next incomplete task and implement it. \
3. Commit your changes. \
4. Update progress.txt with what you did. \
ONLY DO ONE TASK AT A TIME." --dir "$1" --agent build --model opencode/minimax-m2.5
}
