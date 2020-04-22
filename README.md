# Wiki

My personal wiki page contains, not limited to, the following contents:

Kyumatic instructions, concepts, glossary
K_FRET, K_RISC related
Mobility
SETFOS
PAIOS
Data Automation

## Markdown syntax

1. Use `<sup>` and `</sup>` for superscript. (github doesn't support `[^ref]` and `[^ref]: footnote` )
2. Use `#` \~ `######` for the font size.


## Git
1. create local branch
```
git checkout -b dev_ingest
git branch dev_ingest
```
2. connect to repo
```
git push --set-upstream origin dev_ingest
```
3. pull remote branch
```
git checkout -t origin/dev_ingest
```
4. delete local and remote branch
```
git branch --delete dev_ingest
git push origin :dev_ingest
```
5. pull request (?)
```
git push --noff
```
