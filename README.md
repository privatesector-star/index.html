# index.html # initialize repo
git init
git add index.html
git commit -m "Initial commit: BTC DEX Screener single-file app"

# create remote repo on GitHub (requires GitHub CLI `gh` installed and logged in)
# If you don't have gh, skip the gh command and create repository on github.com (web) then add remote.
gh repo create your-username/btc-dex-screener --public --source=. --remote=origin --push
