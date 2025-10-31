## Instalación de Azure CLI
1. Como primer punto es necesario acceder a consola, en este caso puede ser powershell, ejecutandose como administrador
2. ingresamos el siguiente comando:
```Comando Azure CLI
winget install --exact --id Microsoft.AzureCLI --source winget
```
3. Una vez terminado de instalar el paquete cerramos las ventanas de power shell para que carguen los repositorios descargados y entramos a vsc
4. Dentro de VSC, tenemos que usar la combinación de teclas ctl + ñ, para poder abir una terminal
5. Introducimos el siguiente comando para que se aparezca el inicio de sesión de microsoft
```Comando de AZ
az login
```
6. Despues de ingresarlo se mostrara un login de microsoft donde iniciamos sesión desde la cuenta donde se tiene el tenant para desplegar
7. Una vez ingresado a la cuenta con los accesos, se cargara en la terminal los tenant donde esta integrada la cuenta de azure, se selecciona el tenat especifico y se termina la configuración
