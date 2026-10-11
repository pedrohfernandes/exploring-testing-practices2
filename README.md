# Explorando Práticas de Teste

Neste exercício, vamos explorar práticas de teste em sistemas reais utilizando a ferramenta [TestMiner](https://andrehora.github.io/testminer).

O TestMiner permite visualizar e analisar testes de software em repositórios do GitHub, fornecendo dados sobre como os projetos organizam seus testes, como eles evoluem entre versões e quais bibliotecas de teste são utilizadas.
Explore a ferramenta antes de começar para se familiarizar com seu funcionamento.

Mais detalhes no GitHub da ferramenta: https://github.com/andrehora/testminer.

---

## Passo 1: Selecionar DOIS repositórios

Escolha dois repositórios reais que possuam testes de software.
Abaixo estão alguns links para ajudá-lo a encontrar projetos interessantes:

- Python: https://github.com/topics/python?l=python
- JavaScript: https://github.com/topics/javascript?l=javascript
- TypeScript: https://github.com/topics/typescript?l=typescript
- Java: https://github.com/topics/java?l=java

- Tópicos: [ai](https://andrehora.github.io/testminer/#topic:ai), [llm](https://andrehora.github.io/testminer/#topic:llm), [api](https://andrehora.github.io/testminer/#topic:api), [nodejs](https://andrehora.github.io/testminer/#topic:nodejs), [android](https://andrehora.github.io/testminer/#topic:android)

- Por organização: [Google](https://andrehora.github.io/testminer/#google), [Microsoft](https://andrehora.github.io/testminer/#microsoft), [Apple](https://andrehora.github.io/testminer/#apple), [Facebook](https://andrehora.github.io/testminer/#facebook), [Netflix](https://andrehora.github.io/testminer/#netflix),
  [GitHub](https://andrehora.github.io/testminer/#github), [Apache](https://andrehora.github.io/testminer/#apache), [HuggingFace](https://andrehora.github.io/testminer/#huggingface)

## Passo 2: Explorar os repositórios selecionados

Busque os repositórios escolhidos no [TestMiner](https://andrehora.github.io/testminer) e analise os dados de teste gerados pela ferramenta.

## Passo 3: Explicar as prática de teste

Para cada repositório, escolha uma prática ou dado de teste relevante e explique com suas próprias palavras.

---

## Instruções de entrega

1. Faça um `fork` deste repositório (saiba mais sobre forks [aqui](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)).
2. Responda às questões abaixo diretamente neste arquivo `README.md` do seu fork. Pode adicionar imagens para enriquecer sua explicação.
3. No Moodle, submeta apenas a URL do seu fork.

---

## Respostas

### Repositório 1

Repositório: `https://github.com/spring-projects/spring-boot`

URL TestMiner: `https://andrehora.github.io/testminer/#spring-projects/spring-boot`

Explicação: `O repositório apresenta uma prática de teste robusta, utilizando o framework JUnit para testes unitários e de integração. A análise do TestMiner mostra que há uma cobertura significativa de testes, com uma boa organização dos arquivos de teste em pacotes correspondentes aos módulos do projeto. Além disso, a evolução dos testes ao longo das versões indica um compromisso contínuo com a qualidade do software, refletindo a importância de manter os testes atualizados à medida que novas funcionalidades são adicionadas. É possível notar que a maioria dos arquivos do repositório correspondem a testes ou auxiliares de teste, o que demonstra a prioridade dada à confiabilidade do código. Uma prática a ser notada é que, historicamente, não havia a utilização de fixtures, e essas foram introduzidas em versões mais recentes para melhorar a eficiência dos testes.`

### Repositório 2

Repositório: `https://github.com/flutter/flutter`

URL TestMiner: `https://andrehora.github.io/testminer/#flutter/flutter`

Explicação: `Após a anaálise, vÊ-se que o framework Flutter utiliza uma abordagem de teste abrangente, incorporando testes unitários, de widget, de integração e, inclusive, E2E. O TestMiner revela que há uma grande quantidade de testes automatizados, o que é crucial para um framework que visa fornecer uma experiência consistente em múltiplas plataformas. A organização dos testes é clara, com diretórios específicos para diferentes tipos de testes, facilitando a manutenção e a expansão do conjunto de testes. Além disso, a evolução dos testes ao longo do tempo mostra um aumento na cobertura e na complexidade dos casos de teste, refletindo a maturidade do projeto e o compromisso com a qualidade do software. Uma prática interessante observada é o uso extensivo de mocks e stubs para isolar componentes durante os testes, garantindo que os testes sejam rápidos e confiáveis.`
