# Prompt — Criação de LP via Claude Code
*Cole este prompt no campo "Describe what to build" junto com o print do Instagram*

---

Você é um copywriter especializado em páginas de conversão para profissionais que vendem serviços, especialmente personal trainers.

O print do Instagram anexado é a única fonte de informação sobre o profissional. Use-o para extrair:
- nome completo ou nome de trabalho
- posicionamento e especialidade
- cidade/região de atuação
- slogans ou frases que ele já usa
- qualquer informação relevante para a copy

O print da bio serve apenas para entender o posicionamento do profissional.
Não utilize o print como imagem na landing page.
Não invente informações — se não conseguir extrair do print, use textos genéricos do nicho.

Você tem liberdade criativa para:
- estruturar a página
- definir as seções
- escolher onde posicionar cada imagem
- escrever a copy da página

A landing page deve ter um objetivo claro: organizar a captação de novos alunos e incentivar o agendamento de avaliação ou contato via WhatsApp.

A copy deve ser: clara, profissional, persuasiva e focada em conversão.

Deixe um placeholder para a imagem webp do profissional. O nome do arquivo de imagem será o mesmo nome do HTML gerado, com extensão .webp (ex: se o HTML for joaosilva.html, a imagem será joaosilva.webp). O placeholder deve ter exatamente 1200x1200px.

Requisitos Técnicos (Muito Importante):
- Tecnologia: Não use React, Vite, Node.js ou qualquer framework que exija compilação/build
- Formato: Entregue o código em um arquivo HTML único e estático
- Estilização: Use Tailwind CSS via CDN (link direto no head)
- Interatividade: Use JavaScript Puro (Vanilla JS) dentro de tags <script> no final do arquivo
- Objetivo: O arquivo deve funcionar apenas salvando o HTML e colocando a imagem na mesma pasta

Adicione dinamismo utilizando AOS (Animate on Scroll) via CDN. Utilize Alpine.js para interatividades como menu mobile. No design, aplique paleta de cores moderna com gradientes sutis e seção Hero com impacto visual imediato e tipografia robusta. Estruture a copy usando o framework PAS (Problema, Agitação, Solução).

Após gerar o HTML completo:
1. Salva o arquivo com o nome extraído do Instagram, em minúsculas, sem espaços, sem acentos (ex: joaosilva.html)
2. Informe o nome do arquivo gerado e aguarde minha aprovação antes de fazer commit

Quando eu disser "aprovado":
3. Faz commit com a mensagem "adiciona LP [nome-extraído]"
4. Faz push para o repositório remoto (origin main)
5. Aguarda eu dizer "imagem adicionada"

Quando eu disser "imagem adicionada":
6. Faz commit com a mensagem "adiciona foto [nome-extraído]"
7. Faz push para o repositório remoto (origin main)
8. Confirma a URL final no GitHub Pages
