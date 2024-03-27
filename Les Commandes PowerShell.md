# Les commandes PowerShell

Les commandes PowerShell sont des instructions qui permettent d'effectuer des tâches spécifiques dans PowerShell. Elles sont utilisées pour automatiser des tâches, gérer des ressources, interagir avec des systèmes distants, etc. Les commandes PowerShell sont généralement des applets de commande qui prennent des paramètres et des arguments pour effectuer une action spécifique.

La liste ci-dessous contient les commandes PowerShell disponibles nativement dans PowerShell. Vous remarquerez qu'elles commencent toutes par un verbe d'action suivi d'un nom de nom commun. Cela permet de standardiser les noms des commandes et de rendre le code plus lisible.

---

## Liste des commandes PowerShell (v7.0^)

| Commandes PowerShell            | Description                                                  |
| Add-Content                     | Ajoute du contenu à un élément                               |
| Add-History                     | Ajoute des éléments à l'historique de la session             |
| Add-Member                      | Ajoute des membres à un objet                                |
| Add-Type                        | Charge une nouvelle définition de type à partir d'un fichier |
| Clear-Content                   | Efface le contenu d'un élément, mais ne le supprime pas      |
| Clear-History                   | Efface l'historique de la session                            |
| Clear-Item                      | Efface le contenu d'un élément et le supprime                |
| Clear-ItemProperty              | Efface la valeur d'une propriété d'un élément                |
| Clear-Variable                  | Efface la valeur d'une variable                              |
| Compare-Object                  | Compare deux objets et indique les différences               |
| Convert-Path                    | Convertit un chemin en un chemin de chemin d'accès absolu    |
| ConvertFrom-Csv                 | Convertit des objets CSV en objets PowerShell                |
| ConvertFrom-Json                | Convertit des objets JSON en objets PowerShell               |
| ConvertFrom-Markdown            | Convertit des objets Markdown en objets PowerShell           |
| ConvertFrom-SecureString        | Convertit une chaîne sécurisée en texte non sécurisé         |
| ConvertFrom-StringData          | Convertit une chaîne de données en objets PowerShell         |
| ConvertTo-Csv                   | Convertit des objets PowerShell en objets CSV                |
| ConvertTo-Html                  | Convertit des objets PowerShell en objets HTML               |
| ConvertTo-Json                  | Convertit des objets PowerShell en objets JSON               |
| ConvertTo-SecureString          | Convertit du texte non sécurisé en chaîne sécurisée          |
| ConvertTo-Xml                   | Convertit des objets PowerShell en objets XML                |
| Copy-Item                       | Copie un élément                                             |
| Copy-ItemProperty               | Copie une propriété d'un élément vers un autre élément       |
| Debug-Job                       | Démarre le débogage d'un travail en arrière-plan             |
| Debug-Process                   | Démarre le débogage d'un processus                           |
| Debug-Runspace                  | Démarre le débogage d'un espace d'exécution                  |
| Disable-ExperimentalFeature     | Désactive une fonctionnalité expérimentale                   |
| Disable-PSBreakpoint            | Désactive un point d'arrêt                                   |
| Disable-RunspaceDebug           | Désactive le débogage de l'espace d'exécution                |
| Enable-ExperimentalFeature      | Active une fonctionnalité expérimentale                      |
| Enable-PSBreakpoint             | Active un point d'arrêt                                      |
| Enable-RunspaceDebug            | Active le débogage de l'espace d'exécution                   |
| Enter-PSHostProcess             | Ouvre une session PowerShell dans un processus hôte          |
| Enter-PSSession                 | Ouvre une session PowerShell sur un ordinateur distant       |
| Exit-PSHostProcess              | Quitte une session PowerShell dans un processus hôte         |
| Exit-PSSession                  | Quitte une session PowerShell sur un ordinateur distant      |
| Export-Alias                    | Exporte des alias                                            |
| Export-Clixml                   | Exporte des objets au format XML                             |
| Export-Csv                      | Exporte des objets au format CSV                             |
| Export-FormatData               | Exporte des données de format                                |
| Export-ModuleMember             | Exporte des membres de module                                |
| Export-PSSession                | Exporte des sessions PowerShell                              |
| Find-Package                    | Recherche des packages                                       |
| Find-PackageProvider            | Recherche des fournisseurs de packages                       |
| Find-PSResource                 | Recherche des ressources PowerShell                          |
| ForEach-Object                  | Invoque une commande pour chaque élément                     |
| Format-Custom                   | Formate la sortie en utilisant un fichier de mise en forme   |
| Format-Hex                      | Formate les données en hexadécimal                           |
| Format-List                     | Formate la sortie en une liste                               |
| Format-Table                    | Formate la sortie en une table                               |
| Format-Wide                     | Formate la sortie en largeur                                 |
| Get-Alias                       | Récupère des alias                                           |
| Get-ChildItem                   | Récupère des éléments enfants                                |
| Get-Clipboard                   | Récupère le contenu du presse-papiers                        |
| Get-CmsMessage                  | Récupère des messages CMS                                    |
| Get-Command                     | Récupère des commandes                                       |
| Get-Content                     | Récupère le contenu d'un élément                             |
| Get-Credential                  | Récupère des informations d'identification                   |
| Get-Culture                     | Récupère la culture actuelle                                 |
| Get-Date                        | Récupère la date actuelle                                    |
| Get-Error                       | Récupère des erreurs                                         |
| Get-Event                       | Récupère des événements                                      |
| Get-EventSubscriber             | Récupère des abonnés d'événements                            |
| Get-ExecutionPolicy             | Récupère la stratégie d'exécution                            |
| Get-ExperimentalFeature         | Récupère des fonctionnalités expérimentales                  |
| Get-FileHash                    | Récupère le hachage d'un fichier                             |
| Get-FormatData                  | Récupère des données de format                               |
| Get-Help                        | Récupère de l'aide                                           |
| Get-History                     | Récupère l'historique de la session                          |
| Get-Host                        | Récupère l'hôte actuel                                       |
| Get-InstalledPSResource         | Récupère des ressources PowerShell installées                |
| Get-Item                        | Récupère un élément                                          |
| Get-ItemProperty                | Récupère des propriétés d'un élément                         |
| Get-ItemPropertyValue           | Récupère la valeur d'une propriété d'un élément              |
| Get-Job                         | Récupère des travaux en arrière-plan                         |
| Get-Location                    | Récupère le répertoire actuel                                |
| Get-MarkdownOption              | Récupère les options Markdown                                |
| Get-Member                      | Récupère des membres d'un objet                              |
| Get-Module                      | Récupère des modules                                         |
| Get-Package                     | Récupère des packages                                        |
| Get-PackageProvider             | Récupère des fournisseurs de packages                        |
| Get-PackageSource               | Récupère des sources de packages                             |
| Get-PfxCertificate              | Récupère des certificats PFX                                 |
| Get-Process                     | Récupère des processus                                       |
| Get-PSBreakpoint                | Récupère des points d'arrêt                                  |
| Get-PSCallStack                 | Récupère la pile d'appels                                    |
| Get-PSDrive                     | Récupère des lecteurs                                        |
| Get-PSHostProcessInfo           | Récupère des informations sur les processus hôtes            |
| Get-PSProvider                  | Récupère des fournisseurs                                    |
| Get-PSReadLineKeyHandler        | Récupère des gestionnaires de touches PSReadLine             |
| Get-PSReadLineOption            | Récupère les options PSReadLine                              |
| Get-PSResourceRepository        | Récupère des dépôts de ressources PowerShell                 |
| Get-PSScriptFileInfo            | Récupère des informations de script                          |
| Get-PSSession                   | Récupère des sessions                                        |
| Get-Random                      | Récupère des nombres aléatoires                              |
| Get-Runspace                    | Récupère des espaces d'exécution                             |
| Get-RunspaceDebug               | Récupère des informations de débogage de l'espace d'exécution|
| Get-SecureRandom                | Récupère des nombres aléatoires sécurisés                    |
| Get-TimeZone                    | Récupère le fuseau horaire actuel                            |
| Get-TraceSource                 | Récupère des sources de trace                                |
| Get-TypeData                    | Récupère des données de type                                 |
| Get-UICulture                   | Récupère la culture de l'interface utilisateur               |
| Get-Unique                      | Récupère des éléments uniques                                |
| Get-Uptime                      | Récupère le temps de fonctionnement                          |
| Get-Variable                    | Récupère des variables                                       |
| Get-Verb                        | Récupère des verbes de commande                              |
| Group-Object                    | Groupe les objets par propriété                              |
| Import-Alias                    | Importe des alias                                            |
| Import-Clixml                   | Importe des objets à partir d'un fichier XML                 |
| Import-Csv                      | Importe des objets à partir d'un fichier CSV                 |
| Import-LocalizedData            | Importe des données localisées                               |
| Import-Module                   | Importe des modules                                          |
| Import-PackageProvider          | Importe des fournisseurs de packages                         |
| Import-PowerShellDataFile       | Importe des données PowerShell                               |
| Import-PSSession                | Importe des sessions                                         |
| Install-Package                 | Installe des packages                                        |
| Install-PackageProvider         | Installe des fournisseurs de packages                        |
| Install-PSResource              | Installe des ressources PowerShell                           |
| Invoke-Command                  | Invoque des commandes sur des ordinateurs distants           |
| Invoke-Expression               | Invoque des expressions                                      |
| Invoke-History                  | Invoque des commandes de l'historique                        |
| Invoke-Item                     | Invoque des éléments                                         |
| Invoke-RestMethod               | Invoque une méthode HTTP REST                                |
| Invoke-WebRequest               | Invoque une requête Web                                      |
| Join-Path                       | Joint des éléments de chemin                                 |
| Join-String                     | Joint des chaînes de caractères                              |
| Measure-Command                 | Mesure le temps d'exécution d'une commande                   |
| Measure-Object                  | Mesure des objets                                            |
| Move-Item                       | Déplace un élément                                           |
| Move-ItemProperty               | Déplace une propriété d'un élément vers un autre élément    |
| New-Alias                       | Crée un alias                                                |
| New-Event                       | Crée un événement                                            |
| New-Guid                        | Crée un GUID                                                 |
| New-Item                        | Crée un élément                                              |
| New-ItemProperty                | Crée une propriété d'un élément                              |
| New-Module                      | Crée un module                                               |
| New-ModuleManifest              | Crée un manifeste de module                                  |
| New-Object                      | Crée un objet                                                |
| New-PSDrive                     | Crée un lecteur                                              |
| New-PSRoleCapabilityFile        | Crée un fichier de capacité de rôle                          |
| New-PSScriptFileInfo            | Crée un fichier d'informations de script                     |
| New-PSSession                   | Crée une session                                             |
| New-PSSessionConfigurationFile  | Crée un fichier de configuration de session                  |
| New-PSSessionOption             | Crée une option de session                                   |
| New-PSTransportOption           | Crée une option de transport                                 |
| New-TemporaryFile               | Crée un fichier temporaire                                   |
| New-TimeSpan                    | Crée un intervalle de temps                                  |
| New-Variable                    | Crée une variable                                            |
| Out-Default                     | Envoie la sortie par défaut                                  |
| Out-File                        | Envoie la sortie vers un fichier                             |
| Out-Host                        | Envoie la sortie vers l'hôte                                 |
| Out-Null                        | Envoie la sortie vers $null                                  |
| Out-String                      | Envoie la sortie sous forme de chaîne de caractères          |
| Pop-Location                    | Supprime le répertoire actuel de la pile                     |
| Protect-CmsMessage              | Protège un message CMS                                       |
| Publish-PSResource              | Publie des ressources PowerShell                             |
| Push-Location                   | Ajoute le répertoire actuel à la pile                        |
| Read-Host                       | Lit une ligne de texte                                       |
| Receive-Job                     | Reçoit des travaux en arrière-plan                           |
| Register-ArgumentCompleter      | Enregistre un compléteur d'arguments                         |
| Register-EngineEvent            | Enregistre un gestionnaire d'événements pour le moteur PowerShell |
| Register-ObjectEvent            | Enregistre un gestionnaire d'événements pour un objet spécifique |
| Register-PackageSource          | Enregistre une source de packages pour PackageManagement     |
| Register-PSResourceRepository   | Enregistre un dépôt pour les ressources PowerShell           |
| Remove-Alias                    | Supprime un alias                                            |
| Remove-Event                    | Supprime un gestionnaire d'événements                        |
| Remove-Item                     | Supprime les éléments spécifiés                              |
| Remove-ItemProperty             | Supprime une propriété d'un élément                          |
| Remove-Job                      | Supprime un travail en arrière-plan                          |
| Remove-Module                   | Supprime un module de la session actuelle                    |
| Remove-PSBreakpoint             | Supprime les points d'arrêt actifs                            |
| Remove-PSDrive                  | Supprime un lecteur PowerShell                               |
| Remove-PSReadLineKeyHandler     | Supprime un gestionnaire d'événements de touches de lecture PSReadLine |
| Remove-PSSession                | Supprime une session PowerShell                              |
| Remove-TypeData                 | Supprime les types de données personnalisés                   |
| Remove-Variable                 | Supprime les variables spécifiées                             |
| Rename-Item                     | Renomme les éléments spécifiés                               |
| Rename-ItemProperty             | Renomme une propriété d'un élément                           |
| Resolve-Path                    | Résout les éléments spécifiés en emplacements absolus        |
| Restart-Computer                | Redémarre les ordinateurs distants ou locaux                 |
| Save-Help                       | Enregistre les fichiers d'aide de commande                   |
| Save-Package                    | Enregistre des packages sur l'ordinateur local                |
| Save-PSResource                 | Enregistre les ressources dans un package PowerShell          |
| Select-Object                   | Sélectionne les objets d'une collection en fonction de leurs propriétés |
| Select-String                   | Sélectionne les chaînes dans les objets et les fichiers à partir de motifs |
| Select-Xml                      | Sélectionne du contenu XML à partir de l'entrée               |
| Send-MailMessage                | Envoie un message électronique                               |
| Set-Alias                       | Crée ou modifie un alias                                    |
| Set-Clipboard                   | Place les données sur le Presse-papiers                      |
| Set-Content                     | Modifie le contenu d'un élément                              |
| Set-Date                        | Modifie la date du système                                   |
| Set-ExecutionPolicy             | Modifie la stratégie d'exécution actuelle                    |
| Set-Item                        | Modifie les propriétés d'un élément                          |
| Set-ItemProperty                | Modifie une propriété d'un élément                           |
| Set-Location                    | Définit l'emplacement actuel                                  |
| Set-MarkdownOption              | Définit les options pour la génération Markdown               |
| Set-PackageSource               | Modifie les informations sur une source de package            |
| Set-PSBreakpoint                | Définit les points d'arrêt dans le code                       |
| Set-PSDebug                     | Active ou désactive le débogage de scripts                   |
| Set-PSReadLineKeyHandler        | Associe une action à une touche dans PSReadLine              |
| Set-PSReadLineOption            | Définit les options pour PSReadLine                          |
| Set-PSResourceRepository        | Modifie un dépôt pour les ressources PowerShell              |
| Set-StrictMode                  | Définit le mode strict pour les erreurs                       |
| Set-TraceSource                 | Modifie la configuration d'une source de trace                |
| Set-Variable                    | Définit la valeur d'une variable                              |
| Show-Markdown                   | Affiche du texte en Markdown dans une fenêtre de navigateur   |
| Sort-Object                     | Trie les objets en fonction de leurs propriétés               |
| Split-Path                      | Divise les éléments d'un chemin d'accès en éléments individuels |
| Start-Job                       | Démarre un travail en arrière-plan                            |
| Start-Process                   | Démarre un processus et attend sa fin                         |
| Start-Sleep                     | Suspend l'exécution d'un script pendant un laps de temps spécifié |
| Start-ThreadJob                 | Démarre un travail dans un thread                             |
| Start-Transcript                | Commence à enregistrer les appels de fonction et les opérations de l'interface utilisateur |
| Stop-Computer                   | Arrête les ordinateurs distants ou locaux                     |
| Stop-Job                        | Arrête les travaux en arrière-plan                            |
| Stop-Process                    | Arrête les processus qui correspondent aux conditions spécifiées |
| Stop-Transcript                 | Arrête l'enregistrement de la transcription                  |
| Switch-Process                  | Change les propriétés des processus en cours d'exécution      |
| Tee-Object                      | Envoie les objets d'une chaîne de pipeline à deux destinations |
| Test-Connection                 | Teste la connexion réseau vers un ordinateur ou un service    |
| Test-Json                       | Teste si une chaîne est au format JSON                        |
| Test-ModuleManifest             | Teste la validité du manifeste d'un module                   |
| Test-Path                       | Vérifie l'existence des chemins spécifiés                    |
| Test-PSScriptFileInfo           | Teste le fichier de script PowerShell pour des problèmes de codage |
| Trace-Command                   | Surveille l'exécution des commandes                           |
| Unblock-File                    | Débloque les fichiers téléchargés depuis Internet            |
| Uninstall-Package               | Désinstalle des packages                                      |
| Uninstall-PSResource            | Désinstalle des ressources dans un package PowerShell         |
| Unprotect-CmsMessage            | Déchiffre un message CMS                                      |
| Unregister-Event                | Supprime les gestionnaires d'événements                       |
| Unregister-PackageSource        | Supprime une source de package                                |
| Unregister-PSResourceRepository | Supprime un dépôt pour les ressources PowerShell              |
| Update-FormatData               | Met à jour les fichiers de données de format                 |
| Update-Help                     | Télécharge et installe les fichiers d'aide de commande à jour |
| Update-List                     | Met à jour la vue actuelle                                    |
| Update-PSModuleManifest         | Met à jour le manifeste d'un module                           |
| Update-PSResource               | Met à jour les ressources dans un package PowerShell          |
| Update-PSScriptFileInfo         | Met à jour les informations du fichier de script PowerShell   |
| Update-TypeData                 | Met à jour les types de données personnalisés                  |
| Wait-Debugger                   | Attend qu'un débogueur se connecte                             |
| Wait-Event                      | Attend qu'un événement se produise                             |
| Wait-Job                        | Attend la fin d'un travail en arrière-plan                     |
| Wait-Process                    | Attend que les processus spécifiés se terminent                |
| Where-Object                    | Sélectionne les objets en fonction des critères spécifiés      |
| Write-Debug                     | Écrit des informations de débogage dans le flux de sortie      |
| Write-Error                     | Écrit un objet d'erreur dans le flux d'erreur                  |
| Write-Host                      | Affiche les objets dans la fenêtre de la console               |
| Write-Information               | Écrit des informations dans le flux d'information               |
| Write-Output                    | Écrit les objets dans le flux de sortie                        |
| Write-Progress                  | Affiche une barre de progression dans la fenêtre de la console  |
| Write-Verbose                   | Écrit des messages détaillés dans le flux de sortie            |
| Write-Warning                   | Écrit un avertissement dans le flux de sortie                  |
