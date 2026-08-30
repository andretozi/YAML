# YAML

Aplicação web mínima em **Flask** desenvolvida como exercício da disciplina de Engenharia de Software. O projeto expõe uma rota inicial que retorna uma mensagem de saudação e inclui um workflow de **GitHub Actions** (CI/CD).

> Fork de [ProfJuliani/EngSoft](https://github.com/ProfJuliani/EngSoft).

## 🚀 Tecnologias

- [Python 3](https://www.python.org/)
- [Flask](https://flask.palletsprojects.com/)
- [GitHub Actions](https://docs.github.com/actions)

## 📁 Estrutura do projeto

```
YAML/
├── .github/workflows/   # Pipeline de CI/CD (GitHub Actions)
├── .gitignore
├── app.py               # Aplicação Flask
└── requirements.txt     # Dependências do projeto
```

## ⚙️ Como executar localmente

Pré-requisito: Python 3 instalado.

```bash
# 1. Clone o repositório
git clone https://github.com/andretozi/YAML.git
cd YAML

# 2. (Opcional) Crie e ative um ambiente virtual
python -m venv venv
source venv/bin/activate        # Linux/macOS
venv\Scripts\activate           # Windows

# 3. Instale as dependências
pip install -r requirements.txt

# 4. Rode a aplicação
flask run
```

A aplicação ficará disponível em `http://127.0.0.1:5000/`.

## 🔗 Rotas

| Método | Rota | Descrição                        |
| ------ | ---- | -------------------------------- |
| GET    | `/`  | Retorna uma mensagem de saudação |

## 👤 Autor

**Andre Tozi Magalhaes**

## 📄 Licença

Projeto de uso acadêmico.
