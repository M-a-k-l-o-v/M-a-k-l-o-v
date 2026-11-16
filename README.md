# Marvellous Olushola

Final-year Computer Science and Mathematics student at Lancaster University. I work on 3D reconstruction from ordinary video, and I'm learning to build and evaluate the models behind it.

## What I'm building now

**[Virtual Space Constructor](https://github.com/M-a-k-l-o-v/open3d_world_recon_and_action_sim)** (Python, Open3D, PyTorch)
Turn a phone video of a real space into a 3D reconstruction, then a physics simulation of it. Checkpoints in order: reconstruct, simulate, add actors. Currently on checkpoint 1.

- First result: [why my first reconstruction stacked layers](https://github.com/M-a-k-l-o-v/open3d_world_recon_and_action_sim/blob/main/report_notes/Stage%20Reports/Midas_pose_drift_as_baseline.md). Even with known camera poses, per-frame MiDaS depth disagrees between frames: 2.4 mm at the calibration board, about 30 mm at 30–60 cm from it. Stacking frames therefore makes layers however the alignment is tuned.
- Next: measure a feed-forward pose model (VGGT) against COLMAP, with checkerboard poses as ground truth.

## Other work

**[Eval-driven personal task agent](https://github.com/M-a-k-l-o-v/Eval-driven-personal-task-agent)** (Python)
A locally hostable task agent with an evaluation harness, built with a partner. My part: the agent core, the inference service, the OpenAI and MLX backends, the output adapter and telemetry. My partner owns the eval harness, training pipeline and scenarios. It runs against fake in-memory tools, not real accounts.

**[Regional Integrated Transport Application](https://github.com/M-a-k-l-o-v/Regional-Integrated-Transport-Application)** (TypeScript)
University team project. My part: the Express, Prisma and Postgres backend, live bus and rail feed ingestion, and the admin API with API-key auth and role-based access.

### Earlier projects

- [Bach-man](https://github.com/M-a-k-l-o-v/Bach_man_game_for_A_level_project) (Python, pygame, SQLite): my A-level project, a Pac-Man-style maze game with player accounts and a high-score table.
- [Early experiments](https://github.com/M-a-k-l-o-v/early-experiments): first scripts, web pages and Django tutorials from 2021–2023. Kept for history; not maintained.

## How I work

- Every project ends in a write-up with numbers and a line on what it doesn't show.
- I say which parts are mine and which are a teammate's.
- Where an AI assistant helped write code or text, the repo says so.

## Find me

- LinkedIn: [marvellousolushola](https://www.linkedin.com/in/marvellousolushola/)
- LeetCode: [Marvellous_Olushola](https://leetcode.com/u/Marvellous_Olushola/)
