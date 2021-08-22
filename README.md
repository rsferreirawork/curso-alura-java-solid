# curso-alura-java-solid

Este repositório diz respeito ao "Curso de SOLID com Java: Princípios da programação orientada a objetos" na plataforma Alura.

-> [Curso](https://cursos.alura.com.br/course/solid-orientacao-objetos-java)

## Proposta

Faça esse curso de Boas práticas em Java e:
- Aprenda conceitos avançados de orientação a objetos
- Escreva código coeso com Single Responsibility Principle
- Saiba como lidar com acoplamento
- Entenda a fundo os ganhos do encapsulamento
- Domine os princípios de código sólido
- Veja técnicas e exemplos em Java

## Ementa
- Orientação a Objetos Ver primeiro vídeo
	- Apresentação
	- Projeto inicial do treinamento
	- Coesão
	- Classes coesas
	- Encapsulamento
	- Protegendo o código
	- Acoplamento
	- Dependências no código
	- Faça como eu fiz
	- O que aprendemos?
- Melhorando a coesão
	- Extraindo a lógica de reajuste salarial
	- Extraindo classe
	- Single Responsibility Principle
	- Definição de SRP
	- Faça como eu fiz
	- O que aprendemos?
- Reduzindo o acoplamento
	- Projeto da aula anterior
	- Extraindo validações
	- Muitas validações
	- Open Closed Principle
	- Garantindo que o sistema seja extensível
	- Faça como eu fiz
	- O que aprendemos?
- Herança indesejada
	- Projeto da aula anterior
	- Implementando uma nova regra de negócio
	- Utilizando herança da maneira errada
	- Herança
	- Liskov Substitution Principle
	- Alternativa à herança
	- Faça como eu fiz
	- O que aprendemos?
- Trabalhando com abstrações
	- Projeto da aula anterior
	- Criando abstrações com interfaces e polimorfismo
	- Dependency Inversion Principle
	- Vantagem ao criar dependências com interfaces
	- Interface Segregation Principle
	- Definição do ISP
	- Faça como eu fiz
	- Projeto final do curso
	
## Aprendizado

- Coesão:
	- Uma classe coesa faz bem uma única coisa
	- Classes coesas não devem ter várias responsabilidades
- Encapsulamento:
	- Getters e setters não são formas eficientes de aplicar encapsulamento
	- É interessante fornecer acesso apenas ao que é necessário em nossas classes
	- O encapsulamento torna o uso das nossas classes mais fácil e intuitivo
- Acoplamento:
	- Acoplamento é a dependência entre classes
	- Acoplamento nem sempre é ruim, e que é impossível criar um sistema sem nenhum acoplamento
	- Devemos controlar o nível de acoplamento na nossa aplicação (falaremos mais sobre isso)


- Que classes/métodos/funções/módulos devem ter uma única responsabilidade bem definida;
- Que, segundo o Princípio de Responsabilidade Única (SRP), uma classe deve ter um e apenas um motivo para ser alterada;
- Como realizar uma refatoração no nosso sistema, para aplicar o SRP;
- Como extrair uma classe.

- Que cada classe deve conhecer e ser responsável por suas próprias regras de negócio;
- Que o princípio Aberto/Fechado (OCP) diz que um sistema deve ser aberto para a extensão, mas fechado para a modificação
- Isso significa que devemos poder criar novas funcionalidades e estender o sistema sem precisar modificar muitas classes já existentes
- Uma classe que tende a crescer "para sempre" é uma forte candidata a sofrer alguma espécie de refatoração.

- Que, embora a herança favoreça o reaproveitamento de código, ela pode trazer efeitos colaterais quando não utilizada da maneira correta;
- Que o Princípio de Substituição de Liskov (LSP) diz que devemos poder substituir classes base por suas classes derivadas em qualquer lugar, sem problema.

- Que é mais interessante e mais seguro para o nosso código depender de interfaces (classes abstratas, assinaturas de métodos e interfaces em si) do que das implementações de uma classe;
- Que as interfaces são menos propensas a sofrer mudanças enquanto implementações podem mudar a qualquer momento;
- Que o Princípio de Inversão de Dependência (DIP) diz que implementações devem depender de abstrações e abstrações não devem depender de implementações;
- Que as interfaces devem definir apenas os métodos que fazem sentido para seu contexto;
- Que o Princípio de Segregação de Interfaces (ISP) diz que uma classe não deve ser obrigada a implementar um método que ela não precisa;
- Os conceitos aprendidos neste treinamento formam o acrônimo SOLID
	- **S**ingle Responsibility Principle
	- **O**pen Closed Principle
	- **L**iskov Substitution Principle
	- **I**nterface Segregation Principle
	- **D**ependency Inversion Principle

## Conclusão

É um curso rápido e pratico que pode até ser feito em um dia, porém traz um aprendizado significativo e diferencial sobre o processo de construção de software.
