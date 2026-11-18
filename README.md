# Hackathon 2026 Setup Instructions

### Setup

The hackathon uses the same **`m3` environment** as the Module 3 tutorials, so there is nothing new to install.

1. **Before the hackathon day:** if you haven't set up the `m3` environment yet, follow the **Prerequisites and Setup** section of the Module 3 repository: [https://github.com/Sandoretal/module3_2026](https://github.com/Sandoretal/module3_2026)

2. Download this entire GitHub repository ([https://github.com/Sandoretal/hackathon_2026](https://github.com/Sandoretal/hackathon_2026)) as ZIP, extract it, and place the extracted folder (`hackathon_2026-main`) on the Desktop

3. Open the folder in VS Code (**File → Open Folder…**)

4. Open `Part1.ipynb`, click **Select Kernel** (top right) and choose **Python (m3)**. If it isn't listed: `Ctrl+Shift+P` / `Cmd+Shift+P` → **Python: Select Interpreter** → pick the path containing `envs/m3`, then try again

5. Run the first code cell: you should see a table of the data with no errors

### Notebooks and data files

| Part | Notebook | Start from |
|---|---|---|
| Part 1 | `Part1.ipynb` | `data/ppmi_hack_dirty.csv` |
| Part 2 | `Part2.ipynb` | `data/backups/ppmi_hack_cleaned_part1.csv` (question 1), then `data/backups/ppmi_hack_imputed_part2.csv` (questions 2–4) |
| Part 3 | `Part3.ipynb` | `data/backups/ppmi_hack_imputed_part2.csv`, plus `data/clinics_lookup_dirty.csv` for the Final Challenge |

**Parts 2 and 3 start from the backup files in `data/backups/`**, so every group works from the same data and you can attempt the parts in any order. Still save your own outputs when the notebooks ask: `data/ppmi_hack_cleaned_part1.csv` (end of Part 1) and `data/ppmi_hack_imputed_part2.csv` (end of Part 2).

Write your code and answers in the empty cells under each question.

**No generative AI tools, including GitHub Copilot** (Extensions → GitHub Copilot → gear icon → Disable).
