## Expresión: 
Siempre retorna un valor (ejemplo 1+1 y nos retorna 2)

## Statement: 
Realiza una acción (ejemplo, if else)

## Expresiones Artitmeticas: 
Resuelven un valor numérico

## Expresiones de string: 
Resuelven texto (ejemplo: Hola + Mundo)

## Expresiones Logicas: 
Resuelven un valor booleano (ejemplo: 10>9 false)

## Expresiones primarias: 
Escribo una expresión que no tiene operador (ejemplo: "Hola" retorna Hola)

## Expresiones de asignación: 
Funciona cuando uso el signo igual (ejemplo: a=2, guarda y retorna 2)

## Expresiones con efectos secundarios: 
Evalua el valor de la variable y suma una acción (ejemplo: contador++ o ++contador)

## Funciones: 
puede haber funtion statemes y funtion expresions. 

## F State ejemplo:
function toni(a,b,c) {}

## F Expresions Statements ejemplo:
let array = {1,2}
array.map(function (a) {return a * 2})
Resultado 2 y 4

Aca espera una expresión y en el otro no. La expresión es la del Var.

## Inmediatly Invoked Function Expresions ejemplo: 

(function (){
    return 10
}) () //con el parentesis final retorna el valor de la función. 


## Condicional Statements: If else o Switch; 

if() {

}else {

}

Switch (valor) {
    case 'opción1':
        //se ajusta si el valor es opción1
        breack;
    case 'opción2':
        //se ajusta si el valor es opción2
        breack;
    case 'opción3':
        //se ajusta si el valor es opción3
        breack;
    default:
        //se ejecuta siempre. Si los casos anteriores no son, va con este. 
}

## Loops

while(condicion){
    //ejecuta el código mientras la expresión sea verdadera
}

for (let i = 1; i > 10; i++){
    Desde , hasta, acción.
    Ejecuta el código 9 veces
}

function () {
    bloque de código
    return; //Cuando llega acá, sale de la ejecución de la función y retorna el valor

}

for (let i = 1; i < 10; i++) {
    continue; // Saltea a la siguiente iteracion del bucle

}






