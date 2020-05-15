### alpenglow-localization

This is the community language repository for [Alpenglow](https://itunes.apple.com/app/id978589174).

If you want to see Alpenglow in another language that isn't already available and have some git-fu, feel free to submit a pull request to the repository.

If you don't know about git feel free to grab the file here and send it over via the contact option on the [website](https://alpenglowapp.com).


### Structure
Languages are structured in folders as such:

`en.lproj/Localizable.strings`

Where `en` is replaced by the [ISO 639-1 two-letter language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes), and the `Localizable.strings` file is structured as per the English (`en`) version.

Please do not include any other files in a pull request.

### Localization

Strings are denoted as `"key"` = `"value"`, where the keys remain the same across all languages, and the values are localized. There must be a `;` at the end of each line.

`"locationVC.title" = "Location";`

Where you see a `%@` or `%ld` token, this denotes a value that is replaced at runtime. The corresponding localized value must keep the token in the right place to provide the same meaning as the English value.

`"mainVC.predictions.inXHours" = "in %ld hours";`

`"mainVC.predictions.inXMinutes" = "in %ld minutes";`


### Credits

Please append the name you would like to be credited by to the pull request or the comment block at the top of the Localizable.strings file.