# FATPY - Gerenciador de Faturas de Energia

## Descrição
O FATPY é uma aplicação em Python para automação do processamento de faturas de energia elétrica. Ele lê arquivos Excel contendo dados das faturas, realiza cálculos sobre o consumo e gera novos arquivos Excel com os valores atualizados, além de permitir o armazenamento das faturas processadas.

## Tecnologias Utilizadas
- Python
- Pandas
- OpenPyXL
- Tkinter
- ttkbootstrap

## Instalação

Antes de rodar o FATPY, instale as dependências necessárias:

```bash
pip install pandas openpyxl ttkbootstrap
```

## Uso

1. Execute o script principal:
   ```bash
   python fatpy.py
   ```
2. Selecione um arquivo Excel contendo os dados das faturas.
3. Configure as taxas fixas e variáveis.
4. Escolha um diretório para salvar as faturas geradas.
5. Pressione "GERAR" para processar os arquivos.

## Funcionalidades
- Leitura de arquivos Excel com dados de consumo de energia.
- Tratamento e validação dos dados, como remoção de valores inconsistentes.
- Cálculo automático das taxas variáveis e fixas de energia.
- Geração de novas faturas no formato Excel.
- Interface gráfica desenvolvida com ttkbootstrap para melhor experiência do usuário.

## Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/fatpy.git
   cd fatpy
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o programa:
   ```bash
   python fatpy.py
   ```

## Contato
Caso tenha dúvidas ou sugestões, entre em contato:
- **Email**: [joao.neto1883@gmail.com](mailto:seuemail@example.com)
---

Este repositório foi criado para facilitar a geração de faturas de energia de forma automática e eficiente. Esperamos que seja útil!
