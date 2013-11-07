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

	yy = short year

	yyyy = long year

	M = month (1-12)

	MM = month (01-12)

	MMM = month abbreviation (Jan, Feb … Dec)

	MMMM = long month (January, February … December)

	d = day (1 - 31)

	dd = day (01 - 31)

	ddd = day of the week in words (Monday, Tuesday … Sunday)

	D - Ordinal day (1st, 2nd, 3rd, 21st, 22nd, 23rd, 31st, 4th…)
