<div align="center">

# 9LEVEL

**Infraestrutura inteligente para quem não pode parar**

Ferramentas open source, em Go, para operar infraestrutura crítica —
binário único, zero dependências, roda no seu ambiente.

</div>

---

## Nossas soluções

Quatro produtos **open source (MIT)** que resolvem dores reais de quem opera
ambiente de produção — do monitoramento de frota à administração de banco.
Todos rodam self-hosted, sem SaaS obrigatório e sem prender seus dados.

| Produto | O que resolve | Stack | Status |
|---------|---------------|-------|--------|
| **[sysmon](https://github.com/9LEVEL/sysmon)** | Painel de todas as suas máquinas Linux na área de trabalho — fica vermelho quando um host esquenta, enche ou cai. Sem servidor, sem banco, sem nuvem | Go | MIT · `v5.7.1` |
| **[pgtui](https://github.com/9LEVEL/pgtui)** | Administração de PostgreSQL no terminal (o *k9s do Postgres*) — sessões, roles/grants, databases e tuning (advisor, `ALTER SYSTEM`, editor de `pg_hba`) | Go | MIT · `v0.5.0` |
| **[9level-monitor](https://github.com/9LEVEL/9level-monitor)** | Monitoramento real-time de PBX Asterisk — MOS, jitter, RTT, endpoints PJSIP e eventos de segurança, via AMI + ARI | Go | MIT · `v2.0.0` |
| **[lgpd-consent](https://github.com/9LEVEL/lgpd-consent)** | Gestão de cookies e consentimento em conformidade com a LGPD (Lei 13.709/18) — 100% pt-BR, zero dependências | Vanilla JS | MIT · `v1.0.2` |

---

## Quick start

```bash
# pgtui — instalação em uma linha (Linux/macOS, binário estático)
curl -fsSL https://raw.githubusercontent.com/9level/pgtui/master/install.sh | sh
```

```bash
# 9level-monitor — em 30 segundos, sem dependências externas
git clone https://github.com/9LEVEL/9level-monitor
cd 9level-monitor && cp .env.example .env && docker compose up -d
# Acesse http://localhost:8100
```

`sysmon` (desktop + agente) e `lgpd-consent` (3 arquivos, zero config) têm o
passo a passo completo no README de cada repositório.

---

## O DNA técnico

O que os quatro têm em comum — e o que você pode esperar de qualquer coisa que
publicarmos:

- **Go** — backend único, binário estático, **zero dependências externas**
- **Self-hosted** — roda on-prem ou no seu cloud; seus dados ficam com você
- **Leve** — sem runtime pesado, sem banco obrigatório onde não é preciso
- **MIT** — use em produção, modifique, distribua

---

## A missão

Não somos um MSP tradicional nem uma software house genérica. Cada produto
nasce de um problema real enfrentado operando ambiente crítico para setores
regulados — e de quem vive o *skin in the game* da operação.

**Construímos o que usamos. Abrimos o que podemos.** Ferramentas que não
dependem de nuvem de terceiro, que não prendem seus dados e que um sysadmin
consegue subir sozinho, num binário.

A maioria dos projetos é **100% MIT**. Onde existe uma **Enterprise Edition**
(ex.: 9level-monitor), ela adiciona recursos avançados, suporte com SLA,
implantação assistida e atualizações prioritárias — a Community Edition segue
livre e completa.

→ [Falar com um especialista](https://9level.com.br/contato)

---

## Contribuir

Contribuições são bem-vindas. Em qualquer repositório:

1. Faça um fork e crie sua branch (`git checkout -b feat/minha-feature`)
2. Commit seguindo [Conventional Commits](https://www.conventionalcommits.org/)
3. Push e abra um Pull Request

---

## Links

- **Site**: [9level.com.br](https://9level.com.br)
- **LinkedIn**: [/company/9LEVEL](https://linkedin.com/company/9LEVEL)
- **Contato**: github@9level.com.br

---

<div align="center">

**9LEVEL** · Joinville, SC · Ferramentas open source para infraestrutura crítica

</div>
