# ♿ Projeto de Acessibilidade Básica

Este projeto foi desenvolvido durante o curso [**Do Zero ao Código: Acessibilidade Digital para DEVS**](https://www.udemy.com/course/formacao-acessibilidade-digital/) na Udemy.  
O objetivo foi aplicar conceitos fundamentais de **acessibilidade web** para tornar uma página mais inclusiva, compreensível e compatível com tecnologias assistivas.

---

## 🎯 Objetivo

Melhorar a acessibilidade de uma página existente, corrigindo problemas detectados por ferramentas automáticas (como o **axe DevTools** e o **WAVE**) e seguindo boas práticas de semântica e usabilidade.

---

## 🧩 Ajustes realizados

Durante o projeto, foram aplicadas diversas melhorias, como:

- Uso correto de **elementos semânticos HTML** (`<header>`, `<main>`, `<nav>`, `<footer>`, etc);
- Inclusão de **textos alternativos (`alt`)** em imagens;
- Correção de **contraste de cores** insuficiente;
- Melhoria na **ordem de tabulação** e **foco visível**;
- Adição de **rótulos acessíveis (`aria-label`, `label for`, etc)**;
- Estruturação adequada de **títulos e hierarquia (`h1`, `h2`, `h3`)**;
- Garantia de que todos os elementos interativos são acessíveis via teclado.

---

## 🧪 Resultado da Análise com axe DevTools

Abaixo, o comparativo da análise **antes e depois** das correções feitas:

### 🔴 Antes das correções

<img width="500" height="971" alt="Antes das correções - axe report" src="https://github.com/user-attachments/assets/c5a9b3d9-aae2-4198-8044-fae66cdba6ef" />

### 🟢 Depois das correções

<img width="500" height="984" alt="Depois das correções - axe report" src="https://github.com/user-attachments/assets/9cb1fb88-1d3b-4cf8-aea1-707f33ae7493" />

> As imagens mostram a redução dos erros e alertas após a implementação das boas práticas de acessibilidade.

---

## 🛠️ Tecnologias utilizadas

- **HTML5**  
- **CSS3**  
- **axe DevTools** (extensão do navegador para auditoria de acessibilidade)
- **WAVE** (extensão do navegador para auditoria de acessibilidade)

---

## 💡 Aprendizados

Durante o curso, aprendi a importância de pensar na **inclusão digital desde o início do desenvolvimento** e como pequenas mudanças no código podem ter um grande impacto na experiência de pessoas com deficiência.
Além de saber os momentos certos do que deve ser apresentado.

---

## 📚 Curso

**Do Zero ao Código: Acessibilidade Digital para DEVS** – Udemy  
Instrutor: *Eduardo Corrêa*  
🔗 [Acesse o curso aqui](https://www.udemy.com/course/formacao-acessibilidade-digital/)

---

## 🧑‍💻 Anotações

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
