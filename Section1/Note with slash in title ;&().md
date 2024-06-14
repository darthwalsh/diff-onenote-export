Windows and Linux files definitely can't have directory separator in file name, and other symbols might be iffy  
Solutions:

- munge the markdown filename use a YAML frontmatter Property with the original filename
- Use similar Unicode glyphs like ∕ (this is not a forward slash, it is "division slash", see [http://www.fileformat.info/info/unicode/char/2215/index.htm](http://www.fileformat.info/info/unicode/char/2215/index.htm) )