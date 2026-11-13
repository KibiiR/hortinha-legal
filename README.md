# Páginas legais da Hortinha

As páginas que a Google Play exige que existam num endereço público, para a
app **Hortinha** (`pt.hortinha.app`):

- **Política de privacidade** — <https://kibiir.github.io/hortinha-legal/politica-de-privacidade.html>
- **Apagar a conta** — <https://kibiir.github.io/hortinha-legal/apagar-conta.html>

E uma que ninguém exige, mas que faz falta:

- **Conta confirmada** — <https://kibiir.github.io/hortinha-legal/conta-confirmada.html>
  É para aqui que o Supabase manda quem clica em "confirmar email". Sem ela,
  a pessoa confirmava a conta e aterrava numa página de erro.

## Isto é saída, não é fonte

**Não edites o HTML daqui.** Estas páginas são geradas a partir do markdown
que vive no repositório da app, por `ferramentas/fazer-privacidade.mjs`, e
qualquer alteração feita aqui desaparece na geração seguinte.

A fonte é o markdown por duas razões. Uma política que não coincide com o que
a app faz é exactamente o problema que ela devia resolver, e manter texto em
dois sítios é tê-los a divergir ao fim da segunda alteração. E um texto em
markdown revê-se num diff, que é como se vê o que mudou numa política.

Para alterar: mexe no markdown lá, corre o gerador, e copia os ficheiros
para cá.

## Porque é que este repositório existe à parte

O código da Hortinha é privado, e o GitHub Pages em repositório privado é
plano pago. Este repositório tem só as páginas públicas — o que lhes dá
um endereço estável sem abrir o resto.

Os ficheiros são autónomos: sem CSS externo, sem JavaScript, sem tipos de
letra remotos, sem um único pedido à rede. Quem abre a política de privacidade
não devia ser seguido por fazê-lo.
