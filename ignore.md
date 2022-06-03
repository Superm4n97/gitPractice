#ignore all .a files
*.a

#but do track lib.a, even though you are ignoring all .a files
!lib.a

#only ignore the TODO file in the current directory not subdir/TODO
/TODO

#ignore doc/notes.txt, but not doc/server/arch.text
doc/*.text

#ignore all the pdf files in the doc/ directory and any of its subdirectories
doc/**/*.pdf


