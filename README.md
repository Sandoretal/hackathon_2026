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
| Part 2 | `Part2.ipynb` | your cleaned data from Part 1, **or** `data/backups/ppmi_hack_cleaned_part1.csv` |
| Part 3 | `Part3.ipynb` | your imputed data from Part 2, **or** `data/backups/ppmi_hack_imputed_part2.csv`; plus `data/clinics_lookup_dirty.csv` for the Final Challenge |

Each part builds on the previous one, but **you don't need to finish a part to attempt the next one**: the intermediate files in `data/backups/` let you start Part 2 or Part 3 at any time. Save your own outputs to `data/ppmi_hack_cleaned_part1.csv` (end of Part 1) and `data/ppmi_hack_imputed_part2.csv` (end of Part 2).

Write your code and answers in the empty cells under each question.

**No generative AI tools, including GitHub Copilot** (Extensions → GitHub Copilot → gear icon → Disable).
