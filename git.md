```
git config --global user.name "Kirill Osenkov"
git config --global user.email "my email"

git config --global fetch.prune true
git config --global merge.conflictstyle diff3
git config --global rerere.enabled true
git config --global push.default simple
git config --global core.editor "vsnotepad -n"
git config --global format.pretty oneline
git config --global log.abbrevCommit true
git config --global push.autoSetupRemote true

git config --global submodule.fetchJobs 8       # Parallel submodule fetches
git config --global status.submoduleSummary true # Show submodule changes in git status
git config --global diff.submodule log           # Show submodule diffs as commit logs
```
