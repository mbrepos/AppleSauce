https://github.com/raycast/script-commands/tree/master/commands/web-searches
# Use the following structure when updating this file: 
```bash
echo "'<command>' <comment>" | cat >> NOTEPAD.md
```
# Git References (SORTED)
'git remote add origin https://github.com/mbrepos/AppleSauce.git' # Links a remote repo to the current directory
'git commit -m <message>' # Prepares updates to the current LINKED remote
'git branch' # Checks what branch (if any) is currently set
'git push origin main' # Pushes the commit to the designated branch
'git fetch origin' # fetches the origin of the repo to get most recent updates
'git rebase origin main' # Used on divergent branches to consolidate commit history
'git config --global gpg.format ssh' # Tell GitHub to use SSH as Global Signing Format
'git config --global user.signingkey </PATH/TO/.SSH/KEY.PUB>' # Tell GitHub to use <key.pub> as Key for Signing
'echo "Current branch: $(git branch --show-current 2>/dev/null || echo 'not a repo')"' # Exports the Current Branch (I.E., "Main")
 ######
