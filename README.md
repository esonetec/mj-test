Come one, come all! Just create Pull Requests, we'll merge them.

Directory layout

 - Place *.mj files which are supposed to compile in pos/
 - Place *.mj files which are supposed to parse successfully, but not compile, in pos-parser/
 - Place *.mj files which are not supposed to compile in neg/
 - Place *.mj files which are intended to be compiled and executed,
   and print values to stdout (via `System.out.println`).
   Place a *.check file with the same name as the *.mj file to specify the expected output.

List of tests/tools (please keep up to date):
* `lexfuzz.py`: lexer fuzzer, prints string to be lexed to stdout, expected result (in --lextest format) to stderr.
