# Roteiro de vídeo — Biblioteca Digital UniFECAF

**Duração estimada:** 3 a 4 minutos  
**Antes de gravar:** preencher nome, publicar o site e abrir navegador e VS Code.

## 0:00–0:25 — Apresentação

**Mostrar:** navegador com o topo do site em desktop.

“Olá, meu nome é [nome]. Este é meu projeto da disciplina de Design Web: uma interface para a Biblioteca Digital UniFECAF, construída somente com HTML5 e CSS3. O objetivo foi transformar a estrutura proposta em uma página moderna, responsiva e acessível.”

## 0:25–0:50 — Protótipo e implementação

**Mostrar:** protótipo da página 3 do PDF e, em seguida, voltar ao navegador.

“Mantive a sequência principal do protótipo: cabeçalho, banner, apresentação da biblioteca, quatro destaques, seis livros, três unidades e área final de contato. Os cards continuam em duas fileiras no desktop, e as unidades preservam a relação horizontal entre imagem e texto. A partir dessa base, criei hierarquia tipográfica, cores e espaçamentos.”

## 0:50–1:40 — Demonstração das seções

**Mostrar:** navegar lentamente pela página.

“No cabeçalho, os links levam diretamente às seções. O banner apresenta o propósito da interface. A seção Sobre explica que este é um projeto demonstrativo e reúne quatro benefícios. Em Nossos livros, seis obras reais em domínio público aparecem em uma grade. Os links não simulam páginas internas: direcionam ao portal Domínio Público. As unidades são blocos conceituais e não inventam endereços. No final, o visitante é orientado ao site oficial da UniFECAF.”

## 1:40–2:10 — Cores e tipografia

**Mostrar:** VS Code em `css/style.css`, nas variáveis de `:root`.

“A paleta usa azul como cor principal, branco e cinza nos fundos e amarelo como destaque de foco. As cores ficam em variáveis CSS para facilitar manutenção. Usei Arial com alternativas nativas, evitando fontes externas e mantendo carregamento simples.”

## 2:10–2:40 — Organização do código

**Mostrar:** árvore de arquivos e partes de `index.html`.

“O HTML e o CSS estão separados. O HTML usa elementos semânticos como header, nav, main, section, article e footer. As imagens ficam em assets, e a documentação fica na pasta docs. Não há JavaScript, framework ou backend.”

## 2:40–3:15 — Responsividade e acessibilidade

**Mostrar:** ferramentas de desenvolvedor; alternar entre 1440 px, 768 px e 375 px.

“O projeto usa abordagem mobile-first. Os cards ficam em uma coluna no celular, duas no tablet e três no desktop. Flexbox, Grid, medidas relativas e media queries ajustam o conteúdo sem rolagem horizontal. Também incluí textos alternativos, foco visível, hierarquia de títulos, link para pular ao conteúdo e respeito à preferência por movimento reduzido.”

## 3:15–3:45 — Desafios e encerramento

**Mostrar:** navegador no topo ou visão geral do site.

“Os principais desafios foram equilibrar uma aparência profissional com código simples e não apresentar recursos inexistentes como funcionais. O projeto reforçou meu aprendizado sobre semântica, componentes visuais, responsividade e acessibilidade. Obrigado por assistir.”

## Checklist de gravação

- trocar todos os campos entre colchetes;
- fechar abas e notificações pessoais;
- aumentar zoom do VS Code para o código ficar legível;
- testar microfone antes de gravar;
- mostrar 375 px, 768 px e 1440 px;
- conferir duração final entre 3 e 4 minutos;
- inserir link do vídeo no `README.md`.
