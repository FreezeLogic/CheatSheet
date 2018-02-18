# C++  CheatSheet


## String literal table

| Literal name  | Character types  | String content       | Minimum C++ version
| ------------- | ---------------- | -------------------- | ------------------ 
| L             | const wchar_t[]  | unescaped or escaped | 
| u8            | const char[]     | unescaped or escaped | C++ 11
| u             | const char16_t[] | unescaped or escaped | C++ 11
| U             | const char32_t[] | unescaped or escaped | C++ 11
| *prefix* R    | type as prefix   | raw                  | C++ 11

unescaped - Any valid character except the double-quote ( " ) , backslash ( \\ ) , or new-line character
escaped	 -	Any valid escaped character (See Escape sequences table)
raw	      -	Any character sequence, except that it must not contain the closing sequence )delimiter"
prefix	-	One of L, u8, u, U


|Escape sequence|	Description                	| Representation 
| ------------- | --------------------------- | -------------------- 
|'	            | single quote	              | byte 0x27 in ASCII encoding
|\"	            | double quote	              | byte 0x22 in ASCII encoding
|\?            	|	question mark	              | byte 0x3f in ASCII encoding
|\\           	|	backslash	byte              | 0x5c in ASCII encoding
|\a	            |	audible bell	              | byte 0x07 in ASCII encoding
|\b	            |	backspace	                  | byte 0x08 in ASCII encoding
|\f	            |	form feed - new page	      | byte 0x0c in ASCII encoding
|\n           	|	line feed - new line      	| byte 0x0a in ASCII encoding
|\r	            |	carriage return	            | byte 0x0d in ASCII encoding
|\t             |	horizontal tab            	| byte 0x09 in ASCII encoding
|\v	            |	vertical tab              	| byte 0x0b in ASCII encoding
|\nnn         	|	arbitrary octal value	      | byte nnn
|\xnn	          |	arbitrary hexadecimal value	| byte nn
|\unnnn        	|	universal character name*  	| code point U+nnnn
|\Unnnnnnnn	    |	universal character name*  	| code point U+nnnnnnnn

* universal character name content arbitrary Unicode value may result in several characters
