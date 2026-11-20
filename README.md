# Radar SEO e GEO

Plugin autoral de Carlos Felipe para auditar páginas de serviço e notícias no ChatGPT. Comece com uma URL, um trecho de HTML ou uma planilha. A resposta mostra o que foi observado, qual mudança vale testar primeiro e como medir o resultado.

## Habilidades

| Habilidade | O que faz |
| --- | --- |
| [Auditoria e conversão](skills/auditoria-e-conversao/SKILL.md) | Revisa descoberta, indexação e caminho até o contato. |
| [Prontidão para IA](skills/prontidao-ia/SKILL.md) | Examina acesso dos rastreadores, clareza da página, fontes e evidências de citação. |
| [Search Console](skills/search-console/SKILL.md) | Compara cliques e impressões e encontra consultas com potencial de revisão. |
| [Pesquisa de mercado](skills/pesquisa-de-mercado/SKILL.md) | Agrupa buscas por intenção e ajuda a escolher qual página revisar ou criar. |

## Primeira conversa

> Esta é a página do meu serviço. Mostre o que você conseguiu confirmar, qual mudança vale fazer primeiro e como vou saber se funcionou.

O pacote funciona com arquivos fornecidos na conversa. Consultas a contas privadas dependem de conexões autorizadas e as métricas de mercado dependem dos dados disponíveis.

## Empacotar

Na raiz do repositório, execute:

```sh
zip -r ../Radar-SEO-e-GEO-0.1.0.zip plugin.json skills assets
```

O arquivo gerado pode ser usado no Plugin Creator para criar uma instalação privada.

## Validação da versão 0.1.0

Foram verificados o manifesto, as quatro habilidades e os arquivos de apoio. Os cenários fictícios cobriram detecção de `noindex`, CTR de 0,8% (8 de 1.000), regras distintas para OAI-SearchBot e GPTBot, pesquisa sem fonte de métricas e 30 cliques no WhatsApp com total de contatos desconhecido. A validação usou testes locais e revisão de instruções. A execução completa em conversa com o plugin instalado ficou pendente.

Veja os [créditos e as fontes técnicas](skills/creditos.md).
