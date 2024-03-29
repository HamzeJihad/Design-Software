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
- [x] **Visão do sistema**<br>
A visão do sistema projetado está bem explicitado no documento [README.md](https://github.com/HamzeJihad/Design-Software/blob/main/README.md), disponível no repositório.

- [x] **Limites do sistema**<br>
O diagrama de contexto, encontrado no documento [diagrama-contexto.png](https://github.com/HamzeJihad/Design-Software/blob/main/diagrama-contexto.png), define de maneira clara os limites do sistema sendo projetado.

- [ ] **Team contract**<br>
Apesar de, no início do projeto e ao longo dos encontros semanais sempre ocorrer acordos verbais sobre a separação de funções da equipe, nunca foi gerado nenhum tipo de documentação que sirva como registro.

- [x] **Abordagem de design de software**<br>
A abordagem de design utilizada pelo time é a _bottom-up_, começando o planejamento pela perspectiva dos dados do sistema e só ai final projetando a UI.

- [ ] **Data contract**<br>
Não foi gerada uma documentação explicitando o data contract do projeto.

- [ ] **Levantamento de sistemas que irão interagir com o backend**<br>
Não foi feito levantamento de sistemas que possivelmente irão interagir com o backend do projeto.

- [x] **User contract**<br>
O user contract está representado nos [diagrama-contexto.png](https://github.com/HamzeJihad/Design-Software/blob/main/diagrama-contexto.png) e [diagrama_container.png](https://github.com/HamzeJihad/Design-Software/blob/main/diagrama_container.png) e está mais bem explicitado no [diagrama_frontend.png](https://github.com/HamzeJihad/Design-Software/blob/main/diagrama_frontend.png). 

- [ ] **Mock-up da UI**<br>
Ainda não foi ferado um mock-up ou qualquer tipo de protótipo da UI do sistema.

- [x] **UI and backend integration contract**<br>
O integration contract está bem explicitado nos [diagrama-contexto.png](https://github.com/HamzeJihad/Design-Software/blob/main/diagrama-contexto.png), [diagrama_container.png](https://github.com/HamzeJihad/Design-Software/blob/main/diagrama_container.png) e [back-end-diagrama.png](https://github.com/HamzeJihad/Design-Software/blob/main/back-end-diagrama.png).

- [x] **Diagramas de negócio**<br>
O Diagrama de negócios do sistema é bem representado no artefato [diagrama-codigo.png](https://github.com/HamzeJihad/Design-Software/blob/main/diagrama-codigo.png).

- [ ] **Esquema de dados**<br>
Não foi gerado documentação sobre o esquema de dados do sistema.

- [x] **Diagramas de topologia do sistema**<br>
O Diagrama de topologia do sistema é bem representado no artefato [back-end-diagrama.png](https://github.com/HamzeJihad/Design-Software/blob/main/back-end-diagrama.png).
