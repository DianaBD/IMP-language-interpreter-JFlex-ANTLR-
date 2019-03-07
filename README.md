# IMP-language-interpreter-JFlex-ANTLR-
JFlex(parser and interpreter):
  - unzip JFlex_336CA_BrodoceanuDiana.zip
  - in folder JFlex_336CA_BrodoceanuDiana there should be a Makefile -> run "make" command
  - copy checker.sh and test(folder) into Flex_336CA_BrodoceanuDiana/JFlex
  - from Flex_336CA_BrodoceanuDiana/JFlex run command "./checker.sh" to see test results
  - to try the program on an individual test do the following:
        -> in Parser.java line 19 change "input" to whatever test file name you want ex: "test/in/8.in"
        -> "make run"
        -> (first run "make clean" for clarity) results in "output" and "arbore" files
  
 ANTLR(just parser):
  - unzip ANTLR_336CA_BrodoceanuDiana.zip
  - in folder ANTLR_336CA_BrodoceanuDiana there is a Makefile -> run "make" command
  - copy checker.sh and test(folder) into ANTLR_336CA_BrodoceanuDiana
  - from ANTLR_336CA_BrodoceanuDiana run command "./checker.sh" to see test results
  - to try the program on an individual test do the following:
        -> in MyMain.java line 11 change "input" to whatever test file name you want ex: "test/in/8.in"
        -> "make run"
        -> (first run "make clean" for clarity) results in "arbore" file
