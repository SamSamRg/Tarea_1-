# Sobre_mi
Tarea 1 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        let jugador; 
        let pc ;
        
        jugador = prompt ("Elige tu opcion 1.-piedra 2.-papel o 3.-tijera")
        pc = prompt ("pc")
        
        
            
        if (jugador == 1)
        {
            if(pc == 3 ){
                alert("Ganaste");
                alert ("Un dato curioso de mi es que cuando tenia 10 años queria ser contador publico XD");   
            }
            if(pc == 2){
                alert("Perdiste, creo que te flata nivel para poder ganarme XD");    
            }
            if(pc == 1){
                alert("Es un empate XD");
            }
        }
        while (jugador == 2 && pc == 1)
        {
	        alert("Tu ganaste O.o");
	        alert("Un Dato curioso de mi es que un sueño frustado que tengo es ser musico o cantante XD");
            break;
        }   
        while (jugador == 2 && pc == 2)
        {
            alert("Es un empate");
            break;
        }
        while (jugador == 2 && pc == 3)
        {
            alert("Perdiste, intentalo de nuevo.");
            break;
        }
        const jugadorint = parseInt (jugador, 10)
        switch (jugadorint){
            case 3: 
            const pcint = parseInt (pc, 10)
            switch (pcint){
                case 3:
                    alert("es un empate");
                    break; 
                case 2:
                    alert("Tu ganaste O.o")
                    alert("Un Dato curioso de mi es que soy el unico de mis hermanos que solo tiene un nombre.");
                    break;
                case 1:
                    alert("Perdiste, lo siento mucho.")
                    break;
            }
            
        }
