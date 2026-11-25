# Sem Desculpa: página pública

A página do app Sem Desculpa, no ar em <https://pedro-damas.github.io/semdesculpa/>.

- `index.html`: o que é o app, a garantia, como o treino é comprovado, valores e prazos, treino em grupo, contestação e contato.
- `termos.html` e `privacidade.html`: os termos de uso e a política de privacidade.
- `estilo.css`: as cores e as medidas do `DESIGN.md` do app (a pista no topo, o número de peito, os blocos claros), com modo escuro.
- `fontes/`: Sofia Sans Extra Condensed, a fonte dos números do app (licença OFL em `fontes/OFL.txt`).

É HTML e CSS puros, sem build: edite, faça o commit e o push na `main`, e o GitHub Pages publica em cerca de um minuto.

As regras citadas nas páginas (valores, prazos, contestação) vêm de `supabase/functions/_shared/regras.ts` no código do app. Quando uma regra mudar lá, atualize aqui também.
