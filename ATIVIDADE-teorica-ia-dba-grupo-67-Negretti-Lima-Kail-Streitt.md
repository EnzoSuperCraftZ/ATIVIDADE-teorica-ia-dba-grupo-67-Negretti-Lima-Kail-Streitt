# Atividade Teórica: Usuários Especialistas, IA e Distribuição Segura de Dados

**Aluno(s):** Caio Negretti Honorato, Eduardo Guimarães Lima, Enzo Kail Vizalli, Pedro Streitt 
**Turma:** Banco de Dados 2026
**Data:** 16/08/2026
**Repositório Git:** https://github.com/usuario/atividade-bd

## Resumo Executivo

Breve descrição do tema e da posição adotada pelo grupo.

## 1. Desenvolvimento Teórico

### 1.1 O que é o DBA e quais suas funções?
DBA, ou Database Administrator (Administrador de Banco de Dados), é o profissional com a função de gerenciar, instalar, configurar, proteger e manter ativos os bancos de dados de uma empresa ou instituição. Ele assegura que os dados armazenados nestes bancos sempre estejam íntegros, disponíveis e eficientes para as necessidades do usuário.

### 1.2 Perfis de usuários de banco de dados

Programadores de Aplicações
    São os profissionais de TI que escrevem rotinas, programas e interfaces interagir com o banco de dados.
        Vantagens:
          - Conseguem criar rotinas complexas que processam milhões de registros sem intervenção humana.
          - Constroem interfaces que impedem o usuário comum de cometer erros ou acessar dados restritos.
          - Sabem como usar índices, transações e consultas eficientes para não travar o servidor.
        Desvantagens:
          - Qualquer alteração na estrutura do banco exige que eles atualizem e testem o código do sistema.
          - Às vezes focam tanto na interface do aplicativo que se esquecem de otimizar a lógica direta do banco de dados.
    
Usuários Sofisticados
    São engenheiros, analistas de negócios, cientistas de dados ou estatísticos. Eles não criam aplicativos para terceiros, mas conhecem profundamente a linguagem SQL e ferramentas de análise para extrair informações por conta própria.
        Vantagens:
          - Não dependem do setor de TI ou de programadores para gerar relatórios complexos ou gráficos de tendências.
          - Conseguem criar consultas sob demanda para responder a perguntas de negócios de forma imediata.
          - Combinam o conhecimento técnico do banco com a necessidade real da empresa.
        Desvantagens:
          - Podem executar consultas pesadas e travar o desempenho do banco de produção.
          - Como criam suas próprias consultas, correm o risco de ignorar regras de governança ou interpretar dados de forma isolada.

Usuários Especialistas
    São profissionais que utilizam o banco de dados para aplicações altamente complexas e específicas fora do ambiente tradicional de negócios. Exemplos incluem engenheiros de sistemas de Informação Geográfica, pesquisadores de inteligência artificial ou modeladores científicos.
        Vantagens:
          - Sabem manipular tipos de dados complexos, como coordenadas geoespaciais, imagens médicas ou grandes volumes de texto não estruturado.
          - Extraem o máximo de recursos avançados do SGBD, como extensões PostGIS ou pacotes matemáticos integrados.
        Limitações:
          - Podem ser brilhantes na área específica deles, mas demonstram pouca familiaridade com o funcionamento geral, segurança ou administração do SGBD.
          - As soluções criadas por eles costumam ser difíceis de integrar com os sistemas operacionais comuns da empresa.

Usuários Navegantes
    É a maior parte dos usuários de uma empresa, como vendedores, caixas, atendentes de suporte. Eles interagem com o banco de dados sem saber que ele existe, utilizando apenas menus, botões e formulários prontos da aplicação.
        Vantagens:
          -Não precisam entender de SQL, código ou modelagem de dados para realizar o trabalho diário.
          -Como só usam caminhos pré-definidos, o risco de inserirem dados inválidos ou corromperem a estrutura do banco é mínimo.
        Limitações:
          -Se precisarem de um relatório que não foi previamente programado na tela do sistema, ficam completamente de mãos atadas.
          -Se a interface do software contiver uma falha de validação, esse usuário pode inserir dados incorretos repetidamente sem notar o impacto no banco.


O usuário especialista é o foco de atenção porque ele lida com dados complexos e consultas pesadas que podem travar o servidor. Por dominar a sua área técnica, mas não a TI, a arquitetura do banco precisa ser desenhada sob medida para que ele consiga trabalhar sem derrubar o sistema dos demais usuários.

### 1.3 Riscos do uso de IA por usuários especialistas
Consulta incorreta, exposição de dados sensíveis, degradação de performance,
vazamento por prompts — impactos na segurança e na integridade.

### 1.4 Distribuição segura de dados
Menor privilégio, views, roles customizadas, controle de execução, auditoria,
conformidade (LGPD).

### 1.5 Atuação do DBA no cenário de IA
Monitoramento, políticas de acesso, auditoria, orientação aos usuários,
performance e backups.

### 1.6 Análise crítica: qual a melhor abordagem?
Posição fundamentada do grupo sobre como distribuir dados com segurança
no contexto do uso de IA.

## 2. Exemplos e Casos

Exemplo de view `clientes_visiveis` no PostgreSQL e exemplo de role/permissão.
Um caso real: sistema de vendas, clínica ou biblioteca.

## 3. Referências

https://www.alura.com.br/artigos/administrador-de-banco-de-dados?srsltid=AfmBOooZuNypvyRAtCszHvCazJQmUqS_ebldSr5QJD0uQSHIVsnFhl68

https://ebaconline.com.br/blog/tipos-de-programadores-seo

https://pt.linkedin.com/pulse/modelagem-de-bancos-dados-sem-segredos-parte-04-barreto-mouta-vusnf

## 4. Conclusões

Aprendizados, reflexões e principais pontos observados pelo grupo.
git branch -M main
## Link do Repositório Git