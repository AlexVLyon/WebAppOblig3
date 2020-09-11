# Oppgave 3:



$ git switch oppgave3
Switched to branch 'oppgave3'

## Lage fil i dev branch lokalt (hiof.js fil med console.log("hiof"))

- $ git add hiof.js

- $ git commit
 - [oppgave3 cbf956d3] Created hiof.js
 - 1 file changed, 1 insertion(+)
 - create mode 100644 oppgave2/hiof.js

- $ git push

- $ git remote https://github.com/AlexVLyon/WebAppOblig3

Pushe endringene til repo
Lage en fil i dev branch remote
Hente endringene lokalt


- Sette opp nytt repo i Github
- Lage dev branch lokalt
    - $ git branch oppgave3
- Lage fil i dev branch lokalt (hiof.js fil med console.log("hiof"))
    - $ git add hiof.js
- Commite disse
    - $ git commit
     - [oppgave3 cbf956d3] Created hiof.js
     - 1 file changed, 1 insertion(+)
     - create mode 100644 oppgave2/hiof.js

- Pushe endringene til repo
    - $ git push
- Lage en fil i dev branch remote
- Hente endringene lokalt
    - git pull
- Merge filene fra dev i master
    - $ git switch master
    - git merge oppgave3
        -får error: The following untracked working tree files would be overwritten by merge:
    - git add
- Samarbeide med en kollega eller en annen konto du har for å få til merge conflict
    -skriver dette på en annen pc.

- Resolve merge conflict
- (frivillig prøve ut stash, pop og cherry-pick)