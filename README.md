# Menno's dotfiles

Deze README zal nog aangevuld worden

## Profile

### Modify prompt

Ik heb hiervoor de code gebruikt die (standaard) gegeven is, maar deze een beetje aangepast zodat dit er beter uitziet in de terminal. Ook heb ik een ander icoon gebruikt.

`PS1="🦊  \$(basename \$(pwd)) "`

### Welcome message

Een simpel welkom bericht toegevoegd.

`echo Het is weer tijd om te hacken, Menno!`

### Cowsay with random quote

Ik heb cowsay en fortune geïnstalleerd en via onderstaande code krijg ik bij elke nieuwe terminal die geopend wordt een koe met daarin een quote die elke keer anders is.

`fortune | cowsay`

### Aliases

_informatie volgt nog_

## Hushlogin

Ik heb een .hushlogin aangemaakt met onderstaande code om zo van de "Last login" melding af te komen.

`touch .hushlogin`
