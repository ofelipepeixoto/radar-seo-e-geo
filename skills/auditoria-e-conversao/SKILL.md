---
name: auditoria-e-conversao
description: Use quando perguntarem por que uma página não aparece no Google, o que corrigir primeiro, como auditar uma migração ou por que visitas e cliques não viram pedidos.
---

Leia [o formato de evidência](../evidencia.md) e aplique o [checklist por URL](checklist.md) conforme a pergunta. Comece pela página que deveria trazer o leitor ou cliente. Determine serviço ou pauta, consulta pretendida, região quando relevante e ação esperada.

Registre status HTTP, cadeia e destino final, regras aplicáveis de robots.txt, noindex em HTML e X-Robots-Tag, canônica declarada e descoberta por links internos e sitemap. Se houver inspeção autorizada ou captura, registre indexação e canônica selecionada pelo Google. Distinga a versão indexada do teste ao vivo da interface. Com HTML isolado, cite diretivas visíveis e indique Inspeção de URL na propriedade para confirmar indexação e canônica. Em migração, compare URLs antigas com destinos equivalentes. Quando pertinente, confira Bing Webmaster Tools e recibo do IndexNow. O recibo confirma recebimento, e a indexação depende do buscador.

Revise título, H1, texto, intenção, imagens e texto alternativo, links internos, SEO local e dados estruturados. Confira se informações do serviço ou da matéria sustentam a marcação. No celular examine formulário, visibilidade dos botões e estabilidade da página. Para Core Web Vitals de campo, declare URL ou origem, período e percentil 75. Use LCP ≤ 2,5 s, INP ≤ 200 ms e CLS ≤ 0,1 como limites de boa experiência. Apresente métricas de laboratório em separado e identifique o ambiente.

Para conversão, confira separadamente descoberta na busca, visitas, cliques no WhatsApp, mensagens recebidas e pedidos registrados. Use GA4 e totais agregados do atendimento ou CRM com período e filtros comparáveis. Mantenha as etapas desconhecidas em aberto. Proponha um teste manual em celular: abrir a página, acionar o botão, verificar o evento no GA4 quando disponível e pedir ao responsável que envie uma mensagem de teste e confirme o recebimento no destino. Compare com totais do mesmo período.
