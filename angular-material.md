# Como utilizar o Angular Material <br>
O.b.s.: Antes de iniciar essa parte, faça o tutorial de como criar a aplicação angular do ZERO, que encontra-se no arquivo: criando-app.md<br>
### #Primeiros passos: <br>
1 - Abra o VSCode <br>
2 - Abra a pasta da sua aplicação: Arquivo > Abrir Pasta... > *Procure a pasta da sua aplicação angular* > OK <br>
3 - Abra o terminal: Terminal > Novo Terminal <br>
4 - Inclua o Angular Material, utilizando o seguinte comando via terminal: *ng add @angular/material* <br>
5 - Escolha o estilo que deseja seguir na sua aplicação: *Indingo/Pink, Deep Purble/Amber, Pink/Glue Grey ou Purple/Green* <br>
6 - Set up global Angular Material typography styles? [YES] <br>
7 - Set up browser animations for Angular Material? [YES] <br>
8 - Pronto! O angular material ja está adicionado ao seu projeto. Se quiser verificar, acesse a pasta *package-lock.json* e verifique que estará la, escrito da seguinte forma "@angular/material": "^11.2.3" <br>

### #Como utilizar o angular material: <br>
1 - Com a aplicação aberta no VSCode, navegue até o arquivo *app.module.ts* <br>
2 - Faça o import da API do componente do Angular Material, que você deseja utilizar ( *exemplo:* import {MatToolbarModule} from '@angular/material/toolbar'; )  <br>
o.b.s: as API's estão disponíveis em: https://material.angular.io/<br>
3 - Ainda no arquivo *app.module.ts*, insira o nome do componente(que está entre as {} do import) que irá utilizar, na parte *imports: [ ]* .<br>
a) Exemplo.1: *imports: [ MatToolbarModule ]* <br>
b) o.b.s.: Para utilizar dois ou mais componentes, você deve por a vírgula separando o nome dos componentes. (exemplo: *imports: [MatToolbarModule, MatTabsModule]*) <br>
4 - Vá até o arquivo *app.component.html* e apague TUDO que estiver lá. <br>
5 - Insira o component que você deseja utilizar, em formato de Tag HTML5 (<*insira-aqui-a-tag*>) <br>
(exemplo: se você fez o import do componente *MatToolbarModule* , então você pode usar o Toolbar. Para utiliza-lo, escreva a Tag <*mat-toolbar*> Texto <*/mat-toolbar*> <br>
6 - Suba a aplicação na web, utilizando o comando **ng serve** , via *Terminal*. <br>
7 - Acesse a aplicação (*localhost:4200*) e visualize o componente que você acabou de por.<br>
8 - Pronto! Agora você ja sabe como introduzir um componente do Angular Material nas suas páginas HTML da sua aplicação angular.
9 - Para ter acesso ao material completo, acesse: https://material.angular.io/