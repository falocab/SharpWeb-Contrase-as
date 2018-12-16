# SharpWeb

## Introducccion

SharpWeb es un proyecto compatible con .NET 2.0 CLR que puede recuperar inicios de sesión guardados de Google Chrome, Firefox, Internet Explorer y Microsoft Edge. En el futuro, este proyecto se ampliará para recuperar elementos de Cookies e Historial de estos navegadores.

## Uso

```
LA CARPETA BIN se crea despues de abrir el archivo # SharpWeb.sln en Visual Studio
uso:
ABRIMOS POWERSHELL
 bin\Debug\SharpWeb.exe arg

arg:
    all       - Retrieve all Chrome, FireFox and IE/Edge credentials.
    full      - The same as 'all'
    chrome    - Fetch saved Chrome logins.
    firefox   - Fetch saved FireFox logins.
    edge      - Fetch saved Internet Explorer/Microsoft Edge logins.

## EJEMPLO: Para Firefox y Edge (asi vemos que podemos excluir a chrome por ejemplo)

```
.\SharpWeb.exe edge firefox
```
![FireFox/Edge](Images/ff_edge.png)

 falocab
I look at you and I hack your face, bitch !!
