## Segurança-da-Mulher
Exercício para curso de AI agentes da DIO

#Contexto e Objetivos:

As fontes detalham os preocupantes índices de **violência de gênero** no Brasil, destacando o aumento de **feminicídios** e agressões domésticas registrados entre 2024 e 2026. Diante desse cenário, o poder público articula medidas de autodefesa, como o projeto de lei que autoriza a posse de **spray de pimenta** para mulheres e a criação de programas de **capacitação em defesa pessoal**. O material também descreve propostas tecnológicas, a exemplo do **botão do pânico**, e iniciativas educativas voltadas ao fortalecimento jurídico de mulheres em áreas rurais. Além de expor estatísticas alarmantes de canais de denúncia como o **Ligue 180**, os textos reforçam que o combate ao problema exige ações estruturais que vão além do endurecimento de penas. Por fim, as informações ressaltam a importância da rede de apoio e da **transparência dos dados** para enfrentar a subnotificação e proteger as vítimas.

#Curadoria de Fontes:

https://agenciabrasil.ebc.com.br/direitos-humanos/noticia/2026-04/publicadas-leis-que-ampliam-combate-violencia-contra-mulheres
https://g1.globo.com/ro/rondonia/noticia/2026/02/25/entenda-como-funciona-a-lei-que-autoriza-mulheres-usarem-spray-de-pimenta-para-defesa-pessoal-em-rondonia.ghtml
https://etecfernandoprestes.cps.sp.gov.br/dia-da-mulher-autodefesa/
https://www12.senado.leg.br/institucional/procuradoria/noticias/violencia-de-genero-no-brasil

#1. Estratégia de Contextualização (Persona e Domínio)

Para obter respostas que não fossem genéricas, calibramos a persona e o território.Pergunta Estratégica: Como obter dados de segurança que sejam academicamente válidos, mas práticos para o dia a dia?Prompt de Persona: "Você é um pesquisador com doutorado em segurança pública..."Resultado: A IA parou de dar conselhos superficiais e passou a citar órgãos oficiais (FBSP, Ministério das Mulheres) e leis específicas.

#2. Variações de Prompts e Refinamento (Iterações)Testamos diferentes camadas de profundidade para chegar ao resultado final:Versão do PromptIntençãoResposta da IAV1: "Últimas pesquisas sobre segurança da mulher"Panorama GeralTrouxe dados estatísticos de 2025/2026 e recordes de feminicídio.V2: "Soluções como autodefesa e links"PraticidadeFiltrou artigos que tratam a autodefesa como política pública, não apenas luta física.V3: "Prós e contras de ferramentas de sobrevivência"Análise de RiscoGerou um balanço técnico entre sprays, tasers e botões de pânico.

#3. Troubleshooting e Dificuldades (Onde a IA "travou")A Barreira da Atualidade (Real-Time)Desafio: O usuário pediu dados "atualizados". Muitas IAs falham ao citar dados de anos anteriores (2022/2023) como se fossem novos.Solução (Engenharia): Forcei a busca por marcos temporais específicos (2025 e 2026). Isso obrigou o modelo a ignorar o banco de dados estático e focar em eventos recentes (como o recorde de feminicídios de 2025).A Questão Ética e de Segurança (Guardrails)Desafio: Recomendar itens de "defesa" pode acionar filtros de segurança da IA para evitar a promoção de violência.Solução: O prompt foi estruturado focando em "legitima defesa" e "políticas de venda". Ao pedir itens que não ferem as políticas, a IA conseguiu filtrar o que é legal (spray de gengibre, alarmes) em vez de sugerir armas restritas.Precisão LegislativaDesafio: Leis brasileiras mudam rápido. Citá-las genericamente não ajuda um pesquisador.Solução: Buscamos o número exato das leis sancionadas em abril de 2026 (ex: Lei do Vicaricídio), garantindo que a referência fosse útil para um relatório oficial.

#4. Referências Estratégicas Utilizadas
Nesta sessão, priorizamos:FBSP (Fórum Brasileiro de Segurança Pública): Padrão-ouro para estatísticas criminais.DOU (Diário Oficial da União): Fonte primária para leis sancionadas.Atlas da Violência: Para recortes raciais e sociais.

##1. Prompt de Análise Legislativa (Foco em Direito)
Use este prompt sempre que uma nova lei for sancionada ou um projeto de lei (PL) avançar.

Prompt: "Aja como um doutor em Direito e Segurança Pública. Realize uma análise técnica da [Inserir Nome/Número da Lei].

Explique o fato gerador (o que motivou a lei).

Identifique as mudanças práticas no Código Penal ou na Lei Maria da Penha.

Aponte possíveis brechas jurídicas ou dificuldades que as polícias podem enfrentar na ponta para aplicar essa norma.

Forneça o link oficial do Diário Oficial da União (DOU)."

#2. Prompt de Auditoria de Dados (Foco em Estatística)
Ideal para quando novos relatórios (como o Atlas da Violência ou Anuário do FBSP) forem publicados.

Prompt: "Como um analista de dados especializado em criminalidade de gênero, extraia os principais insights do [Inserir Nome do Relatório] de [Inserir Ano].

Quais são as taxas de variação em relação ao ano anterior?

Detalhe o recorte interseccional (raça, idade, localização geográfica).

Existe correlação entre os novos dados e a eficácia das medidas protetivas?

Apresente os dados em uma tabela comparativa."

#3. Prompt de Avaliação de Tecnologias (Foco em Ferramentas)
Use para revisar a eficácia de novos gadgets, apps ou dispositivos de segurança.

Prompt: "Aja como um consultor de segurança pessoal. Analise a ferramenta [Inserir Nome do Dispositivo/App] sob o prisma da viabilidade imediata.

Quais são os prós e contras técnicos (bateria, alcance, facilidade de uso)?

Analise a segurança jurídica: o uso deste item pode ser interpretado como excesso de legítima defesa?

Compare com 2 alternativas de mercado que não firam as políticas de venda brasileiras."

#Dicas de Ouro para Engenharia de Prompts (Troubleshooting)
Ao utilizar esses prompts, você pode encontrar algumas resistências da IA. Aqui está como resolver:

Se a IA der uma resposta curta demais: Adicione ao final do prompt: "Seja exaustivo e utilize terminologia acadêmica. Não economize em detalhes técnicos."

Se a IA citar leis antigas: Adicione: "Ignore dados anteriores a 2025. Foque exclusivamente em atualizações publicadas nos últimos 12 meses."

Se a IA recusar falar de 'armas': Substitua o termo por "instrumentos de baixa letalidade para legítima defesa civil" ou "dispositivos de alerta e dissuasão".

##1. Resumo Estruturado: Segurança da Mulher no Brasil (2025-2026)

O panorama atual é caracterizado pela transição de políticas puramente punitivas para estratégias de proteção ativa e tecnologia aplicada.

Cenário Estatístico: Apesar do endurecimento das penas, 2025 registrou picos de feminicídio. A principal falha identificada por pesquisadores é a fiscalização das medidas protetivas, já que uma porcentagem significativa das vítimas já possuía amparo legal que não foi suficiente para deter o agressor.

Políticas de Autodefesa: A autodefesa passou a ser vista como política pública. Municípios e estados brasileiros começaram a oferecer cursos gratuitos focados em consciência situacional, desescalada verbal e técnicas físicas de desvencilhamento.

Soluções Tecnológicas: O uso de Botões de Pânico e dispositivos de monitoramento (como tornozeleiras integradas a apps para a vítima) tornou-se a ferramenta padrão para quem possui medidas protetivas vigentes.

Legislação Recente: O foco legislativo de 2026 voltou-se para a proteção de terceiros e o combate à manipulação do sistema, com destaque para a tipificação do vicaricídio e mudanças nas audiências de retratação para evitar coação.

#2. Glossário de Conceitos Chave
Feminicídio: Homicídio praticado contra a mulher por razões da condição de sexo feminino (envolvendo violência doméstica ou menosprezo à condição de mulher).

Violência Vicária (Vicaricídio): Violência exercida contra pessoas próximas à mulher (geralmente filhos ou pais) com o intuito de causar sofrimento psicológico extremo à vítima principal.

Consciência Situacional: A habilidade de identificar e processar elementos críticos de informação sobre o que está acontecendo ao seu redor, permitindo antecipar riscos e evitar confrontos.

Baixa Letalidade: Categoria de instrumentos (como sprays de gengibre e alarmes) projetados para interromper uma agressão sem causar danos permanentes ou morte, priorizando a fuga da vítima.

Medida Protetiva de Urgência (MPU): Ordem judicial que impõe restrições ao agressor (como limite de distância) para garantir a integridade da vítima.

Retratação: Ato de a vítima retirar a representação criminal contra o agressor. A lei atual exige rigor para garantir que essa decisão seja voluntária e não fruto de ameaça.

#3. Ferramentas de Apoio à Sobrevivência Imediata
Para fins de estudo e aplicação prática, estas são as ferramentas que se alinham à legislação civil brasileira atual:

Alarme de Segurança Pessoal SafeSound: Dispositivo de dissuasão sonora de 140dB para atrair atenção e desorientar ameaças.

Caneta Tática Invictus: Instrumento de escrita em alumínio aeroespacial, utilizado como ferramenta de impacto e resgate.

Spray de Gengibre ANL: Agente de baixa letalidade permitido para civis, focado em criar uma janela de tempo para evasão.
