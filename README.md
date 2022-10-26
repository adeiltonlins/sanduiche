# sanduiche
function Sanduiche (mensagem) {
    return function() {
        console.log (mensagem)
    }    
}

var FrangoAssado = Sanduiche ('O sanduíche de frango assado custa $4,50')
    FrangoAssado()

var Pepperoni = Sanduiche ('O ingrediente adicional pepperoni custa $0,99')
    Pepperoni()

var QueijoMussarelaRalado = Sanduiche ('O ingrediente adicional queijo mussarela ralado custa $2,00')
    QueijoMussarelaRalado()
