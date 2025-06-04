Main
    int jugador
    int computadora
    string resultado

    mostrar "Elige una opción:"
    mostrar "1. Piedra"
    mostrar "2. Papel"
    mostrar "3. Tijera"
    lee jugador

    computadora = Random(1, 4)

    si(jugador == computadora)
        resultado = "Empate"
    Sino
        si((jugador == 1 && computadora == 3) || 
           (jugador == 2 && computadora == 1) || 
           (jugador == 3 && computadora == 2))
            resultado = "Ganaste"
        Sino
            resultado = "Perdiste"
        finIf
    finIf

    mostrar "La computadora eligió: ", computadora
    mostrar resultado
FinMain
