# 👩‍🔬 React TDD

<p align="center">
  Projeto com foco em desenvolver o frontend orientado a testes,
  utilizando o React Testing Library e o Jest 🃏
</p>

## 📦 Dependências

- **`ts-jest`:** um *transformer* do Jest para conseguirmos testar
aplicações escritas em TypeScript;

- **`jest` e `@types/jest`:** framework utilizado para realizar testes 
unitários e o pacote necessário para utilização do jest com typescript, 
respectivamente;

- **`jsdom` e `jest-environment-jsdom`:** de acordo com a documentação 
do `jsdom`, ele é uma implementação em JavaScript puro de muitos 
padrões da web, como os padrões WHATWG DOM e HTML, para uso com Node.js. 
Em geral, o objetivo do projeto é emular o suficiente de um subconjunto 
de um navegador da Web para ser útil para testar e extrair aplicativos 
da Web do mundo real.

  Logo, o `jest-environment-jsdom` serve para habilitarmos esse ambiente
para desenvolver os testes com o Jest;

Conjunto de ferramentas voltadas para testar os componentes React:

- **`@testing-library/react`:** fornece funções utilitárias leves em 
cima do `react-dom` e `react-dom/test-utils`, de uma forma que 
incentiva melhores práticas de teste;

- **`@testing-library/jest-dom`:** oferece jest *matchers* customizados
estendendo o jest para testar o estado da DOM, tornando os testes mais
declarativos e fáceis de ler e manter;

  > Os matchers em Jest são métodos como `.toBe()`, `.toBeTruthy()`,
  > entre outros. Mas quando instalamos esse pacote, temos acesso à
  > matchers relacionados à DOM, como `.toBeInTheDocument()`, 
  > `.toBeDisable()`, entre outros. Por isso se tornam fáceis de ler.

- **`@testing-library/user-event`:** busca simular os eventos reais que 
aconteceriam no navegador enquanto o usuário interage com ele. Por 
exemplo, `userEvent.click(checkbox)` alteraria o estado do checkbox;

- **`identity-obj-proxy`:** útil para testar importações triviais de 
webpack. Por exemplo, você pode dizer ao Jest para simular este objeto 
como módulos CSS importados, então todas as pesquisas de `className` 
no objeto de estilos importado serão retornadas como estão. 
  
  Resumindo, serve para, quando importarmos arquivos como imagens ou 
estilos em nosso código, não dê problema nos testes. E isso é feito 
através de mocks, ou seja, uma simulação desses arquivos.

### Referências

Ideia do projeto:
[[Alura] React: testando os seus componentes](https://cursos.alura.com.br/course/react-testando-componentes)

Para fazer o setup: 

➜ [[Medium] React Hero: TypeScript + Jest + React Testing Library setup](https://medium.com/tinyso/react-hero-typescript-jest-react-testing-library-setup-c2ecce18ec96)

➜ [[Youtube] Configurando Jest + React Testing Library no Vite #Dia23 ](https://www.youtube.com/watch?v=HLgY_Cmqe14)

Para mockar alguns hooks:
[[Medium] Mocking hooks for testing with jest and react-testing-library](https://chanonroy.medium.com/mocking-hooks-for-testing-with-jest-and-react-testing-library-d34505616d12)

<h4 align="center">🚧 Readme em construção 👷🏻‍♀️</h4>

<hr>

<p align="center">
  Feito com ❤️ por
  <a align="center" href="https://www.linkedin.com/in/ana-beatriz-nunes/">
    Ana Beatriz Nunes
  </a>
</p>