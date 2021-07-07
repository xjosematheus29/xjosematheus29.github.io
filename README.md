# Meus Projetos
## [Multiscript](https://github.com/xjosematheus29/Multiscript/releases)

# Faça O Download Do Script
![Img2.4215;5.523.png](https://github.com/xjosematheus29/Multiscript/blob/main/Img/Img2.4215;5.523.png?raw=true)
- Para Fazer O Download [CLIQUE AQUI ✔](https://github.com/xjosematheus29/Multiscript/releases)

# Multiscript
Tenha tudo que você precisa em apenas um arquivo

## Código Do Script 1.5
![Img2045637786645.png](https://github.com/xjosematheus29/Multiscript/blob/main/Img/Img2045637786645.png?raw=true)
"@echo off
cls
echo.
echo.
echo Digite a opcao que voce deseja...
echo.
echo.
echo Opcao [1] Verificacao simples (Administrador)
echo Opcao [2] Verificacao mais ampla (Administrador)
echo Opcao [3] Informacoes do windows e do hardware
echo Opcao [4] Diskpart (Administrador) blocked
echo Opcao [5] Diskpart + Listdisk (Administrador) blocked
echo opcao [6] Fechar
echo opcao [7] N/D
echo opcao [8] N/D
echo opcao [9] N/D
echo opcao [10] N/D

set /p opcao=Digite A Opcao Que Voce Dejesa...

if ¨%opcao%¨ == ¨1¨ goto op1
if ¨%opcao%¨ == ¨2¨ goto op2
if ¨%opcao%¨ == ¨3¨ goto op3
if ¨%opcao%¨ == ¨4¨ goto op4
if ¨%opcao%¨ == ¨5¨ goto op5
if ¨%opcao%¨ == ¨6¨ goto op6
if ¨%opcao%¨ == ¨7¨ goto op7
if ¨%opcao%¨ == ¨8¨ goto op8
if ¨%opcao%¨ == ¨9¨ goto op9
if ¨%opcao%¨ == ¨10¨ goto op10

:op1
cls
echo.
echo.
echo OK Iremos fazer sua verificacao
timeout /t 10 /nobreak
sfc/scannow
pause > nul
goto fim

:op2
cls
echo.
echo.
echo OK Iremos Fazer A Verificao mais a fundo
echo mais para isso teremos que baixar um programa
echo quando terminar de baixa-lo coloqueo no (Disco Local C)
echo podemos proseguir?
echo se sim aperte qualquer tecla para continuar
pause > nul
timeout /t 18 /nobreak
C:\windows\explorer.exe "https://firebasestorage.googleapis.com/v0/b/assistente-de-download43563672.appspot.com/o/JRT.exe?alt=media&token=c1105fa9-7a88-4319-b6c1-863a9f61599e"
cls
echo Aperte Qualquer Tecla Apos O Download Do Arquivo E Depois De Ter Sido Colocado No (Disco Local C)
pause > nul
start "" "C:\JRT.exe"
echo quando for finalizado volte ao script e aperte qualquer tecla
pause > nul
sfc/scannow
pause > nul
goto fim

:op3
cls
echo.
echo.
echo OK
pause
timeout /t 5 /nobreak
cls
systeminfo
pause
goto fim

:op4
cls
echo.
echo.
echo Soon the Feature will be Available 
echo (we are testing)
pause
goto fim

:op5
cls
echo.
echo.
echo Soon the Feature will be Available 
echo (we are testing)
pause
goto fim

:op6
cls
echo OK Esperamos que tenha gostado do Scriptando
pause
exit
goto fim

:op7
cls
echo.
echo.
echo esta opcao nao existe
goto fim

:op8
cls
echo.
echo.
echo esta opcao nao existe
goto fim

:op9
cls
echo.
echo.
echo esta opcao nao existe
goto fim

:op10
cls
echo.
echo.
echo esta opcao nao existe
goto fim

:fim
echo.
echo.
echo >> historic.txt comandos que foram usados (ECHO, START, CLS, SFC/SCANNOW)
md >> ola
echo Fim Dos Processor :)
pause > nul"
# Creditos de midias ultilizadas
![img342f5fgr6hjnbv](https://github.com/xjosematheus29/Multiscript/blob/main/Img/1841784.png?raw=true)
## [Freepik](https://br.freepik.com/)
