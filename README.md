# DesafioBackend Java TechSolutio

Primeiramente, obrigado pelo seu interesse em trabalhar conosco. Prezamos pelo desconhecido, pelo novo e sempre queremos agregar ao nosso time pessoas que nos ensinem alguma coisa, afinal, contratamos pessoas para melhorar nossos processos e não engessá-los.

- Orientações Gerais para você comerçar bem:
  - Crie um repositório no seu GitHub sem citar a TechSolutio.
  - Realize os commits do seu trabalho neste repositório criado;
  - Ao término, envie o link do seu repositório para o email informado nos contatos das entrevistas preliminares.
  - Fique à vontade para consultar o Google, Stackoverflow ou qualquer outra fonte de conhecimento, isso faz parte do nosso trabalho.
  - Leia com atenção todo o nosso material, ele tem pontos fundamentais para nossa avaliação.
  - Fique de olho na entrevista, por lá você poderá absorver dicas para alguns passos dentro do nosso processo.
  - Ah! Não fiquei na dúvida, pergunte tudo o que for preciso aos recrutadores, eles não são seu INIMIGO!

E prá gente terminar essas orientações, fique tranquilo, respire, faça uma pausa quando preciso. A gente por aqui já passou por isso, você vai tirar de LETRA! Boa sorte! :)

**TECHSOLUTIO Developer Team**

# Sobre a entrega
Envie por email as seguintes informações ao término do desafio, vamos lá:

- Seu Nome
- Link do repositório
- Link do Linkedin

# Ambiente da Aplicação
Foque nas suas habilidades, escolha o framework mais latente ao seu conhecimento. Queremos avaliar seu conhecimento em JAVA, esse teste não foca em FRAMEWORK, mas na sua maturidade na linguagem JAVA. Decida por algo que esteja e seja mais seguro dentro do seu conhecimento. Queremos que você fale com o máximo de segurança em nossa devolutiva.

Caso deseje, você pode optar por não usar FRAMEWORK nenhum. Para casos como este, realize a implementaçào via script, assim reduziremos a necessidade de criar um servidor.

Se optar pelo uso de um FRAMEWORK, evite os métodos **MÁGICOS** ou mecanismos já prontos. É claro que isso ajuda muito no dia-dia e garante uma boa produtividade, mas aqui, queremos ver sua maneira de resolver problemas e ver você **CODANDO**.

Pense em containers, a gente gosta bastante disse e valorizamos uma boa estrutura.

# Preparo para o dia da Entrevista / Code Review

No dia agendado, a aplicação deve estar pronta em execução na sua máquina. Será a oportunidade de nos apresentar o seu desenvolvimento e responder os questionamentos que possivelmente realizaremos. Será um **CODE REVIEW**, como se você já estivesse integrado ao nosso time ❤️. Você explicará prá gente como pensou, planejou e executou seu projeto. Ah! Lembre-se de trazer pontos de melhorias futuras, a gente gosta disso!

# Desafio Produtos

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc fringilla in orci nec pretium. Nam et purus velit. Vestibulum finibus, mauris nec hendrerit varius, nisl lorem tempor dui, eu molestie ligula dui vitae lectus. Nam et purus est. Cras ut metus nec tellus faucibus fermentum. In convallis purus et lacus porta feugiat. Cras orci urna, elementum ut lorem at, facilisis pharetra nibh. Ut pharetra rutrum erat, non dignissim ante vehicula in. Cras sagittis turpis at diam imperdiet, et cursus arcu porttitor. Curabitur lacinia lacus nibh. Mauris ultricies ante fermentum metus dignissim luctus.

- Este serviço deve ser uma API RestFULL.

### Payload

Monte seu payload próprio, pense simples, abaixo um exemplo de simplicidade:

```
{
  "sender": 12,
  "receiver": 25,
  "value": 100.0,
  "message": "YES, I can do it!"
}
```

# Avaliação

- Mostra sua entrega utilizando o framework que você desejar, mas fundamente sua escolha, justifique a esclha. 
- Cumpra todos os requisitos ou a maioria deles. Caso os cumpra parcialmente, a gente discutirá contigo porque faltou, traga suas dores e queixas, isso nos ajuda a melhorar sempre.

Nossa avaliação será composta por 3 etapas, sendo elas:
- Entrevista.
- Desafio Técnico.
- Code Review do Desafio.

Para o desafio, temos 2 etapas, sendo:
- Correção objetiva através do script de correção automática, esse você roda na sua máquina mesmo ou usando outra ferramenta:
  
```
docker run -it --rm -v $(pwd):/project -w /project jakzal/phpqa phpmd app text cleancode,codesize,controversial,design,naming,unusedcode
```

- CodeReview, oportunidade a qual bateremos um papo leve e você terá oportunidade de explicar seu código, veja quais serão os critérios: 
  - Aplicação de argumentos para tratativas de segurança.
  - Aplicação de Padrões (SOLID, PSR, etc).
  - Apresentar domínio sobre as escolhas.
  - Código documentado.
  - Código limpo, organização (Clean Code).
  - Desacoplamento de Componentes (Service, Repository, etc).
  - Manutenção de Código.
  - Modelagem de Dados.
  - Saber defendar suas escolhas para o desafio.
  - Tratamento de Erros.

 
## O que não avaliaremos
- Fluxos adotados para resolver o problema, afinal, há mais de um caminho para chegarmos no objetivo.
- Design UX/UI.

## No que você pode se destacar
- Documentação.
- Propostas de evolução e melhorias futuras.
- Simplicidade em resolver problemas.
- Testes (unitários e de integração).
- Uso de DOCKER.

## Links Úteis
Padrões [Porque usar Padrões]([https://pages.github.com/](https://hub.packtpub.com/why-we-need-design-patterns/)https://hub.packtpub.com/why-we-need-design-patterns/).
