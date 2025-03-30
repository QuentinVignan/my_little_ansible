My Little Ansible

📄 Description

My Little Ansible est un outil d'automatisation de configuration de serveurs, inspiré d'Ansible mais plus léger et adapté aux besoins spécifiques. Il permet d'exécuter des tâches à distance via des fichiers de configuration définis par l'utilisateur.

🛠 Prérequis

Python 3

Bibliothèques requises (voir installation ci-dessous)

🛠️ Installation

Clonez le dépôt et installez les dépendances :

# Cloner le dépôt
git clone https://github.com/QuentinVignan/my_little_ansible.git
cd my_little_ansible

# Installer les dépendances
python3 -m pip install -r requirements.txt

🚀 Utilisation

Exécuter un playbook

python3 app.py --config ./configs/playbook.yaml

Ajouter un module personnalisé

Placez vos scripts dans le répertoire modules/ et référencez-les dans votre fichier de configuration.

🌟 Fonctionnalités

Exécution de tâches automatisées sur des serveurs distants

Fichiers de configuration YAML pour définir les actions

Extensibilité avec des modules personnalisés

📑 Licence

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus d'informations.

👨‍💻 Auteur

Quentin Vignan - GitHub

🛢 Contribution

Les contributions sont les bienvenues ! Merci de soumettre une issue ou une pull request pour proposer des améliorations.
