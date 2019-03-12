Ybaud profil root-me :


HTML - boutons désactivés :

J'ai procédé en modifiant les lignes suivantes du code source, en remplaçant disabled par enable :

<input disabled type="text" name="auth-login" value="" />
<input disabled type="submit" value="Member access" name="authbutton" />


Javascript - Authentification :

J'ai procédé en affichant la source, puis login.js ou est écrit en clair le login et le mot de passe pour s'authentifier à la page. (if (pseudo=="4dm1n" && password=="sh.org")


Javascript - Source :

Même procédé, le mot de passe est inscrit en clair dans le code source de la page à la variable "pass". (if ( pass == "123456azerty")


Javascript - Authentification 2 :

En affichant la source puis login.js, on remarque que le login et le mot de passe sont le résultat d'une variable elle même utilisée par une autre variable, etc...

            var TheLists = ["GOD:HIDDEN"];
            var TheSplit = TheLists[i].split(":");
            var TheUsername = TheSplit[0];
            var ThePassword = TheSplit[1];
            if (username == TheUsername && password == ThePassword)
            
 Donc l'Username = la variable TheUsername = Thesplit 0 qui est la première valeur de Thelists "GOD", même chose pour le mot de passe avec la seconde valeur "HIDDEN".

