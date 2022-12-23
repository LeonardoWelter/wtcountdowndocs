Como usar
=====

.. _installation:

Instalação
------------

Para instalar o WT Countdown, primeiramente selecione a aba "Plugins" no menu administrativo do Wordpress:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wtcountdowndocs/main/docs/images/wtcount_docs_plugins_page1_marked.png
   :width: 60%
   :align: center
   :alt: Página de plugins do Wordpress

   Página de plugins do Wordpress

Selecione "Adicionar Novo" no topo da página, e então selecione "Enviar Plugin":

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wtcountdowndocs/main/docs/images/wtcount_docs_plugins_page2_marked.png
   :width: 60%
   :align: center
   :alt: Página de envio de plugins Wordpress

   Página de envio de plugins Wordpress

Clique em "Procurar", selecione o arquivo ``wtcountdown.zip`` e clique em "Instalar agora":

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wtcountdowndocs/main/docs/images/wtcount_docs_plugins_page3_marked.png
   :width: 60%
   :align: center
   :alt: Enviando o plugin

   Enviando o plugin

Após enviar, aparecerá uma página informando o status da instalação do plugin, clique em "Ativar Plugin" para finalizar a instalação:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wtcountdowndocs/main/docs/images/wtcount_docs_plugin_install_marked.png
   :width: 60%
   :align: center
   :alt: Instalando o plugin

   Instalando o plugin

Pronto, a instalação foi finalizada e a página de configuração do plugin pode ser encontrada no menu do Wordpress:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wtcountdowndocs/main/docs/images/wtcount_docs_plugin_installed_marked.png
   :width: 60%
   :align: center
   :alt: Menu do Wordpress

   Menu do Wordpress

Ao selecionar WT Countdown no menu, você será direcionado a dashboard do plugin:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wtcountdowndocs/main/docs/images/wtcount_docs_dashboard.png
   :width: 60%
   :align: center
   :alt: Dashboard

   Dashboard

Criando seu primeiro Contador
----------------

Para criar o seu primeiro Contador, no dashboard do plugin, clique em Contadores.

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wtcountdowndocs/main/docs/images/wtcount_docs_dashboard.png
   :width: 60%
   :align: center
   :alt: Dashboard WT Countdown

   Dashboard WT Countdown

Na página dos Contadores, clique em "Adicionar Contador" no canto superior direito:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wtcountdowndocs/main/docs/images/wtcount_docs_index_marked.png
   :width: 60%
   :align: center
   :alt: Página Contadores

   Página Contadores

Na página seguinte, preencha os dados do formulário e clique no botão "Criar":

.. note::

   Mais detalhes sobre as opções de customização do contador podem ser encontrados em :doc:`features`.

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wtcountdowndocs/main/docs/images/wtcount_docs_add.png
   :width: 60%
   :align: center
   :alt: Página de Criação do Contador

   Página de Criação do Contador

Após a criação, você será redirecionado a listagem dos Contadores criados, clique no botão na coluna "Shortcode" para copiar o shortcode do Contador criado:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wtcountdowndocs/main/docs/images/wtcount_docs_raffle_index_created_shortcode.png
   :width: 60%
   :align: center
   :alt: Copiando o shortcode do Contador criado

   Copiando o shortcode do Contador criado

Após copiar o shortcode, deveremos inserir o mesmo em uma página.

Inserindo o Contador em uma página
----------------

Para mostrar o Contador, basta inserir o shortcode em alguma página.

.. note::

   O componente do Contador inclui somente a contagem e o botão após finalização da contagem, fica a cargo do administrador do site criar a apresentação da página.

Selecione uma página, insira um bloco de shortcode:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wtcountdowndocs/main/docs/images/wtcount_docs_shortcode_marked.png
   :width: 60%
   :align: center
   :alt: Inserindo bloco de Shortcode

   Inserindo bloco de Shortcode 1

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wtcountdowndocs/main/docs/images/wtcount_docs_shortcode_add.png
   :width: 60%
   :align: center
   :alt: Inserindo bloco de Shortcode

   Inserindo bloco de Shortcode 2

Coloque o shortcode ``[wtcountdown id=1]`` copiado anteriormente e salve a página:

.. note::

   O shortcode pode ser copiado no menu do plugin em "Contadores".

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wtcountdowndocs/main/docs/images/wtcount_docs_shortcode_paste_marked.png
   :width: 60%
   :align: center
   :alt: Inserindo o shortcode

   Inserindo o shortcode

Após inserir o shortcode clique em "Atualizar", no canto superior direito.

Se visitar a página onde foi inserido o shortcode, o componente do Contador estará funcionando:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wtcountdowndocs/main/docs/images/wtcount_docs_countdown.png
   :width: 60%
   :align: center
   :alt: Componente do Contador

   Componente do Contador

Quando a contagem encerrar, será exibido o botão, conforme definido na criação do Contador.

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wtcountdowndocs/main/docs/images/wtcount_docs_cta.png
   :width: 60%
   :align: center
   :alt: Botão pós término

   Botão pós término

Se a documentação foi seguida, o Contador já está funcionando.