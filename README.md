# Manager Cloud
Arquitetura de um sistema de controle de ambientes que estão hospedados em suas dependências.

Uma empresa de tecnologia precisa desenvolver um sistema de controle de ambientes que estão hospedados em suas dependências. 
Neste controle deveremos ter um inventário basicamente dos itens: 
  Servidores, 
  Switches, 
  Sistemas Operacionais, 
  SGBDs, 
  Servidores de Aplicação, 
  e Aplicativos. 
Quem são os responsáveis por cada item registrado e quem são os contatos que devem ser avisados em caso de problemas. 
Cada um deles deve ter seu conjunto de atributos. 
Pede-se que construa o modelo de dados que consiga exibir cada item com suas informações básicas e, além disto, a relação de dependência entre eles. 
É necessário controlar também o prazo de garantia de cada item a que esta situação for existente (Servidores, por exemplo). 
Dica: Para se modelar um servidor deveremos modelar diversas tabelas que contém as informações de cada componente com CPU, Disco, etc...
