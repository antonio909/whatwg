<h1>Extensibilidade</h1>

<i>Esta seção é informativa.</i>

<p align="justify">
  O HTML possui uma ampla gama de mecanismos de extensibilidade que podem ser usados para adicionar semântica de maneira segura:
</p>

<ul>
  <li align="justify">
    Os autores podem usar o atributo <b>class</b> para estender elementos, criando efetivamente seus próprios elementos, ao mesmo tempo em que utilizam o elemento HTML 'real' mais aplicável, para que navegadores e outras ferramentas que não conheçam a extensão ainda possam suportá-la razoavelmente bem.
    Essa é a abordagem utilizada pelos microformatos, por exemplo.
  </li>

  <li align="justify">
    Os autores podem incluir dados para serem processados por scripts do lado do cliente (inline) ou scripts do lado do servidor em todo o site usando os atributos <code>data-*=""</code>.
    É garantido que esses atributos nunca serão alterados pelos navegadores, permitindo que os scripts incluam dados em elementos HTML para que, posteriormente, possam ser localizados e processados.
  </li>

  <li align="justify">
    Os autores podem usar o mecanismo <code>&lt;meta name="" content=""&gt;</code> para incluir metadados em toda a página.
  </li>

  <li align="justify">
    Os autores podem usar o mecanismo <code>rel=""</code> para anotar links com significados específicos, registrando extensões para o conjunto predefinido de tipos de links.
    Isso também é utilizado por microformatos.
  </li>

  <li align="justify">
    Os autores podem incorporar dados brutos usando o mecanismo <code>&lt;script type=""&gt;</code> com um tipo personalizado, para posterior processamento por scripts inline ou no lado do servidor.
  </li>

  <li align="justify">
    Os autores podem estender APIs usando o mecanismo de prototipagem do JavaScript.
    Isso é amplamente utilizado por bibliotecas de scripts, por exemplo.
  </li>

  <li align="justify">
    Os autores pode usar o recurso de <b>microdados</b> (os atributos <code>itemscope=""</code> e <code>itemprop=""</code>) para incorporar pares nome-valor de dados aninhados, a fim de serem compartilhados com outros aplicativos e sites.
  </li>

  <li align="justify">
    Autores podem definir, compartilhar e usar elementos personalizados para estender o vocabulário do HTML.
    Os requisitos para nomes válidos de elementos personalizados garantem a compatibilidade futura (visto que nenhum elemento com hífens em seus nomes locais será adicionado ao HTML, SVG ou MathMl no futuro).
  </li>
</ul>
