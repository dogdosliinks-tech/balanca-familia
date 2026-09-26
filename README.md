# Balança da Família

App simples para acompanhar o peso da família: uma pessoa por perfil, pesagens por data,
gráfico de tendência e metas. Dá para digitar o peso ou mandar uma foto/print do app da balança
(o texto é lido no próprio aparelho).

## Como usar

**No celular Android:** abra https://dogdosliinks-tech.github.io/balanca-familia/ no Chrome e toque em
**Instalar app** (no topo) ou no menu ⋮ → **Instalar app**. Também dá para baixar o APK na aba
[Releases](https://github.com/dogdosliinks-tech/balanca-familia/releases/latest).

**No computador:** abra o `index.html` no navegador.

## Privacidade

- **As pesagens ficam só no aparelho** (armazenamento do navegador). Nada é enviado para servidor nenhum,
  e este repositório não contém dado de ninguém.
- Para trocar de celular, use **Baixar backup** e depois **Importar backup** no aparelho novo.
  Os arquivos de backup têm dados pessoais: guarde com cuidado e não publique.
- A leitura de foto usa o Tesseract.js, que roda **dentro do aparelho**; na primeira vez ele baixa o
  leitor pela internet (jsDelivr). A imagem não sai do celular.
- A fonte do app vem do Google Fonts.

## Licença

MIT — veja `LICENSE`.
