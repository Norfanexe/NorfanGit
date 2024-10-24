# DIA 3 & 4 - TESTE DE SOFTWARE

## CONTEÚDO

* 1 - Fundamentos em Testes de software e QA
* 2 - Testes baseados em IEC/ISO 25010

# 1 - Fundamentos em testes de software e QA

## Por que o próprio Dev não testa?

Certos defeitos, apenas o Dev encontra, outros podem exigir apoio de demais pessoas.Todo mundo pode testar (PO, Scrum Master, Agile Coach, Cliente, Usuário, Analista etc).

## Habilidades Pessoais do Testador/QA (Soft Skills)

### Habilidades Pessoais

- Motivação
- Persistência
- Curiosidade (Como funciona, Como faz e Como aprende)
- Gostar de aprender
- Perfeccionismo
- Detalhista
- Resiliência (Lidar com mudanças frequentes)
- Foco em solução
- Organização (Informações, Canais, Arquivos, Tarefas e Tempo)
- Priorização (O que fazer, Quando e Quem sabe fazer e Ritmo)
- Autogerenciamento

### Habilidades Interpessoais

- Comunicação (Ouvir, Falar, Postura, Ler, Escrever, Desenhar, Interpretar e Não ser um Portador de Má Notícia)
- Negociação
- Empatia
- Trabalho em equipe
- Cultura de qualidade
- Prevenir defeitos
- Sem pessimismo profissional

## Hard Skills

### Gerais

- Sistemas Operacionais (Windows, Linux, Mainframes, Mobile)
- Pacote Office (Word, Excel e PowerPoint)
- E-mail
- Mensagens Instantâneas
- Idiomas
- Internet
- Acesso Remoto
- Reuniões (Videochamada)
- Segurança (Privacidade, Fragilidade e Vulnerabilidades)

### Conhecimento de Negócio

- Tipo de Cliente (Banco, Seguradora, Comércio, Indústria)
- Padrões (Normas, Modelos, Avaliações e Certificações)
- Legislações
- Usos e Costumes
- Regras (Explícitas e Implícitas)
- Estudo de Concorrentes (Diretos e Indiretos)
- Uso Real do Software

### Tecnologia

- Programação (Lógica e Linguagem)
- Telecomunicações (Protocolos, Meios e Redes)
- Infraestrutura (Virtualização, Servidores, Indicadores, Equipamentos e Componentes)
- Banco de Dados (Relacionais e Não Relacionais)

### Teste e QA

- Planejar
- Analisar
- Modelar
- Implementar / Preparar
- Executar (Manual, Automatizada)
- Comunicação e Acompanhamento de Defeitos (Como Reproduzir Defeito e Como Encontrar de Novo o Bug)
- Evidências (Prints, Vídeos e Logs)
- Acompanhamento de Defeitos (Teste de Confirmação e Teste de Regressão)
- Técnicas de Teste (Quantos Testes no Cenário e Quais Testes são Mais Relevantes)
- Práticas
- Processos (Abordagens)
- Estratégias
- Ferramentas

# 2 - Testes baseados em IEC/ISO 25010

## Características de Testes IEC/ISO: 25010
Os métodos de teste a seguir serão embasados em dois modelos: Testes de negócio (funcional) e testes técnicos (não funcionais).

## Testes de Negócios (Teste Funcional)

### AF (Adequação Funcional)

De forma geral, a adequação funcional garante que o software está funcional para o uso final do cliente, atendendo às expectativas solicitadas para o projeto. É dividida em três principais categorias:

1. **Completude (funcional)**: Garantir que os comandos e ações programadas para o sistema realmente estão ocorrendo de forma correta e ideal.

2. **Correção (funcional)**: Garantir que o resultado está correto.

3. **Apropriação (funcional)**: Verificar se o resultado apresentado é apropriado para o sistema criado e o contexto atribuído a ele.

## Testes Técnicos (Não Funcionais)

### U (Usabilidade)

Define se o programa está apto para uso e se suas funções são práticas para o usuário final utilizar sem dificuldades. Os critérios de usabilidade incluem:

1. **Reconhecibilidade**: Facilitar que o usuário reconheça elementos e comportamentos no sistema desenvolvido.

2. **Aprendizibilidade**: Facilitar o aprendizado do usuário, incluindo FAQs e wizards para facilitar a navegação no sistema.

3. **Operabilidade**: Facilitar a operação e navegação, utilizando sessões e recursos do sistema que sejam rápidos, práticos e funcionais.

4. **Proteção contra erro ao usuário**: Garantir que o software não tenha opções que induzam ou façam ações incorretas de forma não voluntária.

5. **Estética (Interface x usuário)**: Garantir que a página do sistema seja prática e apresentável ao usuário final, garantindo uma percepção rápida e prática.

6. **Acessibilidade**: Garantir facilidade de acesso à ferramenta para todos, independentemente do contexto de conhecimento e dificuldades motoras gerais.

### C (Compatibilidade)

Verifica se o software possui compatibilidade com outros softwares, tanto na parte de coexistência sem gerar interferências quanto na interoperabilidade, facilitando a comunicação do software com outros recursos ao seu redor.

### C (Confiança)

Garante que o software estará sempre disponível para uso, com ou sem bugs, que sejam resolvidos rapidamente para manter a ferramenta operando. A confiabilidade é garantida por:

- **Maturidade**: Perceber e prevenir falhas antes que aconteçam.

- **Disponibilidade**: Manter a ferramenta à disposição dos usuários e sistemas.

- **Tolerância a falhas**: Garantir a percepção e solução para compensar falhas em tempo real.

- **Recuperabilidade**: Recuperar de falhas e travamentos de forma eficiente e rápida.

### E (Eficiência no Desempenho)

A velocidade de entrega e devolutiva de informações dentro da ferramenta é fundamental para propor dinamismo e evitar a perda de clientes devido a lentidões e travamentos. A avaliação pode ocorrer em relação ao tempo de resposta de uma ação, aos recursos consumidos e à capacidade da ferramenta em eventos de grande demanda.