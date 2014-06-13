manifest.appcache: 
	cp manifest.header manifest.appcache
	echo -n "# " >> manifest.appcache
	git describe >> manifest.appcache
	find . -type f  >> manifest.appcache


.PHONY: manifest.appcache
