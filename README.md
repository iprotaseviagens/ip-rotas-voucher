# ip-rotas-voucher — descontinuado

Este gerador foi substituído em outubro de 2026 pela operação dentro do Claude. A extração do voucher da operadora é feita no próprio chat; os dois modelos vivem como Artifacts e a entrega ao cliente é sempre em PDF.

- **Voucher (confirmação de serviços):** https://claude.ai/artifact/FRGEzmtNhfPdj72mNnpRBV
- **Cartilha de boas-vindas:** https://claude.ai/artifact/PxgDWhhdTKGDRtyK6qSLs2
- **Skill `voucher-ip-rotas`** (Claude Code): `~/.claude/skills/voucher-ip-rotas/` — templates, `render-pdf.js` e as regras de curadoria.

Como usar: em qualquer chat do Claude, envie o voucher da operadora (PDF, imagem ou texto) e peça "formata esse voucher IP Rotas". O resultado são dois PDFs.

O site na Vercel está pausado e a `ANTHROPIC_API_KEY` deve ser removida do projeto e revogada no console da Anthropic. O código em `index.html` e `api/claude.js` fica aqui apenas como histórico.
