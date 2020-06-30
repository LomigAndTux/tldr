# 7za

> Un archiveur de fichiers avec un haut taux de compression.
> Une version autonome de 7z avec un support moindre de types d'archives.
> Plus d'informations : <https://www.7-zip.org/>.

- Archiver un fichier ou un répertoire :

`7za a {{archive.7z}} {{chemin/vers/fichier_ou_dossier}}`

- Extraire une archive 7z avec la structure de dossier originelle :

`7za x {{archive}}`

- Archiver en spécifiant le format d'archive désiré :

`7za a -t{{zip|gzip|bzip2|tar}} {{archive}} {{chemin/vers/fichier_ou_dossier}}`

- Lister les formats d'archive disponibles :

`7za i`

- Lister le contenu d'une archive :

`7za l {{archive}}`
