# DIA 5 - TESTE DE SOFTWARE, MYERS E PARETO
## CONTEÚDO

* 1 - Como gerar qualidade nos projetos
* 2 - Myers
* 3 - Pareto

# Fundamentos do Teste de Software

## 1 - Como Gerar Qualidade

A atividade de testar engloba uma variedade de artefatos que, juntos, geram a qualidade do produto. Podemos citar:

- Requisitos atendidos
- Confiança
- Identificação de defeitos
- Tomadas de decisão
- Redução de riscos
- Conformidades contratuais e regulatórias

Gerar qualidade não é somente testar o software; nossa principal preocupação deve ser garantir que a solicitação do cliente está de fato sendo realizada pela aplicação!

## 2 - Teste Estático vs Dinâmico

### Estático

- Revisão, inspeção e análise estática dos artefatos
- Qualquer documento do projeto pode ser avaliado desta forma

### Dinâmico

- Necessita que o software seja executado
- É o mais utilizado pelo mercado
- O custo tende a ser mais alto

## 3 - Teste e Depuração

### Teste

Podem mostrar falhas causadas por defeitos de software.

### Depuração do Código

Atividade de desenvolvimento que localiza, analisa e corrige os defeitos.

### Teste de Confirmação

Verifica se as correções resolveram os defeitos.

**Observação:** O mais usual é que o testador foque nas atividades de ‘teste’ e ‘teste de confirmação’, enquanto o desenvolvedor fique com a responsabilidade de depurar o código.

## Eficiência x Eficácia

O desafio do tester é alcançar a eficácia e eficiência. O teste que encontra defeitos cria a oportunidade de melhorar a qualidade do produto.

## Teste = Qualidade?

O teste só aumenta a qualidade do software quando:

- Defeitos são encontrados e corrigidos
- Ocorre a verificação da conformidade dos requisitos funcionais
- Requisitos não-funcionais (confiabilidade, usabilidade, escalabilidade, etc.) são verificados
- Reduzimos drasticamente o retrabalho
- Reduzimos custos de manutenção e os chamados de suporte
- Obtemos um software bem estruturado que facilita novos projetos

## Erro, Defeito e Falha

### Erro (Error)

Ação humana que produz um resultado incorreto. Pode ser cometido em qualquer fase do desenvolvimento de software.

### Defeito (Defect)

Uma imperfeição ou deficiência em um produto de trabalho que faz com que ele não atenda seus requisitos ou especificações. É o resultado do erro cometido.

### Falha (Failure)

Um evento no qual um componente ou sistema executa uma função necessária além dos limites especificados.

- Um software pode conter defeitos e nunca falhar
- Falha é um evento
- Defeito é um estado do software causado por um erro
- Cuidado com falsos positivos: defeitos nos dados do teste podem indicar problemas que de fato não existem na aplicação
- Cuidado com falsos negativos: problemas nos testes que fazem com que ele não detecte o defeito que deveria ser detectado

## Os Sete Princípios de Testes

O teste precisa ter uma boa cobertura, passando confiança aos stakeholders, mas também precisa respeitar a estimativa alinhada.

1. **Teste Mostra Presença de Defeitos**

   Teste reduz a probabilidade de defeitos não descobertos permanecerem no software. Mesmo que não sejam encontrados defeitos, isso não é prova de que eles não existem.

2. **Testes Exaustivos São Impossíveis**

   Testes exaustivos são impossíveis, custam caro e tomam muito tempo.

3. **Teste Inicial Economiza Tempo e Dinheiro**

   Testes precisam iniciar o mais cedo possível no ciclo de vida do desenvolvimento. Quanto antes iniciarem as atividades de teste, maior a probabilidade de não ocorrerem propagações de falhas.

4. **Defeitos se Agrupam**

   Seguindo o princípio de Pareto, um pequeno número de módulos geralmente contém a maioria dos defeitos.

5. **Paradoxo do Pesticida**

   Os testes precisam ser regularmente atualizados, caso contrário, eles se tornam ineficazes, tal qual um pesticida aplicado numa praga que já evoluiu e não é mais afetada por seus efeitos.

## 6 - Testes Dependem do Contexto

O teste precisa ser realizado de forma diferente em diferentes domínios de aplicativos.

## 7 - Ausência de Erros é uma Ilusão

Independentemente de quantos defeitos foram encontrados e corrigidos, isso não significa necessariamente que os usuários estejam satisfeitos com o produto ou que ele atenderá ao seu propósito.

## Fatores Contextuais

Conhecimento que pode ser usado para análise e modelagem do teste:

### Exemplos

- Requisitos do projeto/produto
- Histórias de usuário
- Requisitos não funcionais
- Especificações funcionais e/ou técnicas
- Lista de navegadores que devem ser suportados
- Ambientes operacionais
- Dispositivos móveis

O tester deve estar atento a todos os aspectos do projeto.

## Atividades e Tarefas de Teste

### Planejamento do Teste

Definir os propósitos e a abordagem do teste, além da criação do plano de teste (cronograma, exceções, recursos necessários), definindo o escopo, métricas e o nível de detalhamento do teste.

### Análise do Teste

Condições de teste associadas à base de teste analisada no tópico anterior.

### Modelagem do Teste

Elaboração de casos de teste com base nas condições levantadas anteriormente. Estrutura de modelagem:

- Priorizar o conjunto de casos de teste
- Identificar os dados de teste (massa de dados)
- Projetar o ambiente de teste

### Implementação do Teste

Preparar os dados de teste e garantir que eles sejam carregados corretamente no ambiente de teste, criando scripts de testes automatizados e criando a suíte de testes. Isso inclui:

- Os procedimentos de teste e seu sequenciamento
- As suítes de teste
- Um cronograma de execução do teste

### Execução do Teste

Executar os testes de acordo com o cronograma de execução, desde a execução manual, com evidências e comparativo de resultados. Caso sejam identificados defeitos, comunicá-los e registrar o resultado da execução do teste.

### Conclusão do Teste

- Métricas consolidadas de encerramento dos testes
- Lançamento do software
- Verificar se todos os relatórios de defeitos estão fechados
- Analisar lições aprendidas
- Melhorar a maturidade dos processos
 