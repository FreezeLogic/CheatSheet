C++  CheatSheet

" (unescaped_character|escaped_character)* "	(1)	
L " (unescaped_character|escaped_character)* "	(2)	
u8 " (unescaped_character|escaped_character)* "	(3)	(since C++11)
u " (unescaped_character|escaped_character)* "	(4)	(since C++11)
U " (unescaped_character|escaped_character)* "	(5)	(since C++11)
prefix(optional) R "delimiter( raw_characters )delimiter"	(6)	(since C++11)


String literal table

| Literal name  | Character types  | String content       | Minimum C++ version|
| ------------- | ---------------- | -------------------- | ------------------ |
| L             | const wchar_t[]  | unescaped or escaped |                    |
| u8            | const char[]     | unescaped or escaped | C++ 11             |
| u             | const char16_t[] | unescaped or escaped | C++ 11             |
| U             | const char32_t[] | unescaped or escaped | C++ 11             |
| prefix R      | type as prefix   | raw                  | C++ 11             |

