# SED
```
sed -e '/start_marker/,/end_marker/d' 	# remove lines between start_marker and end_marker
sed -e '/^--/d' 			# remove lines starting with -- e.g. SQL comments
sed -e '/^$/d '                         # remove blank lines
```
