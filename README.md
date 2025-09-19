# HelloWord Smart Contract – Marcelo Magallanes

Este proyecto es parte del **primer práctico del Ethereum Developer Pack (ETH Kipu)**.  
Se trata de un contrato sencillo que permite **guardar y actualizar un saludo en la blockchain**, demostrando:

- Variables de estado (`string s_greet`)
- Funciones `setGreet` y `getGreet`
- Eventos (`HelloWord_HelloWordUpdate`)
- Buenas prácticas de documentación (NatSpec)

---

## 🚀 Cómo probar el proyecto

### 1. Clonar el repositorio
```bash
git clone https://github.com/marcelomagallaneslab23-lab/hello-word-contract.git
cd hello-word-contract

### 2. Abrir en un IDE (Remix)

Entrar a Remix IDE
.
Crear un workspace nuevo y subir el archivo contracts/HelloWord.sol.

Compilar con Solidity 0.8.26 (optimizer OFF).

Deploy con Injected Provider - MetaMask en la red Sepolia.

🔗 Contrato desplegado

Dirección (Sepolia): 0x49372899155e4ae5c3516e89d175ec3107e14aba

Etherscan: Ver en Sepolia Etherscan "https://sepolia.etherscan.io/address/0x49372899155e4ae5c3516e89d175ec3107e14aba"

📚 Conclusión

Este proyecto permitió poner en práctica los fundamentos de Solidity:

Definición de contratos y funciones.

Manejo de variables de estado y eventos.

Interacción en un entorno Testnet real (Sepolia).

Verificación de contrato en Etherscan y publicación del ABI.

Es un ejemplo educativo para entender la base de los contratos inteligentes y su ciclo de vida completo: escribir → desplegar → verificar → documentar.
