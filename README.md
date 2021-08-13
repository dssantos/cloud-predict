# cloud-predict
Experimentos de predição de cargas de trabalhos de nós computacionais utilizando modelos ARIMA e Redes Neurais LSTM

## Como implantar
Com o Python 3.6+ instalado execute os comandos em um terminal:
```bash
git clone https://github.com/dssantos/cloud-predict cloud-predict
cd cloud-predict
python -m venv .cloud-predict
source .cloud-predict/bin/activate # Caso esteja no Windows: .cloud-predict\Scripts\activate.bat
python -m pip install -U pip
pip install -r requirements.txt
```

## Como usar
Execute o comando no terminal:
```bash
jupyter notebook
```
Em seguida, acesse os notebooks em http://localhost:8888 e faça os experimentos.
