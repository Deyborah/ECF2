# ECF2

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
