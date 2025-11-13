# 🔭 Espectroscopia com Luz Visível

Este repositório contém o código-fonte da aplicação "Espectroscopia com Luz Visível", uma ferramenta interativa construída em Streamlit para auxiliar no ensino e aprendizado de espectroscopia, radiação de corpo negro e classificação estelar.

A aplicação guia o usuário por diferentes etapas, desde a radiação ideal da Lei de Wien até a análise de espectros reais, culminando em uma reflexão sobre o trabalho de Cecilia Payne.

---

## ⚠️ Aviso sobre Acesso Online (Streamlit Cloud)

Se você estiver acessando esta aplicação através de um link público (hospedado no Streamlit Cloud), é possível que você encontre a seguinte mensagem:

---

 😴

**Zzzz**

This app has gone to sleep due to inactivity. Would you like to wake it back up?

> **Yes, get this app back up!**

If you believe this is a bug, please contact us or visit the Streamlit forums.

---

**Por que isso acontece?**
O Streamlit Cloud (a plataforma gratuita de hospedagem) coloca aplicações em "modo de espera" (sleep) após um período de inatividade para economizar recursos.

**O que fazer?**
Não se preocupe, a aplicação não está quebrada.
1.  Basta clicar no botão **"Yes, get this app back up!"** (Sim, reative este app!).
2.  Aguarde alguns segundos ou minutos para que a plataforma "acorde" a aplicação.
3.  Após o carregamento, a aplicação estará totalmente funcional.



## 🚀 Execução Local

Para offline à ferramenta, a melhor opção é executá-la localmente em seu próprio computador.

A aplicação funcionará perfeitamente offline após a instalação das dependências.

### 1. Requisitos Técnicos

Para executar este projeto localmente, você precisará ter os seguintes softwares instalados:

* **Python**: Versão 3.11 ou superior.
* **Git**: Para clonar o repositório (opcional, mas recomendado).
* **Bibliotecas Python**: As dependências estão listadas no arquivo `requirements.txt` e incluem:
    * `streamlit`
    * `pandas`
    * `numpy`
    * `matplotlib`

### 2. Instalação e Execução (Passo a Passo)

Siga estas instruções em seu terminal ou linha de comando:

**I. Clone o repositório:**
```bash
git clone https://github.com/wvanucci/espectroscopia_absorcao.git
```
(Se não tiver o Git, você pode baixar o ZIP do repositório e extraí-lo manualmente.)

**II. Navegue até o diretório do projeto:**

```bash
cd espectroscopia_absorcao
```
(O nome da pasta pode variar ligeiramente dependendo de como você baixou os arquivos)

**III. (Opcional) Crie um ambiente virtual:**

```bash
python -m venv .venv
```

**VI. Ative o ambiente virtual:**

* No Windows:
```bash

.venv\Scripts\activate
```

* No macOS/Linux:

```bash
source .venv/bin/activate
```

**V. Instale as dependências necessárias:**
```bash
pip install -r requirements.txt
```
**VI. Execute a aplicação Streamlit:**
```bash
streamlit run app.py
```

Após executar o último comando, o Streamlit iniciará um servidor local e abrirá automaticamente a aplicação no seu navegador padrão.
