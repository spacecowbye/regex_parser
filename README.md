# A full-featured regex engine from scratch (Python, no imports)
## This is a regex engine we coded, It's around 240 lines of Python and is a regex-directed engine based on backtracking. Because of this, and because of the way it's written, it's not the fastest. However, it's written to be clear rather than fast. It uses no libraries or imports of any kind.

### It supports:

1. Literals (abc)
2. Sets ([abc])
3. Star/question mark/plus (a*b?c+)
4. Alternates (a|b)
5. Start and end (^abc$)
6. Matching in the middle of a string an returning the match
7. Custom escape sequences (\a \d)
8. It includes a simple test, so you can just run it with Python 3.