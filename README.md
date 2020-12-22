This repository contains translations for SimpleLogin's iOS and Android apps.

Do not find your language here? Feel free to make a pull request to propose your translation of a new language.

## How to contribute
Each language has it own folder with 2 files:
- `Localizable.strings` for iOS
- `strings.xml` for Android

They both contain the same set of keys. Please respect the key order and modify only the translated texts.

Some of the texts are to be interpolated in runtime, so please pay attention to the placeholder and do not change their format (`%@` for iOS and `%1$d` for Android).

#### Add a new language
- Make sure to name the folder with this format `<iso code>-<english name>` (for example: `fr-French`, `it-Italian`...).

- Make sure to copy all the keys from English version.

## Credit
The apps will have a section in About page dedicated to contributors of this repository.

Want to be an unsung hero? Drop an email to [hi@simplelogin.io](hi@simplelogin.io) to let us know.
