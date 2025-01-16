# flask_app
 Création d'une application web et gestion

# Installation
1. Clonez le dépôt :
   ```bash
   git clone https://github.com/Eddy-DIT/flask_app
   cd flask_app

# Application web

   from flask import Flask

app = Flask(__name__)

@app.route('/')
def home():
    return "Bienvenue sur la page d'accueil !"

@app.route('/contact')
def contact():
    return "Page de contact"

if __name__ == '__main__':
    app.run(debug=True)

# Installation des dépendances 
# Add application
# Run application

!(image.png)
