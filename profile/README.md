<div align="center">

# 9LEVEL

**Infraestrutura inteligente para quem não pode parar**

Ferramentas open source para infraestrutura corporativa.  
Go + Vue.js + PostgreSQL.

---

</div>

## Nossas Soluções

Cinco produtos que cobrem o ciclo completo de gestão de TI para setores regulados — do monitoramento à conformidade.

| Produto | O que resolve | Stack | Modelo | Status |
|---------|--------------|-------|--------|--------|
| **[9level-monitor](https://github.com/9LEVEL/9level-monitor)** | Monitoramento real-time de PBX Asterisk — MOS, jitter, RTT, endpoints PJSIP, alertas de segurança | Go · Vue.js · PostgreSQL | Open-core (MIT) | `v1.0.0` |
| **[lgpd-consent](https://github.com/9LEVEL/lgpd-consent)** | Gerenciamento de cookies/consentimento LGPD (Lei 13.709/18). 3 arquivos, zero deps, 100% pt-BR | JS puro | Open source (MIT) | `Publicado` |
| **Corely** | PSA/sistema de chamados — tickets, clientes, contratos, SLA automático, multi-tenant | Go · Vue.js · PostgreSQL | SaaS / On-prem | `Em dev` |
| **9Track** | Analytics comportamental com Sankey + cadeia de Markov. Funil de conversão e comportamento | Go · Vue.js · PostgreSQL | SaaS | `Em dev` |
| **AD Unlock** | Desbloqueio de contas Active Directory via Microsoft Graph API com auditoria | Go · Vue.js | On-prem | `Produção` |

---

## Quick Start

```bash
# 9level-monitor — instale em 30 segundos
git clone https://github.com/9LEVEL/9level-monitor
cd 9level-monitor
cp .env.example .env
docker compose up -d

# Acesse http://localhost:8100
# Pronto. Sem dependências externas.
```

```bash
# lgpd-consent — 3 arquivos, zero config
# Copie lgpd-consent.js, lgpd-consent.css e lgpd-consent-config.js para seu projeto
# Adicione ao HTML:
# <link rel="stylesheet" href="lgpd-consent.css">
# <script src="lgpd-consent-config.js"></script>
# <script src="lgpd-consent.js"></script>
```

---

## Stack Tecnológico

Todos os produtos compartilham o mesmo DNA técnico:

- **Golang** — Backend único, binário estático, zero dependências externas
- **Vue.js** — Frontend reativo, SPA leve, componentes reutilizáveis
- **PostgreSQL** — Multi-tenant com row-level isolation, JSONB para flexibilidade
- **Docker** — Deploy em Swarm ou Compose, registry privado, Traefik v3

---

## Enterprise

A **Community Edition** é gratuita e MIT. Use em produção, modifique, distribua.

A **Enterprise Edition** adiciona:

- Funcionalidades avançadas por produto
- Suporte com SLA definido
- Implantação assistida
- Treinamento da equipe
- Updates e patches prioritários

→ [Falar com especialista](https://9level.com.br/contato)

---

## Por que 9LEVEL?

Não somos um MSP tradicional nem uma software house genérica. Cada produto nasce de um problema real enfrentado na gestão de **1.300+ dispositivos** com EDR, XDR e NAC num escritório bancário em Joinville, SC.

Construímos o que usamos. Abrimos o que podemos.


---

## Contribuir

Contribuições são bem-vindas! Para cada repositório:

1. Fork o projeto
2. Crie sua branch (`git checkout -b feature/minha-feature`)
3. Commit suas mudanças (`git commit -m 'feat: minha feature'`)
4. Push para a branch (`git push origin feature/minha-feature`)
5. Abra um Pull Request

Usamos [Conventional Commits](https://www.conventionalcommits.org/) em todos os repositórios.

---

## Links

- **Site**: [9level.com.br](https://9level.com.br)
- **LinkedIn**: [/company/9LEVEL](https://linkedin.com/company/9LEVEL)
- **Contato**: github@9level.com.br

---

<div align="center">

**9LEVEL** · Joinville, SC · Produtos de tecnologia para setores regulados

</div>
