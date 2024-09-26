# Presentation
Romanian translation for Mautic 4. The translation on Transifex has some known errors that Mautic 4 cannot handle.

# Installation
1. Copy the folder `ro_RO` into `"${MAUTIC_FOLDER}translations"`
1. Ensure the permissions are still correct for `www-data` user
    1. Run: `chown -R www-data:www-data "${MAUTIC_FOLDER}"`
    1. Run: `chmod -R 755 "${MAUTIC_FOLDER}"`
1. Update cache with (run using `www-data` user): `sudo -u www-data /usr/bin/php ${MAUTIC_FOLDER}bin/console cache:clear --no-interaction`
1. If you cleared the cache using `root` user, then assign the permissions again.

# Official translation
Actually the Romanian translation is downloaded with this command:
```sh
wget 'https://updates.mautic.org/index.php?option=com_mauticdownload&task=downloadLanguagePackage&langCode=ro_RO' -O ro_RO.zip
```

Then you unzip it into the `"${MAUTIC_FOLDER}translations"` folder and follow the steps above, to assign the right permissions and clear the cache.

You also can improve official Romanian Translation for Mautic on Transifex here: https://app.transifex.com/mautic/mautic/translate/ (you should create an account for yourself).

If my work has been useful to you, do not hesitate to offer me a strawberry milk 😃

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/ionutojica)

