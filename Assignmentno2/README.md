FILE HANDLING : PHP has several function for creating,reading,uploading and editing files.

fopen() function is used to open the file.
Files opening modes : Modes Description r opens a file for read only.File pointer starts at the beginning of file w opens a file for write only.Erases the contents of the files or creates a new file if it doesn't exists.Files pointer starts at the beginning of file a open file for write only. The existing data in file is preserved.File pointer starts at the end of the file.Creates a new file if the file doesn't exists r+ opens a file for read/write.File pointer starts at the beginning of the file. w+ opens a file for read/write.Erases the contents of the files or creates a new file if it doesn't exists.Files pointer starts at the beginning of file a+ opens a file for read/write. The existing data in file is preserved.File pointer starts at the end of the file.Creates a new file if the file doesn't exists x creates a new file for write only.Returns FALSE and an error file already exits x+ creates a new file for read/write.Returns FALSE and an error if filealready exists
     1) fread() function reads from an open file.
     2) fclose() function is used to close an open file.
     3) fgets() function is used to read a single line from a file.
     4) fgetc() function is used to read a single character from a file.
     5) feof() function checks if the "end-of-file" (EOF) has been reached.
      6)fopen() function is also use to create a file.
PATTERN MATCHING :

PHP includes two different kinds of string pattern matching using regular expression : one that is based in POSIX regular expression and one the is based on Perl regular expressions, like those of javascript.
A regular expression is a sequence of characters that forms a search pattern.It can be a single character,or a more complicated pattern.
Regular expression can be used to perform all types of text search and text replace operations.
1)preg_match() : it returns 1 if the pattern was found in the string and 0 if not.
2)pre_match_all() : it returns the number of times the pattern was found in the string
3)pre_replace() : returns a new string where matched patterns have been replaced with another string