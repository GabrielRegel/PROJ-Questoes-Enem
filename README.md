# 📚 PROJ-Questoes-Enem: Coletor e Processador de Questões do ENEM

<p align="center">
  <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-blue?style=for-the-badge" alt="Status do Projeto: Em Desenvolvimento">
  <img src="https://img.shields.io/badge/Linguagem-Python-blue?style=for-the-badge&logo=python" alt="Linguagem: Python">
  <img src="https://img.shields.io/badge/Dependência-Pillow-darkgreen?style=for-the-badge&logo=python-pillow" alt="Dependência: Pillow">
  <img src="https://img.shields.io/badge/Licença-MIT-green?style=for-the-badge" alt="Licença: MIT">
  <img src="https://img.shields.io/github/issues/GabrielRegel/PROJ-Questoes-Enem?style=for-the-badge&color=yellow" alt="Issues Abertas">
</p>

---

## 📜 Sumário
* [💡 Sobre o Projeto](#-sobre-o-projeto)
* [✨ Tecnologias Utilizadas](#-tecnologias-utilizadas)
* [💻 Como Instalar e Rodar](#-como-instalar-e-rodar)
* [⚙️ Uso](#️-uso)
* [🛣️ Roadmap Futuro](#-roadmap-futuro)
* [🤝 Contribuição](#-contribuição)
* [Contato](#contato)

---

## 💡 Sobre o Projeto

O **PROJ-Questoes-Enem** é uma ferramenta desenvolvida em **Python** com o objetivo de **coletar, processar e organizar** questões de provas anteriores do Exame Nacional do Ensino Médio (**ENEM**).

A principal funcionalidade deste projeto é utilizar a biblioteca **Pillow** (PIL) para manipular e, potencialmente, recortar ou extrair elementos gráficos das provas, facilitando a criação de um banco de dados visual e organizado para estudos.

### O que ele faz?

* **Coleta e Download:** Permite obter os arquivos das provas.
* **Processamento de Imagens:** Usa **Pillow** para abrir e manipular arquivos (como PDFs ou imagens) contendo as questões.
* **Geração de Recursos:** O resultado final é um conjunto de imagens/arquivos organizados por questão, prontos para serem usados em simulados ou plataformas de estudo.

---

## ✨ Tecnologias Utilizadas

O núcleo deste projeto reside em **Python** e suas bibliotecas de manipulação de imagens:

* **Python:** A linguagem base do projeto.
* **Pillow (PIL):** Essencial para o processamento, recorte e manipulação das imagens das questões.
* **[Outra dependência, ex: Requests/BeautifulSoup]:** *Adicione aqui a biblioteca que você usa para fazer o download ou raspagem das provas, se houver.*

---

## 💻 Como Instalar e Rodar

Siga estes passos para configurar o ambiente e rodar o coletor:

### Pré-requisitos

* **Python 3.x**
* **pip** (gerenciador de pacotes do Python)

### Instalação

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/GabrielRegel/PROJ-Questoes-Enem.git](https://github.com/GabrielRegel/PROJ-Questoes-Enem.git)
    ```
2.  **Entre no diretório do projeto:**
    ```bash
    cd PROJ-Questoes-Enem
    ```
3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    # (Ou instale a Pillow manualmente, se o arquivo requirements.txt não existir)
    # pip install Pillow
    ```

### ⚙️ Uso

Para executar o script de coleta e processamento (assumindo que o arquivo principal se chame `main.py`):

```bash
python main.py