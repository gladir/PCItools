# PCItools
Suite de commande écrit en Pascal (Turbo Pascal ou Free Pascal) pour les périphériques PCI.

<h2>Liste des fichiers</h2>

Voici la liste des différents fichiers proposés dans PCItools :

<table>
		<tr>
			<th>Nom</th>
			<th>Description</th>	
		</tr>
		<tr>
			<td><b>PCIINFO.PAS</b></td>
			<td>Cette commande permet de rechercher les périphériques PCI installé sur le micro-ordinateur.</td>
		</tr>
</table>

<h3>Syntaxe</h3>

PCIINFO [/?] [/USEBIOS]

<h3>Paramètres</h3>

<table>
  <tr>
    <th>Nom</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><b>/USEBIOS</b></td>
    <td>Ce paramètre permet d'indiquer qu'il faut utiliser la détection par le BIOS.</td>
  </tr>
</table>

<h3>Remarques</h3>

<ul>
	<li>Par défaut, il effectue une détection à partir de l'électronique, vous devez donc indiquer avec le paramètre /USEBIOS pour ne pas qu'il utilise des accès directes.</li>
	<li>Les logiciels proposés dans cette suite de commande sont développés pour le système d'exploitation DOS.</li>
</ul>

