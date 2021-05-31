# Coleção Postman - Testes para uma API REST

## Pré condição
* Ter o [Postman](https://www.postman.com) instalado na sua máquina

## Como fazer a importação

### Método 1
1. Clique no arquivo `JSON PlaceHolder.postman_collection.json`
2. Clique no botão *Raw*
3. Copie a URL do seu navegador que está exibindo o arquivo
4. Abra o Postman
5. Selecione o menu *File -> Import*
6. Clique na aba *Link*
7. Cole o conteúdo copiado o campo *Enter a URL*
8. Clique no botão *Continue*
9. Clique no botão *Import*

### Método 2
1. Efetue o download deste repositório ou do arquivo `JSON PlaceHolder.postman_collection.json`
2. Abra o Postman
3. Selecione o menu *File -> Import*
4. Selecione a aba *File*
5. Clique no botão *Upload Files*
6. Navegue até o diretório onde você salvou o arquivo e selecione-o
7. Clique no botão *Import*

## Como executar os testes
1. Com a collection importada clicar em "..."
2. Em seguida clicar em: Run Collection > Run JSON PlaceHolder
3. Para visualizar os resultados clicar em: View Summary / Ver Resumo.

Ou usando docker:
1. docker run -t postman/newman run https://www.getpostman.com/collections/df66857f2e66f4bb0cf1
