# HTML-The-Essentials

>  
> HTML
> 
> MDN Web Docs - Resources for developers (HTML , CSS,  JS)
> Link : https://developer.mozilla.org/en-US/
> 
**HTML is a markup language.**

Common Elements:

```<p>``` element - represents a paragraph of text

```<h1>``` element - represents the main header on a page

```<img>``` element - embeds an image

```<form>``` element - represents a form
 

>HTML
>
> Headers
>
  
```<h1> Cím </h1>``` - mindig csak egy van belőle

```<h2> SubTopic1 </h2>```

```<h3> SubTopic1SubTopicja </h3>```

```<h2> SubTopic2 </h2>```

Méretre kisebbek de nem méret szerint növekszik a számuk!!

```lorem```- töltelék text
  

> HTML
> 
> Boilerplate OR HTML-Skeleton
>

```
<!DOCTYPE html> 
<html>
<head>
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
  
```<!DOCTYPE html>``` - doesn't have closing tag,its just a flag. Basically saying : I am using the  latest featurest of HTML (HTML5)

```<head> </head>``` - root element , everything else on the page supposed to be a descendant of this element

```<title> </title>```  - the title of the website on google,on chrome etc..

```<body> </body>``` - everything we've typed

**Shortcut**: write ! to VsCode and hit Tab.

> HTML
>
> Ordered and Unordered Lists
>

***Ordered Lists*** - ```<ol> </ol>```
```
<ol>
    <li>Bantam
        <ol>
            <li>Silkie</li>
            <li>Polish</li>
        </ol>
    </li>
</ol>
```

***Unordered Lists*** - ```<ul> </ul>```


```
<ul>
    <li>Bantam
        <ul>
            <li>Silkie</li>
            <li>Polish</li>
        </ul>
    </li>
</ul>
```

> HTML
>
> The Anchor element - LINKS  ```<a> </a>``` 
>

Link to an another website:  ```<a href="http://www.facebook.com"> I am a link to facebook!!</a>```

Link to my own website : ```<a href="about.html"> This is a link to my own <b>About Me</b> website</a>```

Link as a world in the text : ```<a href="https://en.wikipedia.org/wiki/Capon">capon</a>```
