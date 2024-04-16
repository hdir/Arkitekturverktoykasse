# Arkitekturverktoykasse

Verktøykasse for arkitekturleveranser, archimate viewpoints etc.

Koble til repositoriet gjennom Archi med Github-plugin eller se på innholdet i [pdf rapporten](https://github.com/hdir/Arkitekturverktoykasse/blob/gh-pages/Arkitekturverktoykasse.pdf), eller på den automatisk genererte [html siden](https://hdir.github.io/Arkitekturverktoykasse/).

## Modelleringsprinsipper i Archimate modeller

* "Keep it simple“
* Det viktigste er at det er forståelig.
* Bruk eksisterende viewpoints.
* Bruk færrest mulig elementtyper.
* Bruk standardfarger fra archimate
* Bruk bokser som figur for elementer.
  * Unntak for aktør ++
* Brukertest av modellene tidlig.

## Archi og coArchi Archi plugin

For å åpne modellene trenger du arkitekturverktøyet [Archi](https://www.archimatetool.com/) og coArchi plugin. Archi kan lastes ned [her](https://www.archimatetool.com/download/) og plugin lastes ned fra [Archimate tool](https://www.archimatetool.com/plugins/#coArchi). Plugin må installeres i Archi.

Nå trenger du et [Personal access token fra Github](https://github.com/settings/tokens).

På Collobaration velger du `Add remote model`, og legger inn:

* url: `https://github.com/hdir/Tillitsrammeverk.git`
* user name: ditt Github brukernavn
* password: ditt personal access token

Etter du har lastet ned til Archi, kan du nå vise arbeidsområdene fra Collaboration-menyen i Archi.

## Les mer

* [Archimate tool](https://www.archimatetool.com/)
* [Archimate model, repository and Git integration](https://github.com/markusvanaardt/readme-coArchi)
