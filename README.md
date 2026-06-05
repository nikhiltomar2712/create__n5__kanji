# JLPT N5 Kanji (110)

This repository contains a small tool and output file for the 110 kanji commonly listed for JLPT N5.

Files
- create_n5_kanji.py — script that generates the kanji file and README. UTF-8 output.
- kanji_n5.txt — generated file with one kanji per line (110 kanji).
- README.md — this file.

How to generate
1. Open a terminal in this repository (Linux).
2. Run:
   python3 create_n5_kanji.py

The script will create or overwrite `kanji_n5.txt` and `README.md` in the working directory.

Usage ideas
- Import `kanji_n5.txt` into flashcard apps (Anki, Quizlet).
- Use it as input for study tools, parsing exercises, or language-processing scripts.
- Convert to CSV/JSON for programmatic use.

Notes
- The script asserts the list length equals 110; it will raise an AssertionError if changed.
- Files are written using UTF-8 encoding.

License
- Public domain / CC0. Use freely for educational purposes.

```
# JLPT N5 Kanji (110)

This repository contains a small tool and output file for the 110 kanji commonly listed for JLPT N5.


How to generate
1. Open a terminal in this repository (Linux).
2. Run:
   python3 create_n5_kanji.py

The script will create or overwrite `kanji_n5.txt` and `README.md` in the working directory.

Usage ideas
- Import `kanji_n5.txt` into flashcard apps (Anki, Quizlet).
- Use it as input for study tools, parsing exercises, or language-processing scripts.
- Convert to CSV/JSON for programmatic use.

Notes
- The script asserts the list length equals 110; it will raise an AssertionError if changed.
- Files are written using UTF-8 encoding.

License
- Public domain / CC0. Use freely for educational purposes.
