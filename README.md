# 🔄 Otkin

**Otkin améliore la visibilité de Nikto.** Parce qu’un outil de pentest aussi exceptionnel mérite une sortie à la hauteur de ses trouvailles ! ✨

Nikto est le meilleur outil de pentest 🏆. Je trouvais simplement que sa lisibilité devait être au même niveau que la qualité des vulnérabilités trouvées 🔍. Voici donc **Otkin** : Nikto, avec une petite pirouette en plus 🤸 — et une confiance en soi inversement proportionnelle à la lisibilité de sa sortie.

## 🚀 Installation

Ajoutez cette fonction à votre fichier `~/.bashrc` ou `~/.zshrc` :
```
    otkin() {
      nikto "$@" | rev
    }
```
Puis rechargez votre configuration :

    source ~/.bashrc

*(Avec Zsh, utilisez plutôt `source ~/.zshrc`.)*

## 🧪 Utilisation

Lancez Otkin avec les mêmes arguments que Nikto :
```
    otkin -h digigolo.com
```
Tous les arguments transmis à `otkin` sont passés à `nikto`. Ensuite, `rev` inverse les caractères de chaque ligne. 🔃

Oui, **les caractères**. Pas les vulnérabilités. Pas le serveur. Pas le sens de la vie. 😌

## 💡 Pourquoi Otkin ?

- 🔎 **Nikto** trouve des vulnérabilités.
- 🔄 **Otkin** optimise leur affichage en le rendant strictement moins lisible.
- 🧠 Votre cerveau fait le travail de décodage. C’est donc aussi un outil de formation.
- 👀 Votre terminal n’a jamais été aussi… différent !

## ⚠️ Avertissement

Otkin est tellement puissant qu'il est à utiliser uniquement sur des systèmes pour lesquels vous avez une autorisation de test. 🛡️
