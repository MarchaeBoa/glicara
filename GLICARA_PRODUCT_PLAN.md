# GLICARA — Planejamento Completo do Produto

> *"Sua rotina com diabetes, finalmente organizada."*

---

## 1. VISAO GERAL DO PRODUTO

**Glicara** e uma plataforma SaaS de saude digital (healthtech) focada em pessoas com diabetes tipo 1, tipo 2 e gestacional. O produto centraliza a gestao da rotina do usuario diabetico em um unico lugar: lembretes de insulina e medicamentos, registro de glicemia, acompanhamento nutricional, descoberta de medicos especializados proximos, e uma comunidade exclusiva de apoio entre assinantes.

**Glicara NAO e um app medico.** Nao diagnostica, nao prescreve, nao substitui profissionais de saude. E uma ferramenta de **organizacao, acompanhamento e suporte** que complementa o tratamento medico.

**Modelo:** SaaS B2C com freemium + planos pagos mensais/anuais.

**Plataformas:** Web app responsivo (PWA) + aplicativo nativo iOS/Android (V2).

---

## 2. PUBLICO-ALVO

### Primario
- Pessoas diagnosticadas com diabetes tipo 1 ou tipo 2 (18-65 anos)
- Pais/cuidadores de criancas e adolescentes diabeticos
- Gestantes com diabetes gestacional

### Secundario
- Pre-diabeticos que querem monitorar a saude preventivamente
- Profissionais de saude que querem indicar a ferramenta para pacientes

### Perfil Comportamental
| Aspecto | Detalhe |
|---|---|
| Dor principal | Esquecimento de medicacao, desorganizacao alimentar, isolamento |
| Motivacao | Viver melhor, evitar complicacoes, ter controle |
| Comportamento digital | Usa WhatsApp, redes sociais, busca informacao no Google |
| Poder aquisitivo | Classes B e C (R$19-49/mes e viavel) |
| Dispositivo | 80% mobile, 20% desktop |

---

## 3. PRINCIPAIS DORES DOS USUARIOS

| # | Dor | Impacto |
|---|---|---|
| 1 | **Esquecimento de aplicacao de insulina/medicamentos** | Descontrole glicemico, risco de internacao |
| 2 | **Nao saber o que comer** | Ansiedade, restricao excessiva, picos de glicemia |
| 3 | **Dificuldade de encontrar medicos especializados** | Demora no tratamento, consultas com profissionais nao-especializados |
| 4 | **Isolamento emocional** | Depressao, falta de motivacao para aderir ao tratamento |
| 5 | **Registros de glicemia desorganizados** | Medico nao consegue avaliar evolucao, paciente nao enxerga padroes |
| 6 | **Falta de rotina estruturada** | Horarios inconsistentes de medicacao e refeicao |
| 7 | **Sobrecarga de informacao** | Nao sabe o que e confiavel, conteudo generico demais |
| 8 | **Cuidadores sem ferramentas** | Pais/familiares nao conseguem acompanhar remotamente |

---

## 4. PROPOSTA DE VALOR

> **"Glicara organiza sua rotina com diabetes em um so lugar — lembretes, alimentacao, glicemia, medicos e comunidade — para que voce foque em viver, nao em se preocupar."**

### Canvas de Valor

**Ganhos que entregamos:**
- Nunca mais esquecer medicacao
- Entender padroes da propria glicemia
- Saber o que comer com seguranca
- Encontrar medicos certos rapido
- Sentir-se parte de uma comunidade que entende

**Dores que eliminamos:**
- Desorganizacao de rotina
- Informacao confusa e generica
- Isolamento no tratamento
- Registros perdidos em papel ou apps diferentes

---

## 5. DIFERENCIAIS COMPETITIVOS

| Concorrente | Foco | Limitacao | Glicara supera porque... |
|---|---|---|---|
| mySugr | Registro de glicemia | Frio, sem comunidade, sem nutricao | Unifica rotina + comunidade + alimentacao |
| Glooko | Integracao com dispositivos | B2B, nao acessivel ao usuario final | B2C acessivel, UX amigavel |
| Apps de lembrete genericos | Alarmes | Nao entendem contexto de diabetes | Lembretes inteligentes por tipo de insulina/medicamento |
| Grupos de Facebook | Comunidade | Sem moderacao, informacao perigosa | Comunidade moderada com conteudo validado |

### 5 Diferenciais-Chave da Glicara

1. **Lembrete inteligente contextual** — nao e so alarme; entende tipo de insulina (rapida vs basal), rotacao de aplicacao, e avisa se passou do horario
2. **Cardapio semanal adaptado** — sugestoes de refeicoes com indice glicemico, nao "dieta", mas organizacao alimentar pratica
3. **Mapa de medicos especializados** — endocrinologistas, nutricionistas, podologos, oftalmologistas proximos com filtro por convonio e avaliacao
4. **Comunidade moderada** — forum + grupos tematicos com moderacao ativa (sem cura milagrosa, sem fake news)
5. **Painel do cuidador** — familiares acompanham remotamente com permissao do usuario

---

## 6. ESTRUTURA COMPLETA DE FUNCIONALIDADES

### 6.1 Nucleo (Core Features)

#### A) Lembretes Inteligentes
- Cadastro de medicamentos/insulinas com tipo, dosagem e horarios
- Lembretes via push notification, SMS (premium) e WhatsApp (premium)
- Confirmacao de tomada ("Tomei" / "Pular" com motivo)
- Historico de adesao (% de lembretes confirmados)
- Alerta de estoque baixo de medicamentos
- Rotacao de local de aplicacao de insulina (mapa corporal interativo)

#### B) Registro de Glicemia
- Input manual rapido (campo numerico + horario + contexto: jejum/pos-refeicao/noturno)
- Grafico de evolucao diario/semanal/mensal
- Deteccao automatica de padroes (ex: "sua glicemia de jejum subiu 15% esta semana")
- Exportacao em PDF para levar ao medico
- Meta de faixa-alvo personalizavel

#### C) Alimentacao Inteligente
- Cardapio semanal sugerido (cafe, almoco, lanche, jantar)
- Cada refeicao com: indice glicemico, carga glicemica, macros simplificados
- Filtros: sem gluten, sem lactose, vegetariano, low carb
- Lista de compras automatica baseada no cardapio
- Banco de receitas com busca por ingrediente
- Tag de "seguro para diabetico" com explicacao (nao e prescricao medica)
- Disclaimer permanente: "consulte seu nutricionista"

#### D) Mapa de Profissionais de Saude
- Busca por especialidade: endocrinologista, nutricionista, nefrologista, podologista, oftalmologista, psicologo
- Filtro por: localizacao (GPS), convonio, avaliacao, teleconsulta
- Perfil do profissional com formacao, especialidades, horarios
- Avaliacao e comentarios de outros usuarios Glicara
- Botao de agendamento (link externo ou integracao futura)
- Secao "indicados pela comunidade"

#### E) Comunidade Glicara
- Feed principal com posts de usuarios
- Grupos tematicos: "Diabetes Tipo 1", "Gestacional", "Pais de DM1", "Receitas", "Exercicios", "Saude Mental"
- Sistema de reacao (apoiar, util, inspirador — sem negatividade)
- Moderacao ativa + regras claras (sem promessa de cura, sem venda)
- Especialistas verificados podem responder com selo
- Desafios semanais ("7 dias medindo glicemia de jejum")

### 6.2 Features Premium

#### F) Painel do Cuidador
- Convite por e-mail/link para familiar
- Visualizacao de: lembretes confirmados, glicemias, alertas
- Notificacao se usuario nao confirmar lembrete em X horas
- Modo "cuidador de crianca" com controle total

#### G) Relatorios Medicos
- Relatorio PDF/imprimivel com: media glicemica, variabilidade, adesao a medicacao, padroes
- Formato padrao para consulta medica
- Comparativo entre periodos
- Grafico de tempo no alvo (Time in Range)

#### H) Integracao com Dispositivos (V2+)
- Importacao de dados de glicosimetros Bluetooth
- Integracao com Apple Health / Google Fit
- Futuramente: leitura de CGM (sensor continuo)

#### I) Assistente IA (V2+)
- Chat com IA treinada em conteudo sobre diabetes
- Respostas baseadas nos dados do usuario
- Nunca prescreve, sempre sugere consultar profissional
- Exemplos: "Sua glicemia pos-almoco tem subido. Quer ver receitas de baixo IG para almoco?"

---

## 7. ESTRUTURA DAS PAGINAS DO SISTEMA

### 7.1 Paginas Publicas (Marketing)
```
/                     → Landing page (hero, features, depoimentos, planos, CTA)
/sobre                → Missao, equipe, historia
/funcionalidades      → Detalhamento visual de cada feature
/planos               → Comparativo de planos com CTA
/blog                 → Conteudo educativo sobre diabetes
/blog/:slug           → Artigo individual
/profissionais        → Pagina para medicos indicarem Glicara
/termos               → Termos de uso
/privacidade          → Politica de privacidade (LGPD compliant)
/cadastro             → Registro de novo usuario
/login                → Login
/recuperar-senha      → Reset de senha
```

### 7.2 Dashboard do Usuario (App)
```
/app                      → Dashboard principal (resumo do dia)
/app/lembretes            → Lista e gestao de lembretes
/app/lembretes/novo       → Cadastro de novo medicamento/insulina
/app/glicemia             → Registro e historico de glicemia
/app/glicemia/registrar   → Novo registro rapido
/app/alimentacao          → Cardapio semanal + receitas
/app/alimentacao/receitas → Banco de receitas com busca
/app/alimentacao/lista    → Lista de compras
/app/medicos              → Mapa de profissionais proximos
/app/medicos/:id          → Perfil do profissional
/app/comunidade           → Feed principal
/app/comunidade/:grupo    → Grupo tematico
/app/comunidade/post/:id  → Post individual com respostas
/app/relatorios           → Relatorios e exportacao PDF
/app/perfil               → Dados pessoais, tipo de diabetes, metas
/app/perfil/cuidadores    → Gerenciar cuidadores vinculados
/app/configuracoes        → Notificacoes, tema, idioma
/app/assinatura           → Gestao do plano
```

### 7.3 Painel do Cuidador
```
/cuidador                  → Dashboard do cuidador
/cuidador/paciente/:id     → Visao do familiar acompanhado
/cuidador/alertas          → Alertas recebidos
```

### 7.4 Painel Administrativo
```
/admin                     → Dashboard geral (metricas)
/admin/usuarios            → Gestao de usuarios
/admin/profissionais       → Gestao de medicos cadastrados
/admin/comunidade          → Moderacao de posts e denuncias
/admin/conteudo            → Gestao de receitas e artigos
/admin/planos              → Gestao de planos e cupons
/admin/financeiro          → Receita, churn, MRR, LTV
/admin/notificacoes        → Gestao de campanhas push/email
/admin/configuracoes       → Config do sistema
```

---

## 8. FLUXO DO USUARIO

```
┌─────────────────────────────────────────────────────────────────┐
│                    JORNADA DO USUARIO GLICARA                   │
└─────────────────────────────────────────────────────────────────┘

1. DESCOBERTA
   └→ Anuncio / SEO / Indicacao medica / Comunidade
       └→ Landing page (/)

2. CADASTRO (onboarding em 4 etapas)
   └→ Etapa 1: Email + senha (ou Google/Apple)
   └→ Etapa 2: "Qual seu tipo de diabetes?" (Tipo 1 / Tipo 2 / Gestacional / Pre-diabetes / Cuidador)
   └→ Etapa 3: "Quais medicamentos voce usa?" (busca + selecao rapida dos mais comuns)
   └→ Etapa 4: "Em que horarios voce costuma aplicar/tomar?" (config de lembretes inicial)

3. PRIMEIRO USO (Dia 1)
   └→ Dashboard com checklist de boas-vindas:
       ☐ Configurar primeiro lembrete
       ☐ Registrar primeira glicemia
       ☐ Explorar cardapio semanal
       ☐ Encontrar um medico proximo
       ☐ Entrar na comunidade
   └→ Tooltip guiado nos primeiros cliques
   └→ Primeiro lembrete dispara em algumas horas

4. USO RECORRENTE (Dia 2-30)
   └→ Lembretes diarios → confirma tomada
   └→ Registra glicemia 1-3x por dia
   └→ Consulta cardapio e receitas
   └→ Participa de 1 desafio semanal na comunidade
   └→ Recebe insight semanal: "Sua media melhorou 8% esta semana!"

5. RETENCAO (Dia 30+)
   └→ Relatorio mensal automatico
   └→ Notificacao: "Voce completou 30 dias! Veja sua evolucao"
   └→ Convite para plano Premium com trial de 7 dias
   └→ Streak de adesao ("15 dias seguidos sem esquecer insulina!")
   └→ Comunidade como habito social

6. CONVERSAO (Free → Premium)
   └→ Gatilhos: paywall suave ao tentar exportar PDF,
      acessar cardapio completo, ou adicionar cuidador
   └→ Trial de 7 dias gratis
   └→ Upsell contextual (nao agressivo)

7. ADVOCACIA
   └→ "Convide um amigo e ganhe 1 mes gratis"
   └→ Compartilhar conquistas na comunidade
   └→ Indicar para o medico
```

---

## 9. ESTRUTURA DE PLANOS E MONETIZACAO

### Planos

| Feature | Gratuito | Essencial (R$19,90/mes) | Premium (R$39,90/mes) |
|---|:---:|:---:|:---:|
| Lembretes de medicacao | 3 medicamentos | Ilimitado | Ilimitado |
| Registro de glicemia | Sim | Sim | Sim |
| Graficos basicos | Sim | Sim | Sim |
| Graficos avancados + padroes | — | Sim | Sim |
| Cardapio semanal | 1 dia preview | Completo | Completo + personalizacao |
| Receitas | 5 por semana | Ilimitadas | Ilimitadas |
| Lista de compras | — | Sim | Sim |
| Mapa de medicos | Basico (3 resultados) | Completo + filtros | Completo + filtros |
| Comunidade | Leitura apenas | Participacao total | Participacao + grupos VIP |
| Relatorio PDF | — | Basico | Completo + historico |
| Painel do cuidador | — | — | Ate 3 cuidadores |
| Lembretes WhatsApp/SMS | — | — | Sim |
| Assistente IA | — | — | Sim (V2) |
| Suporte | Email | Email prioritario | Chat + email prioritario |

### Descontos
- **Anual:** 2 meses gratis (equivale a ~17% desconto)
- **Estudante/aposentado:** 30% off com comprovante
- **Indicacao:** 1 mes gratis para quem indica e quem e indicado

### Receita Projetada (Cenario conservador - 12 meses)
```
Meta: 5.000 usuarios em 12 meses
- 60% free (3.000)
- 25% Essencial (1.250 × R$19,90 = R$24.875/mes)
- 15% Premium (750 × R$39,90 = R$29.925/mes)
- MRR projetado: ~R$54.800/mes
- ARR projetado: ~R$657.600/ano
```

---

## 10. FUNCOES DO PAINEL ADMINISTRATIVO

### Dashboard Principal
- **MRR atual** (Monthly Recurring Revenue)
- **Usuarios ativos** (DAU/MAU)
- **Taxa de churn** mensal
- **Novos cadastros** hoje/semana/mes
- **Conversao free → pago** (funil)
- **NPS** (Net Promoter Score)

### Gestao de Usuarios
- Lista com busca, filtros (plano, tipo diabetes, data cadastro, status)
- Visualizar perfil completo do usuario
- Alterar plano manualmente
- Desativar/banir conta
- Exportar CSV

### Gestao de Profissionais de Saude
- Aprovar/rejeitar cadastro de medicos
- Verificar CRM/CRN
- Gerenciar avaliacoes e denuncias
- Destacar profissionais parceiros

### Moderacao da Comunidade
- Fila de denuncias com prioridade
- Remover posts/comentarios
- Banir usuarios da comunidade
- Gerenciar regras e filtros automaticos
- Palavras-chave bloqueadas

### Gestao de Conteudo
- CRUD de receitas (ingredientes, modo preparo, info nutricional, IG)
- CRUD de artigos do blog
- Gestao de cardapios semanais
- Programacao de publicacao

### Financeiro
- Receita por plano
- LTV (Lifetime Value) medio
- Churn por cohort
- Reembolsos
- Cupons ativos e utilizacao

### Campanhas e Notificacoes
- Push notifications segmentadas
- Campanhas de email (integracao com SendGrid/Resend)
- Automacoes (ex: "usuario nao logou em 7 dias → email de reengajamento")

---

## 11. IDEIAS EXTRAS PARA AUMENTAR RETENCAO

### Gamificacao
1. **Streaks de adesao** — "12 dias seguidos confirmando insulina!" com badge visual
2. **Niveis de usuario** — Iniciante → Consciente → Disciplinado → Mestre Glicara
3. **Conquistas desbloqueaveis** — "Primeira semana completa", "100 registros de glicemia", "30 dias no alvo"
4. **Desafios semanais** — "Registre glicemia 3x por dia por 7 dias" com recompensa (badge + destaque na comunidade)

### Engajamento Social
5. **Buddy System** — conectar 2 usuarios com perfil similar para apoio mutuo
6. **AMAs (Ask Me Anything)** — lives mensais com endocrinologistas/nutricionistas na comunidade
7. **Historia da Semana** — usuario conta sua jornada, e destacado no app
8. **Ranking de comunidade** — "membros mais colaborativos" (sem competicao, foco em apoio)

### Conteudo e Educacao
9. **Mini-curso de onboarding** — "Diabetes 101" em 5 dias por email/push
10. **Dica do dia** — card no dashboard com informacao rapida e util
11. **Quiz semanal** — "Voce sabia que...?" com fato sobre diabetes
12. **Alertas sazonais** — "No verao, cuidado com desidratacao" / "Festas de fim de ano: como manter o controle"

### Utilidade Pratica
13. **Cartao digital de emergencia** — QR code com info medica basica (tipo diabetes, medicamentos, contato emergencia)
14. **Modo viagem** — ajustar fusos horarios de lembretes automaticamente
15. **Integracao com farmacias** — alerta de promocao de insulina/fitas proximas (parceria futura)
16. **Relatorio anual** — "Seu Ano com Glicara" — retrospectiva com evolucao

---

## 12. SUGESTAO DE STACK IDEAL

### Frontend
| Camada | Tecnologia | Justificativa |
|---|---|---|
| Framework | **Next.js 14+ (App Router)** | SSR, SEO para landing/blog, API routes, excelente DX |
| UI Library | **React 18+** | Ecossistema maduro, componentes reutilizaveis |
| Estilizacao | **Tailwind CSS + shadcn/ui** | Produtividade, consistencia, componentes acessiveis |
| Estado | **Zustand** | Leve, simples, sem boilerplate |
| Formularios | **React Hook Form + Zod** | Validacao robusta com tipagem |
| Graficos | **Recharts ou Tremor** | Graficos de glicemia bonitos e responsivos |
| PWA | **next-pwa** | Experiencia nativa no mobile sem app store (V1) |
| Animacoes | **Framer Motion** | Transicoes premium e suaves |

### Backend
| Camada | Tecnologia | Justificativa |
|---|---|---|
| Runtime | **Node.js com Next.js API Routes** | Unificado com frontend, serverless-ready |
| ORM | **Prisma** | Type-safe, migrations, otimo com PostgreSQL |
| Auth | **NextAuth.js (Auth.js v5)** | Google, Apple, email/senha, sessoes seguras |
| Validacao | **Zod** | Schema compartilhado front+back |

### Banco de Dados
| Servico | Uso |
|---|---|
| **Supabase (PostgreSQL)** | Banco principal — usuarios, medicamentos, glicemias, posts |
| **Redis (Upstash)** | Cache de sessoes, rate limiting, filas |
| **Supabase Storage / S3** | Imagens de perfil, receitas, PDFs |

### Infraestrutura
| Servico | Uso |
|---|---|
| **Vercel** | Deploy do Next.js, edge functions, analytics |
| **Supabase** | BaaS — DB, auth alternativo, storage, realtime |
| **Resend** | Emails transacionais (confirmacao, lembretes, relatorios) |
| **Novu ou OneSignal** | Push notifications multi-canal |
| **Stripe** | Pagamentos, assinaturas, portal do cliente |
| **PostHog** | Analytics de produto, funnels, feature flags |
| **Sentry** | Monitoramento de erros |
| **GitHub Actions** | CI/CD |

### Mobile (V2)
| Tecnologia | Justificativa |
|---|---|
| **React Native (Expo)** | Compartilha logica com web, push nativo, acesso a sensores |
| **Expo Notifications** | Push local e remoto |
| **Expo Health** | Integracao Apple Health / Google Fit |

---

## 13. SEGURANCA, PRIVACIDADE E BOAS PRATICAS

### LGPD (Lei Geral de Protecao de Dados)
- **Consentimento explicito** no cadastro para coleta de dados de saude (dados sensiveis - Art. 11)
- **Finalidade clara** — cada dado coletado tem justificativa documentada
- **Direito de acesso/portabilidade** — usuario pode exportar todos os seus dados
- **Direito de exclusao** — "deletar minha conta" com remocao real dos dados em 30 dias
- **DPO (Data Protection Officer)** designado
- **Politica de privacidade** clara, acessivel e em linguagem simples
- **Base legal:** Consentimento do titular (dados de saude sao dados sensiveis)

### Seguranca Tecnica
- **Criptografia em transito:** TLS 1.3 em todas as conexoes
- **Criptografia em repouso:** dados de saude criptografados no banco (AES-256)
- **Autenticacao:** bcrypt para senhas, MFA opcional (TOTP)
- **Sessoes:** JWT com rotacao, httpOnly cookies, CSRF protection
- **Rate limiting:** protecao contra brute force em login e APIs
- **Input sanitization:** prevencao de XSS e SQL injection em todos os inputs
- **RBAC:** controle de acesso por role (usuario, cuidador, admin, profissional)
- **Audit log:** registrar acessos a dados sensiveis
- **Backups:** diarios automaticos com retencao de 90 dias
- **Pentest:** pelo menos 1 antes do lancamento publico

### Boas Praticas de Healthtech
- **Nunca usar termos medicos prescritivos** — "sugestao" e "organizacao", nunca "tratamento" ou "prescricao"
- **Disclaimers visiveis** em todas as telas de alimentacao e conteudo de saude
- **Nao correlacionar dados para diagnostico** — a plataforma organiza, nao interpreta clinicamente
- **Validacao de profissionais** — verificar CRM/CRN antes de exibir no mapa
- **Moderacao ativa** — impedir conteudo perigoso na comunidade (curas milagrosas, anti-ciencia)
- **Termos de uso claros** sobre limitacao de responsabilidade

---

## 14. ROADMAP — V1, V2 e V3

### V1 — MVP (3-4 meses) — "O Essencial que Funciona"
**Objetivo:** Validar produto com primeiros 500 usuarios

- [ ] Landing page com waitlist/cadastro
- [ ] Onboarding em 4 etapas
- [ ] Dashboard com resumo do dia
- [ ] Cadastro de medicamentos/insulinas com lembretes (push)
- [ ] Registro manual de glicemia + grafico basico
- [ ] Cardapio semanal simples (10-15 receitas iniciais)
- [ ] Mapa de medicos (integracao Google Places API + cadastro manual)
- [ ] Comunidade basica (feed + 3 grupos)
- [ ] Perfil do usuario com tipo de diabetes
- [ ] Planos Free + Essencial via Stripe
- [ ] Painel admin basico (usuarios, conteudo)
- [ ] PWA para uso mobile
- [ ] Blog com 10 artigos SEO

### V2 — Crescimento (3-4 meses apos V1) — "Profundidade e Mobile"
**Objetivo:** Escalar para 2.000+ usuarios, lancamento mobile

- [ ] App nativo iOS/Android (React Native/Expo)
- [ ] Lembretes via WhatsApp (API oficial)
- [ ] Rotacao de local de aplicacao (mapa corporal)
- [ ] Graficos avancados + deteccao de padroes
- [ ] Relatorio PDF para medico
- [ ] Painel do cuidador
- [ ] Plano Premium completo
- [ ] Gamificacao (streaks, conquistas, niveis)
- [ ] Desafios semanais na comunidade
- [ ] Sistema de avaliacao de profissionais
- [ ] Alertas de estoque de medicamento
- [ ] Dica do dia no dashboard
- [ ] Cartao digital de emergencia

### V3 — Escala e IA (4-6 meses apos V2) — "Inteligencia e Ecossistema"
**Objetivo:** 5.000+ usuarios, diferenciacao por IA

- [ ] Assistente IA contextual (baseado nos dados do usuario)
- [ ] Integracao com glicosimetros Bluetooth
- [ ] Integracao Apple Health / Google Fit
- [ ] Lista de compras automatica por cardapio
- [ ] Buddy System (pareamento de usuarios)
- [ ] AMAs com profissionais (lives na comunidade)
- [ ] Modo viagem (ajuste de fuso)
- [ ] Relatorio anual "Seu Ano com Glicara"
- [ ] API publica para clinicas/profissionais
- [ ] Parceria com farmacias (alertas de promocao)
- [ ] Programa de indicacao automatizado
- [ ] Internacionalizacao (espanhol como segundo idioma)

---

## 15. POSICIONAMENTO VISUAL DA MARCA

### Identidade
| Aspecto | Direcao |
|---|---|
| **Nome** | Glicara — fusao de "Glicemia" + "Cara" (cuidado, identidade) |
| **Tagline** | "Sua rotina com diabetes, finalmente organizada." |
| **Tom de voz** | Acolhedor, otimista, empoderador. Nunca clinico ou assustador |
| **Personalidade** | Um amigo inteligente que entende diabetes e te ajuda sem julgamento |

### Paleta de Cores
```
Primaria:     #0D9488 (teal/verde-azulado — saude, calma, confianca)
Secundaria:   #6366F1 (indigo — tecnologia, inovacao)
Acento:       #F59E0B (amber — energia, positividade, alertas amigaveis)
Sucesso:      #10B981 (verde esmeralda — "no alvo", positivo)
Alerta:       #EF4444 (vermelho suave — fora do alvo, atencao)
Fundo claro:  #F8FAFC (slate-50)
Fundo escuro: #0F172A (slate-900, para dark mode)
Texto:        #1E293B (slate-800)
```

### Tipografia
- **Headings:** Inter (moderna, limpa, legivel)
- **Body:** Inter ou DM Sans
- **Numeros/dados:** JetBrains Mono ou Space Mono (para glicemias, metricas)

### Estilo Visual
- **Cards com bordas suaves** (rounded-2xl) e sombras leves
- **Icones:** Lucide Icons (consistente com shadcn/ui)
- **Ilustracoes:** Estilo flat healthcare com diversidade (pessoas reais, nao clipart)
- **Graficos:** gradientes suaves, cores da paleta, tooltips informativos
- **Espacamento generoso** — sem telas poluidas, respiro visual
- **Dark mode** como cidadao de primeira classe (muitos usuarios checam glicemia a noite)
- **Microinteracoes:** animacoes sutis em confirmacao de lembrete, registro de glicemia, conquistas

### Referencias Visuais (Benchmarks de UX)
- **Linear** — simplicidade e elegancia de dashboard SaaS
- **Headspace** — acolhimento e onboarding premium de app de saude
- **Dexcom Clarity** — graficos de glicemia bem feitos
- **Notion** — fluidez e organizacao
- **Stripe Dashboard** — painel admin impecavel

### Logo (Direcao)
- Simbolo: gota + onda (representando glicemia estabilizada)
- Ou: circulo com grafico de linha suave dentro
- Wordmark limpa, sem serifa, com o "G" destacado
- Deve funcionar bem em: favicon, app icon, header, impressao

---

## RESUMO EXECUTIVO

| Aspecto | Detalhe |
|---|---|
| Produto | Glicara — SaaS para gestao da rotina diabetica |
| Modelo | Freemium B2C (R$0 / R$19,90 / R$39,90 por mes) |
| Stack | Next.js + Tailwind + Supabase + Vercel + Stripe |
| V1 MVP | 3-4 meses de desenvolvimento |
| Meta 12 meses | 5.000 usuarios, MRR ~R$55k |
| Diferencial | Unica plataforma que une lembretes + alimentacao + medicos + comunidade para diabetes |
| Compliance | LGPD, dados sensiveis criptografados, disclaimers medicos |

---

> **Proximo passo:** Definir se partimos para o desenvolvimento da V1 (landing + dashboard + core features) ou se deseja ajustar algum aspecto do planejamento.
