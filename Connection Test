@echo off
echo.
echo Connection Test
echo.
:test
ping google.com|find "Antwort von " >nul
cls
echo/
echo Connection Test
echo/
if not errorlevel 1 (goto Succes) ELSE goto Fail

:Succes
color 0a
echo Connection : OKAY
goto ende

:fail
color 0c
echo Connection : ERROR
:ende
echo/
echo/
timeout 2>nul
goto Test
