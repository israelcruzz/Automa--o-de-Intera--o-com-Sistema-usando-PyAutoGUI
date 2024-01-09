# Automação de Interação com Sistema usando PyAutoGUI

Este script em Python usa a biblioteca PyAutoGUI para automatizar a interação com um aplicativo web. O objetivo é realizar tarefas específicas, como preenchimento de formulários, clicar em botões e rolar a página.

## Requisitos

- Python instalado (pode ser obtido em [python.org](https://www.python.org/))
- Biblioteca PyAutoGUI instalada (`pip install pyautogui`)
- Biblioteca Pandas instalada (`pip install pandas`)

## Execução do Script

1. Clone este repositório ou faça o download do arquivo `script.py`.
2. Certifique-se de ter os requisitos instalados.
3. Abra um terminal ou prompt de comando e navegue até o diretório onde o script está localizado.
4. Execute o script com o comando `python script.py`.

## Descrição do Script

O script realiza as seguintes ações:

1. Abre o navegador Edge.
2. Acessa um link específico.
3. Preenche um formulário de login.
4. Lê dados de um arquivo CSV chamado "produtos.csv" usando a biblioteca Pandas.
5. Para cada linha do DataFrame, realiza as seguintes ações:
   - Clica em uma posição específica na tela.
   - Preenche informações do produto no formulário.
   - Se houver uma observação (`obs`), escreve-a no campo correspondente.
   - Pressiona teclas "Tab" para navegar entre os campos.
   - Pressiona "Enter" para enviar o formulário.
   - Realiza um scroll na página.

## Notas Importantes

- Certifique-se de ajustar as coordenadas de clique (`x` e `y`) para corresponderem à posição correta no seu aplicativo.
- Verifique se o arquivo "produtos.csv" está presente no mesmo diretório do script.
- Este script é um exemplo educativo e pode precisar de ajustes para funcionar no seu ambiente específico.
- Use com responsabilidade, considerando as políticas e termos de serviço do aplicativo ou site que está sendo automatizado.

