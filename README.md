This repository contains 2 things - how to add autocomplete and a wiki entry to CIDE through an external mod, and contains the default wiki pages that are shipped with CIDE.

For the external autocomplete, all you have to do is add a json file in data/yourmodid/cide/wiki in the resource folder. File name is what will be getting autocompleted. In the example, pcinfo.json - pcinfo will be shown as autocomplete, you can add aliases, functions of your autocomplete, and so on in there. To create a wiki entry create a .md with the same name as .json file, what kind of identation is supported is shown in the .md file.

Everything visible in this repo is licensed MIT.
