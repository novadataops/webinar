первый репозиторий


git filter-branch --force --index-filter \
  'git rm --cached --ignore-unmatch 1.txt' \
  --prune-empty --tag-name-filter cat -- --all