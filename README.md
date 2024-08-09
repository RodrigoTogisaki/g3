# g3
Projeto do grupo 3


#Pequena apresentação

##Relatório Pessoal de Rodrigo de Almeida

Junto aos membros, Gabriel Monteiro, Izadora e Eduardo, fomos responsáveis por planejar o projeto, contudo os responsáveis por tentar abstrair e tentar gerar UML´s que teriam por fim orientar o grupo, a atingir os passo a passo do projeto foi Rodrigo e Izadora, por meio de UML´s e a Izadora por criar principalmente a interface gráfica. Sendo assim, eu, Gabriel e Eduardo, fomos responsáveis por pensar no Back-end, desde as classes Interfaces, Abstratas e Concretas e por fim o Banco de Dados, em questão de banco de dados, fui responsável por fazer as exigências mínimas do que deveria ter ou não. Os mesmos também me ajudou a desenvolver algumas classes e consertar pequenos bugs e erros de compilação, a exemplo de uso classes diferentes aos usuais para ajudar a consertar problemas de implementação, de classe que apenas deveriam determinar tipos de climas e ambientes, assim como pequenos problemas como a falta ou de variáveis que tinham no contrato, mas que ao escrever os códigos esquecíamos devido o volume de classes e detalhes a serem lembrados para evitar alguns problemas acerca de compilação e sintaxe. E por fim, nesta última consideração em relação as participações das partes, eu, Izadora, Gabriel e Eduardo, fomos responsáveis por criar um controller para integrar ambas esferas, sendo o back-end e o Front-end.

# Relatório Pessoal do Projeto de MarketPlace de simulação de sistemas de geração fotovoltáica

## Seção 1 - Introdução

### Justificativa
A crescente demanda por fontes de energia renovável e sustentável tem impulsionado o desenvolvimento e a adoção de tecnologias de geração de energia solar fotovoltaica. No entanto, a aquisição e instalação de sistemas fotovoltaicos podem ser desafiadoras para consumidores devido à variedade de opções, custos envolvidos e a complexidade dos cálculos de retorno sobre o investimento. Para facilitar a disseminação dessa tecnologia e otimizar a experiência do usuário, é essencial criar uma plataforma que centralize e simplifique o processo de simulação, avaliação e comercialização de sistemas de geração fotovoltaica.

### Descrição do Problema
O principal problema que este projeto visa resolver é a falta de uma plataforma integrada onde consumidores possam simular, avaliar e adquirir sistemas de geração de energia solar fotovoltaica de maneira eficiente e informada. Atualmente, os consumidores enfrentam dificuldades em:
1. Entender o potencial de geração de energia solar de suas propriedades.
2. Comparar diferentes ofertas de sistemas fotovoltaicos de várias empresas.
3. Avaliar o custo-benefício de diferentes sistemas.
4. Obter cotações personalizadas e realizar simulações de retorno financeiro.
5. Orçamentos fáceis e rápido, para estimar possibilidade de instalação.

### Motivação
A motivação por trás deste projeto é a necessidade de empoderar consumidores com informações claras e precisas, permitindo uma tomada de decisão informada e consciente sobre a adoção de energia solar fotovoltaica. Além disso, o projeto visa:
1. Promover o uso de energia limpa e renovável.
2. Simplificar o processo de aquisição e instalação de sistemas fotovoltaicos.
3. Facilitar a conexão entre consumidores e fornecedores de soluções de energia solar.
4. Contribuir para a redução da pegada de carbono e o combate às mudanças climáticas.

### Tecnologias Utilizadas
- **Java**: Para a implementação da lógica de negócios e operações de CRUD.
- **BlueJ**: Ambiente de desenvolvimento integrado (IDE) usado para prototipagem e testes iniciais.
- **UML**: Para a modelagem e design do sistema. Por meio do plant.txt
- **GIT DESKTOP**: Usei este meio para criar algumas coisas necessárias no GitHub
- **VSCODE**: Este foi usado mais como teste e curiosidade no seu funcionamento

### Estrutura de Classes e Interações
O projeto será estruturado com base nas melhores práticas de programação orientada a objetos (OOP), incluindo o uso de classes abstratas, interfaces, e operações CRUD. As principais classes incluem:

- **Entity**: Classe abstrata base para todas as entidades com um identificador único.
- **User**: Representa um usuário do sistema, contendo informações como nome, email e senha.
- **Project**: Representa um projeto de instalação de painéis solares, incluindo área, nível de eficiência e tipo de ambiente.
- **Offer**: Representa uma oferta de sistema fotovoltaico de uma empresa, incluindo preço e nome da empresa.
- **Simulation**: Responsável por simular a produção de energia e os custos baseados nos dados do projeto.
- **DataProvider**: Classe responsável pelas operações de CRUD para `User`, `Project` e `Offer`.


![image](https://github.com/user-attachments/assets/5f97c42c-3251-484d-8231-484e0ea48a18)

###A implementação do código
