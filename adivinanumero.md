Main
    int numJugador
    int intentos = 7
    bool adivinado = FALSO
    int numeroSecreto = Random(0,101)

    while (intentos > 0 && !adivinado)
        lee numJugador
        if(numJugador == numeroSecreto)
              adivinado = VERDADERO
              mostrar "Has adivinado"
              --intentos
        Sino
        if(numJugador > numeroSecreto)
         mostrar  "Demasiado alto"
               --intentos
        Sino
        if(numJugador < numeroSecreto)
         mostrar "Demasiado bajo"
              --intentos
        finIf

        finWhile

FinMain
