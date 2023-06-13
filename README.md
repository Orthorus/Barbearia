# Barbearia
Projeto de sistema gestor de barbearia para faculdade


Visto que essa versão do projeto não é uma versão pronta para uso, ainda não é possivel instalar a aplicação de forma prática e ainda não possui um arquivo executavel.
      Para instalar essa versão, deve-se efetuar o download do arquivo zip e instalar pela ferramenta da IDE NetBeans "Import project by Zip file".
      Caso esse metodo não funcione, deve-se extrair a pasta do arquivo zip e tentar abrir o projeto pelo NetBeans com a função "open project" e procurando a pasta extraida do arquivo zip.
      O ideal para o banco de dados seria o uso do MySQL, mas, para evitar o problema de portabilidade, foi usada uma classe "Banco" interna ao projeto que contem as informações do banco de dados.
      Devido ao uso das classes DAO, a aplicação de um banco de dados exxterno pode ser feita facilmente.
      É possivel ver que o repositorio possui um arquivo zip e uma pasta, ambos com o nome "Barbearia". O arquivo zip é o recomendavel para a instalação, e a pasta esta ali apenas para facilitar a visualização. Por algum motivo, ao tentar fazer o upload da pasta do projeto alguns arquivos estranhos apareceram na pasta, então apenas o arquivo zip está funcionando, por isso, use a pasta apenas para explorar o codigo sem precisar efetuar o download.
      Infelizmente não foi possivel implementar todas as funcionalidades que eram pretendidas no inicio do projeto, então apenas a função de agendamento funciona perfeitamente.
      Os usuarios foram pré-definidos no banco de dados, então, nessa versão não é possivel edita-los diretamente pela aplicação. O mesmo pode ser dito dos usuarios e serviços (Mas o valor do serviço e as notas podem ser modificadas pelo barbeiro na etapa de agendamento, por isso, nessa função o prejuizo é menor).
