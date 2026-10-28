# invia-sites (hub)

Projeto "hub" do Vercel. Não tem site próprio: só encaminha cada slug para o projeto do site (Vercel Multi Zones).

Para adicionar um site novo, incluir as duas linhas de `rewrites` do slug no `vercel.json` e dar push na `main`. Manter o `"trailingSlash": false`: ele redireciona `/slug/` para `/slug` (sem ele, dá 404).

| Slug | Destino |
|---|---|
| `/fv-energia` | https://fv-energia-solar.vercel.app/fv-energia |
| `/renata-atanasio` | https://renata-atanasio.vercel.app/renata-atanasio |
| `/colegio-davilohn` | https://colegio-davilohn.vercel.app/colegio-davilohn |
| `/vila-raposa` | https://vila-raposa.vercel.app/vila-raposa |
| `/studio-ello` | https://studio-ello-kappa.vercel.app/studio-ello (o nome studio-ello.vercel.app já era de outra pessoa) |
| `/mariana-cabral` | https://mariana-cabral.vercel.app/mariana-cabral |
| `/lidia-arquiteta` | https://lidia-arquiteta.vercel.app/lidia-arquiteta |
| `/thais-dela-justina` | https://thais-dela-justina.vercel.app/thais-dela-justina |
