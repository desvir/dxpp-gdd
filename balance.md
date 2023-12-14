## Pruebas y equilibrio

### Plan de pruebas

Se contratará a un equipo de testing especializado en videojuegos vr y con un mínimo de 6 personas que realizará pruebas para buscar errores y pruebas de balanceo del juego, 
Para las pruebas unitarias se usará Unity Test Framework que es un Framework creado por unity para crear pruebas automatizadas.

### Pruebas de balanceo

Se realizarán pruebas manuales con los siguientes objetivos:

	1. Comprobar que la economía del juego esta balanceada, que los objetos no sean demasiado caros para lo que hacen.
	2. Comprobar que la munición que se le proporciona al jugador de cada arma es suficiente para que aguante al menos 2 rondas.
	3. Comprobar que los zombies no escalen demasiado alto de vida, daño o cantidad.
	4. Comprobar que la dificultad se adapta dependiendo de los jugadores que estén conectados en el mapa.
	5. Dar a probar el juego a personas poco experimentadas para comprobar si marea.
	6. Revisar que la media que duran las partidas sea aproximadamente de 4 minutos.
	7. Hacer pruebas pero con diferente número de jugadores para comprobar que todo funciona correctamente.
	
Después de hacer cada prueba se apuntarán los problemas de balanceo que se encuentren y se le pasará al equipo de balanceo para que lo arregle.

### Pruebas de errores

Se realizarán pruebas automatizadas y pruebas manuales con los siguientes objetivos:

	1. Comprobar que la munición y el daño de las armas sea el correcto.
	2. Comprobar que las mecánicas de los zombies especiales funcionan correctamente:
		- El zombie policía: tiene que tener bien delimitada la zona donde no le afectan las balas.
		- El zombie bombero: no le pueden hacer daño desde ninguna fuente de fuego del juego.
		- El enfermero: comprobar que el ácido hace daño a todos los personajes y que resiste menos balas que un zombie normal.
		- El Gentleman: comprobar que salta todos los obstáculos de su mapa y que incapacite a cualquier personaje del juego.
	3. Comprobar que las mecánicas especiales implementadas en cada mapa funcionen correctamente. 
	4. Probar que todas las habilidades de los personajes funcionan correctamente.

Después de hacer cada prueba se apuntarán los fallos que se encuentren y se le pasará al equipo de balanceo para que lo arregle.

