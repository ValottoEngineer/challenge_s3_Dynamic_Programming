# Challenge HC LEPIC - Sprint 3 - Dynamic Programming 

Este projeto é parte do desenvolvimento de uma solução chamada LifeLink, que visa auxiliar no treinamento de residentes de medicina utilizando realidade virtual (VR). A solução implementa um sistema onde residentes podem treinar e melhorar suas habilidades em cirurgias e procedimentos médicos simulados em um ambiente seguro e controlado. Através de uma interface interativa, tanto os residentes quanto seus tutores podem monitorar o progresso de treinamento e identificar áreas de melhoria.

## 🚀 Começando

Estas instruções permitirão que você configure e execute o projeto em sua máquina local para desenvolvimento e testes.

### 📋 Pré-requisitos

Aqui estão os requisitos para configurar o ambiente:

Python 3.8+: Certifique-se de que a versão correta do Python esteja instalada.
Bibliotecas Python: As seguintes bibliotecas precisam ser instaladas para o funcionamento correto do sistema.

```
pip install numpy matplotlib
```

### 🔧 Instalação

Passo-a-passo para rodar o projeto:

1. Clone o repositório do GitHub:
```
git clone https://github.com/seu-usuario/lifelink.git
```
2. Navegue até o diretório do projeto:
```
cd lifelink
```
3. Crie um ambiente virtual e ative-o:
```
python3 -m venv venv
source venv/bin/activate (Linux/Mac)
venv\Scripts\activate (Windows)
```
4. Instale as dependências:
```
pip install -r requirements.txt
```
5. Execute o código principal:
```
python main.py
```
6. Para gerar gráficos de desempenho dos residentes, execute:
```
python training_analysis.py
```

## ⚙️ Executando os testes

Os testes são automatizados e garantem que o sistema esteja funcionando conforme esperado.

### 🔩 Testes de ponta a ponta

Os testes de ponta a ponta verificam os seguintes aspectos:
  • Simulações VR: Testa a execução dos cenários de treinamento em realidade virtual.
  • Monitoramento de desenvolvimento: Verifica se os dados de performance dos residentes são capturados e armazenados corretamente.
Para rodar os testes:
```
pytest tests/test_vr_simulation.py
```

### ⌨️ Testes de estilo de codificação

Utilizamos o PEP8 como base para o estilo de código Python. Para verificar o estilo de código, use:
```
flake8 src/
```

## 📦 Implantação

Se o projeto for implantado em um servidor, adicione as configurações de ambiente necessárias (como variáveis de ambiente e URLs de banco de dados) no arquivo .env. O sistema pode ser configurado para rodar com containers Docker, facilitando a implantação em ambientes de produção.
```
docker-compose up --build
```

## ✒️ Autores

* **Pedro Oliveira Valotto** - (https://www.linkedin.com/in/pedro-oliveira-valotto-346918219/)
* **Lucas Laia Manentti** - (https://www.linkedin.com/in/lucas-laia-manentti-08a577208/)
* **Tomáz Versolato Carballo** - (https://www.linkedin.com/in/tomazcarballo/)
* **Rony Ken Nagai** - (https://www.linkedin.com/in/rony-nagai/)

---
