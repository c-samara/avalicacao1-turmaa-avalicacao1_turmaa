[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=21627118)
# Avaliação 1 – Etapa 1  
### **Preparação Técnica e Integração com Azure**

## 👥 **Grupo**
- Samara Cardoso  
- João Paulo  
- Bruno Oliveira  
- Victor Miguel  

---

## 🎯 **Objetivo da Etapa**
Esta etapa tem como foco preparar todo o ambiente técnico necessário para o projeto, garantindo integração contínua, testes automatizados e infraestrutura inicial na nuvem.  
Os principais objetivos são:

- Configurar o ambiente de DevOps  
- Criar pipeline CI automatizado com build, lint e testes  
- Provisionar recursos básicos no Azure usando Terraform  

---

## 📁 **Estrutura do Projeto**

/
├── .github/workflows/ci.yml # Pipeline CI com build, flake8 e pytest
├── app/
│ └── main.py # Código principal da aplicação (ex.: cálculo de média)
├── tests/
│ └── test_main.py # Testes automatizados com pytest
└── main.tf # Arquitetura e recursos Azure via Terraform



---

## 🚀 **Entregáveis da Avaliação**

### Pipeline funcional no GitHub Actions
- Execução automática em push/pull request  
- Instalação de dependências  
- Lint com flake8  
- Testes com pytest  
- Status verde no GitHub Actions  

### Evidências
- Prints da configuração do ambiente  
- Prints do pipeline rodando  
- Prints do deploy no Azure via Terraform  

### Entrega Final
- Link do repositório no GitHub Classroom  

---

## ☁️ **Tecnologias Utilizadas**
- **Python 3.11**  
- **Pytest** para testes automatizados  
- **Flake8** para lint  
- **GitHub Actions** (CI/CD)  
- **Terraform** para provisionamento no Azure  
- **Azure** (recursos básicos da nuvem)
