# Criando roteamentos para chamar as páginas.

### #Iniciando: <br>
1 - Vá até o arquivo *app.component.html* e apague TODO o código que lá estiver escrito. <br>
2 - Inclua a Tag de roteamento do angular: <*router-outlet*></*router-outlet*> <br>
### #Criando um component: <br>
1 - Via terminal, crie um novo component com o seguinte comando: **ng g c xxxx**  (sendo "xxxx" o nome do component).<br>
o.b.s.: Para melhor organização, gere os components em pastas separadas, de acordo com suas funcionalidades. Por exemplo: *para o component da página "Home", deixe-a na pastas "paginas"*. <br>
o.b.s.2: Para criar uma pasta, vá no diretório à esquerda > clique com o botão direito em cima da pasta **app** > NOva Pasta > dê nome a pasta.<br>
o.b.s.3: VocÊ pode criar uma pasta ao mesmo tempo que for criar um novo componente, via terminal, utilizando o seguinte comando: **ng g c xxxx/yyyy** (sendo "xxxx" o nome do component e "yyyy" o nome da pasta).
o.b.s.4: De mesmo modo, você pode criar e inserir novos components, em pastas pré-existentes, utilizando o **mesmo** comando da **o.b.s.3** (ng g c kkkk/yyyy - sendo "kkkk" o component e "yyyy" a pasta ja existente) <br>
2 - Vá até o arquivo *app.component.html*  e inclua em formato de Tag HTML, o component criado, abaixo do <*router-outlet*></*router-outlet*> da seguinte maneira: <*app-nome-do-component*></*app-nome-do-component*> <br>
exemplo: se você criou um component cujo nome é **home**, então insira da seguinte forma: <*app-home*></*app-home*> <br>
3 - SUba a aplicação na web com o seguinte comando: **ng serve** e acesse localhost:4200