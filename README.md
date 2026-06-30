# allergyTranslations
Open-source locale files for the Allergy Flashcards app. This repository contains multilingual translations of food allergy and food preparation phrases, making it easier for developers to build safer, more accessible applications for international travelers.

## Install

```bash
npm install allergy-translations
```

## Use

Import a specific locale file:

```js
import en from "allergy-translations/locales/en.js";
import fr from "allergy-translations/locales/fr.js";
```

Or import the bundled registry from the package root:

```js
import locales, { en, fr } from "allergy-translations";

console.log(locales.en);
```
