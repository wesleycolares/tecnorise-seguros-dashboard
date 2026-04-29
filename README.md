# Dashboard de Prontidão de Dados — Projeto Seguros Tecnorise

**Repositório privado** · Tecnorise · Extraído em 28 de abril de 2026

---

## Conteúdo

| Arquivo | Descrição |
|---|---|
| `bundle.html` | Dashboard executivo interativo — abre direto no navegador, sem dependências |
| `data.json` | Dados consolidados extraídos do Gear Admin (`gear_dev`) |

---

## Como usar o dashboard

Baixe o `bundle.html` e abra no navegador. Funciona offline, sem servidor.

---

## Dados consolidados (`data.json`)

Todos os números foram extraídos em tempo real do banco `gear_dev` via Gear Admin MCP.

### Base da plataforma
| Métrica | Valor |
|---|---|
| Moradores cadastrados (ativos) | 1.564.045 |
| Condomínios ativos | 6.845 |
| Unidades com app instalado | 253.370 |
| Moradores ativos no app (30d) | 40.160 |
| Veículos cadastrados | 110.421 |

### Completude dos dados para seguros
| Campo | Completude |
|---|---|
| Data de nascimento | 96,8% ✅ |
| Foto do morador | 67,4% 🟡 |
| Celular | 65,5% 🟡 |
| CPF | 65,4% 🟡 |
| Email | 50,5% 🟡 |

### Pool qualificado para o motor de personalização
| Critério | Moradores | % da base |
|---|---|---|
| Base total | 1.564.045 | 100% |
| CPF + 18 meses na plataforma | 479.747 | 30,7% |
| CPF + 18 meses + Email | 293.667 | **18,8%** |

> Pool com personalização completa = **18,8% da base** no lançamento.

### Status dos dados do projeto
| Dado | Status | Completude |
|---|---|---|
| Veículos (placa + modelo) | ✅ Pronto | 100% |
| Data de nascimento | ✅ Pronto | 96,8% |
| Engajamento app (DAU/WAU) | ❌ Não existe | 0% |
| Perfil familiar / dependentes | ❌ Não existe | 0% |
| Síndico profissional | ❌ Não existe | 0% |
| Classe econômica por CEP | ❌ Não existe | 0% |
| Plano de saúde do morador | ⚠️ Parcial | 0,4% |
| Grupo de controle A/B | ❌ Não existe | 0% |

---

## Fonte
Gear Admin · Banco `gear_dev` · Tecnorise · Abril 2026
