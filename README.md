SearchCot

SearchCot é um buscador avançado de código aberto, projetado em dois verticais complementares:

1. Versão Humano

Interface web simples, tipo navegador, com barra de URL e formulário de busca.

Permite navegar páginas, visualizar resultados e snippets diretamente no navegador.

Indexação local via crawler assíncrono, com suporte a TF-IDF, BM25 e busca semântica opcional.

Ideal para usuários que querem explorar e interagir com resultados como fariam em um navegador comum.



2. Versão Inteligência Artificial

API dedicada para LLMs e modelos de IA consumirem resultados diretamente.

Retorna JSON estruturado com título, URL, snippet, links, imagens e resumo do conteúdo.

Indexação em memória ou persistente, com suporte a ranking semântico.

Permite que modelos de IA interpretem e utilizem resultados de forma eficiente e programática.




Funcionalidades principais

Crawler assíncrono com filtragem e extração de texto, links e imagens.

Rankers TF-IDF, BM25 e reranking semântico com embeddings (opcional).

Snippets e resumos automáticos para melhor compreensão do conteúdo.

Implementação local, segura e de código aberto, sem dependência de APIs externas.


Uso

CLI: crawl, search, serve (humano ou AI).

API REST pronta para integração com IA (/ai/search, /ai/doc/<id>).


Licença: Apache 2.0


---
