# Oppgave 1 - angremekanismer

Før du begynner, klon repoet:

```
git clone git@github.com:sindrebn/git-oppgave-1-angremekanismer.git
```

Hvis noe går galt: `./reset.sh` tilbakestiller repoet.

## a) Angre unstaged

1. Endre innholdet i app.txt
1. Angre endringen i arbeidskatalogen
1. Verifiser at du har «nothing to commit» (`git status`)

## b) Angre staged

1. Endre innholdet i app.txt
1. Stage endringen (`git add app.txt`)
1. Fjern endringen fra staging area
1. Verifiser at app.txt er «Changes not staged for commit» (`git status`)

## c) Angre commit
1. Endre innholdet i app.txt
1. Commit endringen (`git commit --all --message "Melding"`)
1. Angre commiten, men behold endringen i staging area
1. Verifiser at app.txt er «Changes to be commited» (`git status`)

## d) Angre reset
1. (Fjern endringen fra forrige oppgave)
1. Slett den nyeste commiten helt
1. Hent den tilbake (med f. eks. `git cherry-pick <sha>`) 
