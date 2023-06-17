My most starred repos:
| ⭐️Stars   | 📦Repo    | 📚Description | Timestamp |
| --------- | ----------- | -------------- | ---------- |
{{ loop 2_RECENTLY_PUSHED_REPOS }}
| {{ REPO_STARS }} | [{{ REPO_FULL_NAME }}]({{ REPO_URL }}) | {{ REPO_DESCRIPTION }} | {{ REPO_PUSHED_TIMESTAMP }}
{{ end 2_RECENTLY_PUSHED_REPOS }}