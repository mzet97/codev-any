# codev-any

Codev rodando no Codeanywhere.

## Requisitos

- Python 3.x
- `pip` instalado

Se aparecer erro de modulo ausente (por exemplo, `requests`), instale com:

```bash
python -m pip install requests
```

Se o seu sistema usa outro comando para Python, troque `python` por `python3`.

## Instalacao

1. Clone o repositorio e entre na pasta do projeto.
2. Instale as dependencias:

```bash
python -m pip install -r requirements.txt
```

Se faltar o `pip`:

- Linux (Debian/Ubuntu): `sudo apt-get install python3-pip`
- Windows: siga as instrucoes em `https://pip.pypa.io/en/stable/installation/`

## Execucao

```bash
python Codev.py
```

## Configuracao de ferramentas externas

O Codev usa um arquivo `Settings.txt` para configurar ferramentas como editor, compilador C++ e leitor de PDF.

Na primeira execucao, se `Settings.txt` nao existir, o programa tenta copiar automaticamente:

- `Settings.txt.Windows` (Windows)
- `Settings.txt.Linux` (Linux)

Ferramentas esperadas por padrao:

- Linux: `gedit`, `g++`, Google Chrome (PDF)
- Windows: Notepad++, Dev-C++, Google Chrome (PDF)

Se voce usar ferramentas diferentes ou caminhos diferentes de instalacao, ajuste os comandos no `Settings.txt`.

## Referencia

Mais detalhes estao em `Installation.txt`.