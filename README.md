# Template LaTeX para Relatório de Estágio - UNIJUÍ

Este repositório contém um **template LaTeX** para relatórios de estágio dos cursos de **Ciência da Computação** e **Engenharia de Software** da **Universidade Regional do Estado do Rio Grande do Sul (UNIJUÍ)**.

## Sobre o Template
O template foi desenvolvido com base no **abnTeX2** e inclui diversas customizações específicas para atender às normas da UNIJUÍ. Ele facilita a formatação correta de trabalhos acadêmicos, garantindo conformidade com as diretrizes institucionais e as normas da ABNT.

## Estrutura do Projeto

### Arquivos principais

- **`main.tex`**: Define as configurações iniciais do projeto LaTeX, incluindo o tipo de documento, templates e pacotes utilizados. Organiza a estrutura do documento, carregando os arquivos de configuração e incluindo as seções pretextuais, textuais e pós-textuais.

- **`metadados.tex`**: Armazena as informações da capa e da folha de rosto, como título do trabalho, autor, instituição, orientador, data e o preâmbulo do documento.

- **`elementos_textuais.tex`**: Reúne os capítulos e seções do relatório de estágio, como introdução, apresentação da empresa, metodologia, revisão bibliográfica, atividades desenvolvidas e considerações finais.

- **`references.bib`**: Arquivo BibTeX que armazena as referências bibliográficas do trabalho, permitindo a geração automática de citações conforme o estilo definido.

### Diretórios e arquivos auxiliares

- **`imagens/`**: Pasta destinada ao armazenamento das figuras utilizadas no relatório. Recomenda-se criar uma estrutura hierárquica de diretórios dentro de `imagens/` para organizar as imagens conforme as seções do trabalho.
  
  **Exemplo de estrutura:**
  ```
  imagens/
    ├── introducao/
    ├── referencial-teorico/
    │   ├── nome-secao-1/
    │   │   ├── nome-imagem1.jpg (ou .eps, .png)
    │   │   ├── nome-imagem2.jpg
    │   │   ├── nome-imagem3.jpg
    ├── nome-da-secao-de-desenvolvimento/
    │   ├── nome-secao-1/
    │   ├── nome-secao-2/
  ```

- **`templates/`**: Contém os templates customizados para a formatação do documento.
  - **`abntex2cite.sty`**: Arquivo de estilo para formatação de citações conforme as normas da ABNT, baseado no projeto abnTeX2 com ajustes específicos.
  - **`unijui.sty`**: Arquivo de estilo específico da UNIJUÍ, contendo regras de formatação padronizadas para documentos acadêmicos da instituição.

## Como Usar

Para utilizar o template, basta **clonar** este repositório e editar os arquivos conforme necessário.

📌 **Contribuições e sugestões são bem-vindas!** Caso encontre algum problema ou tenha melhorias a sugerir, fique à vontade para abrir uma issue ou enviar um pull request.
