## Mode d'emploi

  * avoir sa propre clé publique sous le nom de cle_publique (cp ~/.ssh/cle.pub /cle_publique)
  * puis vagrant up 
  * ansible-playbook play.yml -i inventory

### TP 1 :

 * Basculer le restart d'apache2 et nginx dans un handler
 * Ajouter php à apache dans le role apache et insérer une page de test phpinfo() par défaut.
 * Ajouter des regles iptables sur le nginx et apache pour n'accepter qu'une liste de ports définie

## question bonus :

 * indication sur utilisation du module import_tasks pour le role fusion. Ansible va applique la condition à toutes les tâches du fichier importé