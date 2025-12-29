# Estrutura desta especificação

*Esta seção é informativa.*

Esta especificação está dividida nas seguintes seções principais:

## Introdução
  Materiais informativos que fornecem contexto para o padrão HTML.

## Infraestrutura comum
  As classes de conformidade, os algoritmos, as definições e os fundamentos
  comuns do restante da especificação.

## Semântica, estrutura, e APIs de documentos HTML
  Os documentos são construídos a partir de elementos. Esses elementos formam uma árvore
  usando o **DOM** (Modelo de Objeto de Documento). Esta seção define as características desse
  DOM, além de introduzir as funcionalidades comuns a todos os elementos e os conceitos
  utilizados na definição dos mesmos.

## Os elementos do HTML
  Cada elemento possui um significado predefinido, que é explicado nesta seção. Também são
  fornecidas regras para desenvolvedores sobre como utilizar o elemento, juntamente com os requisitos
  do agente do usuário (browser) sobre como manipular cada um deles. Isso inclui recursos de
  grande destaque do HTML, como reprodução de vídeos e legendas, controles e envio de
  formulários, e uma API de gráficos 2D conhecida como HTML *canvas*.

## Microdata
  Esta especificação introduz um mecanismo para adicionar anotações legíveis por máquina a
  documentos, de modo que ferramentas possam extrair árvores de pares nome-valor do
  documento. Esta seção descreve este mecanismo e alguns algoritmos que podem ser usados
  para converter documentos HTML em outros formatos. Esta seção também define alguns
  vocabulários de Microdados de exemplo para informações de contato, eventos de calendário
  e licenciamento de obras.

## Interação com o usuário
  Os documentos HTML fornecem uma série de mecanismos para que os usuários interajam e
  modifiquem o conteúdo, os quais são descritos nesta seção, como o funcionamento do foco e
  o recurso de arrastar e soltar (drag-and-drop).

## Carregamento de páginas web
  Documentos HTML não existem em um vácuo — esta seção define muitos dos recursos que
  afetam ambientes que lidam com múltiplas páginas, tais como navegadores web.

## APIs de aplicações web
  Esta seção apresenta funcionalidades básicas para a criação de scripts de
  aplicações em HTML.

## Web workers
  Esta seção define uma API para threads de segundo plano em JavaScript.

## Worklets
  Esta seção define a infraestrutura para APIs que precisam executar JavaScript de forma
  independente (ou separada) do ambiente principal de execução de JavaScript.

## As APIs de comunicação
  Esta seção descreve alguns mecanismos que aplicações escritas em HTML podem usar para
  se comunicar com outras aplicações de domínios diferentes sendo executadas no mesmo
  cliente. Também apresenta um mecanismo de fluxo de eventos por push do servidor conhecido
  como *Server Sent Events* (Eventos Enviados pelo Servidor) ou *EventSource*, e um protocolo de
  socket full-duplex bidirecional para scripts conhecido como *Web Sockets*.

## Web storage
  Esta seção define um mecanismo de armazenamento no lado do cliente baseado em pares de
  nome-valor.

## A sintaxe HTML
## A sintaxe XML
  Todos esses recursos seriam inúteis se não pudessem ser representados em uma
  forma serializada e enviados a outras pessoas; portanto, estas seções definem as
  sintaxes do HTML e do XML, juntamente com as regras de como processar (parse)
  conteúdos utilizando essas sintaxes.

## Renderização
  Esta seção define as regras de renderização padrão para navegadores web.

Há também alguns apêndices, listando recursos obsoletos e considerações da IANA, além de
vários índices.
