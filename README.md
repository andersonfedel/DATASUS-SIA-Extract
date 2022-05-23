# DATASUS-SIA-Extract
Código em Python executável pelo ambiente Colab que coleta dados de informações ambulatoriais (SIA) diretamente do FTP do DATASUS 

Não será necessário instalar qualquer programa ou biblioteca na máquina local. O ambiente será configurado dentro do próprio Google Colab. 
Será necessário apenas logar a uma conta Google e montar o Google Drive no Notebook.
Os arquivos DATASUS são disponibilzados no formato .DBC, proprietário do Ministério da Saúde. 
Este notebook converterá os arquivos .DBC selecionados em arquivos .parquet .
O código usa como base a biblioteca PySUS, que é a reponsável por fazer a conversão de .DBC para Pandas DataFrame.
Assim, também é possível consumir os dados desejados como dataframe no próprio Notebook.
