Création d'une UO, d'un Groupe d'Utilisateurs, et d'un Utilisateur dans Active Directory
1. Créer une Unité d'Organisation : Wilders_students
Ouvrir Active Directory Users and Computers.
Clic droit sur le domaine wilders.lan, puis sélectionner New > Organizational Unit.
Nommer l'OU : Wilders_students.
Cocher Protect container from accidental deletion pour éviter les suppressions accidentelles.
Cliquer sur OK pour créer.
2. Créer un Groupe d'Utilisateurs : Students
Dans Active Directory Users and Computers, aller dans Wilders_students.
Clic droit sur Wilders_students, puis sélectionner New > Group.
Nommer le groupe : Students.
Choisir le Group scope : Global et Group type : Security.
Cliquer sur OK pour créer le groupe.
3. Créer un utilisateur : Test Toto
Clique droit sur Wilders_students > New > User
First name : Test, Full name : Toto. Le reste des champs se remplit automatiquement
Next
4. Ajouter Test Toto au groupe Students :
Clique droit sur le nouvel utilisateur "Test Toto" > Add to group
Dans le champ libre "Enter the object names to select" > Students > Check Names > Selectionner Students > Ok
