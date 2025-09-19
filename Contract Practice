// SPDX-License-Identifier: MIT
pragma solidity 0.8.26;

//Layout

/* ////////////////////////////////////////
imports
///////////////////////////////////////////*/

/* ////////////////////////////////////////
Interfaces
///////////////////////////////////////////*/

/* ////////////////////////////////////////
Libraries
///////////////////////////////////////////*/

//------------------------------------------------------------------------------------------------------------------------

/**
    *@title HelloWord contrato de practica 
    *@author marcelomagallanes-dev
    *@notice El contrato envia un saludo al mundo desentralizado
    *@custom:seguridad Contrato con unico proposito educativo y no debe ser usado en produccion
*/

contract HelloWord {

/*////////////////////////
				Variables de Estado        
////////////////////////*/

///@notice variable para almacenar mensajes de saludos.
    string private s_greet = "Hello Word Smart Value";

/*////////////////////////
					Eventos
////////////////////////*/

///@notice evento emitido cuando el mensaje es actualizado
	event HelloWord_HelloWordUpdate(string greet);
	    
/*////////////////////////
					Funciones
////////////////////////*/
/*
	@notice Función utilizada para Actualizar un mensaje en la blockchain
	@param _greet entrada del tipo string
*/
	function setGreet(string memory _greet) external {
		s_greet = _greet;
/// @notice evento emitido cuando se cambia el saludo		
		emit HelloWord_HelloWordUpdate(_greet);
	}     

/**
	*@notice función get para devolver el mensaje almacenado
	*@return _greet almacenado
*/
	function getGreet() public view returns(string memory ){
		return s_greet;
	}
       

/*///////////////////////////////////
          Type declarations
///////////////////////////////////*/

/*///////////////////////////////////
           State variables
///////////////////////////////////*/

/*///////////////////////////////////
               Events
///////////////////////////////////*/

/*///////////////////////////////////
               Errors
///////////////////////////////////*/

/*///////////////////////////////////
            Modifiers
///////////////////////////////////*/

/*///////////////////////////////////
            Functions
///////////////////////////////////*/

/*/////////////////////////
        constructor
/////////////////////////*/

/*/////////////////////////
     Receive&Fallback
/////////////////////////*/

/*/////////////////////////
        external
/////////////////////////*/

/*/////////////////////////
         public
/////////////////////////*/

/*/////////////////////////
        internal
/////////////////////////*/

/*/////////////////////////
        private
/////////////////////////*/

/*/////////////////////////
      View & Pure
/////////////////////////*/
}

/**
 *custom:contractABI resultado del "ABI"

 [{"anonymous":false,"inputs":
 [{"indexed":false,"internalType":"string","name":"greet","type":"string"}],
 "name":"HelloWord_HelloWordUpdate","type":"event"},
 {"inputs":[],"name":"getGreet","outputs":
 [{"internalType":"string","name":"","type":"string"}],
 "stateMutability":"view","type":"function"},
 {"inputs":[{"internalType":"string","name":"_greet","type":"string"}],
 "name":"setGreet","outputs":[],"stateMutability":"nonpayable","type":"function"}]
*/
