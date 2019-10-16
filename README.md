Pour lancer le playbook:

ansible-playbook system.yml -i hosts
                 mysql.yml
                 apache.yml

Pour installer un rôle (par exemple mysql de geerlingguy)

ansible-galaxy install -r requirements.yml


