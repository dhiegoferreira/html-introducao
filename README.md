
## Oque é HTML?
### HTML (HyperText Markup Language) não é uma linguagem de programação, é uma linguagem de marcação utilizada parra dizer ao seu navegador coo estrutura a página web que você visita. A página pode ser tanto omplicada como simples quanto o desenvolverdor web deseja que seja. HTML consiste em uma série de elementos que você usa para anexar, envolver ou marcar diferentes partes do conteúdo para que apareça ou aja de uma certa maneira.



## Anatomia de um elemento HTML

![Image](https://mdn.mozillademos.org/files/9347/grumpy-cat-small.png)

<ol> 
  <li> Tag de abertura </li>
  <li> Tag de fechamento </li>
  <li> O conteúdo </li>
  <li> O elemento </li>
</ol>




## **Alinhando elementos** 
#### quando colocamos elementos dentro de outros elementos. 
- Exemplo:

  ```
  <p>Veja como podemos <strong> destacar </strong> uma palavra.</p> 
  ```

##  Elementos em bloco vs Elementos inline
#### Elementos em bloco: Elementos em bloco formam um bloco visível na página eles aparecerção em uma nova linha logo após qualquer elemento que venha antes dele, e qualquer conteúdo depois de um elemnento em bloco também aparecerá em uma nova linha. Aparecem em parágrafos, listas, menus de navegação, rodapés
- Exemplo:

  ```
  <p> primeiro </p><p>segundo</p><p>terceiro</p>
  ```

#### - Elementos inline (na linha): São aqueles que estão contido dentro de elementos em bloco e envolvem apenas pequenas partes do conteúdo do documento e não parágrafos inteiros ou agrupamentos de conteúdo.
- Exemplo:

  ```
  <em>quarto</em><em>quinto</em><em>sexto</em>
  ```





## **Elementos Vazios**
#### Consistem apenas em uma única tag, que é geralmente usada para iserir/incorporar algo no documento no lugar em que ele é incluído. Comumente chamados de *void elements*
- Exemplo:
 
 ```
 <img src="https://raw.githubvusercontent.com/mdn/beginner-html-site/gh-pagees/images/firefox-icon.png" 
  ```

![firefox](https://raw.githubusercontent.com/mdn/beginner-html-site/gh-pages/images/firefox-icon.png)

## Atributos
#### Elementos também podem conter atributos, que se apresentam da seguinte forma:
![atributos](https://mdn.mozillademos.org/files/9345/grumpy-cat-attribute-small.png)

#### Atributos contém informação extra sobre o elemento, mas que você não deseja que apareça no conteúdo. Neste caso, o atributo *class* permite que você dê ao elemento um nomde de identificação, que pode ser usado mais tarde para direcionar informação de estile ao elemento e outras coisas.

#### Um atributo deve conter:
<ol>
  <li> Um espaço ente ele e o nome do elemento (ou o atributo anterior, caso o elemento já contenham um ou mais atributos.) </li>
  <li> O nome do atributo, seguido por um sina de igual. </li>
  <li> Um valor de atributo, com aspas de abertura e fechamento em volta dele. </li>
</ol>






## Anatomia de um documento HTML
```
  <!DOCTYPE html>
  <html>
    <head>
      <meta charse="utf8>
      <title> Título da página </title>
    <head>
    <body>
      <img src="diretorio/pasta/imagempasta/imagem.png" alt="imagem de xx>
              
     </body> 
  </html>    
 ```

- \<!DOCTYPE html> : É a parte inicial obrigatória do documento. Nas névoas do tempo, quando o HTML era novo (por volta de 1991/2), doctypes eram cirados para agir como links para um nconjunto de regras quee a página HTML tinh que seguir para ser considerada um bom HTML, o que poderia significar checagem automática de erros e outras coisas úteis. Atualmente, eles não fazem muito sentido e são basicamente necessários para garantior que o documento se comporte corretamente.
  
- \<html></html> : Esse elemento envolvo todo o donteúdo da página e às vezes é conhecido como elemento raiz.
  
- \<head></head> : Esse elemento age como um recipiente de tudo o que você deseja incluir em uma página HTML que **não é** conteudo que você quer mostrar para quem vê a página.  

- \<title></title> : Define o título da sua página. que é o título que aparece na guia do navegador onde sua página é carregada. Ele também é usado para descever a página quando você a adiciona aos favoritos.

- \<body></body> : Contém **todo** o conteúdo que você quer mostrar ao público que visita sua página, seja texto, imagens, videos. jogos, faixas de áudio reproduzíves ou qualquer outra coisa.

  
  
  
## Listas
#### **Listas não ordenadas: ** A ordem dos itens não importa e, portanto, não possuem enumeração. São envolvidas em um elemento \<ol> (unordered list)
Exemplo:
  ```
   <ul>
     <li> item sem enumerador </li>
     <li> item sem enumerador </li>
     <li> item sem enumerador </li>
  </ul>  
  ```
#### O resultado seria:
- #### item sem enumerador
- #### item sem enumerador
- #### item sem enumerador
  
#### **Listas ordenadas:** A ordem dos itens importa (ordered list), como uma receita. São envolvidas em um elemento <ol>
Exemplo:
``` 
  <ol>
    <li> primero item enumerado </li>
    <li> segundo item enumerado </li>
    <li> terceiro item enumerado </li>
  </ol>
```
#### O resultado seria:
  <ol>
    <li> primeiro item enumerado </li>
    <li> segundo item enumerado </li>
    <li> terceiro item enumerado </li>
  </ol>

  
  
## Links

  #### Para transforma o texto do seu par[agafo em uma link basta envolver o texto com a tag \<a> com o atributo \href="".
  
  ```
  <a href="https://www.site.com/" > Texto que terá um link para o site referenciado>
  ```
    
    ### href: hypertext reference (referência em hipertexto)




#### Referências
- https://docs.github.com/en/github/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks
- https://developer.mozilla.org/pt-BR/docs/Learn/HTML/Introduction_to_HTML/Getting_started
