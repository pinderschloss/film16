# film16
A partir d'un GIF, crée un gcode pour dessiner ce gif sur une table traçante selon une disposition de pellicule.

# environnement
Sur linux, la première fois:

```
git https://github.com/pinderschloss/film16.git
cd film16
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install --upgrade pip
python3 -m pip install vtracer
python3 -m pip install pil
python3 -m pip install svg-to-gcode
python3 -m pip install jupyter
jupyter-notebook
```
ouvrir le notebook gif_vers_gcode

Une fois installé, depuis le répertoire film16:
```
source .venv/bin/activate
jupyter-notebook
```
