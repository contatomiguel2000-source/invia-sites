# invia-sites (hub)

Projeto "hub" do Vercel. Não tem site próprio: só encaminha cada slug para o projeto do site (Vercel Multi Zones).

Para adicionar um site novo, incluir as duas linhas de `rewrites` do slug no `vercel.json` e dar push na `main`.

| Slug | Destino |
|---|---|
| `/fv-energia` | https://fv-energia-solar.vercel.app/fv-energia |
