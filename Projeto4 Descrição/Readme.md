Primeiro, criei os recursos necessários no Azure para configurar a pesquisa. Isso incluiu a criação de um recurso Azure AI Search com as configurações adequadas, como nome de serviço único e localização. Também provisionei um recurso Azure AI Services na mesma região para enriquecer os dados com insights gerados por IA. Além disso, criei uma conta de armazenamento para guardar os documentos brutos.

Em seguida, extraí os dados dos documentos e os carreguei para um contêiner de blob na minha conta de armazenamento. Utilizei o Import Data Wizard do Azure para criar um índice e um indexador. Configurando-o para extrair dados do armazenamento de blobs e enriquecê-los com habilidades de IA, como extração de localizações, frases-chave, detecção de sentimentos, entre outros. Também criei um conhecimento store para armazenar os dados enriquecidos.

Depois de indexar os documentos, pude consultar o índice utilizando o Search Explorer. Escrevi e testei consultas para encontrar insights específicos nos documentos, filtrando por localização, sentimento e outros parâmetros.

Por fim, explorei o conhecimento store para examinar os dados enriquecidos. Pude visualizar as projeções de objetos, imagens e tabelas de entidades, como frases-chave extraídas dos documentos.

Essa configuração no Azure AI Search é extremamente útil, pois oferece uma maneira eficiente de indexar, pesquisar e extrair insights de grandes conjuntos de dados não estruturados, como documentos de texto e imagens. Durante o processo, aprendi bastante sobre como configurar recursos do Azure, extrair e enriquecer dados, e consultar o índice para obter insights valiosos.
