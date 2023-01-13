# Game Project

```sh
cd game
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.text 
python3 main.py
```

```sh
pip3 install matplotlib
pip3 freeze
pip3 install matplotlib==3.5.0
sudo apt install -y python3-venv
```
# entornos virtuales
-- Game
```sh
which python3
which pip3
cd game
python3 -m venv env
source env/bin/activate
deactivate
```

```sh
source env/bin/activate
pip3 install matplotlib
pip3 freeze
```

# file requirements.txt
-- Nos permite tener un listado de todas las dependencias del proyecto
```sh
cd game
pip3 freeze > requirements.text
pip3 install -r requirements.text 
```