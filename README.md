Mini-manual GNU/Linux V.0.5
===========

Mini manual GNU/Linux: Este manual es un resumen de comandos de GNU/Linux :)


**Terminal uso basico**


Cambiar a entorno CLI:  `Ctrl + Alt + F1`

Volver a entorno grafico: `Ctrl + Alt + F7`

Ejecutar un programa:     `Alt + F2`

    CTRL L = Clear the terminal 
    CTRL D = Logout 
    SHIFT Page Up/Down = Go up/down the terminal 
    CTRL A = Cursor to start of line 
    CTRL E = Cursor the end of line 
    CTRL U = Delete left of the cursor 
    CTRL K = Delete right of the cursor 
    CTRL W = Delete word on the left 
    CTRL Y = Paste (after CTRL U,K or W) 
    TAB = auto completion of file or command 
    CTRL R = reverse search history 
    !! = repeat last command 


**Navegacion basica en la terminal**


    ls -a = list all files and folders
    ls <folderName> = list files in folder
    ls -lh = Detailed list, Human readable
    ls -l *.jpg = list jpeg files only
    ls -lh <fileName> = Result for file only

    cd <folderName> = change directory
                           if folder name has spaces use “ “
    cd / = go to root
    cd .. = go up one folder, tip: ../../../
    cd ~ = Ir al home 

    du -h: Disk usage of folders, human readable
    du -ah: “ “ “ files & folders, Human readable
    du -sh: only show disc usage of folders

    pwd = imprimir directorio actual
    man <comando> = muestra el manual


**Buscando archivos desde la terminal**

Metodo lento

   
    locate <text> = search the content of all the files
    locate <fileName> = search for a file
    sudo updatedb = update database of files

