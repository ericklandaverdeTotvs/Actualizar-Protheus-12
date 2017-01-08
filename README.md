
# Actualizar-Protheus-12
Actualizar Protheus 12 Todo lo necesario para actualizar su ambiente

Esta carpeta incluye todo lo necesario para actualizar protheus a su ultima version (para Mexico logicamente)
1.	Sustituyes Binarios C:\TOTVS 12\Microsiga\Protheus\bin (Tanto smartclient/appserver)
Importante Sacar archivos de la carpeta binappserverace_8.00 y dejarlos sobre la raíz en la que se encuentra esa capeta
2. Sustituyes Includes C:\TOTVS 12\Microsiga\Protheus\include
3. Sustituyes  RPO C:\TOTVS 12\Microsiga\Protheus\apo
4. Colocas el archivo de la carpeta LIB (archivo PTM) en la siguiente ruta  C:\TOTVS 12\Microsiga\protheus_data\updates\ptm
5. Sustituyes Diccionario de datos (TANTO DIFERENCIALES COMO COMPLEMENTOS) C:\TOTVS 12\Microsiga\protheus_data\systemload
6. Sustituyes Helps (TANTO DIFERENCIALES COMO COMPLEMENTOS) C:\TOTVS 12\Microsiga\protheus_data\systemload
7. Sustituyes Menus en C:\TOTVS 12\Microsiga\protheus_data\system

Cuando tengas todo esto listo…
Corre el patch (archivo PTM) desde  tu devstudio (complemento informacion en la descripcion en github)

Al correr el path y todo estar correcto
Corre el compatibilizardor UPDDISTR (puedes copiar desde el archivo txt para no equivocarte)
Primero correlo como una prueba…
Observa todo los log de error que te mostrara…
Corrige de ser necesario esos Log (Puedes guiarte con la pagina (acceso directo de la carpeta|Errores de Instalacion))
IMPORTANTE Cuando todo este correcto vuelve a correr el compatibilizador antes de eso tiene que borrar el archivo mpupddistri.tsk 
(Este archivo esta contenido en  C:\TOTVS 12\Microsiga\Protheus\bin\appserver)
Este archivo contiene el historial de la última instalación….
Todo esto lo puedes comprobar en el acceso directo 5 DICAS ATUALIZAÇÃO PROTHEUS 12

Por ultimo revisa que el proceso termine en successful
Listo… protheus con la ultima version
Tratare de darle una vista a las actualizaciones cada mes y tener este repositorio en github actulizado…

SALUDOS!!!!
