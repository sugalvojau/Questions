### Encodings
- What is Unicode?
<a href="#" title="
Unicode is a computing industry standard for the consistent encoding, representation, and handling of text expressed in most of the world's writing systems. Developed in conjunction with the Universal Coded Character Set (UCS) standard and published as The Unicode Standard. The standard consists of a set of code charts for visual reference, an encoding method and set of standard character encodings, a set of reference data files, and a number of related items, such as character properties, rules for normalization, decomposition, collation, rendering, and bidirectional display order (for the correct display of text containing both right-to-left scripts, such as Arabic and Hebrew, and left-to-right scripts). Unicode can be implemented by different character encodings. The most commonly used encodings are UTF-8, UTF-16 and the now-obsolete UCS-2. We often say 'Unicode' when we mean 'not ASCII', but that’s silly since of course all of ASCII is also included in Unicode.
">⌘</a>
 
- What is Unicode Consortium?
<a href="#" title="
The Unicode Consortium (Unicode Inc.) is a 501(c)(3) type non-profit organization that coordinates the development of the Unicode standard. Its stated goal is to eventually replace existing character encoding schemes with Unicode and its standard Unicode Transformation Format (UTF) schemes, contending that many of the alternative schemes are limited in size and scope, and are incompatible with multilingual environments. Tho Organization cooperates with many standards development organizations, including ISO/IEC JTC1, W3C, IETF, and ECMA. Full members include most of the main computer software and hardware companies with any interest in text-processing standards, including Adobe Systems, Apple, Facebook, Google, Huawei, IBM, Microsoft, Oracle Corporation, Yahoo! and SAP SE.
">⌘</a>
 
- What is American Standard Code for Information Interchange (ASCII)?
<a href="#" title="
ASCII, sometimes called US-ASCII, is a character encoding standard. ASCII codes represent text in computers, telecommunications equipment, and other devices. Most modern character-encoding schemes are based on ASCII, although they support many additional characters. ASCII originally based on the English alphabet, ASCII encodes 128 specified characters into seven-bit integers. The characters encoded are numbers 0 to 9, lowercase letters a to z, uppercase letters A to Z, basic punctuation symbols, control codes that originated with Teletype machines, and a space. ASCII includes definitions for 128 characters: 33 are non-printing control characters (many now obsolete) that affect how text and space are processed and 95 printable characters, including the space (which is considered an invisible graphic).
">⌘</a>
 
- What is the difference between ASCII and US-ASCII?
<a href="#" title="
No real difference, both are about the same. However, Internet Assigned Numbers Authority (IANA) encourages use of the name 'US-ASCII' for Internet uses of ASCII (even if it is a redundant acronym, but the US is needed because of regular confusion of the ASCII term with other 8 bit based character encoding schemes such as Extended ASCII or UTF-8 for example).
">⌘</a>
 
- What is the difference between ASCII and Extended ASCII?
<a href="#" title="
">⌘</a>
 
- What is American National Standards Institute (ANSI)?
<a href="#" title="
The American National Standards Institute (ANSI) is a private non-profit organization that oversees the development of voluntary consensus standards for products, services, processes, systems, and personnel in the United States. The organization also coordinates U.S. standards with international standards so that American products can be used worldwide. American National Standards Institute or ANSI is the organization that developed ASCII. The organization was called American Standards Association's (ASA) back in 1960 when first meetings started. The formation of the organization dates back to 1918. There are around 125,000 companies and 3.5 million professionals as members in 2017.
">⌘</a>
 
- What is the differece between ASCII and ANSI?
<a href="#" title="
">⌘</a>
 
- What is UCS-2?
<a href="#" title="
">⌘</a>
 
- What is UTF-8?
<a href="#" title="
UTF-8 is commonly used encoding that implements Unicode standard. UTF-8 uses one byte for any ASCII character, all of which have the same code values in both UTF-8 and ASCII encoding, and up to four bytes for other characters. In short: Variable length of a character, ASCII characters (the decent-official version of ASCII - range 0 to 127) are still one byte.
">⌘</a>
 
- What is the max UTF-`...` available?
<a href="#" title="
">⌘</a>
 
- What is the difference between UTF-8 and Unicode?
<a href="#" title="
">⌘</a>
 
- What is the difference between UTF-8 and Extended ASCII?
<a href="#" title="
">⌘</a>
 
- What is Byte order mark (BOM)?
<a href="#" title="
">⌘</a>
 
- What is the difference between big-endian and little-endian?
<a href="#" title="
The terms big endian and little endian come originally from Gulliver's Travels. In computer science they refer to the the integer byte-order for a processor. Big endian processors, such as Sparc and PowerPC store the most significant byte in the first memory location of a multi-byte integer. Little endian processors, such as Intel and Alpha do it the other way around. So the 16-bit number 258 (HEX in a decent format: 0x102) would be 0x0102 on big endian and 0x0201 on little endian machines.
">⌘</a>
 
- What is the difference between line feed `LF` (0x0A) and `\n`, or between carriage return `CR` (0x0D) and `\r` ?
<a href="#" title="
CR and LF are ASCII and Unicode control characters while \\r and \\n are abstractions used in certain programming languages. In addition, for example, \n doesn't mean the same thing in all programming languages.
">⌘</a>
 
- What is the difference between NEXT LINE (NEL) (U+0085), Line Separator (LS) (U+2028), and End Of Line (EOL)?
<a href="#" title="
">⌘</a>
 
- What is the default End Of Line (EOL) for each of the following: Windows, Linux, OSX, Unix, older Mac?
<a href="#" title="
 LF - Unix and Unix-like systems (Linux, macOS, FreeBSD, Multics, AIX, Xenix, etc.), BeOS, Amiga, RISC OS; CR+LF - Microsoft Windows, DOS (MS-DOS, PC DOS, etc.), DEC TOPS-10, RT-11, CP/M, MP/M, Atari TOS, OS/2, Symbian OS, Palm OS, Amstrad CPC, and most other early non-Unix and non-IBM OSes; CR - Commodore 8-bit machines, Acorn BBC, ZX Spectrum, TRS-80, Apple II family, Oberon, the classic Mac OS up to version 9, MIT Lisp Machine and OS-9; RS - QNX pre-POSIX implementation; 0x9B - Atari 8-bit machines using ATASCII variant of ASCII (155 in decimal), LF+CR - Acorn BBC and RISC OS spooled text output.
">⌘</a>

- What is the meaning of `full stop` (0x2E)?
<a href="#" title="
In punctuation, the full stop (British English) or period (Canadian and American English) is a punctuation mark placed at the end of a sentence. The stop glyph is sometimes called a baseline dot because, typographically, it is a dot on the baseline. This term distinguishes the baseline dot from the interpunct (a raised dot). In computing, the full stop is often used as a delimiter (commonly called a 'dot'), such as in DNS lookups, web addresses, and file names: www.wikipedia.org, document.txt, 192.168.0.1 More info: https://en.wikipedia.org/wiki/Full_stop
">⌘</a>

- What is `iconv`?
<a href="#" title="
http://pubs.opengroup.org/onlinepubs/7908799/xsh/iconv.html
">⌘</a>

- **Why do some of emails contain "J", for example "RegardsJ"?**  
If you have Wingdings installed on your computer, the following character will appear as a smiley face. Otherwise, it will be the letter "J": J  
This is because the letter J represents a smiley face icon in the Wingdings font. Microsoft Outlook, a popular e-mail client, automatically converts the :) and :-) text emoticons into smiley face icons using the Wingdings font. Therefore, when Microsoft Outlook users type smiley faces in an e-mail message, they are sent as visual smiley face icons.  
Read more:  
https://pc.net/helpcenter/answers/letter_j_in_email_messages  

#### MySQL

- **What is the difference between Collation and Character Set?**  
Collation: A collation is a set of rules for comparing characters in a character set.  
Character-Set: A character set is a set of symbols and encoding, mostly this information is derived from the type of collation.  
Collation and Character-Set in MySQL are meant for strings.  
Read more:  
https://medium.com/@manish_demblani/breaking-out-from-the-mysql-character-set-hell-24c6a306e1e5  
https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/  

- **How many levels of basic collation and character set exists in MySQL? Just note if collation and character set may be set specifically for a database, a table, a column.**  
MySQL defines a basic collation and a character-set for each of its databases; Furthermore, each table created can have its own collation and character-set which can be same as that of the database or different from it. Furthermore, to provide even more flexibility, a column in a table has a collation and character-set of its own, which can be same as the table or different from it. Although this gives a lot of flexibility but also increases the complexity of handling data.  
Read more:  
https://medium.com/@manish_demblani/breaking-out-from-the-mysql-character-set-hell-24c6a306e1e5  

- **Lets say we have MySQL database that supports UTF-8 (utf8mb3 by default, utf8mb4 if modified). There is a type of data (a data container) for a text to be stored in - TINYTEXT. TINYTEXT is set to be 255 bytes in size. How many utf8mb3 and utf8mb4 characters can TINYTEXT store?**  
???  
`utf8mb3` - 255 bytes / 3 characters per byte -> 85 characters  
`utf8mb4` - 255 bytes / 4 characters per byte -> 63 characters  
Read more:  
https://mathiasbynens.be/notes/mysql-utf8mb4  

- **What is the difference between `utf8_unicode_ci` and `utf8_general_ci`?**  
In general, `utf8_general_ci` is faster than `utf8_unicode_ci`, but less correct.   
For any Unicode character set, operations performed using the `_general_ci` collation are faster than those for the `_unicode_ci` collation. For example, comparisons for the `utf8_general_ci` collation are faster, but slightly less correct, than comparisons for `utf8_unicode_ci`. The reason for this is that `utf8_unicode_ci` supports mappings such as expansions; that is, when one character compares as equal to combinations of other characters. For example, in German and some other languages `ß` is equal to `ss`. `utf8_unicode_ci` also supports contractions and ignorable characters. `utf8_general_ci` is a legacy collation that does not support expansions, contractions, or ignorable characters. It can make only one-to-one comparisons between characters.  
Read more:  
https://stackoverflow.com/questions/2344118/utf-8-general-bin-unicode/2344130#2344130  
https://dev.mysql.com/doc/refman/8.0/en/charset-unicode-sets.html  


- **What is the difference between `utf8_bin` and `utf8_general_ci`?**  
`utf8_bin` compares the bits blindly. No case folding, no accent stripping.  
`utf8_general_ci` compares one byte with one byte. It does case folding and accent stripping, but no 2-character comparisions: `ij` is not equal `ĳ` in this collation.  
Read more:  
https://stackoverflow.com/questions/2344118/utf-8-general-bin-unicode/2344130  
