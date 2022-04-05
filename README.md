######
Date : 2021-11-22
Projet : BlablaTech
webApp de messagerie instantanée avec un serveur Flask et un frontend React.  
#####
design sur figma:
  - version Desktop: https://www.figma.com/file/7Tl1rRwfgMktB5efdxlMjE/BlaBlaApp?node-id=0%3A1
  - version Mobile:  https://www.figma.com/file/7Tl1rRwfgMktB5efdxlMjE/BlaBlaApp
Dossier Git-lab :
git clone https://gitlab.matrice.io/blablapp-react-426/jtchibb-blablapp-react

#####
Commandes à lancer à la première installation

cd jtchibb-blablapp-react
cd Back

##### Environnement Virtuel
>>> Dans le répertoire : jtchibb-blablapp-react/Back (Back sur flask)

# Installation de virtualenv :
pip install virtualenv (windows)
pip3 install virtualenv (linux)
# Création de l'environnement virtuel env :
virtualenv -p python3 virt-env
# Activation de virt-env :
source virt-env/bin/activate
résultat ==> (virt-env) jtchibb-blablapp-react

# désactivation de virt-env :
deactivate
résultat ==> jtchibb-blablapp-react

###### Prérequis à installer avant la première utilisation :

## Dans le répertoire : jtchibb-blablapp-react/Back

pip3 install -r requirements.txt

>>> Lancer le Back

python3 init_db.py (ou lancer directement le "Run")
python3 main.py (ou lancer directement le "Run")

###### Installer Socket io dans le back
## Dans le répertoire : jtchibb-blablapp-react/Back

pip install flask-socketio
pip install simple-websocket

## Dans le répertoire : jtchibb-blablapp-react/Front (ReactApp)

>>> Installer Socket io dans le Front

npm i socket.io-client@2.3.1
npm i socket.io express cors colors

>>> Lancer la react app 

npm install
npm start 
