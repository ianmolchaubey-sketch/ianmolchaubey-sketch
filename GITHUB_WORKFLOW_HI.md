# GitHub Workflow (Hinglish)

## Profile README kaise show hota hai

1. GitHub par `ianmolchaubey-sketch` naam ka **public** repository banao.
2. Repository ka owner aur repository name bilkul GitHub username ke same hone chahiye.
3. Is folder ka `README.md` us repository ke root mein upload ya push karo.
4. GitHub profile reload karo. README profile ke top par show hoga.

## Har repository ke liye same issue aur PR templates

1. GitHub par ek alag **public** repository banao jiska naam exactly `.github` ho.
2. Is profile repository se `community-templates/pull_request_template.md` ko new repository ke `.github/pull_request_template.md` path par copy karo.
3. `community-templates/ISSUE_TEMPLATE` folder ko new repository ke `.github/ISSUE_TEMPLATE` path par copy karo.
4. Future project repositories mein local templates na hone par GitHub in shared templates ko use karega.

## Aaj ek genuine contribution kaise karein

1. `network-labs` jaisa useful public repository banao.
2. Ek real lab add karo: goal, topology, configuration, verification commands, and troubleshooting notes.
3. `git add .`, meaningful message ke saath commit karo, aur default branch par push karo.
4. Public repository par valid author email ke saath pushed commit contribution graph mein count ho sakta hai. GitHub ko update dikhane mein thoda time lag sakta hai.

## Issue kya hai

Issue task, bug, idea, ya question ko track karta hai.

Example: `Document OSPF neighbor troubleshooting steps`

Issue body mein problem, expected outcome, acceptance checklist, aur relevant logs/configuration ke sanitized snippets likho.

## Pull Request kya hai

Pull Request (PR) ek branch ke changes ko main branch mein review aur merge karne ka request hota hai.

Flow:

```text
Issue -> branch -> commits -> Pull Request -> review -> merge
```

Example branch: `docs/ospf-troubleshooting`

## Commit kya hai

Commit code or documentation ka saved, reviewable change hota hai. Small aur honest commits rakho:

```text
docs: add OSPF verification commands
feat: add subnet calculator input validation
fix: retry DNS query on timeout
```

## Contribution graph ke rules

- Green squares ke liye empty commits, copied repos, ya repeated README edits mat karo.
- Real commits, approved PRs, issue discussions, code reviews, documentation, aur labs build karo.
- Commit author email GitHub account mein verified email se match honi chahiye.
- Commit default branch (usually `main`) ya `gh-pages` par hona chahiye, aur repository standalone honi chahiye; fork-only commit usually count nahi hota.
- Public repo commits normally count hote hain; private contribution display GitHub profile settings se controlled hota hai.

## Recommended repository order

1. `network-labs`
2. `linux-server-hardening`
3. `python-network-tools`
4. `cloud-networking-notes`
5. `dsa-cpp`

Ek strong documented repository paanch empty repositories se better hota hai.
