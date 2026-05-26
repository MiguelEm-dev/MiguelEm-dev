# Miguel Mendes 👋
Estudante de Engenharia de Software • Entusiasta de Cibersegurança

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Miguel--Emidio-blue?logo=linkedin)](https://www.linkedin.com/in/miguel-emidio-6b8680409)  
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

## Sumário
- [Sobre mim](#sobre-mim)
- [Tecnologias](#tecnologias)
- [Projetos](#projetos)
- [Exemplo de uso](#exemplo-de-uso)
- [Boas práticas de segurança](#boas-práticas-de-segurança)
- [Contato](#contato)
- [Licença](#licença)

## Sobre mim
Sou estudante de Engenharia de Software com foco em desenvolvimento seguro e práticas de cibersegurança. Gosto de automatizar verificações, criar ferramentas utilitárias e estudar técnicas ofensivas e defensivas aplicadas.

## Tecnologias e ferramentas
- Linguagens: **Python**
- IDE/editor: **PyCharm** (recomendo também **VS Code**)
- Plataformas: **Windows**, **Linux**
- Ferramentas: Git, virtualenv/venv

## Projetos
- Password Strength Validator — https://github.com/MiguelEm-dev/password-strength-validator  
  Script Python (PT/EN) que valida requisitos de segurança de senhas: comprimento mínimo, maiúsculas/minúsculas, dígitos, símbolos e opção de checar contra lista de senhas comprometidas.

**Exemplo de uso**
Clone o repositório:
git clone https://github.com/MiguelEm-dev/password-strength-validator.git
cd password-strength-validator

Crie e ative o ambiente virtual:
python -m venv .venv
# Linux / macOS
source .venv/bin/activate
# Windows (PowerShell)
.venv\Scripts\Activate.ps1
# Windows (CMD)
.venv\Scripts\activate

Instale dependências:
pip install -r requirements.txt

Executar o validador:
python validator.py --password "Exemplo@123"

**Boas práticas de segurança**
- Nunca inclua senhas reais em commits, issues ou exemplos públicos.
- Armazene chaves e segredos em variáveis de ambiente ou em um arquivo .env (e adicione .env ao .gitignore).
- Execute ferramentas de segurança apenas em ambientes controlados (máquinas virtuais ou containers) e com autorização explícita.
- Documente claramente o escopo e o uso responsável do projeto (disclaimer).

  **Contato**

    **LinkedIn**: https://www.linkedin.com/in/miguel-emidio-6b8680409

  **Licença**

_**Este projeto está licenciado sob a licença MIT — veja o arquivo LICENSE para detalhes.**_
