# MODELAGEM DE SISTEMAS EM UML

## (ARA1391 / _Disciplina Digital_ / 2023.2) Turma 9001

1. O uso de camadas tem vantagens que justificam seu uso, mas existem pontos negativos. Com base nesse contexto, assinale a ÚNICA alternativa que apresenta uma desvantagem do uso de camadas no desenvolvimento de software:

   - Permite substituir uma tecnologia que implemente uma camada de forma simples.
   - Torna o código mais organizado e legível.
   - Aumenta o número de classes do sistema. 👈🏽✅
   - Permite melhor reuso do código ou dos objetos.
   - Permite o desenvolvimento, o teste e a manutenção de cada camada isoladamente

   ***

   - Resposta
     **Aumenta o número de classes do sistema.**
   - Comentário
     Embora o uso de camadas tenha várias vantagens, como permitir o desenvolvimento, teste e manutenção de cada camada isoladamente, melhorar a organização do código e facilitar o reuso de código ou objetos, uma desvantagem potencial é que pode resultar em um aumento no número de classes no sistema, o que pode tornar o código mais complexo e difícil de gerenciar em projetos muito grandes ou mal projetados.

   ***

2. Fonte: VUNESP - 2013 - FUNDUNESP - Analista Programador Júnior

   Considere o seguinte elemento pertencente à notação UML 2.5.

   ![pacote](<q9(13).jpg>)

   O elemento representa um (a)

   - Statechart
   - Dependência
   - Estado de sincronismo
   - Pacote 👈🏽✅
   - Estereótipo

   ***

   - Resposta
     Pacote
   - Comentário

   ***

3. Qual dos passos abaixo não diz respeito à criação de um diagrama de interação :

   - Determine o caso de uso que será modelado e identifique suas operações.
   - Identifique as classes de análise que serão modeladas no projeto. 👈🏽✅
   - Identifique a sequência de fluxos de mensagens na interação entre os objetos.
   - Identifique as conexões e relacionamentos entre eles e, em seguida, categorize-os.
   - Para cada operação, identifique os objetos que farão parte da sua interação.

   ***

   - Resposta
     **Identifique as classes de análise que serão modeladas no projeto.**
   - Comentário
     Os diagramas de interação, como os diagramas de sequência e os diagramas de comunicação, estão mais relacionados à modelagem das interações entre os objetos em um sistema do que à identificação das classes de análise em si. A identificação das classes de análise é uma etapa anterior no processo de modelagem, geralmente associada à criação de diagramas de classes ou diagramas de pacotes, que descrevem a estrutura do sistema em termos de classes, pacotes, interfaces etc.

   ***

4. (CEPS ‒ UFPA ‒ 2018) Um engenheiro de software está especificando os requisitos para um software que automatize a distribuição das turmas em salas de aula disponíveis em um campus de uma instituição de ensino superior.

   Durante o processo de levantamento e especificação de requisitos, o engenheiro de software identificou requisitos funcionais e requisitos não funcionais relacionados com o projeto que está sob sua responsabilidade.

   Considere os requisitos relacionados a seguir:

   I - O sistema deve ser compatível com navegadores Web executando em smartphones.

   II - O sistema deve permitir o cadastro das salas de aula disponíveis para uso, sua localização e sua capacidade.

   III - O sistema deve permitir a emissão de relatórios contendo a alocação das salas e turmas.

   IV - O sistema deve ser desenvolvido com a linguagem Java.

   V - O sistema deve fornecer uma solução de interoperabilidade com os outros sistemas existentes na instituição.

   VI - Os relatórios gerenciais devem ser emitidos em no máximo dez segundos no contexto de mil usuários simultâneos.

   Dentre os itens relacionados de I a VI, são requisitos não funcionais:

   - V e VI, somente
   - II, III e V, somente
   - II, III, IV, V e VI, somente
   - I, IV, V e VI, somente 👈🏽✅
   - I, II e IV, somente

   ***

   - Resposta
     - I, IV, V e VI, somente
   - Comentário
     Os requisitos não funcionais são aqueles que descrevem propriedades e características do sistema que não estão diretamente relacionados a funcionalidades específicas, mas sim a atributos de qualidade ou restrições. Os requisitos não funcionais são:
     - **I - O sistema deve ser compatível com navegadores Web executando em smartphones.**
       - Este é um requisito não funcional relacionado à compatibilidade e usabilidade do sistema.
     - **IV - O sistema deve ser desenvolvido com a linguagem Java.**
       - A escolha da linguagem de programação é um requisito não funcional relacionado à implementação técnica do sistema.
     - **V - O sistema deve fornecer uma solução de interoperabilidade com os outros sistemas existentes na instituição.**
       - A interoperabilidade é um requisito não funcional que se refere à capacidade do sistema de trabalhar em conjunto com outros sistemas.
     - **VI - Os relatórios gerenciais devem ser emitidos em no máximo dez segundos no contexto de mil usuários simultâneos.**
       - O tempo de resposta é um requisito não funcional que diz respeito ao desempenho do sistema.

   ***

5. Assinale a alternativa que define a intenção do princípio da Segregação de Interfaces:

   - Cada módulo deve ter uma, e apenas uma, razão para mudar.
   - Entidades concretas devem depender de abstrações, e não de outras entidades concretas.
   - Clientes de um módulo não devem ser forçados a depender de operações que eles não utilizem. 👈🏽✅
   - Cada módulo deve estar aberto para extensões, mas fechado para modificações.
   - Um tipo deve poder ser substituído por qualquer um de seus subtipos, sem alterar o correto funcionamento do sistema.

   ***

   - Resposta
     **Clientes de um módulo não devem ser forçados a depender de operações que eles não utilizem.**
   - Comentário
     1. **Cada módulo deve ter uma, e apenas uma, razão para mudar.**
        - Isso se refere ao Princípio da Responsabilidade Única (Single Responsibility Principle - SRP). Embora seja uma boa prática, não é a intenção específica da segregação de interfaces.
     2. **Entidades concretas devem depender de abstrações, e não de outras entidades concretas.**
        - Este é o Princípio da Inversão de Dependência (Dependency Inversion Principle - DIP). Ele sugere que as classes devem depender de interfaces abstratas em vez de implementações concretas.
     3. **Clientes de um módulo não devem ser forçados a depender de operações que eles não utilizem.**
        - Este é o princípio específico da Segregação de Interfaces. Ele destaca a importância de dividir interfaces grandes em interfaces menores e mais específicas, para que as classes que as implementam não sejam sobrecarregadas com métodos que não são relevantes para sua funcionalidade.
     4. **Cada módulo deve estar aberto para extensões, mas fechado para modificações.**
        - Este é o Princípio do Aberto/Fechado (Open/Closed Principle - OCP). Refere-se à capacidade de estender o comportamento de um módulo sem modificá-lo.
     5. **Um tipo deve poder ser substituído por qualquer um de seus subtipos, sem alterar o correto funcionamento do sistema.**
        - Este é o Princípio da Substituição de Liskov (Liskov Substitution Principle - LSP). Diz respeito à substituibilidade dos objetos de uma classe por objetos de suas subclasses sem afetar a integridade do programa.
     A terceira opção é a que mais especificamente aborda a intenção da Segregação de Interfaces, focando na ideia de que as interfaces devem ser específicas para os clientes que as utilizam, evitando impor métodos desnecessários aos clientes.

   ***

6. Modelos vêm ajudando cada vez mais as pessoas a desenvolverem suas ideias de forma gráfica e discutir facilmente com sua equipe e com os usuários.

   Avalie as assertivas I e II, a seguir.

   I. Uma realidade complexa exige maior número de perspectivas de análise do que um problema mais elementar.

   PORQUE

   II. Para entender a totalidade, precisamos enxergar o problema sob várias perspectivas.

   E assinale a alternativa correta.

   - A assertiva I é falsa e a assertiva II é verdadeira.
   - As assertivas I e II são verdadeiras e a assertiva II não justifica a I.
   - As assertivas I e II são falsas.
   - As assertivas I e II são verdadeiras e a assertiva II justifica a I. 👈🏽✅
   - A assertiva I é verdadeira e a assertiva II é falsa.

   ***

   - Resposta
     - **As assertivas I e II são verdadeiras e a assertiva II justifica a I.**
   - Comentário
     - I. Uma realidade complexa exige maior número de perspectivas de análise do que um problema mais elementar.
       - Esta afirmação é verdadeira. Problemas complexos geralmente envolvem várias facetas, e uma análise mais aprofundada pode exigir diferentes perspectivas para compreendê-los completamente.
     - II. Para entender a totalidade, precisamos enxergar o problema sob várias perspectivas.
       - Esta afirmação é verdadeira e justifica a afirmativa I. Para compreender completamente uma realidade complexa, é necessário considerar diversas perspectivas, já que uma única perspectiva pode não capturar todos os aspectos relevantes de um problema complexo.

   ***

7. Fonte: Adaptado de Prova: FUNDEP (Gestão de Concursos) - 2018 - INB - Analista de Sistemas

   Qual diagrama UML apresenta os dados armazenados em uma instância de uma classe e seus relacionamentos, como uma fotografia dos dados em determinado momento?

   - Diagrama de dados.
   - Diagrama de classes.
   - Diagrama de atividades
   - Diagrama de casos de uso.
   - Diagrama de objetos. 👈🏽✅

   ***

   - Resposta
     - **Diagrama de objetos.**
   - Comentário
     O Diagrama de Objetos no UML representa uma instância de uma classe em um determinado momento, mostrando os dados (atributos) e relacionamentos associados a essa instância específica. Ele é útil para visualizar o estado de objetos em um ponto específico no tempo durante a execução de um sistema.

   ***

8. Qual das afirmações abaixo não diz respeito à relação de associação no diagrama de classes?

   - As associações são os mecanismos que permitem aos objetos se comunicarem.
   - As associações podem ter uma regra que especifica o propósito da associação.
   - As associações podem ser unidirecionais ou bidirecionais.
   - As associações descrevem a conexão entre diferentes classes.
   - Numa associação, um valor de multiplicidade indica como os objetos se relacionam consigo mesmo. 👈🏽✅

   ***

   - Resposta
     **Numa associação, um valor de multiplicidade indica como os objetos se relacionam consigo mesmo.**
   - Comentário
     Na realidade, a multiplicidade em uma associação indica quantos objetos de uma classe estão associados a quantos objetos da outra classe. Não está relacionada a objetos se relacionando consigo mesmos. A multiplicidade é usada para especificar a quantidade de instâncias de uma classe que podem estar associadas a instâncias de outra classe por meio da associação.

   ***

9. (UFMT/2021 - Adaptada) A respeito do Unified Modeling Language (UML), analise as afirmativas.

   I- É uma linguagem para marcação de tags.

   II- Permite modelar elementos e relacionamentos.

   III- Auxilia no desenvolvimento de software.

   Está correto o que se afirma em:

   - I, II e III.
   - II e III, apenas. 👈🏽✅
   - I, apenas.
   - I e II, apenas.
   - I e III, apenas.

   ***

   - Resposta
     • **II e III, apenas.**
   - Comentário
     - I. **É uma linguagem para marcação de tags.**
       - Esta afirmação é incorreta. UML (Unified Modeling Language) não é uma linguagem de marcação de tags. É uma linguagem de modelagem gráfica usada para visualizar, especificar, construir e documentar sistemas de software.
     - II. **Permite modelar elementos e relacionamentos.**
       - Esta afirmação é correta. A UML permite a modelagem de elementos (como classes, objetos, casos de uso, etc.) e seus relacionamentos em um sistema.
     - III. **Auxilia no desenvolvimento de software.**
       - Esta afirmação é correta. A UML é amplamente utilizada na engenharia de software para ajudar no desenvolvimento, comunicação e documentação de sistemas complexos.

   ***

10. Assinale a opção que contenha o padrão GRASP que possui uma estrutura de solução similar ao padrão GoF Facade:

    - Alta Coesão
    - Criador
    - Polimorfismo
    - Controlador👈🏽✅
    - Baixo Acoplamento

    ***

    - Resposta
      - **Controlador**
    - Comentário
      O padrão GRASP chamado "Controlador" é semelhante ao padrão Facade, pois ambos envolvem a criação de uma interface única para simplificar o acesso a um conjunto de classes. No caso do padrão Controlador, essa interface única é responsável por lidar com as interações e coordenações entre diferentes objetos e subsistemas. Ele ajuda a manter o baixo acoplamento e a alta coesão, princípios fundamentais na orientação a objetos.

    ***
