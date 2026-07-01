# Landing Page - institutoeuricofranca

Projeto HTML single-page para o Instituto Eurico Franca, com foco principal em hipnoterapia clínica.

## Arquivos

- `index.html`: página final para publicação.
- `README.md`: instruções técnicas, histórico do briefing e observações de edição.

## Diretriz aplicada nesta versão

Todos os termos internos usados no prompt/briefing de criação foram removidos do conteúdo público do `index.html` e mantidos somente neste `README.md`.

Termos e conceitos internos que não devem aparecer no site publicado:

- prompt;
- landing page;
- alta conversão;
- UX;
- UI;
- metodologia XYZ;
- método XYZ;
- copy;
- CTA;
- base de dados;
- layout de referência;
- usuário;
- prova de autoridade;
- redução de objeções;
- funil;
- estratégia de conversão;
- página orientada à tomada de decisão.

No HTML final, esses termos foram substituídos por linguagem pública e natural, como:

- site;
- atendimento;
- processo terapêutico;
- como funciona;
- conversa inicial;
- dúvidas frequentes;
- conteúdos do Instituto;
- falar no WhatsApp.

## Principais adaptações feitas

- Header fixo com navegação limpa.
- Hero principal com mensagem focada em hipnoterapia clínica.
- Seção de indicações: ansiedade, fobias, sono, autoestima, padrões repetitivos e traumas.
- Seção de processo terapêutico em três etapas, sem mencionar metodologia XYZ.
- Seção sobre Eurico Franca.
- Seção com conteúdos do YouTube.
- FAQ com comunicação responsável.
- Formulário simples que abre o WhatsApp com mensagem personalizada.
- Botão flutuante de WhatsApp.
- Links oficiais de Instagram e YouTube informados no briefing.

## Como trocar o WhatsApp

No arquivo `index.html`, procure por:

```js
const WHATSAPP_NUMBER = '5511973102446';
```

Troque pelo número desejado no formato internacional, sem espaços, sem parênteses e sem traços.

Também substitua links diretos como:

```txt
https://wa.me/5511973102446
```

## Como trocar imagens

Recomendação de pasta:

```txt
/assets/img/
  banner-desktop.webp
  banner-mobile.webp
  eurico-franca.webp
  sala-atendimento.webp
  conteudo-youtube-01.webp
```

Depois, substitua o caminho da imagem no `src` do HTML.

## Publicação

Pode ser publicado na Netlify, Vercel, Hostinger, cPanel ou qualquer hospedagem que aceite HTML estático.

Para Netlify:

1. Crie uma pasta com `index.html`, `README.md` e a pasta `/assets/img/`, se houver imagens locais.
2. Arraste a pasta para o painel da Netlify ou conecte ao GitHub.
3. Confirme se o arquivo principal está nomeado como `index.html`.

## Observação importante

A página foi escrita de forma ética: hipnoterapia é apresentada como processo terapêutico individual, sem prometer cura, prazo fixo ou resultado garantido, e sem substituir acompanhamento médico ou psicológico quando necessário.


## Ajuste aplicado — cabeçalho compacto

O cabeçalho foi reduzido em altura para liberar mais área vertical para o banner principal. Foram ajustados: espaçamento interno do header, tamanho da logo, escala dos textos do cabeçalho, botões de navegação e espaçamento superior da primeira dobra.

## Atualização dos ícones da seção "Quando a hipnoterapia pode ajudar"

A seção foi padronizada para usar ícones em SVG inline, com o mesmo padrão visual do banner principal: traço branco, base circular em azul-marinho com toque verde/teal e aparência mais clínica/premium.

Categorias padronizadas:
- Ansiedade
- Insônia
- Fobias
- Baixa autoestima
- Compulsões
- Relacionamentos

Os ícones não dependem de arquivos externos de imagem, por isso aparecem diretamente no HTML e carregam junto com a página.


## Link de localização

O site usa o link do Google Maps no menu, na seção de contato, na seção do especialista e no rodapé:

```txt
https://share.google/1lcah9z6ma3azPe02
```

Para trocar a localização, substitua esse link no `index.html`.


## Avaliações no Google

Foi adicionada uma seção de avaliações baseada nos prints enviados pelo usuário, destacando nota 5,0, 85 avaliações e trechos de depoimentos. O botão direciona para o link de localização/Google Maps informado no projeto.


## Seção Sobre o Instituto

Foi adicionada uma seção institucional para apresentar o Instituto Eurico Franca de forma mais forte e comercial, com foco em:

- mais de 23 anos de experiência;
- atendimento especializado e humanizado;
- Hipnoterapia, Psicanálise, Psicoterapia, PNL, Hipnose Ericksoniana e Reiki;
- terapias integrativas sem prometer cura ou resultado garantido;
- CTA para WhatsApp e link de localização.

Texto resumido aplicado no site:

> No Instituto Eurico Franca, o atendimento une experiência clínica, acolhimento e práticas terapêuticas integrativas para ajudar cada pessoa a compreender melhor seus desafios emocionais e buscar mais equilíbrio na rotina.


## Ajuste recente

- Cabeçalho reduzido para liberar mais área vertical ao banner principal.
- Logo, textos, navegação e botão do topo foram compactados.
- Espaçamento superior da primeira dobra reduzido sem afetar o banner.

Atualização: cabeçalho ajustado com logo maior, com sobreposição suave sobre o banner principal, e textos do cabeçalho protegidos contra quebra de linha.


## Política de Privacidade

Foi adicionada uma seção pública no `index.html` com o id:

```txt
#politica-privacidade
```

Também foi criada uma página independente para uso em plataformas como Google Ads:

```txt
politica-de-privacidade.html
```

URL esperada após publicação na Netlify:

```txt
https://SEU-DOMINIO.netlify.app/politica-de-privacidade.html
```

Essa página deve ser usada como URL de política de privacidade em cadastros, formulários, campanhas e configurações de anúncios.

## Ajuste de cabeçalho - logo e alinhamento

- O logo foi mantido totalmente à esquerda, com efeito de degradê e brilho para integrar visualmente com o banner principal.
- O logo pode invadir suavemente a área do banner sem aumentar a altura do cabeçalho.
- Os textos da marca no cabeçalho usam `white-space: nowrap`, evitando quebra de linha.
- O menu superior foi deslocado para iniciar alinhado à área textual do banner principal, começando pelo item “Instituto”, em referência visual ao texto “Sua mente”.


## Ajuste recente do cabeçalho

- Logo mantido dentro de um círculo com degradê interno alinhado às cores do banner.
- Menu aproximado da marca, com pequena distância visual entre nome do Instituto e itens do cabeçalho.
- Botão “Agendar avaliação” com efeito de pulsar e leve aumento visual para reforçar a ação principal.

## Atualização — Política de Privacidade como página virtual/separada

A Política de Privacidade foi removida como seção visível dentro da página principal (`index.html`) e mantida como arquivo independente:

```txt
politica-de-privacidade.html
```

Assim, após publicar na Netlify, a URL pode ser usada diretamente em campanhas, catálogo, Google Ads, Meta Ads, formulários e configurações de rastreamento:

```txt
https://seu-dominio.netlify.app/politica-de-privacidade.html
```

O rodapé do site mantém apenas um link discreto para essa página separada. Isso deixa a página principal mais limpa e mantém a política acessível publicamente para aprovação e conformidade de campanhas.

## Ajuste aplicado — logo dentro do círculo

O logo do cabeçalho foi ajustado para ocupar praticamente toda a área circular de referência, mantendo `overflow: hidden` no círculo para impedir que a marca ultrapasse o limite visual. O efeito de integração com o fundo permanece dentro do círculo.


## Ajuste do logo no cabeçalho

O logo do cabeçalho foi ajustado para remover o fundo circular preenchido. Agora a marca fica sobre fundo transparente, com uma borda circular em degradê pulsante, mantendo integração visual com o banner principal sem criar um bloco sólido atrás do logo.

## Ajuste visual do logo

O cabeçalho usa o arquivo `assets/img/logo-instituto.svg` com fallback para PNG. O logo recebeu fundo radial translúcido com blur, borda em degradê pulsante e sombra suave para parecer integrado às cores do banner/cabeçalho sem criar um círculo sólido atrás da marca.
