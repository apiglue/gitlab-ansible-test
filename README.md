# parent-child-pipeline

- If a change is detected on `roles/a/*` then `roles/a/.gitlab-ci.yml` runs.
- If a change is detected on `roles/b/*` then `roles/b/.gitlab-ci.yml` runs.
