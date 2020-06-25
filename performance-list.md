## Carregamento

- [x] Minificar Arquivos - (html, css, javascript) --> 
- [x] Habilitar gzip
- [x] Lazy loading --> Carregamento lento da página
- [x] Carregue tudo de forma assíncrona --> Arquivo.css 1 --- Servidor --- Arquivo.css 2 --- Servidor--- Arquivo.css 3 --- Servidor
- [x] Seletores CSS
- [x] Recursos que bloqueiam o carregamento da página como iframes, laços de repetição
- [x] Lide com imagens com carinho
- [x] Libere logo o carregamento da página e carregue o resto depois(AFT)

## Execução - Mão na massa
- [x] Main Thread
- [x] SetTimeout --> 'Agenda' recursos na página
- [x] RequestAnimationFrame --> Mesma ideia de cima, mas renderiza de forma descontinua (30fps- alteravel), como se fosse animação
- [x] RequestIdleCallback --> Só é executado quando main thread estiver ociosa, atualização 
- [x] Otimizações de CSS via GPU "thread" --> "Animações" na página usando CSS, GPU
- [x] Tome cuidado ao manipular o DOM - Document Object Manipuation- (Reflow e Repoint) --> 

