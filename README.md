# 💱 ColetorCotacoesViaAPI


Sistema simples, direto e funcional para **consultar cotações de moedas via API**, com interface gráfica amigável desenvolvida em **Tkinter**. Ideal para quem precisa comparar valores de moedas ao longo do tempo ou automatizar a atualização de planilhas com taxas de câmbio.

![image](https://github.com/user-attachments/assets/bb1654c2-3362-4804-a119-7279bb6052b2)

---

## Objetivo do Projeto

Automatizar o processo de **busca e análise de cotações de moedas estrangeiras**, seja para consulta pontual ou atualização em lote, utilizando dados de uma planilha `.xlsx`.

Esse projeto surgiu com o intuito de **facilitar o trabalho de quem lida com câmbio no dia a dia**, como profissionais da área financeira, analistas de dados ou pessoas que precisam acompanhar variações cambiais com praticidade.

---

##  Funcionalidades

🔹 Consulta de moeda específica por data  
🔹 Conversão automática de valor para Reais  
🔹 Busca de cotações em múltiplas datas (via planilha Excel)  
🔹 Mensagens de sucesso e retorno formatado  
🔹 Interface gráfica intuitiva com abas separadas por função

---

##  Tecnologias Utilizadas

- **Python**
- **Tkinter** – Interface gráfica
- **Requests** – Conexão com API
- **pandas** – Leitura e escrita de planilhas
- **openpyxl** – Manipulação de arquivos `.xlsx`
- **datetime** – Manipulação de datas

---

##  Interface

A aplicação possui duas abas:

📌 **Moeda Específica** – Selecione a moeda, escolha uma data e clique em "Pegar Cotação".  
📌 **Múltiplas Moedas** – Indique o período de datas (via planilha) e o sistema atualiza automaticamente as informações.

![Interface do Projeto](./path/to/screenshot.png) ← *(substituir com a imagem se for subir pro GitHub)*

---

##  Estrutura esperada da planilha

```plaintext
A1: Moeda
A2: USD
A3: EUR
...
```

A ferramenta lê a planilha e atualiza a cotação de cada moeda com base nas datas informadas.

---

##  Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/ColetorCotacoesViaAPI.git
   ```

2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

3. Execute o arquivo principal:
   ```bash
   python app.py
   ```

---

##  Futuras melhorias

- Exportação de relatórios automáticos
- Suporte a outras APIs de câmbio
- Modo escuro para interface
- Gráficos com a evolução cambial

---

##  Contribuição

Sugestões são sempre bem-vindas! Sinta-se livre para abrir um _pull request_ ou entrar em contato.
