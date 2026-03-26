# ParamGolf

Fork of openai/parameter-golf with a personal `notes/` folder for studying competition techniques.

## Repo structure

- `notes/` — Jupyter notebook knowledge base (personal study notes, not part of submissions)
- `records/` — Competition submissions
- `train_gpt.py` — Baseline training script
- Everything else — OpenAI's original repo structure

## Submission workflow

- `main` branch: includes `notes/`, visible on GitHub profile
- Submission branches: branch off `upstream/main`, only contain `records/` changes, PR'd to openai/parameter-golf
- Notes never enter submission branches because those branches start from upstream, not fork main

## Note-taking rules

- User pastes articles/content, I convert into Jupyter notebooks in `notes/`
- Simple topics: light notes, key takeaways, enough to recall later
- Advanced topics: thorough documentation with formulas, code, architecture details
- Apply stop-slop principles: no filler, no throat-clearing, direct statements, active voice
