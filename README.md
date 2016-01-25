# kicad-libs
Libraries for Kicad

## Generate a BOM with Eeschema

    sudo apt-get install xsltproc
    
   in eeschema:

    open "BOM"
    add plugin
    name: bom2csv
    
Edit the command if you want to change the name of the output file
    
    command: xsltproc -o "%O-bom.csv" /home/USERNAME/KICAD-DIRECTORY/kicad-libs/BOM/bom2csv.xsl "%I"


    
