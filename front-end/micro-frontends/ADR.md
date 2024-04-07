## Contexto e Declaração do Problema:
Esta aplicação faz scan de carne e fornecer informações detalhadas sobre preços e
benefícios nutricionais. Há uma secção dedicada a notícias relacionadas. Com esta aplicação é também possivel selecionar 
o nosso supermercado mais perto de casa ou supermercado favorito e verificar quais as carnes disponiveis e os seus preços.
Para garantir eficiência e facilidade de manutenção, é necessãrio evitar a complexidade no sistema em construção.

## Drivers da Decisão:
Dividir o sistema em blocos lógicos, em que cada um corresponde a uma e apenas uma responsabilidade, de modo a garantir 
a capacidade de alterar partes específicas sem afetar o resto do sistema são fatores fundamentais para promover a 
escalabilidade e a manutenção do sistema.
Cada equipa autonoma terá como responsabilidade a realização e manutenção de cada um destes blocos.

## Opções Consideradas:

Layers: Organizar o sistema em camadas distintas, como UI, lógica de negócios e armazenamento de dados.
Components: Dividir o sistema em componentes independentes, cada um responsável por uma funcionalidade específica.
Workflow: Estruturar o sistema com base em fluxos de trabalho ou processos específicos.

## Resultado da Decisão:
Decidimos dividir a aplicação em componentes independentes, pois esta abordagem permite uma modularidade mais granular 
e coesão entre os diferentes aspectos da aplicação. 
Cada componente será responsável por uma funcionalidade específica, facilitando a manutenção e o desenvolvimento futuro.

## Consequências:

Positivas:
Simplicidade no sistema, no que toca a realização de testes, manutenção, etc.
Maior granularidade e coesão, o que facilita a compreensão e a manutenção do código.
Os componentes podem ser reutilizados em diferentes partes da aplicação, promovendo a eficiência no desenvolvimento.
Negativas:
Pode haver um aumento na complexidade inicial devido à necessidade de definir e gerenciar interfaces claras entre os componentes.
Requer uma abordagem cuidadosa para garantir que os componentes sejam adequadamente isolados e não introduzam dependências excessivas entre si.


## Mais Informações:
O sistema será dividido em vários componentes independentes,
cada um responsável por uma funcionalidade específica, como a logica da aplicação, as noticias, e o login. 
Essa abordagem proporcionará uma base sólida para o desenvolvimento da aplicação, garantindo sua escalabilidade, 
manutenção facilitada e adaptabilidade a futuras mudanças no sistema.
