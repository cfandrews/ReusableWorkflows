# ReuseableWorkflows
Reusable GitHub workflows.

## python-build
Runs `build.sh` in Python packages in the context of the latest patch version of every Python minor version currently in
security or bugfix support status. See [the official Python support status page](https://devguide.python.org/versions/)
for the most up-to-date list of which minor versions are included.

```
cfandrews/ReusableWorkflows/.github/workflows/python-build.yml
```
