@echo off
color 3
title UNEA
echo. 
echo.
echo.
echo ============ UNEA ============ EXAMEN AUTOMATIZADO ============ TOTAL: 10 PREGUNTAS ============
echo.
echo.   ***     ***    ****       ***
echo.   ***     ***    ******     ***
echo.   ***     ***    *** ***    ***
echo.   ***     ***    ***  ***   ***
echo.   ***********    ***  ****  ***
echo.   ***********    ***    *******
echo.
echo.
echo Instrucciones: Lea la pregunta y seleccione la letra con la respuesta correcta.
echo.
echo.
echo Pregunta 1
echo.
echo Un algoritmo debe tener instrucciones claras. Que caracteristica de un algoritmo es esta?
echo  a)Preciso   b)Definido   c)Finito
echo.
set/p Respuesta-Cual es la letra de la opcion correcta?
echo.
if%Respuesta%==a echo Respuesta correcta. GOOD JOB!! :)
if%Respuesta%==b echo Respuesta incorrecta  :(
if%Respuesta%==c echo Respuesta incorrecta  :(
echo.
echo.
echo Press any key to exit.
pause>nul
exit
