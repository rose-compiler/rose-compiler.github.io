log.txt: #test1.cpp test1.dox
	doxygen Doxygen &>$@
clean:
	rm -rf log.txt
	rm -rf html/ latex/
web:	
	cd html && python3 -m http.server 8000
