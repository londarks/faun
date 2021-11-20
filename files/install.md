
### instalando Flask
para installar o flask em sua maquina basta usar o comando : `pip install Flask` em um terminal com python instalado.

### Iniciando Flask
copie o codigo abaixo e  salve, logo em seguida execulte o programagra com: `python3 main.py`

```python
from flask import Flask

app = Flask(__name__)

@app.route("/")
def hello_world():
    return "<p>Hello, World!</p>"

```
no seu terminal deve aparecer algo como: `127.0.0.1:5000` essa e a url para a pequena aplicação que você acabou de criar se tudo, rodou perfeitamente o flask já esta instalado na sua maquina e rodando perfeitamente.