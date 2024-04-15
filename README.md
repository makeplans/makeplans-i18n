# Localisation files for MakePlans

Here you will find the localisation files for [MakePlans](https://makeplans.com).

If you want to have the booking site in MakePlans you have three options:

1) Contribute to our localisation files by reading the rest of this document.

2) [Contact us](https://makeplans.com/en/contact/) for an automatic translation to your language (Using Google Translate so it will not be perfect).

3) [Contact us](https://makeplans.com/en/contact/) for a paid professional translation to your language.

## Contribute

Pull requests are much welcome :) You can modify existing locales or add a new one. Please contact us if you have any questions.

Please be aware that date and time sections should not be updated as they are currently used in some code specific situations (datepicker etc) so we have to adjust it manually. But please let us know what changes you want and we can have a look.

## Directory structure

* **Root**: Generic object and actions.
* **Delivery**: Email and SMS for the booking site.
* **Deliver/manage**: Email and SMS for the admin system.
* **Views and Views/manage**: For the admin system.
* **Views/themes**: For the booking site divided by each theme.

If you want to use English in the admin system but would like to use your local language only on the booking site then you need to translate the files for your chosen booking site theme (for example `/views/themes/amsterdam/`), the email/SMS texts under `/delivery/` (not `/delivery/manage/`), and parts of the root file.

## Supported locales

### Fully supported

* Danish (da)
* English International (en)
* English American (en-US)
* Spanish (es)
* French (fr)
* Hebrew (hr)
* Lithuanian (lt)
* Latvian (lv)
* Malay - Bahasa (ms)
* Norwegian (nb)
* Russian (ru)
* Swedish (se)

### Only public booking site

* Chezh (cz)
* Dutch (nl)
* Italian (it)
* Polish (pl)
* Slovenian (sl)

# Missing translations

If there are any missing translations the translation for English International will be used. Except for Danish and Swedish where Norwegian will be used.

English American is the same as English International except for date/time formatting.
