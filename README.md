# Barbearia
Projeto de sistema gestor de barbearia para faculdade


Visto que essa versão do projeto não é uma versão pronta para uso, ainda não é possivel instalar a aplicação de forma prática e ainda não possui um arquivo executavel.
      Para instalar essa versão, deve-se efetuar o download do arquivo zip e instalar pela ferramenta da IDE NetBeans "Import project by Zip file".
      Caso esse método não funcione, deve-se extrair a pasta do arquivo zip e tentar abrir o projeto pelo NetBeans com a função "open project" e procurando a pasta extraída do arquivo zip.
      O ideal para o banco de dados seria o uso do MySQL, mas, para evitar o problema de portabilidade, foi usada uma classe "Banco" interna ao projeto que contém as informações do banco de dados.
      Devido ao uso das classes DAO, a aplicação de um banco de dados externo pode ser feita facilmente.
      É possível ver que o repositório possui um arquivo zip e uma pasta, ambos com o nome "Barbearia". O arquivo zip é o recomendável para a instalação, e a pasta está ali apenas para facilitar a visualização. Por algum motivo, ao tentar fazer o upload da pasta do projeto alguns arquivos estranhos apareceram na pasta, então apenas o arquivo zip está funcionando, por isso, use a pasta apenas para explorar o código sem precisar efetuar o download.
      Infelizmente não foi possível implementar todas as funcionalidades que eram pretendidas no início do projeto, então apenas a função de agendamento funciona perfeitamente.
      Os usuários foram pré-definidos no banco de dados, então, nessa versão não é possível editá-los diretamente pela aplicação. O mesmo pode ser dito dos usuários e serviços (Mas o valor do serviço e as notas podem ser modificadas pelo barbeiro na etapa de agendamento, por isso, nessa função o prejuízo é menor).
