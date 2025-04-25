let numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

let parteNumeros = numeros.slice(3, 7)
console.log(parteNumeros)
function juntar(a, b)
{
 let arrayJ = a.concat(b)
 return arrayJ;
}

const frutas = ['Maçã', 'Banana', 'Laranja', 'Limão', 'Abacaxi']
frutas.splice(2, 2, "kiwi", "pêssego")
let menuPrincipal = ["Pizza", "hamburguer", "Croassant"]
let menuDeSobremesas = ["sorvete", "pudim", "bolo"]
let menuCompleto = []
menuCompleto = juntar(menuDeSobremesas, menuPrincipal)
console.log(menuCompleto)
