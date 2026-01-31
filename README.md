# 🌱 Plantehagen - Plant Growing Game

Et morsomt nettbasert spill hvor du dyrker og selger planter for å tjene penger og erfaring!

## 🎮 Hvordan spille

1. Kjøp planter fra butikken med startpengene dine
2. Vent til plantene vokser gjennom 3 stadier
3. Selg fullvokste planter for profitt og erfaring
4. Level opp for å låse opp dyrere og mer lukrative planter
5. Bygg din plantehage med opptil 16 planter samtidig!

## 🌸 Planter

Spillet inneholder 12 forskjellige plantetyper:
- 🌵 Kaktus (Level 1)
- 🌻 Solsikke (Level 1)
- 🌹 Rose (Level 2)
- 🌷 Tulipan (Level 3)
- 🌺 Orkidé (Level 4)
- 🪷 Lotus (Level 5)
- 🌺 Hibiscus (Level 6)
- 🌸 Kirsebærtre (Level 8)
- 🎋 Bonsai (Level 10)
- 🌸 Sakura (Level 13)
- 🌴 Palme (Level 16)
- 🌼 Gullblomst (Level 20)

## 🚀 Deploy til GitHub Pages

### Steg 1: Opprett GitHub Repository
1. Gå til [GitHub](https://github.com) og logg inn
2. Klikk på "New repository" (grønn knapp øverst til høyre)
3. Gi repository et navn, f.eks. `plantehagen`
4. Velg "Public"
5. Klikk "Create repository"

### Steg 2: Last opp filene
Det er to måter å gjøre dette på:

#### Metode A: Via GitHub webside (enklest)
1. I din nye repository, klikk "uploading an existing file"
2. Dra `index.html` filen inn i boksen
3. Skriv en commit melding, f.eks. "Initial commit"
4. Klikk "Commit changes"

#### Metode B: Via Git kommandolinje
```bash
git init
git add index.html
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/DITT-BRUKERNAVN/plantehagen.git
git push -u origin main
```

### Steg 3: Aktiver GitHub Pages
1. I repository, gå til "Settings"
2. Klikk på "Pages" i venstremenyen
3. Under "Source", velg "main" branch
4. Klikk "Save"
5. Vent 1-2 minutter, refresh siden
6. Du vil se en melding: "Your site is live at https://DITT-BRUKERNAVN.github.io/plantehagen/"

### Steg 4: Besøk spillet ditt!
Gå til URL-en som vises (https://DITT-BRUKERNAVN.github.io/plantehagen/)

## 🔧 Teknologi

- React 18
- Tailwind CSS
- Lucide Icons
- Vanilla JavaScript

## 📝 Lisens

Dette er et hobbyprosjekt laget for moro skyld. Føl deg fri til å bruke og modifisere koden!

## 🎨 Features

- ✅ 12 forskjellige plantetyper
- ✅ Level og XP-system
- ✅ Progressiv låsing av planter
- ✅ 4x4 hage med 16 plasser
- ✅ Animasjoner og overganger
- ✅ Responsivt design for mobil og desktop
- ✅ Norsk språk

Lykke til med plantedyrkingen! 🌿
