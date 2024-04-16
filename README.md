# ejercicios_js
# tabla del 5

for (var i = 0; i <= 10; i++) {
    var resultado = 5 * i;
    console.log("5 x " + i + " = " + resultado);

 # modificación del anterior código del 1 al 10 

  //  números del 1 al 10
        for (let i = 1; i <= 10; i++) {
            // tabla de multiplicar para cada número
            for (let j = 1; j <= 10; j++) {
                let resultado = i * j;
                console.log(`${i} x ${j} = ${resultado}`);
            }
            // espacio en blanco entre cada tabla
            console.log(" ");  

# Verificarel tipo de Entrada
  // Pedir al usuario que introduzca un texto
        let texto = prompt("Introduce un texto:");

        // Convertir el texto a un número
        let numero = parseFloat(texto);

        // Verificar si el texto es un valor numérico
        if (!isNaN(numero)) {
            // Si es numérico, mostrar un alert indicando que es un valor numérico
            alert("El texto introducido es un valor numérico.");
        } else {
            // Si no es numérico, mostrar un alert indicando que es una cadena
            alert("El texto introducido es una cadena.");

            