# Sprint_III_MVP_-Engenharia_de_dados_Lakehouse_DBX
Ao final deste MVP, esperamos que o usuário final tenha uma compreensão detalhada dos dados das vitórias nas Maratonas de Londres, respondendo às perguntas propostas e fornecendo insights sobre os aspectos relevantes do evento, como recordes, domínio de países e atletas, e a evolução das diferentes categorias ao longo dos anos.

Neste trabalho, eu documentei o processo para  construir um data lakehouse de dados no Databricks Community utilizando tecnologias na nuvem como Microsoft Azure . 
O Trabalho de conclusão do curso irá envolver a construção de um pipelene (Manual) para  a busca, coleta, e modelagem, para os processos ELT de extração , carga e transformação para a análise Ad-Hoc com os dados escolhidos.


Apresentação do Trabalho

Documentação Organizada

Foram usados notebooks tanto no Google Colab quanto no Databricks Community para documentar o trabalho com vias de conseguir comunicar a implementação do MVP. Onde utilizei células para escrever linhas de código e seus display. Isso também incluiu a descrição do problema, as perguntas de negócio e a justificativa do projeto em um documento para a leitura em formato pdf. Isso ajudará o leitor a manter o foco na documentação organizada e acessível somente num documento pdf.

Ao seguir essa abordagem, cada parte do processo, desde a definição dos objetivos até a análise final, será bem documentada.

Resumo

Os estágios do trabalho detalhados no relatório abaixo são totalmente suportados pelas funcionalidades do workspace no Databricks Community Edition, pelos recursos do Azure Blob Storage Account e do APP Register, e pelo uso do Delta Lake. Além disso, utilizarei alguns comandos básicos em Python e algumas livrarias como Request,  BeautifulSoup, e usei PySpark, Apache SQL e outras bibliotecas integradas no Rol Persona Analytic  Databricks.

A coleta e a persistência dos conjuntos de dados na plataforma de nuvem podem ser gerenciadas através das funcionalidades: Delta Lake e Databricks File System (DBFS)*.

Utilizarei o Delta Lake para a ingestão de dados. O Delta Lake oferece suporte robusto para transações ACID, permitindo uma ingestão de dados confiável e escalável, além da movimentação posterior no modelo Medallion Camadas Bronze e Prata.

*Databricks File System (DBFS): Também é possível utilizar o DBFS para armazenar os arquivos brutos coletados. Pode-se configurar o armazenamento em nuvem, como o Azure Blob Storage, para integrar diretamente com o DBFS.
