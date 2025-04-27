# Création d'une UO, d'un Groupe d'Utilisateurs, et d'un Utilisateur dans Active Directory

## 1. Créer une Unité d'Organisation : Wilders_students
1. Ouvrir **Active Directory Users and Computers**.
2. Clic droit sur le domaine **wilders.lan**, puis sélectionner **New** > **Organizational Unit**.
3. Nommer l'OU : **Wilders_students**.
4. Cocher **Protect container from accidental deletion** pour éviter les suppressions accidentelles.
5. Cliquer sur **OK** pour créer.

## 2. Créer un Groupe d'Utilisateurs : Students
1. Dans **Active Directory Users and Computers**, aller dans **Wilders_students**.
2. Clic droit sur **Wilders_students**, puis sélectionner **New** > **Group**.
3. Nommer le groupe : **Students**.
4. Choisir le **Group scope** : **Global** et **Group type** : **Security**.
5. Cliquer sur **OK** pour créer le groupe.

## 3. Créer un utilisateur : Test Toto
1. Clique droit sur **Wilders_students > New > User**
2. First name : **Test**, Full name : **Toto**. Le reste des champs se remplit automatiquement
3. Next

## 4. Ajouter Test Toto au groupe Students :
5. Clique droit sur le nouvel utilisateur "Test Toto" > **Add to group**
6. Dans le champ libre **"Enter the object names to select" > Students > Check Names > Selectionner Students > Ok**

