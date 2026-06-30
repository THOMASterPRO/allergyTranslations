# allergyTranslations
Open-source locale files for the Allergy Flashcards app. This repository contains multilingual translations of food allergy and food preparation phrases, making it easier for developers to build safer, more accessible applications for international travelers.

This npm packages came as a result of a project i worked on for a school project. I made an app that translates and generates allergy cards for travelers in (currently) all european languages. This way they can avoid the repetitive task of typing the same message in any translation tool and feel more secure in the way they communicate their dietary needs to restaurant staff. Most of the current locales are translated using AI, so they might not be perfect.

If you are a native speaker of any of the currently available languages, and you notice any mistakes or faults in the way things are currently translated of the way sentences are built. Please make suggestions for possible improvements on any of the languages to the github repository of this npm package.

https://github.com/THOMASterPRO/allergyTranslations

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
