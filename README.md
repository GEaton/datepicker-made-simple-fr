datepicker-made-simple-fr
=====================

Code JS - jQuery UI pour avoir un datepicker en français dans made simple


	1. La première étape est d'aller dans votre formulaire où vous désirez avoir un datepicker.

	2. Dans votre formulaire, créer un champ de texte simple
    
	2.1  Dans les "options-avancés" de celui-ci donner lui la classe 'datepicker'
    
	3. Contenu > Pages puis une fois dans la page où apparait votre formulaire "Options"
    
	3.1 dans la partie 'Métadonnées spécifiques pour cette page :' copier/coller le code

Pour aller plus loins
=====================

Pour formater la date qui est générée, il faut juste changer la valeur de 'dateFormat' à la ligne 8 

>> $(function() {$('div.datepicker input').datepicker({dateFormat: 'd MM yy'});});

Voici les différents format : (respecter la CASSE)

	y = short year

	yy = long year

	m = month (1-12)

	mm = month (01-12)

	M = month abbreviation (Jan, Feb … Dec)

	MM = long month (January, February … December)

	d = day (1 - 31)

	dd = day (01 - 31)

	DD = day of the week in words (Monday, Tuesday … Sunday)
	
	D = day abbreviation (Mon, Tues … Sun)

	
	Exemple :
	{dateFormat: 'D dd MM yy'} = vendredi 29 Novembre 2013
	{dateFormat: 'yy-mm-d'} = 2013-11-29
