# inicio-de-sesion
describe el ingreso de de usuario y contraseña a 3 intentos con bucle while
<meta charset="UTF-8">
<h1>No pueleee:c</h1>
<script>
  function saltoLinea()  {
    document.write("<br>");
    document.write("<br>");
}
  function imprimir(frase) {
    document.write(frase);  
    saltoLinea();
  }
  var inicioDeSesionRegistrado = "alura";
    var contrasenhaRegistrada = "alura321";
    var intentosMax = 3;
    var intentoActual = 1;

   
   
  while(intentoActual <= intentoActual) {
    var inicioDeSesionIngresado = prompt("Ingrese su usuario");
    var contrasenhaIngresada = prompt("Ingrese su contraseña");   
      if( inicioDeSesionRegistrado == inicioDeSesionIngresado && contrasenhaRegistrada == contrasenhaIngresada ) {
        alert("Bienvenido al sistema " + inicioDeSesionIngresado);
        intentoActual==intentosMax;     
      }else{
          if (intentoActual == 3) {
            alert("¡llegaste al maximo de intetntos! D: ");
            imprimir("no pueleee :c")
            break;
          } else {
        alert("inicio de sesión inválido. Favor intente de nuevo");
        
    }

}


    // var opcion = prompt("Ingresa una opción (o escribe 'salir' para salir del programa)");
//   if (opcion == "salir") {
    // break;
//   }
 
  }
//   alert("La opción ingresada fue: " + opcion);

// alert("Saliendo del programa...");


  
</script>
