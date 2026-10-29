# Meu Treino Visual

Biblioteca visual de exercícios e montagem de treinos, feito a pedido de um personal trainer.

**Abrir o app:** https://eneas-ena.github.io/meu-treino-visual/

## Como funciona

- App feito em página web; pode ser instalado na tela inicial do iPad, iPhone ou Mac.
- Os dados ficam salvos no Supabase, por isso aparecem iguais em todos os aparelhos.
- Os serviços externos, como a inteligência artificial, passam pelo Worker `meu-treino` no Cloudflare; as chaves secretas ficam guardadas lá, nunca neste código.

## Observações

- `icone.png` (o arquivo grande) é o original do ícone; o app usa `icone-192.png` e `icone-512.png`.

## Como publicar uma nova versão

1. Nesta página do repositório, clique em **Add file → Upload files**.
2. Arraste os arquivos novos, com os mesmos nomes dos antigos.
3. Clique em **Commit changes**.

Em um ou dois minutos a nova versão está no ar no mesmo endereço.

---
Desenvolvido por Bispo Enéas Araújo.
