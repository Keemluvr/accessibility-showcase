<!-- <img width="1910" height="971" alt="image" src="https://github.com/user-attachments/assets/c5a9b3d9-aae2-4198-8044-fae66cdba6ef" /> -->

### Imagens

Com descrição:
```html
alt="Baixe nosso app na Play Store"
```

Apenas decorativa:
```html
alt="" role="presentation"
```


-----

### Hierarquia de títulos

--> H1 = único por página  
--> H2  
--> .  
--> .  
--> .  
--> H6  

Usando span com hierarquia:
```html
<span role="heading" aria-level="2"/>Título</span>
```

-----

### Landmarks

--> header  
--> nav    
--> main  
--> section  
--> aside  
--> footer  
--> .  
--> .  
--> .  

```html
 <section id="features" aria-label="Funcionalidades do app">...</section>
```


-----


### Constraste de cores

https://webaim.org/resources/contrastchecker/



-----

### Trancrição de vídeo

```html
<video muted="muted" autoplay="" loop="" style="max-width: 100%; height: 100%">
    <source src="assets/img/demo-screen.mp4" type="video/mp4" />
    <link rel="transcript" href="#transcricaoVideo1" title="transcrição do novo vídeo"/>
</video>
<transcript id="transcricaoVideo1">
    Transcrição do novo vídeo
</transcript>
```