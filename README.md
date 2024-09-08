# Projeto de Dados de Obras de Arte

Este projeto tem como objetivo criar e gerenciar uma base de dados para obras de arte, fornecendo informações detalhadas sobre cada peça. A base de dados inclui informações como nome da obra, artista, imagem, descrição, tags, localização e estilo da obra, abrangendo diferentes tipos de obras, como pinturas e esculturas.

O Gallery Museum é uma plataforma digital sofisticada projetada para proporcionar uma experiência imersiva e educacional no mundo da arte. O site visa oferecer acesso a uma vasta coleção de obras de arte, permitindo aos usuários explorar, pesquisar e apreciar a arte de maneira interativa e acessível. O projeto combina design elegante, funcionalidade intuitiva e uma interface responsiva para criar um ambiente digital envolvente.

Processo de Criação e Desenvolvimento
1. Concepção e Planejamento
Definição de Objetivos: O objetivo principal do Gallery Museum é criar uma plataforma onde os usuários possam explorar e aprender sobre obras de arte de maneira acessível e atraente. A intenção é oferecer uma experiência de usuário que seja ao mesmo tempo informativa e visualmente atraente.

Pesquisa e Referências: O projeto começou com a pesquisa de plataformas semelhantes e análise de sites de museus e galerias. O design e a funcionalidade foram inspirados em sites que combinam elegância e modernidade, como o site da Work & Co e Starbucks.

Especificação de Requisitos: Definição das funcionalidades necessárias, como a capacidade de pesquisar obras, exibir resultados detalhados e apresentar uma galeria de obras destacadas. Foi definido que a plataforma deve ser responsiva e funcionar bem em dispositivos móveis e desktops.

2. Design e Prototipagem
Criação da Identidade Visual: Desenvolvi uma identidade visual sofisticada e moderna para o Gallery Museum, incluindo um esquema de cores harmonioso e fontes elegantes. A escolha das fontes do Google Fonts e a paleta de cores foram selecionadas para refletir a sofisticação e a modernidade do projeto.

Desenvolvimento da Interface: Criação de wireframes e mockups para as principais páginas e seções do site, incluindo o cabeçalho, área de pesquisa, resultados e galeria de obras destacadas. Utilizei ferramentas de design para criar protótipos visuais e interativos.

Feedback e Revisões: A interface foi ajustada com base no feedback de colegas e usuários para garantir uma experiência de usuário fluida e intuitiva.

3. Desenvolvimento Front-End
Estrutura HTML: Criação da estrutura básica da página com HTML, incluindo a definição das seções para pesquisa, resultados e galeria de obras. A inclusão de elementos como input de pesquisa, botão de busca e seções de resultados foram fundamentais.

Estilização com CSS: Aplicação de estilos usando CSS para criar um design elegante e responsivo. A utilização de Flexbox para layout e a implementação de media queries garantiram que o site se adaptasse a diferentes tamanhos de tela. A folha de estilo incluiu a personalização de botões, seções de resultados e galeria de imagens.

Integração de Imagens e Conteúdo: Inclusão de imagens de obras de arte na galeria destacada e estilização das imagens para garantir uma apresentação visual atraente. A descrição das imagens e a correção de detalhes de acessibilidade foram consideradas.

4. Funcionalidade JavaScript
Implementação de Função de Pesquisa: Desenvolvimento da função pesquisar() em JavaScript para filtrar os resultados com base no texto inserido pelo usuário. A função realiza uma busca nos dados e exibe os resultados relevantes na página.

Manipulação de Dados: A função de pesquisa é conectada a um arquivo de dados (dados.js) que contém informações sobre as obras de arte. O código foi projetado para comparar o texto da pesquisa com diferentes propriedades dos dados e exibir os resultados correspondentes.

5. Testes e Validação
Testes de Usabilidade: Realização de testes com usuários para garantir que a navegação e as funcionalidades do site fossem intuitivas e responsivas. Ajustes foram feitos com base no feedback para melhorar a experiência do usuário.

Validação de Código: Verificação de compatibilidade entre diferentes navegadores e dispositivos. Correção de bugs e otimização do código para garantir um desempenho suave.

6. Implantação e Manutenção
Implantação: Publicação do site em um servidor web, tornando-o acessível ao público. A configuração dos arquivos e a verificação de links e imagens foram realizadas para garantir que tudo funcionasse corretamente.

Manutenção e Atualizações: O site será monitorado e atualizado regularmente para corrigir quaisquer problemas e adicionar novos recursos conforme necessário. A manutenção contínua garantirá que a plataforma permaneça atualizada e relevante.

Conclusão
O Gallery Museum representa uma fusão bem-sucedida de design sofisticado e funcionalidade avançada. Através de um processo cuidadoso de planejamento, design, desenvolvimento e testes, criamos uma plataforma que oferece uma rica experiência de exploração artística, com um design elegante e uma interface amigável. O projeto reflete um compromisso com a excelência em design e funcionalidade, proporcionando aos usuários uma experiência enriquecedora e acessível no mundo da arte.

## Estrutura do Projeto

### 1. **Nome da Obra**
- **Descrição:** O título oficial da obra de arte.
- **Exemplo:** "Noite Estrelada"

### 2. **Artista**
- **Descrição:** Nome completo do artista responsável pela criação da obra.
- **Exemplo:** Vincent van Gogh

### 3. **Imagem**
- **Descrição:** Um link para uma imagem da obra ou um arquivo local da imagem.
- **Exemplo:** ![Noite Estrelada](link_para_imagem.jpg)

### 4. **Descrição**
- **Descrição:** Um resumo ou explicação sobre a obra, incluindo detalhes históricos ou técnicos.
- **Exemplo:** "Uma das obras mais famosas de Vincent van Gogh, pintada em 1889, retratando a vista da janela do quarto de Van Gogh em um asilo em Saint-Rémy-de-Provence."

### 5. **Tags**
- **Descrição:** Palavras-chave que categorizam a obra.
- **Exemplo:** Impressionismo, Céu Noturno, Pintura a Óleo

### 6. **Localização**
- **Descrição:** A localização física da obra, como museus ou galerias.
- **Exemplo:** Museu de Arte Moderna, Nova York

### 7. **Estilo**
- **Descrição:** O movimento artístico ou estilo ao qual a obra pertence.
- **Exemplo:** Pós-Impressionismo


Exemplos de Busca
Para realizar uma busca eficaz no sistema, você pode usar os seguintes títulos de obras:

Mona Lisa - Leonardo da Vinci - Museu do Louvre, Paris
A Noite Estrelada - Vincent van Gogh - Museu de Arte Moderna, Nova York
David - Michelangelo - Galeria da Academia, Florença
O Grito - Edvard Munch - Galeria Nacional, Oslo
Guernica - Pablo Picasso - Museu Reina Sofia, Madrid
A Persistência da Memória - Salvador Dalí - Museu de Arte Moderna, Nova York
O Nascimento de Vênus - Sandro Botticelli - Galeria Uffizi, Florença
A Escola de Atenas - Rafael - Museus Vaticanos, Cidade do Vaticano
A Liberdade Guiando o Povo - Eugène Delacroix - Museu do Louvre, Paris
O Jardim das Delícias Terrenas - Hieronymus Bosch - Museu do Prado, Madrid
O Casamento Arnolfini - Jan van Eyck - Galeria Nacional, Londres
A Última Ceia - Leonardo da Vinci - Convento de Santa Maria delle Grazie, Milão
O Beijo - Gustav Klimt - Galeria Österreichische, Viena
A Morte de Sardanápalo - Eugène Delacroix - Museu do Louvre, Paris
A Grande Onda de Kanagawa - Katsushika Hokusai - Museu Britânico, Londres
A Dança - Henri Matisse - Museu de Arte Moderna, Nova York
A Coroação de Napoleão - Jacques-Louis David - Museu do Louvre, Paris
A Ronda Noturna - Rembrandt - Rijksmuseum, Amsterdã
A Menina com Brinco de Pérola - Johannes Vermeer - Mauritshuis, Haia
O Lavrador de Café - Jean-François Millet - Museu d'Orsay, Paris

Autor: André Oliveira, 2024.

