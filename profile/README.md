<div align="center">

# 9LEVEL

**Infraestrutura inteligente para quem não pode parar**

Ferramentas open source, em Go, para operar infraestrutura crítica —
binário único, zero dependências, roda no seu ambiente.

</div>

---

## ⭐ Destaque — pgtui

**A ferramenta *premium* de administração PostgreSQL para sysadmins & DevOps.**
Open source (MIT), teclado-first — o *k9s do Postgres*, direto no seu terminal,
num binário estático.

[![CI](https://github.com/9level/pgtui/actions/workflows/ci.yml/badge.svg)](https://github.com/9level/pgtui/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/9level/pgtui?sort=semver)](https://github.com/9level/pgtui/releases/latest)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/9LEVEL/pgtui/blob/master/LICENSE)

- **Opere, não só navegue** — veja e mate sessões, gerencie roles/grants, crie e dropa databases, tudo com guardas contra erro destrutivo.
- **Tuning de verdade** — advisor de conexões, editor `ALTER SYSTEM` (validado + `pg_reload_conf`) e **editor de `pg_hba` com safety-net anti-lockout** (backup + rollback automático se o login de admin quebrar).
- **Reset de senha com hash SCRAM-SHA-256** feito no cliente — a senha em texto nunca chega ao servidor nem aos logs.

→ **[github.com/9LEVEL/pgtui](https://github.com/9LEVEL/pgtui)**

---

## Mais soluções open source

Também **MIT**, self-hosted e sem prender seus dados:

| Produto | O que resolve | Stack | Status |
|---------|---------------|-------|--------|
| **[sysmon](https://github.com/9LEVEL/sysmon)** | Painel de todas as suas máquinas Linux na área de trabalho — fica vermelho quando um host esquenta, enche ou cai. Sem servidor, sem banco, sem nuvem | Go | MIT · `v5.7.1` |
| **[9level-monitor](https://github.com/9LEVEL/9level-monitor)** | Monitoramento real-time de PBX Asterisk — MOS, jitter, RTT, endpoints PJSIP e eventos de segurança, via AMI + ARI | Go | MIT · `v2.0.0` |
| **[lgpd-consent](https://github.com/9LEVEL/lgpd-consent)** | Gestão de cookies e consentimento em conformidade com a LGPD (Lei 13.709/18) — 100% pt-BR, zero dependências | Vanilla JS | MIT · `v1.0.2` |

---

## O DNA técnico

O que todos têm em comum — e o que você pode esperar de qualquer coisa que
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
