# ECF2

Dans l'application il y aura une partie utilisateur, ils pourront modifier le nombre d'invité ou en supprimé mais cela sera en attente de validation par un admin (employés de la société). Car l'utilisateur ne peut pas se permettre d'annuler une réservation comme ça, cela doit être contrôlé. Les utilisateurs lambda peuvent consulté les événements auquel ils participent. Pour la création ils passeront par un formulaire, qui sera on non validé par la société. 

Commencez par ouvrir visual studio 2022.
	Ensuite ouvir le dossier si vous en avez crée un au préalable. 
	Attention à être dans le bon dossier au point de départ.
	Dans le terminal powershell de visual studio tapez: 
		dotnet new mvc -n ECF2-Deyborah
	ECF2-Deyborah étant mon nom de projet à vous de choisir le vôtre.
	Il faut se mettre dans son dossier un fois cela fait:
		cd ECF2-Deyborah
	Puis il faut lancer le projet:
		dotnet run
	Installer les packages nécessaire:
		dotnet add package Microsoft.EntityFrameworkCore.SqlServer
		dotnet add package Microsoft.EntityFrameworkCore.Tools
