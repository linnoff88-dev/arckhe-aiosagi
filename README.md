# ðŸ§  AIOS â€” Curso Completo AvanÃ§ado

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso completo em portuguÃªs sobre **AIOS (AI Agent Operating System)** â€” o kernel da [AGI Research (Rutgers)](https://github.com/agiresearch) que embute LLMs no sistema operacional para gerenciar agentes como processos.

Material baseado nas docs oficiais ([docs.aios.foundation](https://docs.aios.foundation/)) e nos papers do projeto (COLM 2025, NAACL 2025, ICLR 2025).

## Estrutura

6 trilhas progressivas Â· 12 mÃ³dulos Â· 72 tÃ³picos Â· ~10h de conteÃºdo

| Trilha | Tema | NÃ­vel | DuraÃ§Ã£o |
|--------|------|-------|---------|
| T1 ðŸ§  Fundamentos | O que Ã© AIOS, posicionamento, paper COLM | BÃ¡sico | ~1h30 |
| T2 ðŸ—ï¸ Arquitetura | Kernel + SDK, syscalls, 6 mÃ³dulos internos | MÃ©dio | ~2h |
| T3 âš™ï¸ InstalaÃ§Ã£o | Python, requirements, providers, Terminal UI | BÃ¡sico | ~1h30 |
| T4 ðŸ§° SDK Cerebrum | Local/Remote, paper NAACL, primeiro agente | MÃ©dio | ~1h30 |
| T5 ðŸ¤– Agentes em ProduÃ§Ã£o | OpenAGI, AutoGen, casos prÃ¡ticos | AvanÃ§ado | ~2h |
| T6 ðŸ§© Computer-Use & ExtensÃ£o | LiteCUA, MCP, A-MEM, LSFS, Rust | AvanÃ§ado | ~2h |

## Como rodar localmente

Site estÃ¡tico puro â€” qualquer servidor HTTP serve:

```bash
python3 -m http.server 8080
# abra http://localhost:8080
```

Ou abra direto `index.html` no navegador.

## Sobre o material

- **Independente** â€” nÃ£o Ã© material oficial da AGI Research, Ã© curso comunitÃ¡rio em portuguÃªs.
- **Aberto** â€” fonte completa neste repo, copie/forke/melhore Ã  vontade.
- **Baseado em fonte primÃ¡ria** â€” papers, repo oficial, docs e Discord.

Repos de referÃªncia:
- [agiresearch/AIOS](https://github.com/agiresearch/AIOS) â€” kernel
- [agiresearch/Cerebrum](https://github.com/agiresearch/Cerebrum) â€” SDK
- [agiresearch/A-mem](https://github.com/agiresearch/A-mem) â€” memÃ³ria agÃªntica
- [agiresearch/LiteCUA](https://github.com/agiresearch/LiteCUA) â€” computer-use
- [agiresearch/openagi](https://github.com/agiresearch/openagi) â€” framework de agentes

## LicenÃ§a

Material educacional â€” uso livre com atribuiÃ§Ã£o. INEMA.CLUB Â· 2026.

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>