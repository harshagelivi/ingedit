ingedit
=======

For linux:(tried and checked in ubuntu)

To add SPL and APL syntax highlighting in gedit

Copy apl.xml and spl.xml into $HOME/.local/share/mime/packages/          (create if any of these doesnt exist)
Copy apl.lang and spl.lang into $HOME/.local/share/gtksourceview-3.0/language-specs/

Now open your terminal and cd into $HOME/.local/share/ and run the belo command:
	update-mime-database mime
Now close any gedit sessions and re-open.
