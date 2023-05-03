* ### HTML tag extensions not available in DJango project

* files -> preferences -> extensons -> file config search on search bar -> edit json settings -> in settings.json file: add below code
---
"html.suggest.html5": true, <br>
"emmet.includeLanguages": {"django-html": "html"},

* ### to exit from virtual environment

deactivate

---

* ### if virtual environment scripts is not running for activation in windows
open windows powershell -> execute the command below:

---
Set-ExecutionPolicy Unrestricted -Force
