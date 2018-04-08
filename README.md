# desafio-app
Uma das tarefas mais comuns em Apps é a interação com web services. Nesse App serão utilizados conceitos importantes: requisições HTTP GET, JSON parsing, download de arquivos, além do desenvolvimento de um layout simples mas bastante comum em diversos aplicativos de mercado.

### INTRODUÇÃO

* Primeiramente, crie um fork deste projeto para subir o seu código.
* Utilize seu conhecimento e qualquer material disponível na web para construir uma solução que atenda as especificações indicadas abaixo.
* As especificações não estão 100% definidas, utilize sua criatividade e experiências anteriores para preencher eventuais gaps e propor a melhor solução técnica para o App.
* Quando concluir, ou em caso em dúvidas, entre em contato conosco.

### O DESAFIO

##### Backend (Webservice iTunes)

A Apple disponibiliza um serviço para pesquisar a loja iTunes e você o utilizará como backend para o desenvolvimento deste App.

A especificação detalhada deste serviço pode ser encontrada em: http://affiliate.itunes.apple.com/resources/documentation/itunes-store-web-service-search-api/

Mas será utilizada basicamente a seguinte chamada para montagem das telas:
https://itunes.apple.com/search?term=aerosmith&entity=music 

(Atenção: devem ser utilizadas requisições assincronas)

O layout proposto para o App encontra-se abaixo. Não é necessário seguir o layout a risca, o mais importante é que todas as funcionalidades e comportamentos propostos estejam presentes.

##### HOME
<img src="https://raw.githubusercontent.com/Webeleven/desafio-app/master/home.png" width="250"/>

A home do App é composta basicamente de 3 partes:
1) Campo de busca
2) Listagem dos resultados de busca
3) Seção "Destaques"

Inicialmente a listagem é apresentada vazia e após o usuário buscar por um artista na barra de busca ela deve ser atualizada para refletir os resultados existentes no iTunes.

A seção de destaques pode ser utilizada como você preferir e não precisa estar atrelada a barra de busca. Uma sugestão é utilizá-la para destacar os albuns do seu artista favorito. Note que ela possui comportamento de carrossel.

##### DETAIL MODAL
Ao clicar em um dos resultados da busca, informações adicionais devem ser exibidas conforme abaixo.
<img src="https://raw.githubusercontent.com/Webeleven/desafio-app/master/detail.png" width="250"/>

Todos os assets necessários para a construção do layout estão disponíveis no diretório assets deste repositório.


