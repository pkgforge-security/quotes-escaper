### ℹ️ About
Escapes Quotes (Single | Double). You can also use [sttr](https://github.com/abhimanyu003/sttr) to do the same more reliably. Or alternatively: https://tools.knowledgewalls.com/online-escape-single-or-double-quotes-from-string

### 🖳 Installation
Use [soar](https://github.com/pkgforge/soar) & Run:
```bash
soar add 'quotes-escaper#github.com.pkgforge-security.quotes-escaper'
```

### 🧰 Usage
```mathematica
❯ quotes-escaper --help
Escapes Quotes (Single | Double)

Options:
  -s | --single Escape single quotes
  -d | --double Escape double quotes
  -f | --file   File path to read input from

# Input can be also passed from stdin or as positional argument
  ❯ quotes-escaper -s "single's" (OR) echo "single's" | quotes-escaper -s (OR) cat "file.txt" | quotes-escaper -s
  ~> single\'s

  ❯ quotes-escaper -d 'double "" quotes' (OR) echo 'double "" quotes' | quotes-escaper -d (OR) cat "file.txt" | quotes-escaper -d
  ~> double \"\" quotes
```