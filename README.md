# AI-Agents-for-Medical-Diagnostics

<img width="900" alt="image" src="https://github.com/user-attachments/assets/b7c87bf6-dfff-42fe-b8d1-9be9e6c7ce86">


Um projeto em Python desenvolvido para criar agentes de IA especializados em LLM que analisam casos médicos complexos. O sistema integra insights de diversos profissionais médicos para fornecer avaliações abrangentes e recomendações de tratamento personalizadas, demonstrando o potencial da IA ​​na medicina multidisciplinar.

Visão geral da versão atual

Na versão atual, implementamos três agentes de IA usando GPT-4o, cada um especializado em um aspecto diferente da análise médica. Um relatório médico é passado para cada um desses agentes, que então o analisam simultaneamente usando encadeamentos, com base em sua área específica de especialização. Cada agente fornece recomendações e diagnósticos de sua própria perspectiva. Após todos os agentes de IA concluírem suas análises, os resultados são combinados e passados ​​para um modelo de linguagem grande, que resume as descobertas e identifica três possíveis problemas de saúde para o paciente.

Agentes de IA
1. Agente Cardiologista

Foco : Identificar quaisquer possíveis problemas cardíacos que possam explicar os sintomas do paciente, incluindo a exclusão de condições como arritmias ou anormalidades estruturais que podem não ser aparentes nas avaliações iniciais.

Recomendação : Sugira exames cardiovasculares adicionais ou monitoramento contínuo, se necessário, para descobrir problemas cardíacos ocultos. Forneça estratégias de tratamento caso seja identificado um problema cardiovascular.

2. Agente Psicólogo

Foco : Determine se os sintomas correspondem a uma condição psicológica, como transtorno do pânico ou outro problema relacionado à ansiedade. Avalie o impacto do estresse, da ansiedade e de fatores de estilo de vida no estado geral do paciente.

Recomendação : Recomendar intervenções psicológicas adequadas (por exemplo, terapia, técnicas de gerenciamento de estresse) ou medicamentos para tratar os aspectos psicológicos dos sintomas. Avaliar se são necessários ajustes no gerenciamento psicológico atual.

3. Agente Pneumologista

Foco : Avalie se sintomas como falta de ar e tontura são causados ​​por uma condição respiratória, como asma, ou um distúrbio respiratório, que pode imitar sintomas cardíacos.

Recomendação : Sugira avaliações respiratórias adicionais, como testes de função pulmonar ou testes de broncoconstrição induzida por exercício, para descartar quaisquer condições pulmonares subjacentes. Recomende exercícios respiratórios ou outros tratamentos se houver suspeita de problema respiratório.

Melhorias futuras
Em versões futuras, o sistema poderá ser expandido para incluir uma gama mais ampla de agentes de IA, cada um especializado em diferentes áreas médicas, como neurologia, endocrinologia e imunologia, para fornecer análises ainda mais abrangentes. Esses agentes de IA poderão ser implementados usando a API Assistant da OpenAI e utilizar function callingseus code interpreterrecursos para aprimorar sua inteligência e eficácia. Além disso, metodologias avançadas de análise sintática poderão ser introduzidas para processar relatórios médicos com estruturas mais complexas, permitindo que o sistema interprete e analise com precisão uma variedade maior de dados médicos.

Estrutura do Repositório
Pasta de Relatórios Médicos : Contém um relatório médico sintético de um paciente com transtorno de ataque de pânico.
Pasta de resultados : armazena as saídas do sistema agentic.
Para poder executar o código, insira sua chave de API OpenAI no apikey.envarquivo.

