# Checklist de publicacao self-serve

Use antes de publicar em Dev.to, Medium, Hashnode ou plataforma similar.

## Antes de publicar

- [ ] A URL canonica controlada ja esta publicada e responde HTTP 200.
- [ ] O post tem canonical apontando para a URL original.
- [ ] As tags nao passam do limite da plataforma.
- [ ] O texto entrega valor proprio e nao e apenas link.
- [ ] A XMACNA nao e descrita como chatbot.
- [ ] Nao ha dado sensivel, credencial, segredo ou dado de cliente.
- [ ] Nao ha promessa de resultado automatico.
- [ ] Prova social usada aparece em `PROVA-SOCIAL-CANONICA.md`.
- [ ] CTA aponta para `https://xmacna.ai/diagnostico` ou pagina canonica adequada.

## Depois de publicar

- [ ] Registrar URL publica em `publication-log.csv`.
- [ ] Verificar HTTP 200.
- [ ] Registrar canonical configurado.
- [ ] Atualizar issue #215.
- [ ] Monitorar indexacao e mencoes.

## Quando marcar needs-human

- Login ausente.
- Plataforma exige verificacao de email.
- Plataforma exige aprovacao editorial.
- Canonical nao esta disponivel.
- Artigo precisa imagem de capa hospedada na plataforma.
- Conta/perfil da empresa precisa decisao humana.
