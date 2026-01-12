### Alias Usage
```
alias uvnew='f(){ git clone https://github.com/Leo-Mooney/python-template.git "$1" && cd "$1" && rm -rf .git && git init -b main && uv sync; }; f'
```
