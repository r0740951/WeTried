# 1ITF Keuzeproject 1 HGH
Dit is de basisstructuur voor **Keuzeproject 1** met **Materialize** in 1ITF van de Thomas More Hogeschool (campus Geel).

<p align="center">
    <img src="https://www.thomasmore.be/themes/wundertheme/logo.svg" alt="Thomas More Kempen" width="300" />
</p>

## Basisvereisten (eenmalig te installeren)

Volgende tool hoef je maar eenmalig te installeren:

(is normaal al in orde voor alle teamleden want in Webdesign Basis ben je hier al mee gestart)

- [**Git**](https://git-scm.com/)


## Stappenplan voor een nieuw project op basis van deze repository

Werk je met twee of meer teamleden aan hetzelfde project, dan volg je best deze werkwijze. Begin alvast met een teamleader 🎓 aan te duiden en een naam voor het project te kiezen.

### Een GitHub account aanmaken en configureren (eenmalig door alle teamleden 🎓👤👤👤)

(is normaal al in orde voor alle teamleden want in Webdesign Basis ben je hier al mee gestart)

1. Maak, met je mailadres van de school, een GitHub-account aan op https://github.com. (Als student krijg je extra features zoals private repos)
2. Upgrade van je education account via https://education.github.com/
3. Stel met volgende commando’s lokaal je identiteit in:   
`git config ‐‐global user.name "je naam"`   
`git config ‐‐global user.email "je mailadres"`   
`git config ‐‐global core.editor notepad`


### Opzetten van een lokale repo door de teamleader 🎓

**De overige teamleden 👤👤👤 doen voorlopig nog niets!**

1. Clone deze repo `git clone https://github.com/AnnHannes/Keuzeproject1_HGH.git`
2. Wis de map **.git** in de repo
3. Initialiseer een nieuwe Git-repo `git init`
4. Voeg alle bestanden (uitgezonderd deze die zijn uitgesloten via **.gitignore**) uit deze map aan de staging area toe   
`git add .`
5. Verplaats de bestanden van de staging area naar de lokale repo `git commit -m "Startbestanden"`
6. Pas de inhoud van ***README.md*** eventueel aan, je mag de algemene instructies verwijderen en bijvoorbeeld je teamnaam en teamleden op lijn 2 zetten 

### Opzetten van een remote repo door de teamleader 🎓

1. Maak een nieuwe, lege, (private) repo **projectNaam** op GitHub   
2. Verbind de lokale repo met de remote repo `git remote add <remote‐name> <remote‐url>`   
bv: `git remote add origin https://github.com/teamleader/projectNaam.git`
3. Push de lokale repo naar de remote repo `git push ‐u origin master`

### Uitnodigen van andere teamleden 👤👤👤 voor samenwerking door teamleader 🎓

1. Klik op de pagina https://github.com/teamleader/projectNaam op ***settings***
2. Klik links in het menu op ***Collaborators***
3. Nodig overige teamleden 👤👤👤 uit
4. Teamleden aanvaarden de uitnodiging via een e-mail van GitHub

### Clonen van de remote repo door andere teamleden 👤👤👤

1. Elk teamlid maakt een exacte copy van de remote repo `git clone https://github.com/teamleader/projectNaam.git`

Proficiat! De samenwerking kan beginnen.

### Stagen en committen van lokaal gewijzigde bestanden 🎓👤👤👤

Maak regelmatig back-ups zodat de ander teamleden weten waar je mee bezig bent.   
Wacht dus niet te lang met wijzigingen op GitHub te plaatsen. 

1. Controleer de status `git status`
2. Voeg alle wijzigingen aan de staging area toe `git add .`
3. Verplaats de bestanden van de staging area naar de lokale repo `git commit -m "Comment"`
4. Synchroniseer met de remote repo `git pull --rebase`
5. Push de lokale repo naar de remote repo `git push`









