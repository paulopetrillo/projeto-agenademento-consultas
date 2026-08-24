# 📊 Comunicado aos Stakeholders - Status do Projeto

**Projeto:** App de Agendamento de Consultas Médicas  
**Data:** 24/08/2026  
**Assunto:** Status do Projeto e Plano de Ação  
**Responsável:** Gerência de Projetos

---

## 1. CONTEXTO ATUAL

O projeto encontra-se em **fase intermediária de desenvolvimento**, com funcionalidades já implementadas e outras em progresso. Nas últimas semanas, enfrentamos desafios que impactam o cronograma e a qualidade da entrega.

### Situação Atual
- ✅ **Funcionalidades básicas:** Cadastro de usuários e agenda médica (entregues)
- ⏳ **Em desenvolvimento:** Agendamento de consultas e notificações
- ⚠️ **Crítico:** Integração com sistema de prontuário (instável)
- 🟡 **Em análise:** Mudanças de requisitos solicitadas

---

## 2. PRINCIPAIS RISCOS IDENTIFICADOS

| ID | Risco | Impacto | Status |
|----|-------|---------|--------|
| 🔴 R01 | **Instabilidade da API** de prontuário | Bloqueia agendamentos | ⚠️ Ativo |
| 🔴 R02 | **Mudanças não documentadas** na API | Quebra integração | ⚠️ Ativo |
| 🟠 R03 | **Alterações de requisitos** dos stakeholders | Retrabalho e atrasos | 🔄 Em andamento |
| 🟠 R04 | **Sobrecarga da equipe** (4 devs + 1 tester) | Queda de produtividade | 🔄 Em andamento |
| 🟠 R06 | **Queda na qualidade** do código | Bugs e débito técnico | 🔄 Em andamento |

---

## 3. AÇÕES EM ANDAMENTO

### 🔴 Ações Críticas (Prioridade Máxima)

| Ação | Responsável | Prazo | Status |
|------|-------------|-------|--------|
| Implementar **Circuit Breaker** na API externa | Dev Líder | 26/08 | 🟡 30% |
| Criar **Anti-Corruption Layer** para isolar integração | Arquiteto | 27/08 | 🟡 20% |
| Configurar **monitoramento** da API em tempo real | DevOps | 27/08 | 🟡 40% |

### 🟠 Ações Prioritárias

| Ação | Responsável | Prazo | Status |
|------|-------------|-------|--------|
| Replanejar sprint reduzindo escopo em 20% | Scrum Master | 25/08 | 🔄 50% |
| Implementar **Quality Gates** no pipeline | DevOps | 29/08 | 🔄 20% |
| Formalizar **processo de mudanças** (CCB) | PM | 26/08 | 🔄 40% |

### 🟡 Ações de Suporte

| Ação | Responsável | Prazo | Status |
|------|-------------|-------|--------|
| Contratar **consultor médico** para validação de regras | PM + RH | 31/08 | ⏳ Pendente |
| Provisionar **ambiente de staging** idêntico à produção | DevOps | 04/09 | ⏳ Pendente |
| Reuniões 1:1 com equipe para avaliar bem-estar | PM | Semanal | ✅ Em dia |

---

## 4. PRÓXIMOS PASSOS

### 📅 Curto Prazo (Esta Semana - até 30/08)

1. **Implementar Circuit Breaker e Cache** - Isolar falhas da API externa
2. **Reunião com stakeholders** para congelar escopo do MVP
3. **Reduzir carga da sprint atual** para garantir qualidade
4. **Iniciar testes de contrato** com a API externa

### 📅 Médio Prazo (Próximas 2 Semanas)

1. **Concluir Anti-Corruption Layer** - Proteger código de mudanças externas
2. **Negociar SLA formal** com fornecedor da API
3. **Automatizar testes de regressão** (Selenium/Cypress)
4. **Contratar consultor médico** para validação de regras

### 📅 Longo Prazo (Próximo Mês)

1. **Estabelecer paridade entre ambientes** (homologação = produção)
2. **Implementar plano de retenção** da equipe
3. **Revisar e ajustar** estratégias de resposta a riscos

---

## 5. SOLICITAÇÕES AOS STAKEHOLDERS

### 🎯 Decisões Necessárias

| Solicitação | Prazo | Prioridade |
|-------------|-------|------------|
| **Congelar escopo** para versão MVP até 15/09 | Imediato | 🔴 Crítico |
| **Aprovar contratação** de consultor médico (R$ X.XXX/mês) | 28/08 | 🟠 Alta |
| **Autorizar horas extras** controladas (máx. 4h/semana) | Imediato | 🟠 Alta |
| **Reavaliar prazo** de entrega (possível +2 semanas) | 31/08 | 🟡 Média |

### 📋 Recomendações

1. **Prioridade máxima:** Permitir o time focar na estabilidade da integração
2. **Evitar novas solicitações** de mudanças até a estabilização
3. **Apoiar a equipe** com recursos adicionais se necessário
4. **Acompanhar o dashboard** de riscos (disponível no repositório)

---

## 6. INDICADORES DE PROGRESSO

| Métrica | Meta | Atual | Tendência |
|---------|------|-------|-----------|
| Taxa de erro da API | < 5% | 12% | ⚠️ Piorando |
| Cobertura de testes | ≥ 80% | 65% | ⚠️ Estável |
| Velocidade da sprint | 16 pts | 10 pts | ⚠️ Caindo |
| Horas extras/semana | < 4h | 8h | ⚠️ Aumentando |
| Bugs em produção | 0 críticos | 2 críticos | ⚠️ Crítico |

---

**Repositório de Riscos:** https://github.com/empresa/gestao-riscos-app-medico  
**Dashboard:** https://dashboard.empresa.com/app-medico

---

**Status do Projeto:** 🟡 **ATENÇÃO** - Risco de atraso, ações em andamento  
**Próxima Atualização:** 31/08/2026

---

*Este comunicado será atualizado semanalmente ou sempre que houver mudanças significativas.*

---

**Agradecemos a atenção e o apoio de todos. Estamos comprometidos com a entrega de qualidade e trabalhamos ativamente para mitigar os desafios identificados.**
