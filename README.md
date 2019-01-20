<h1>Compilador con w64-mingw32-gcc para linux ejecutado con Wine</h1>
<h2>Instalacion w64-mingw32-gcc</h2>
apt-get update<br>
apt-get install mingw-w64<br>

<h2>Instalacion Win y wine64</h2>
apt-get update<br>
apt-get install wine<br>
apt-get install wine64 //Si su equipo es de 64bits<br>

Compilará a .exe y ejecutará la libreria conio.h del c en Linux.

<strong>Nota:</strong> debe tener instalado wine de 64bits.

<h3>Intrucciones:</h3>

apt-get update<br>
apt-get install mingw-w64<br>

copiar y pegar el archivo .c en /compilador<br>
cp file.c /compilador/<br>
cd /compilador/<br>
./w64-mingw32_wine &#60;file.c&#62;<br><br>

o copiar y pegar en /bin/<br>
cd /compilador/<br>
cp w64-mingw32_wine /bin

<h3>Ejecutar:</h3>
w64-mingw32_wine &#60;file.c&#62;
