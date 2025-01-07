# DailyTasks (Todoist) – Teste Exploratório 🚀

Bem-vindo(a) ao repositório do projeto DailyTasks, onde realizei um Teste Exploratório no aplicativo Todoist para gerenciamento de tarefas. A proposta foi avaliar as principais funcionalidades do Todoist em um cenário de criação, edição, conclusão, reabertura e exclusão de tarefas, além de observar possíveis problemas de usabilidade e layout.

O DailyTasks é um conceito de aplicação de lista de tarefas. Para a demonstração prática, escolhi o Todoist como plataforma real a ser testada, pois oferece:

Um ambiente estável para criar, editar e excluir tarefas.
Recursos úteis como datas de vencimento, rótulos, projetos e filtros.
Versão gratuita acessível para qualquer usuário.
O objetivo foi simular testes em um aplicativo de “to-do list” sem precisar criar minha própria aplicação do zero, aproveitando assim um sistema robusto e reconhecido no mercado.

## 1. Escopo e Objetivos 🎯

### Escopo
Criação de tarefas: Títulos, datas, rótulos e subtarefas.
Edição de tarefas: Alteração de título, datas e atributos.
Conclusão de tarefas: Marcar como concluída, conferir comportamento em diferentes cenários.
Reabertura de tarefas: Desfazer a conclusão e restaurar status ativo.
Exclusão de tarefas: Testar exclusão simples e cenários com diferentes dados associados (data, labels, etc.).
### Objetivos Principais
Verificar o comportamento do Todoist em cenários comuns de gerenciamento de tarefas.
Identificar possíveis inconsistências ou falhas de usabilidade e layout.
Documentar o processo de teste (Test Plan, Cenários, Resultados).
Exercitar a abordagem de teste exploratório, simulando um usuário que descobre as funcionalidades em tempo real.
## 3. Ferramentas Utilizadas 🔧

Ferramenta	Finalidade
Todoist	Aplicativo alvo do teste (versão web)
DevTools	Inspeção de console e rede no navegador
Planilha (Excel)	Registro de cenários e resultados (ID, Pass/Fail)
(Opcional) Jira / Trello	Poderia ser usado para relatar bugs, mas não houve ocorrências
## 4. Metodologia de Teste ⚙️

1. Criei um Test Plan Simplificado em formato de documento, definindo o que seria testado (funcionalidades e escopo) e as ferramentas necessárias.
2. Listei cenários de teste para cada funcionalidade principal (Criação, Edição, Conclusão, Reabertura e Exclusão de tarefas). Cada cenário incluiu:
ID do teste (Ex.: CT01, ED01, CO01...)
Passos de execução
Resultado esperado
Status (Pass/Fail)
Observações gerais
3. Realizei o teste exploratório navegando pelo Todoist e executando os cenários sem um roteiro fixo, mas seguindo a lista para garantir cobertura das funcionalidades.
4. Anotei os resultados em uma planilha Excel, atualizando o campo “Resultado Obtido” e “Status”.
5. Observei o DevTools para verificar erros de console ou falhas de rede.
Importante: Não foram encontrados bugs ou comportamentos inesperados nos cenários testados, resultando em todos os testes aprovados (Pass).
## 5. Resultados e Conclusões ✅

### Resultados Gerais
Número de Testes Executados: 50 (10 para cada funcionalidade principal).
Pass: 50
Fail: 0
Bugs Encontrados: Nenhum
### Conclusões
O Todoist demonstrou boa estabilidade e consistência funcional nos cenários explorados.
Mesmo em testes de limite (título longo, caracteres especiais), o sistema se comportou adequadamente, sem gerar falhas aparentes ou erros de console.
Usabilidade: A experiência de criação e organização de tarefas foi fluida. Para um usuário final, o app mostrou-se bastante intuitivo.
Apesar de não terem sido identificados defeitos, esse processo de teste valida as funcionalidades principais do Todoist no que diz respeito ao gerenciamento de tarefas.
