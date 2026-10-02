#  Automação_PY_R - Python + Selenium + PyTest + Allure

Este é um framework robusto e escalável de automação de testes Web desenvolvido em **Python**, utilizando **Selenium WebDriver** para interação com o navegador, **PyTest** para orquestração e asserções de testes, a arquitetura **Page Object Model (POM)** para facilidade de manutenção e **Allure Report** para geração de relatórios interativos com evidências visuais e logs.
Teste de automação manual

## Estrutura do Projeto

```text
QA_Selenium_Project/
├── img/                    # Capturas de tela (.png) - evidências.
├── pages/                  # Camada do Page Object Model.
│   ├── __init__.py
│   ├── base_page.py        # Métodos genéricos do Selenium (esperas, cliques, digitação, screenshots).
│   └── login_page.py       # Mapeamento de elementos e fluxos específicos da tela de login.
├── tests/                  # Suíte de testes automatizados.
│   ├── __init__.py
│   └── test_login.py       # Casos de teste funcionais com PyTest e anotações Allure.
├── conftest.py             # Setup/Teardown do WebDriver e captura automática de erros.
├── requirements.txt        # Dependências do projeto (Selenium, PyTest, Allure, etc.).
└── README.md               # Documentação e instruções de uso do projeto.

----------------------------------------------------------------------------------
