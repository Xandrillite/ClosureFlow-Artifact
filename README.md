# ClosureFlow research artifact

[Download the current artifact ZIP](https://github.com/Xandrillite/ClosureFlow-Artifact/releases/download/artifact-2026-09-25/ClosureFlow_Artifact.zip) (SHA-256 `8d73ab72f0d26ef6dc36001a8e092b86eb47e538ae18513a8032e42f040f5912`). Extract on Windows 10/11 with Python 3.10+; a fresh six-tool run also requires WSL2 Ubuntu 22.04.

```text
python -m pip install -r requirements.txt
python run_all.py --check
python run_all.py --stage rq1
```

The default command re-scores packaged native analyzer responses. For a fresh run: `python run_all.py --stage rq1 --install-tools --re-run`. The ZIP also includes data and scripts for RQ2 (projects and CVEs), RQ3 (recorded ablation counts), and RQ4 (recorded timing). See the README inside for commands, result locations, tool prerequisites and provenance.
