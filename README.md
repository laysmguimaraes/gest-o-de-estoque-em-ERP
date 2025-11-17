
Mini-ERP de Gestão de Estoque

Este é um projeto de faculdade que simula um sistema de gestão de estoque (ERP) em Python.

O programa permite cadastrar produtos, registrar vendas e compras, salvar os dados em um arquivo (erp_dados.json) e visualizar relatórios e gráficos gerenciais.


-Funcionalidades Principais

1. Cadastrar produto: Adiciona um novo item (com custo, preço de venda, demanda, etc.).

2. Registrar Venda: Dá baixa no estoque e calcula o Custo da Mercadoria Vendida (CMV).

3. Registrar Compra: Dá entrada no estoque.

4. Excluir produto: Remove um item.

5. Relatório Simples: Lista o estoque atual.

6. Relatórios Gerenciais: Calcula o Giro de Estoque e o Estoque de Segurança.

7. Dashboards (Gráficos):

Gráfico de Quantidade por Categoria.

Análise de Curva ABC (valor de custo).

Gráfico de Evolução (Valor Estoque vs. CMV).

8. Ver Histórico: Mostra todas as vendas e compras.

9. Sair: Encerra o programa (os dados são salvos automaticamente).




-Como Executar este Projeto

Existem duas formas de testar: baixando os arquivos ou usando o Google Colab. 

Opção 1: Executando no seu Computador (Recomendado)

Baixar os Arquivos:

No GitHub, clique no botão verde <> Code.

Selecione "Download ZIP".

Extraia o arquivo .zip em uma pasta no seu computador.

Instalar as Dependências:

Abra o seu terminal (Prompt de Comando, PowerShell, etc.).

Navegue para dentro da pasta que você acabou de extrair. (Use o comando cd <caminho_da_pasta>).

Digite o comando abaixo para instalar a biblioteca de gráficos:

pip install -r requirements.txt



Executar o Programa:

No mesmo terminal, digite:

python mini_erp_estoque.py



Opção 2: Testando no Google Colab

Instalar a Biblioteca:

Em uma célula de código, rode o comando:

!pip install matplotlib



Ajustar o Código:

Copie e cole o código do mini_erp_estoque.py em uma nova célula.

Importante: Você precisa comentar (colocar um # na frente) todas as linhas que contêm plt.show() (são 3 no total).

Por quê? No Colab, o plt.show() trava o programa e impede o menu de continuar.

Rodar o Programa:

Execute a célula com o código. O menu aparecerá logo abaixo.

