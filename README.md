# CISA_Quiz
Basic html quiz as CISA study guide
## Version 4. Notes 

### Major Changes: 
1. **Better Answer Options** — All 120 questions now have plausible wrong answers with similar length to the correct answer. No more obviously wrong options.
2. **Smart Answer Randomization** — Correct answers are randomized across positions A-D with intelligent distribution to avoid patterns (like "all B answers").
3. **Fixed Missed Questions Checkbox** — Now works properly across all browsers and platforms (Safari, Chrome, desktop, mobile, PWA).
4. **Attempt History & Cumulative Scoring** — Full tracking:
      - See all attempts at each question (e.g., "2 out of 3 correct = 66.6%")
      - Latest quiz score shown on dashboard
      - Cumulative average across all quiz attempts
      - Question-level performance history
5. **Two Filter Options:**
      - "Show only questions missed in last attempt"
      - "Show only questions below 56% target" (new!) — shows questions where you haven't reached the passing threshold
6. **Dashboard Shows 56% Target:**
      - Latest score vs. 56% passing target
      - Cumulative score vs. target
      - Target indicator shows "+5%" if above or "-3%" if below
      - Quick visual feedback on progress
7. **Enhanced Missed Questions View** — Shows your record on each missed question across all attempts (e.g., "2/3 correct = 66%")

### Sources for CISA passing score:
      https://support.isaca.org/s/article/Exams-How-is-my-Certification-exam-scored-brief-version

--------------------------------------------------
## Version 3. Notes 
### Key New Features:
* Partial Quiz Completion — Exit and resume at any time. Your progress is automatically saved.
* Progress Tracking by Domain — Dashboard shows:

### Answered/unanswered counts for each domain
* Overall answered/unanswered counts
* Visual progress bars for each domain

### Question Status Tracking — Each question displays:
* Answered ✓ or Unanswered ○ indicator
* Progress bar showing your position in the quiz

### Resume/Restart Options — When a quiz is in progress:
* "Resume Quiz" button to continue where you left off
* "Restart Quiz" to start fresh with the same domain selection

### Answer Preservation — Your answers are saved to localStorage, so even if you close the app:
* Your progress is retained
* You can resume later
* Domain progress stats update in real-time

### Flexible Quiz Modes:
* Single domain
* Multiple domains (multi-select)
* All domains at once
* Missed questions only (optional)

### Dashboard Enhancements:
* Total answered/unanswered counts
* Per-domain answered/unanswered breakdown
* Overall score tracking
* Quick action buttons

The app fully supports offline use, home screen installation on iPhone/mobile, and all data persists locally on your device.\
