# Git skilaverkefni

## Uppsetning
1.  Afritaðu þessa geymslu á tölvuna þína en passaðu að nota `bare` rofann:

```git clone --bare https://github.com/gestskoli/git_skilaverkefni_grunnur.git```
  
2.  Búðu til tóma lokaða geymslu (*e. private repo*) á github svæðinu þínu. Skýrðu geymsluna **git_verkefni**.

3. Farðu inn í möppuna **git_skilaverkefni_grunnur** á tölvunni þinni og sendu (*e. push*) hana upp á github, í geymsluna sem þú bjóst til í lið 2. Passaðu að nota `mirror` rofann.

```git push --mirror https://github.com/ÞITT_NOTENDANAFN/git_verkefni.git```

5. Farðu núna inn á geymsluna þína á github og sjáðu hvort verkefnið sé ekki komið þangað.
6. Bættu kennaranum þínum við sem samstarfsaðila (*e. collaberator*) á geymsluna. Þú finnur stillinguna fyrir það í **Settings->Collaberators**.
7. Farðu núna inn á Innu og skilaðu hlekknum á geymsluna þína í verkefnið þar.
8. Í Git Bash, farðu úr möppunni **git_skilaverkefni_grunnur** með `cd ..` og keyrðu svo eftirfarandi:

```git clone https://github.com/ÞITT_NOTENDANAFN/git_verkefni.git```

9. Farðu svo inn í möppuna **git_verkefni** og opnaðu Visual Studio Code þar með því að slá inn `code .`.
9. Gott getur verið að vera með viðbót (*e. extension*) í Visual Studio Code sem býður upp á forskoðun á markdown kóða, t.d. *Markdown All in One*.

## Verkefnið
Notaðu Visual Studio Code og Git Bash til að leysa verkefnið.
### Fyrri hluti
Skoðaðu þetta skjal: [markdown_verkefni.pdf](markdown_verkefni.pdf). Notaðu nú hæfileika þína í markdown til að forma [markdown_oformad.md](markdown_oformad.md) þannig að það verði svipað og pdf skjalið sýnir. Mundu að gera `commit` reglulega og senda svo geymsluna á github þegar þessum hluta er lokið.

### Seinni hluti
Leystu þetta verkefni: https://vefhonnun.github.io/verkstjorn/Verkefni.html og skilaðu hér í geymsluna þína. Mundu að gera `commit` eftir hverja spurningu. Notaðu markdown til að setja spurningar og svör snyrtilega upp. Að lokum sendir þú svo geymsluna á github.

## Bjargir
 - [Markdown Syntax (pdf)](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
 - [Markdown Cheatsheet (wiki)](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
 - [Writing on Github](https://help.github.com/en/github/writing-on-github)
