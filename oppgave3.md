# Oppgave 3:

## Lage dev branch lokalt
    - $ git branch oppgave3
## Lage fil i dev branch lokalt (hiof.js fil med console.log("hiof"))
    - $ git add hiof.js
## Commite disse
    - $ git commit
     - [oppgave3 cbf956d3] Created hiof.js
     - 1 file changed, 1 insertion(+)
     - create mode 100644 oppgave2/hiof.js

## Pushe endringene til repo
    - $ git push
## Lage en fil i dev branch remote
## Hente endringene lokalt
    - git pull
## Merge filene fra dev i master
    - $ git switch master
    - $git merge oppgave3
        - får error: The following untracked working tree files would be overwritten by merge:
        - bruker git push og det funker
        - må fikse merge conflict for det jeg akuratt skrev
    - $git merge oppgave3
        - de er merget 
## Samarbeide med en kollega eller en annen konto du har for å få til merge conflict
    - Bruker en annen pc og skriver dette her i oppgave3.md

## Resolve merge conflict
    - trykker "Accept incoming" i VS code
    - //<<<<<<< HEAD
        -skriver dette på en annen pc.

    - //=======
        - Bruker en annen pc og skriver dette her i oppgave3.md
    - //>>>>>>> 1eafdb33ec9ab898be35d85e1a0f8fa10e0aae0b
    
