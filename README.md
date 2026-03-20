# Project Steps for Trial Activation Analytics

1. Create the GitHub public repository. Do not add a README yet if you plan to start entirely locally (to avoid merge conflicts).
2. Clone locally

```bash
git clone https://github.com/your-username/trial_activation_analytics.git
cd trial_activation_analytics
```

3. Initialize dbt inside the cloned repo

```bash
dbt init . # The . tells dbt to create its project files in the current folder (your cloned repo)
```

4. Commit initial dbt files to GitHub

```bash
git add .
git commit -m "Initialize dbt project"
git push origin main
```

## Result:
- dbt project is now fully version-controlled locally and remotely.
- Every change can be pushed to GitHub.
