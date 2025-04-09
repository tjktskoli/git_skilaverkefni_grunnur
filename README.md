# Git skilaverkefni V25

### **Athugið að verkefnið er einstaklingsverkefni, ef tveir eða fleiri skila sömu lausninni verður gefið 0 (núll) fyrir þær lausnir.**

Búðu til nýja lokaða geymslu (e. private repo), hakaðu í **Add a README file**.   
Bjóddu svo kennaranum þínum inn sem [samstarfsaðila](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository) (e. collaborator).  

Skilaðu slóðinni á geymsluna í Innu.  
Smelltu á hnappinn CODE í stjórnunarhluta möppunnar, afritaðu slóðina sem birtist undir HTTPS.  
Opnaðu git-bash á localvélinni þinni.  
Staðsettu þig í þeirri möppu sem þú vilt geyma verkefnið.  
Gefðu skipunina `git clone [afritaða slóðin fer hér]`  
Við þetta færist allt innihald reposins á github yfir í möppuna þína á localvél.


<!--
## Uppsetning
1.  Afritaðu þessa geymslu á tölvuna þína en passaðu að nota `bare` rofann:

`git clone --bare git@github.com:gestskoli/git_skilaverkefni_grunnur`

```git clone --bare https://github.com/gestskoli/git_skilaverkefni_grunnur.git```

2.  Búðu til tóma lokaða geymslu (*e. private repo*) á github svæðinu þínu. Skýrðu geymsluna **git_verkefni**.

3. Farðu inn í möppuna **git_skilaverkefni_grunnur** á tölvunni þinni og sendu (*e. push*) hana upp á github, í geymsluna sem þú bjóst til í lið 2. Passaðu að nota `mirror` rofann.

`git push --mirror git@github.com:ÞITT_NOTENDANAFN/git_verkefni`

```git push --mirror https://github.com/ÞITT_NOTENDANAFN/git_verkefni.git```

5. Farðu núna inn á geymsluna þína á github og sjáðu hvort verkefnið sé ekki komið þangað.
6. Bættu kennaranum þínum við sem samstarfsaðila (*e. collaberator*) á geymsluna. Þú finnur stillinguna fyrir það í **Settings->Manage access**.
7. Farðu núna inn á Innu og skilaðu hlekknum á geymsluna þína í verkefnið þar.
8. Í Git Bash, farðu úr möppunni **git_skilaverkefni_grunnur** með `cd ..` og keyrðu svo eftirfarandi:

`git clone git@github.com:ÞITT_NOTENDANAFN/git_verkefni`

```git clone https://github.com/ÞITT_NOTENDANAFN/git_verkefni.git```

9. Farðu svo inn í möppuna **git_verkefni** og opnaðu Visual Studio Code þar með því að slá inn `code .`.
9. Gott getur verið að vera með viðbót (*e. extension*) í Visual Studio Code sem býður upp á forskoðun á markdown kóða, t.d. *Markdown All in One*.
-->
## Verkefnið
### Fyrri hluti:
Skoðaðu þetta skjal: [formad.svg](./formad.svg), 
appelsínuguli textinn er skýringatexti og er ekki hluti af því sem á að forma. 
Notaðu nú hæfileika þína í markdown til að forma [frumtexti.md](frumtexti.md) 
þannig að það verði svipað og pdf skjalið sýnir. 
Mundu að nota `git add .` og `git commit -m 'skýring'` reglulega.
Sendu svo geymsluna á github þegar þessum hluta er lokið.
`git push`

### Seinni hluti:
Leystu verkefnið sem er hér: https://vefhonnun.github.io/verkstjorn/Verkefni.html 
(ekki þarf að gera *Branching* hlutann) og skilaðu hér í geymsluna þína. 
Mundu að gera `git add .` og `git commit -m 'skýring'` eftir hverja spurningu. 
Notaðu markdown til að setja spurningarnar og svörin snyrtilega upp eins og lista. 
Að lokum sendir þú svo geymsluna á github þegar þessum hluta er lokið.
`git push`

## Bjargir
 - [Markdown Cheatsheet (wiki)](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
 - [Writing on Github](https://help.github.com/en/github/writing-on-github)
