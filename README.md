# Pré-requisitos
1. Instalar as bibliotecas:<br>
pip install databricks-sql-connector<br>
pip install databricks-sql-connector openai<br>
pip install databricks-sql-connector[pyarrow]<br>
pip install pandas<br>

2. Gerar um token de acesso pessoal: <br>
No seu workspace do Databricks, crie um **Token de Acesso Pessoal** (PAT) com as permissões necessárias.

3. Obter as informações do seu warehouse SQL:<br>
**Nome do host do servidor:** Vá para a página do seu warehouse SQL, clique em Detalhes da Conexão e copie o Nome do Host do Servidor.
<br>**Caminho HTTP:** Copie o Caminho HTTP da mesma seção

4. Código para consulta 