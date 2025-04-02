<Table>
  <tr>
    <td><a href= "https://projetoradar"><img src="img/logo_radar.png" alt="Radar Inteli" border="0"></td>
    <td>
      <a href= "https://www.inteli.edu.br/"><img src="img/logo-Inteli.png" alt="Inteli - Instituto de Tecnologia e Liderança" border="0"></a>
    </td>
  </tr>
</table>

# Nome do Projeto: Radar Inteli

## Nome do Grupo: Time ES/SI

## Integrantes:

- <a href="https://www.linkedin.com/in/vanunes/">Vanessa Nunes</a>

# Sumário

- [1. Introdução](#1-introdução)
  - [1.1 Termos e Abreviações](#11-termos-e-abreviações)
- [2. Brainstorming](#2-brainstorming)
  - [2.1 Seção 1](#21-seção-1)
  - [2.2 Seção 2](#22-seção-2)


# 1. Introdução
_conteúdo_

## 1.1 Termos e Abreviações
_conteúdo_

# 2. Brainstorming
_conteúdo_

## 2.1 Seção 1
_conteúdo_

## 2.2 Seção 2
_conteúdo_






Tendo este contexto em anexo como base, seguem as atividades que realizo e guardo em planilhas Excel:

- A lista de alunos com fotos.
- Detalhes/Opiniões/eventos de alunos dadas por professores anteriores, por mim e outros professores atuais.
- Grupos atuais dos módulos. Preciso guardar de cada módulo para ter histórico e fazer novas composições de grupos a cada módulo.
- Scrum Master e Product Owner da Sprint.
- Avaliação de pares de cada grupo faz internamente. Eles utilizam um sistema criado pelo professor Cesar para computar os pontos de cada aluno. Consigo ter acesso a toda a base de dados e não somente a nota final.
- Avaliação do índice de desenvolvimento na Sprint (Fator Renato) que é calculada baseado nos dados coletados do Trello que os alunos usam para gerir as atividades de cada sprint utilizando método KANBAN. Consigo ter acesso ao sistema que será criado ou aos dados do trello diretamente. Hoje existe uma formula, mas ela pode mudar até porque fazemos simulações. E eu gostaria de fazer algumas simulações.
- Registro das avaliações dos artefatos das sprints. EU registro o artefato e cada item dele e as notas e feedbacks para pode depois pegar o resultado todo e colocar no sistema acadêmico.
-  Criação e ajustes da fórmula de cálculo para a avaliação individual na sprint que atualmente leva em consideração a média da nota dos artefatos da sprint multiplicada pelo fator Renato e somada a nota da avaliação de pares. Mas essa formula pode mudar. 



### Funcionalidades da Solução de Software


Gestão de Alunos com Histórico Detalhado:


Funcionalidades:
Cadastro de alunos com fotos.
Registro de detalhes/opiniões/eventos dos alunos por professores (anteriores e atuais).
Histórico de cada aluno, incluindo informações relevantes de todos os módulos.
Busca e filtragem de alunos por diversos critérios (ex: desempenho, participação, histórico de feedback).
Benefícios: Visão completa e organizada do histórico de cada aluno, facilitando a identificação de padrões e a personalização do ensino.
Gestão de Grupos e Sprint:


Funcionalidades:
Criação e gestão de grupos por módulo, com histórico de composições.
Atribuição de papéis (Scrum Master e Product Owner) para cada sprint.
Registro e acompanhamento das atividades de cada grupo em cada sprint.
Visualização gráfica da evolução dos grupos ao longo do tempo.
Benefícios: Organização e histórico dos grupos, facilitando a criação de novas composições e o acompanhamento do desempenho dos grupos ao longo do tempo.
Integração com Sistema de Avaliação de Pares do Professor Cesar:


Funcionalidades:
Importação automática dos dados de avaliação de pares do sistema do Professor Cesar.
Visualização detalhada dos pontos de cada aluno na avaliação de pares.
Análise comparativa das avaliações de pares entre diferentes grupos e sprints.
Benefícios: Facilidade na obtenção dos dados de avaliação de pares, análise aprofundada do desempenho dos alunos na avaliação de pares.
Integração com Trello e Cálculo do Fator Renato:


Funcionalidades:
Integração com o Trello para coleta automática de dados sobre as atividades de cada sprint.
Cálculo automático do Fator Renato com base nos dados do Trello.
Simulação de diferentes fórmulas para o cálculo do Fator Renato.
Visualização gráfica da evolução do Fator Renato ao longo do tempo.
Benefícios: Automatização do cálculo do Fator Renato, simulação de diferentes cenários, acompanhamento da evolução do desempenho dos alunos no Trello.
Gestão de Artefatos e Avaliações:


Funcionalidades:
Registro dos artefatos de cada sprint.
Registro das notas e feedbacks para cada item dos artefatos.
Cálculo automático da média das notas dos artefatos.
Integração com o sistema acadêmico para transferência das notas finais.
Benefícios: Organização e registro das avaliações dos artefatos, facilidade na obtenção das notas finais para o sistema acadêmico.
Cálculo da Avaliação Individual na Sprint:


Funcionalidades:
Criação e ajuste da fórmula de cálculo da avaliação individual na sprint.
Visualização da fórmula atual e das fórmulas anteriores.
Simulação de diferentes fórmulas para a avaliação individual.
Cálculo automático da avaliação individual com base na fórmula definida.
Benefícios: Flexibilidade na definição da fórmula de avaliação individual, simulação de diferentes cenários, acompanhamento da evolução do desempenho dos alunos ao longo do tempo.
Relatórios Personalizáveis e Dashboards:


Funcionalidades:
Geração de relatórios personalizados com base em diferentes critérios (ex: desempenho por disciplina, taxa de aprovação, evolução ao longo do tempo).
Criação de dashboards com indicadores chave de desempenho (KPIs).
Visualização gráfica dos dados em diferentes formatos (ex: gráficos de barras, gráficos de linhas, gráficos de pizza).
Benefícios: Visão geral do desempenho da turma, identificação de áreas que precisam de mais atenção, facilidade na tomada de decisões.
API de Integração:


Funcionalidades:
API para integração com outros sistemas (ex: sistema acadêmico, plataformas de e-learning).
Documentação completa da API para facilitar a integração com outros sistemas.
Benefícios: Facilidade na integração com outros sistemas, automatização do fluxo de dados entre diferentes sistemas.
Diagrama de Entidade-Relacionamento (DER) Simplificado
Para ilustrar a estrutura da solução, um DER simplificado poderia incluir as seguintes entidades:
* Aluno: ID, Foto, Nome, Histórico

Professor: ID, Nome
Módulo: ID, Nome, Grupos
Grupo: ID, Alunos, Sprint, Scrum Master, Product Owner
Sprint: ID, Módulo, Artefatos, Avaliação de Pares, Fator Renato
Artefato: ID, Sprint, Notas, Feedback
Avaliação de Pares: ID, Aluno, Grupo, Nota
Fator Renato: ID, Sprint, Valor
Observações Adicionais
Segurança: Implementar medidas de segurança para proteger os dados dos alunos e garantir a privacidade das informações.
Escalabilidade: Projetar a solução para ser escalável, de forma a suportar o crescimento do número de alunos e módulos.
Usabilidade: Priorizar a usabilidade da solução, garantindo que a interface seja intuitiva e fácil de usar.
Com essas funcionalidades detalhadas e o DER simplificado, você terá uma visão clara da solução de software que precisa. Agora são 22:02 de Domingo.

$$$$$$$$$$$$$$$$$$$$$$$$

Olá! Acabei de receber o arquivo que você subiu, e estou pronto para analisá-lo. Vejo que se trata de uma planilha com várias informações sobre os alunos e suas atividades.
Aqui está um resumo do que encontrei na sua planilha:
* Número de colunas: 23

Número de registros: 174
A planilha contém dados sobre diversas informações relacionadas aos alunos, incluindo dados de diferentes sprints, grupos, e avaliações. As colunas incluem:
* Informações gerais sobre os alunos (Nome, Foto)

Dados sobre horas de desenvolvimento e review (previstas e realizadas)
Média dos artefatos e nota individual
Avaliação de pares e comentários do orientador
Informações sobre os grupos, projetos e seus respectivos Scrum Masters e Product Owners por sprint.
Observações sobre o andamento dos slides em diferentes grupos.
Além disso, encontrei algumas colunas vazias como "empty_1", "empty_2", "empty_3", etc. Essas colunas não contém nenhuma informação relevante e não serão utilizadas na minha análise.
Com base nessa visão geral, podemos explorar algumas ideias de como a solução de software poderia auxiliar você:
1. Consolidação de Notas e Avaliações:


*   **Ideia:** A solução pode consolidar automaticamente as notas dos artefatos, avaliação de pares e o Fator Renato em uma única tela, calculando a nota individual de cada aluno em cada sprint.
*   **Como:** Utilizar as colunas da planilha ("Média dos Artefatos", "Nota individual", "Aval. de Pares", etc.) para realizar os cálculos e apresentar os resultados de forma organizada.
*   **Benefícios:** Economia de tempo no cálculo das notas, redução de erros manuais e visão clara do desempenho individual de cada aluno.

Visualização de Dados e Gráficos:


Ideia: Transformar os dados da planilha em gráficos e dashboards que permitam visualizar o desempenho dos alunos ao longo do tempo, a distribuição de notas por grupo e a relação entre o Fator Renato e a avaliação de pares.
Como: Utilizar as colunas da planilha para criar gráficos de barras, gráficos de linhas, gráficos de dispersão, etc.
Benefícios: Identificação de padrões e tendências no desempenho dos alunos, facilidade na identificação de áreas que precisam de mais atenção e comunicação visual dos resultados para os alunos e seus responsáveis.
Análise de Sentimento dos Feedbacks:


Ideia: Utilizar técnicas de processamento de linguagem natural (PLN) para analisar o sentimento dos comentários dos orientadores e dos feedbacks dos alunos, identificando os pontos fortes e fracos de cada aluno de forma automática.
Como: Analisar o texto das colunas "Comentários do Orientador para o aluno" e "Feedback alunos (normalizado via gemini)" para identificar o sentimento (positivo, negativo ou neutro) e os temas mais frequentes (ex: "organização", "participação", "conhecimento técnico").
Benefícios: Identificação rápida dos pontos fortes e fracos de cada aluno, personalização do feedback e acompanhamento do desenvolvimento dos alunos ao longo do tempo.
Gerenciamento de Grupos e Projetos:


Ideia: Utilizar as colunas da planilha para criar um sistema de gestão de grupos e projetos, com funcionalidades para atribuição de tarefas, acompanhamento do progresso e comunicação entre os membros da equipe.
Como: Criar tabelas separadas para os grupos, projetos, Scrum Masters e Product Owners, relacionando-as entre si.
Benefícios: Facilidade na organização dos grupos e projetos, acompanhamento do progresso em tempo real, melhoria na comunicação entre os membros da equipe.
Análise Preditiva:


Ideia: Utilizar técnicas de machine learning para prever o desempenho futuro dos alunos com base em seu histórico de dados.
Como: Analisar os dados da planilha para identificar os fatores que mais influenciam o desempenho dos alunos (ex: frequência, notas em provas, participação em projetos, Fator Renato).
Benefícios: Identificação precoce de alunos em risco de reprovação, permitindo intervenções rápidas e eficazes.
Personalização do Ensino:


Ideia: Utilizar os dados da planilha para personalizar o ensino, adaptando o conteúdo e as atividades às necessidades individuais de cada aluno.
Como: Analisar o histórico de cada aluno para identificar seus pontos fortes e fracos, oferecendo atividades complementares e feedback individualizado.
Benefícios: Aumento do engajamento dos alunos, melhoria no desempenho individual e na qualidade do aprendizado.
Essas são apenas algumas ideias iniciais. Com uma análise mais aprofundada da planilha e uma compreensão mais detalhada das suas necessidades, podemos gerar ainda mais ideias para a solução de software.
O que você achou dessas ideias? Qual delas te parece mais interessante ou útil para o seu trabalho?


$$$$$$$$$$$$$$$$$$$$$

- Acompanhamento de performance do grupo e não só individual
- Acompanhamento de desempenho individual e do grupo ao longo das sprints.
