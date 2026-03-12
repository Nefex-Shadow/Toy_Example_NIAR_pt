# Relatório de Auditoria – Governança e Impacto Institucional

**Objetivo:**  Avaliar se o projeto considera aspectos institucionais e de governança associados ao desenvolvimento e implantação do sistema de IA, incluindo riscos organizacionais, impactos distributivos e mecanismos de monitoramento e responsabilização.

**Relatório principal analisado:**  
`docs/Governanca/governance_report.md`

**Projeto avaliado:**  `Modelo de predição de risco de agravamento clínico em pacientes hospitalizados.`

**Auditor:** Equipe CIIA-Saúde - NIAR

---

# 1. Contexto de implantação do sistema

- [X] O relatório descreve **o contexto de uso do sistema de IA**.

Exemplos de informações esperadas:

- tipo de instituição onde o sistema será utilizado  
- objetivo operacional ou clínico do sistema  
- público ou população afetada  
- nível de suporte à decisão (assistivo, recomendação, automação)

- [ ] O relatório identifica **os principais atores envolvidos**.

Exemplos:

- profissionais de saúde
- gestores hospitalares
- equipe técnica
- pacientes ou população impactada

- [ ] O relatório descreve **limitações ou condições para uso apropriado do sistema**.

**Referência no relatório:**  
Seção: *Contexto de implantação*

---

# 2. Avaliação de riscos institucionais

- [ ] O projeto identifica **possíveis riscos institucionais associados ao uso do sistema**.

Exemplos de riscos:

- dependência excessiva do sistema
- uso fora do escopo previsto
- interpretação incorreta das previsões
- impacto em fluxos de trabalho clínicos

- [ ] Existe discussão sobre **impactos organizacionais ou operacionais**.

Exemplos:

- mudanças no processo de tomada de decisão
- redistribuição de recursos
- impacto na priorização de atendimento

- [ ] O relatório descreve **estratégias para mitigação desses riscos**.

**Referência no relatório:**  
Seção: *Avaliação de riscos institucionais*

---

# 3. Justiça institucional (fairness institucional)

Esta seção avalia riscos de desigualdade associados ao contexto de implantação do sistema de IA, considerando fatores estruturais que podem influenciar o impacto do modelo.

- [X] **Representatividade dos dados** foi analisada em relação às regiões ou instituições onde o sistema será utilizado.
    
    `O relatório indica que os dados utilizados para treinamento do modelo foram coletados majoritariamente em hospitais de uma região específica. Essa concentração geográfica pode limitar a representatividade para instituições localizadas em outras regiões ou com características diferentes de infraestrutura e perfil epidemiológico.`

- [ ] O relatório discute **diferenças estruturais entre instituições ou regiões** que possam influenciar o desempenho ou impacto do sistema.

    `Diferenças estruturais entre instituições são parcialmente discutidas.
    O relatório reconhece que hospitais em outras regiões podem apresentar diferenças em infraestrutura, disponibilidade de exames e perfil epidemiológico.
    No entanto, não são apresentadas análises empíricas sobre o impacto dessas diferenças no desempenho do modelo.`

- [ ] O projeto analisa o **risco de amplificação de desigualdades existentes**.

    `Risco de amplificação de desigualdades foi mencionado de forma preliminar. O relatório menciona que modelos treinados em dados de instituições com maior disponibilidade de recursos podem apresentar desempenho reduzido em hospitais com menor infraestrutura ou menor volume de dados. Entretanto, não são propostas estratégias específicas para mitigação ou monitoramento desse risco após implantação.`

- [ ] O relatório discute **impactos potenciais do sistema em grupos populacionais ou institucionais potencialmente vulneráveis**.

    `Apenas de forma geral. O relatório sugere que hospitais com menor disponibilidade de exames diagnósticos ou registros clínicos completos podem apresentar dados de entrada menos informativos para o modelo. Esse cenário pode resultar em: previsões menos confiáveis, menor utilidade clínica do sistema, potencial desigualdade na qualidade das recomendações geradas pelo sistema. Não foram identificadas análises específicas sobre impacto em grupos populacionais historicamente sub-representados nos dados.`


**Referência no relatório:**  Seção: *Justiça institucional*

---

# 4. Monitoramento e accountability

- [ ] Existe plano de **monitoramento do desempenho do sistema após implantação**.

Exemplos:

- avaliação periódica de desempenho
- análise de métricas por subgrupo
- auditorias internas

- [ ] Existe definição de **responsabilidades institucionais**.

Exemplos:

- equipe responsável pelo monitoramento
- responsáveis pela atualização do modelo
- responsáveis por decisões baseadas no sistema

- [ ] Existe estratégia para **revisão ou atualização do modelo**.

Exemplos:

- retraining periódico
- auditorias de governança
- revisão após mudanças no contexto epidemiológico

**Referência no relatório:**  
Seção: *Monitoramento e accountability*

---

# 5. Documentação e transparência

- [ ] Existe **documentação institucional do sistema de IA**.

Exemplos:

- descrição do modelo
- limitações conhecidas
- público-alvo do sistema

- [ ] Existe registro de **decisões relevantes no processo de desenvolvimento ou implantação**.

- [ ] O relatório inclui **informações suficientes para auditoria futura**.

---

# Avaliação de maturidade da dimensão Governança

| Nível | Critério |
|------|------|
Ad-hoc | Não há análise de governança ou contexto institucional |
Inicial | Contexto de uso descrito e riscos institucionais identificados |
Desenvolvido | Riscos analisados e estratégias de mitigação documentadas |
Consolidado | Processo formalizado com monitoramento contínuo e responsabilidades definidas |

**Classificação do auditor:**  

Nível: _______

**Justificativa:**

---

# Recomendações para melhoria

Com base na auditoria realizada, o auditor pode sugerir melhorias como:

- aprimoramento da documentação institucional
- definição de responsabilidades de monitoramento
- inclusão de avaliação de impacto em grupos vulneráveis
- desenvolvimento de protocolos de revisão do modelo

---

# Observações do Auditor

Registrar limitações, decisões metodológicas ou pontos críticos identificados durante a auditoria.

Exemplos:

- lacunas de documentação
- ausência de plano de monitoramento
- riscos institucionais não discutidos no relatório analisado