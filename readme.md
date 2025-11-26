# Projeto-Integrador-Front-end

Link do site: http://127.0.0.1:5500/Trabalho%20front/index.html

#  Delícias da Dona Ju

##  Integrantes e Papéis
- **Herbert Vinicius Daris Silva**
- **João Victor**

---

##  Tema, Objetivo e Público-Alvo

**Tema:** Restaurante "Delícias da Dona Ju"  
**Objetivo:** Criar um site simples e funcional que apresente o restaurante, seus produtos e permita o crescimento proporcional do site e restaurante, alcançando não só um publico local 
**Público-alvo:** Pessoas de todas as idades que apreciam uma boa comida, com foco em famílias e grupos que valorizam um ambiente acolhedor.  

###  Justificativa
Pensamos em um negocio real, no qual eu (Herbert Vinicius) costumo ir, e ao ver o objetivo do trabalho pensei em criar um site, pois antes nao tinha

---

##  Protótipo no Figma
 [Acesse o protótipo detalhado no Figma](https://www.figma.com/site/XluG87OjRHG91KJewPpAUV/Sem-t%C3%ADtulo?node-id=0-1&p=f&t=BlLrYyRnZwemwkCW-0)

---

##  Estrutura de Pastas e Arquivos

```
site/
│
├── index.html        
├── sobre.html        
├── contato.html      
├── style.css         
└── imagens/          
    ├── logo.png
    ├── carnes.jpg
    ├── aperitivos.jpg
    └── bebida.jpg
```

---
##  Justificativas de Design

###  **Cores**
- **#836767 (Fundo principal):** Transmite aconchego e elegância, lembrando ambientes de madeira e restaurantes artesanais.  
- **#524141 (header, footer, cards):** Inspira calor e apetite, remetendo à cor de alimentos grelhados e molhos.  
- **#f8f8f8 (Texto):** Contraste suave com o fundo, mantendo boa legibilidade.

###  **Fontes**
- **Merienda One:** Escolhida por seu estilo cursivo leve e acolhedor, transmitindo uma identidade artesanal e próxima do cliente.  

###  **Ícones e Imagens**
- Ícones de redes sociais e imagens de produtos foram escolhidos com base na identidade visual do restaurante.  
- As imagens seguem tons quentes e iluminação natural para reforçar a ideia de comida caseira e saborosa.

###  **Layout**
- Estrutura baseada em blocos simples (`header`, `main`, `footer`) para reforçar a clareza do conteúdo.  
- Menu de navegação fixo e centralizado, facilitando a navegação entre as páginas.  
- Cards de produtos alinhados horizontalmente para destacar as categorias principais (Carnes, Aperitivos e Bebidas).

---

 **Versão do documento:** 1.0  
 **Última atualização:** 14/10/2025  


#  Projeto Integrador Parte 2:

1. 
- Os botões no geral estão funcionando bem, alguns ja levam para outras paginas e outros levam para uma pagina que não existe, pois não foi implementada ainda no código.
- A logo e alguns botões no header que leva para outras paginas.
- no meio das paginas, onde fica uns espaços estranhos entre os elementos, de resto ao meu ver está tranquilo.
- Acredito que a implementação de novas interações na pagina, algo que de a impressão de movimento, talvez alguns componentes em JavaScript.

2. 

2.1
- Sim, o header é praticamente igual em todas as páginas, mudando só o nome das outras paginas.
- De certa forma, semelhantemente ao header.
- Sim, todas as páginas possuem um footer.
- Varios cards com estruturas parecidas, mas nenhum igual.
- A estrutura de contato é baseada em outras estruturas de fora do site, mas dentro do site não tem uma igual.

2.2 
Projeto/
├── index.html
├── sobre.html
├── contato.html
├── componentes/
│   ├── header.html
│   ├── nav.html
│   ├── footer.html
├── css/
│   ├── style.css
│   ├── responsive.css
├── js/
│   └── componentes.js
├── img/
└── README.md

3. 

Ainda não tivemos nenhuma interação com JavaScript, apenas na fase 2.3 do projeto. Apesar de ter o arquivo em JavaScript, nós não conseguimos implementar ele dentro do código html.

4. 

4.1
Verifiquem e implementem os seguintes recursos:

**HTML Semântico:**

- [X]  Usam tags semânticas (**`<header>`**, **`<nav>`**, **`<main>`**, **`<section>`**, **`<article>`**, **`<footer>`**)? <!-- Só não possui <article> -->
- [X]  Cada página tem apenas um **`<h1>`** (título principal)?
- [X]  Os títulos seguem hierarquia lógica (h1 → h2 → h3)? <!-- Só há diferenciação na pagina principal -->

**Imagens e Multimídia:**

- [X]  Todas as imagens têm atributo **`alt`** com descrição clara?
- [X]  Imagens decorativas têm **`alt=""`** (vazio)?

**Formulários:**

- [X]  Todos os campos têm **`<label>`** associado via atributo **`for`**?
- [ ]  Campos obrigatórios estão marcados (atributo **`required`** ou indicação visual)? (mas possui mensagens de erro caso seja escrito "errado")
- [X]  Placeholders não substituem labels?

**Navegação por Teclado:**

- [X]  Todos os links e botões são acessíveis via Tab?
- [X]  O foco está visível (estilo **`:focus`** no CSS)?
- [ ]  Há um skip link ("Pular para o conteúdo principal")?

**Contraste e Legibilidade:**

- [ ]  Texto e fundo têm contraste adequado (mínimo 4.5:1)?
- [X]  Tamanho de fonte é legível (mínimo 16px para texto corrido)?

4.2
Segundo o lighthouse, de performance geral saiu uma nota de 81 na media. Ja contando a acessibilidade deu uma nota geral de 88, sendo considerado uma boa média para o inicio do site.

5. 

5.1
No geral, ao mudar os pixels baseando-se nas diferentes formas de acesso ao site, sendo mobile, tablet e desktop, com isso todos os elementos do site se adaptam da maneira correta e continuam visiveis ao publico alvo que acessa o site. A unica "falha" que acontece no site é o espaçamento lateral de alguns textos, que ficam muito próximos do limite da tela, mas sem afetar muito a leitura.

5.2 ☑️

6. ☑️

7. ☑️

8. 

Como não possui a rubrica, vou avaliar os quesitos baseados com o que está no Note:

Interatividade: 08/10 -> O site está bem interativo com bastante opções de clique e imagens que levam o usuario a tomar suas decisoes, mas meu pensamento está em sites um pouco maiores, por isso a decisão
Acessibilidade: 08/10 -> Segundo o lighthouse a acessibilidade do site está quase perfeita, tendo alguns pequenos erros so na parte da diferenciação de cores do fundo da pagina para outros elementos da propria
Responsividade: 07/10 -> Ao meu ver o site está na média de responsividade, faltando pequenos quesitos para melhorar, que serão adicionados ou modificados no futuro
Modularidade: 06/10 -> A modularidade dentro do vs code e nos codigos do tipo não estão muito boas, pois apos mudar alguns elementos de pasta tive dificuldade de fazer a religação deles dentro do projeto principal. Mas a modularidade dentro do git está boa.
Design: 04/10 -> Aqui está a parte em que eu mais falhei, pois imaginei um site de restaurante de uma forma e acabei representando de outra, deixando assim o design meio "estranho".

9. ## Revisão Final e Testes

Antes de considerar esta etapa concluída:

- [X]  Todos os componentes estão modularizados e funcionando?
- [X]  O site é totalmente responsivo em mobile, tablet e desktop?
- [X]  Checklist de acessibilidade completo?
- [X]  Pelo menos uma integração externa implementada?
- [X]  README.md atualizado com todas as informações?
- [X]  Rubrica de autoavaliação preenchida com justificativas?
- [X]  Código limpo, organizado e comentado onde necessário?
- [X]  Testado em diferentes navegadores (Chrome, Firefox, Safari)?
- [X]  Console do navegador (F12) sem erros críticos?

Tudo correto, apenas com algumas "virgulas" em acessibilidade

#  Projeto Integrador Parte 3:

2.3 -

Acesso ao site:

https://herbert-vinicius.github.io/Projeto-Integrador-Front-end/index.html
https://github.com/Herbert-Vinicius/Projeto-Integrador-Front-end/blob/main/readme.md

<img src="img/Captura de tela 2025-11-25 220423.png" alt="">

3.3 -

Adicionamos e modificamos a ligação do css com o site, sendo essa mudança a partir da minimização do css proposta pelo site.
Além disso implementamos as funções no head, dentre elas a de adicionar um "favicon" na guia da pagina.

4.1 - 

**Para cada navegador, verifiquem:**

- [X]  O layout está correto?
- [X]  Todas as páginas carregam?
- [X]  Imagens aparecem?
- [X]  CSS está aplicado corretamente? (deu falta em um unico botao)
- [ ]  JavaScript funciona (se houver)?
- [X]  Formulários estão funcionais?
- [X]  Menu e navegação funcionam?

4.2 - 

**Para cada tamanho:**

- [ ]  Layout se adapta corretamente?
- [X]  Textos estão legíveis?
- [ ]  Imagens redimensionam bem?
- [X]  Menu funciona (hamburguer no mobile)?
- [ ]  Espaçamentos são adequados?
- [ ]  Nada quebra ou fica cortado?

4.3

**Verifiquem:**

- Touch funciona bem em botões e links? Sim, está funcionando corretamente
- Carregamento é rápido? Algumas partes sim, outras demoram um segundo a mais
- Experiência é boa em conexão 3G/4G? Sim, normalmente

4.4

- Lista de navegadores testados;
_Opera Gx
_Chrome
_Microsoft Edge

- Lista de dispositivos/resoluções testadas;
_Samsung s24 fe
_todas resoluções foram testadas

- Problemas encontrados e como foram resolvidos;
_redimensionamentos não estavam feitos corretamente

- Limitações conhecidas (se houver);
_ em resoluções muito menores o site não se adapta corretamente

- Links para as pastas com prints de evidências.
_Estão no repositório

6.1 -

Herbert: **Aprendizados Técnicos:**

- Quais foram as principais habilidades técnicas que você desenvolveu? (HTML, CSS, Git, organização, etc.)
    Aprendi a criar codigos e foi minha primeira impressao com essas linguagens de programação, tive bastante dificuldade em muitas partes pois em muitas delas tive pouco tempo para trabalhar com, mas consegui.

- Qual foi a tecnologia ou conceito mais desafiador de aprender?
    Encaixar o css no html
- O que você domina melhor agora comparado ao início do projeto?
    Tudo no geral, pois eu nao sabia de nada e era leigo no quesito de front end

**Aprendizados de Processo:**

- Como foi trabalhar em dupla? Quais foram os desafios?
    No começo foi um pouco complicado por causa da falta de conhecimento, mas com o tempo tudo foi conversado e dividido as tarefas
- Como vocês organizaram as tarefas e a comunicação?
    Primeiro observamos as soft skills de cada um e direcionamos as tarefas a partir disso
- O que funcionou bem na metodologia da dupla?
    trabalho em equipe e boa divisao de funções

**Desafios Enfrentados:**

- Qual foi o maior desafio do projeto?
    Ligar todos os pontos e trabalhar pela primeira vez com o git
- Como vocês superaram?
    Estudando muito sobre tais quesitos para o funcionamento do site
- Se pudesse voltar no tempo, o que faria diferente?
    mudaria talvez o tema do site e as cores nele presentes

6.2 -

**Evolução do Projeto:**

- Como o projeto evoluiu da Parte 1 até agora?
    evoluiu bastante, na primeira parte tinha pouco dos elementos que há agora
- Quais foram as maiores mudanças/melhorias?
    Elas foram mais visuais, com a adição de novos elementos com o processo
- O resultado final atende à proposta inicial?
    Não totalmente, queriamos implementar um pouco de Java mas encontramos muita dificuldade com ele.

**Feedbacks Recebidos:**

- O que vocês aprenderam com a avaliação dos colegas?
    De que realmente houve falhas em quesitos que ja haviamos presenciado dificuldade antes, mas tambem tivemos bons feedbacks
- Quais feedbacks foram mais úteis?
    Em relação a falta de componentes ao todo no site
- Como pretendem aplicar essas sugestões?
    Quando ficar com um tempo mais tranquilo iremos trabalhar nessas mudanças, não só para a matéria, mas para um pensamento futuro

**Relevância para o Negócio:**

- O site realmente agregaria valor ao pequeno negócio escolhido?
    Sim, acredito que não inicialmente, mas com mais um tempo de dedicação ao código e criação de outras páginas pode funcionar
- Se pudessem apresentar para o dono do negócio, o que diriam?
    Que esse seria um prototipo inicial da pagina pensada, e que ja possui algumas funções iniciais, ai pediriamos uma avaliação dele
- Vocês usariam este projeto como portfólio? Por quê?
    Sim, pois apesar de ser simples, mostra um pouco do nosso aprendizado da disciplina e mostra uma evolução

6.3 - 

**Melhorias Técnicas Planejadas:**

- [ ]  Adicionar funcionalidade X
- [ ]  Melhorar acessibilidade em Y
- [ ]  Implementar Z com JavaScript
- [ ]  Aprender framework React/Vue para próxima iteração

**Conhecimentos a Aprofundar:**

Liste 3-5 áreas/tecnologias que vocês querem estudar mais:

- Exemplo: "Aprofundar em acessibilidade WCAG"
- Exemplo: "Estudar animações CSS avançadas"
- Exemplo: "Aprender manipulação de APIs"

- Aprender a programar com JavaScript
- Não sentir dificuldade em implementar no git, dominando esse quesito
- Ligar o css ao java com uma boa facilidade

**Aplicação em Disciplinas Futuras:**

Como vocês vão usar este aprendizado em próximos projetos ou disciplinas?

Os conhecimentos adquiridos serão de suma importancia pois alem de aprender a programar em novas linguagens, tambem aprendemos a mexer com a responsividade e entender muitas vezes a visao do cliente ao abrir nossa pagina.

7.1 -

Verifiquem se o README.md contém todas as seções:

- [X]  Título e descrição do projeto
- [X]  Integrantes e papéis
- [X]  Link para wireframe Figma
- [X]  Link do GitHub Pages
- [X]  Tecnologias utilizadas
- [X]  Estrutura de pastas explicada
- [X]  Resumo das três partes do projeto
- [X]  Otimizações realizadas
- [X]  Testes documentados (navegadores, dispositivos)
- [X]  Reflexões individuais e da dupla
- [X]  Plano de melhorias futuras
- [X]  Créditos (fontes, ícones, imagens de terceiros) (imagens não são todas, apenas algumas especificas, outras foram geradas e/ou copiadas de sites distintos, retirando assim os produtos diretamente de um "site" que avalia e indica o restaurante "Dona Ju")

7.4 - 

- [X]  Site publicado no GitHub Pages e funcionando perfeitamente
- [X]  Todas as páginas acessíveis e sem erros
- [X]  Otimizações de performance aplicadas
- [X]  Testes em múltiplos navegadores documentados
- [X]  Testes de responsividade documentados
- [X]  Dois projetos de colegas avaliados com rubrica
- [ ]  Feedbacks recebidos de duas duplas
- [X]  Reflexões individuais e coletivas escritas
- [X]  README.md completo e profissional
- [X]  Pasta **`docs/`** organizada com evidências
- [X]  Código limpo, comentado e organizado
- [X]  Todos os commits com mensagens descritivas
