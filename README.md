# David Pouderou

Administrateur systèmes et réseaux, orienté cybersécurité. Je construis des outils Windows pour le
terrain : un seul exécutable signé, aucune installation, et une mise à jour automatique servie depuis
ce compte.

## Outils publiés

| Outil | Ce qu'il fait | Télécharger |
|---|---|---|
| [Optimus Cleaner](https://github.com/DavidPouderou/OptimusCleaner) | Maintenance Windows 10 / 11 : désinfection, nettoyage, optimisation des disques, mise à jour des applications, réparation du système, fiche technique du matériel | [Releases](https://github.com/DavidPouderou/OptimusCleaner/releases/latest) |
| [PrintRescue](https://github.com/DavidPouderou/PrintRescue) | Dépannage d'impression Windows 10 / 11 : bilan du poste, réparation en cinq cases, journal et rapport d'intervention | [Releases](https://github.com/DavidPouderou/PrintRescue/releases/latest) |
| [AutoBitlocker](https://github.com/DavidPouderou/AutoBitlocker) | Déploiement de BitLocker en série depuis une clé USB, avec enregistrement des clés de récupération (fiche PDF, journal CSV) | [Releases](https://github.com/DavidPouderou/AutoBitlocker/releases/latest) |

Chaque exécutable est signé (Authenticode, `CN=David Pouderou`) et horodaté ; le certificat public est
publié dans chaque dépôt, avec le journal des versions. Le code source reste privé.

## Principes communs

- Windows 10 et 11 ; PowerShell 5.1, C# / .NET 10, WPF ou Win32 natif selon l'outil.
- Aucune action qui modifie un poste sans plan affiché, confirmation et sauvegarde préalable.
- Aucune télémétrie : la seule connexion sortante est la recherche de mise à jour sur GitHub.

[LinkedIn](https://www.linkedin.com/in/david-pouderou/)
