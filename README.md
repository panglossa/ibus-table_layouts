# ibus-table_layouts
#Keyboard layouts for various languages using ibus-table

If you have **ibus-table** installed and configured as your input method, you can install any of these layouts with the command

    ibus-table-createdb -n /usr/share/ibus-table/tables/[FILENAME].db -s [FILENAME].txt

where [FILENAME] is the name you text file containing the desired layout. 


If you want the icon, you have to run this command:

    cp [IMAGEFILENAME] /usr/share/ibus-table/icons/

where [IMAGEFILENAME] is the name of the icon file you want. This should have the same name as specified by the ICON parameter in your layout file.


**These commands should be run with administrative privileges, and from the same directory the corresponding layout files are located.**


For example, if you want to install the coptic layout, you run this command: 

    sudo ibus-table-createdb -n /usr/share/ibus-table/tables/coptic.db -s coptic.txt

and to get the corresponding icon:

    sudo cp coptic.png /usr/share/ibus-table/icons/

