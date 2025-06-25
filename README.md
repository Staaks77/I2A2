# I2A2
Repositório criado para o curso do I2A2

#### Desafioa 24_06
1. Framework escolhida
Para a implementação desta solução, utilizamos o N8N como framework principal. O N8N
permite a criação de fluxos automatizados com integração entre múltiplas ferramentas e
serviços, além de possibilitar a incorporação de agentes de IA de forma flexível e escalável.
2. Como a solução foi estruturada
A estrutura do projeto foi dividida em dois workflows principais, descritos a seguir:
• Workflow 1 – Ingestão de Dados:
 Este fluxo é responsável por receber os arquivos CSV e realizar a ingestão dos dados em
um banco Supabase. Ele garante que os dados estejam organizados e acessíveis para futuras
consultas automatizadas.
• Workflow 2 – Geração e Execução de Queries via Agente:
 Este fluxo utiliza uma LLM (Large Language Model) para interpretar perguntas feitas pelo
usuário e, a partir disso, gerar queries SQL. Um agente autônomo executa essas queries no
banco Supabase e retorna as respostas ao usuário final.
