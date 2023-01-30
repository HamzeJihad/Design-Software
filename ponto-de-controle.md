# Lista de Verificação

O objetivo do seguinte documento é realizar a verificação do processo de construção de software sendo atualmente desenvolvido para a disciplina de Design de Software.

A documentação completa do projeto pode ser encontrada no repositório [HamzeJihad/Design-Software](https://github.com/HamzeJihad/Design-Software).

Para referência de verificação, está sendo utilizado o artigo [Designing a Complex Software System](https://betterprogramming.pub/designing-a-complex-software-system-720897671b6a).

## Itens de verificação

Será avaliada a presença ou ausência dos seguintes itens na documentação geral do projeto:

- **Visão do sistema**<br>
Representa a intenção e o ganho buscado pelos stakeholders quando o projeto foi inicialmente idealizado.

- **Limites do sistema**<br>
Define as restrições de processo, saída ou suporte do sistema projetado.<br>
Restrições podem incluir framework a ser utilizado, linguágem utilizada, tempo de execução, etc.

- **Team contract**<br>
Acordo estabelecendo como o time irá se organizar e operar ao longo do projeto.<br>
Nessa etapa são definicas coisas como estrutura de repositório que será utilizada, obrigatoriedade de testes antes de submissões, padrões de cógido adotados, organização de arquivos fonte, etc.

- **Abordagem de design de software**<br>
Duas abordagens majoritárias são mencionadas no artigo fonte para esta lista de verificação: _top-down_ e _bottom-up_.

   Na abordagem _top-down_, o design começa a ser feito da perspectiva do usuário e o trabalho avança de forma descendente ao longo dos níveis do sistema, até chegar à última camada, normalmente a camada de dados do sistema.

   Na abordagem _bottom-up_, o design começa a partir dos dados requeridos e avança de forma ascendente, até chegar ao nível mais alto, sendo esse o de usuário.

- **Data contract**<br>
Define o modelo de dados, formatação, troca de dados entre serviços e armazenamento de dados que serão utilizados no sistema projetado.

- **Levantamento de sistemas que irão interagir com o backend**<br>
Sondagem de serviços que irão se comunicar com o backend do sistema uma vez que o mesmo esteja operante.

   Caso a necessidade tais serviços e comunicações se mostre verdadeira, é preciso criar um acordo de integração (integration contract) entre o backend do sistema e os serviços que irão interagir com ele.

- **User contract**<br>
Idealização de como o usuário irá interagir com o sistema.

- **Mock-up da UI**<br>
Criação de um protótipo visualmente fiel ao user contract previamente estabelecido.

- **UI and backend integration contract**<br>
Definição da estrutura de comunicação entre a UI e o backend do sistema.

- **Diagramas de negócio**<br>
Confecção de diagramas necessários para melhor contextualização do sistema.

   Essa etapa auxiliará mais tarde nas definições estruturais do sistema, como ações do usuário, transições de estado de objetos, fluxo lógido, etc.

- **Esquema de dados**<br>
Definição do esquema de banco de dados que o sistema adotará.

- **Diagramas de topologia do sistema**<br>
Diagramas em nível de sistema, descrevendo como diferentes aspéctos do backend se conectam e se comunicam.

## Checklist de verificação
- [ ] **Visão do sistema**
- [ ] **Limites do sistema** 
- [ ] **Team contract**
- [ ] **Abordagem de design de software**
- [ ] **Data contract**
- [ ] **Levantamento de sistemas que irão interagir com o backend**
- [ ] **User contract**
- [ ] **Mock-up da UI**
- [ ] **UI and backend integration contract**
- [ ] **Diagramas de negócio**
- [ ] **Esquema de dados**
- [ ] **Diagramas de topologia do sistema**
