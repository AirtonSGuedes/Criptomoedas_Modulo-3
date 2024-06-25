### Utilizando pgAdmin para Importar um Arquivo CSV

1. **Abrir pgAdmin e conectar ao servidor:**
   - Inicie o pgAdmin e conecte-se ao servidor onde o seu banco de dados PostgreSQL está hospedado.
   - criar a tabela 
   - abra o querytol e rode este codigo 
	CREATE TABLE CRYPTO.cryptocurrencies (
   	 SNo INT NOT NULL,
   	 Name TEXT NOT NULL,
   	 Symbol TEXT NOT NULL,
   	 Date TIMESTAMP NOT NULL,
   	 High NUMERIC NOT NULL,
   	 Low NUMERIC NOT NULL,
    	Open NUMERIC NOT NULL,
   	 Close NUMERIC NOT NULL,
  	  Volume NUMERIC NOT NULL,
  	  Marketcap NUMERIC NOT NULL );
		

2. **Selecionar a tabela de destino:**
   - No painel esquerdo do pgAdmin, expanda o servidor PostgreSQL, expanda a base de dados onde está a tabela que deseja inserir os dados e clique com o botão direito na tabela.
   - Selecione "Importar/Exportar" no menu de contexto.

3. **Configurar a importação:**
   - Na janela de "Importar/Exportar", você verá opções para importar dados para a tabela selecionada.
   - Selecione o arquivo CSV que deseja importar. Você pode clicar no botão "Escolher arquivo" ou simplesmente arrastar e soltar o arquivo na área indicada.

4. **Mapear colunas:**
   - Após selecionar o arquivo CSV, o pgAdmin tentará inferir automaticamente os tipos de dados e mapear as colunas do arquivo CSV para as colunas da tabela no PostgreSQL.
   - Revise e ajuste os mapeamentos conforme necessário para garantir que cada coluna do CSV esteja sendo importada para a coluna correta na tabela.

5. **Configurações adicionais:**
   - Dependendo das suas necessidades, você pode ajustar configurações como o delimitador utilizado no arquivo CSV, se há uma linha de cabeçalho, etc.

6. **Executar a importação:**
   - Após configurar todos os detalhes da importação, clique em "Importar" ou equivalente para iniciar o processo de importação dos dados do arquivo CSV para a tabela no PostgreSQL.

7. **Verificar resultados:**
   - Após a conclusão da importação, verifique a tabela no PostgreSQL para garantir que os dados foram corretamente inseridos conforme esperado.

Utilizando o pgAdmin dessa maneira, você pode realizar a importação de forma visual e intuitiva, sem precisar escrever código SQL diretamente ou usar o comando `COPY`. Isso facilita o processo especialmente se você preferir uma abordagem mais guiada e baseada em interface gráfica.