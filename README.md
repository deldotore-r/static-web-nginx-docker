# 🌐 Site RCG — Container Docker + NGINX

Este repositório contém um site estático (HTML, CSS e JavaScript) pronto para ser executado em um container **NGINX** usando **Docker**.

Trata-se do primeiro site institucional do Rotary Club da Guarda, ao qual sou associado, e do qual recebi a honrosa incumbência de criar.
***
<br>


## 📦 Imagem no Docker Hub
🔗 [deldotore/sitercg:1.0](https://hub.docker.com/r/deldotore/sitercg)
<br>
<br>


## 🚀 Como executar

Certifique-se de ter o **Docker** instalado em seu sistema. Caso não tenha, acesse o guia abaixo:

🔗 [Docker - guia de instalação.](https://docs.docker.com/desktop/setup/install/windows-install/)

Para iniciar o site, execute no terminal:

```bash
docker run -d -p 8080:80 deldotore/sitercg:1.0
```

Depois, abra no navegador:
```
http://localhost:8080
```

💡 *Se a porta 8080 já estiver em uso, troque por outra livre*:
```bash
docker run -d -p 8090:80 deldotore/sitercg:1.0
```

---
<br>


## 📂 Estrutura do projeto
```
public/
│   index.html
│   style.css
│   script.js
```
- **index.html** → Página principal.
- **style.css** → Estilos visuais.
- **script.js** → Funcionalidades e interatividade.

---
<br>

## 🛠️ Tecnologias usadas
- **HTML5**
- **CSS3**
- **JavaScript**
- **NGINX**
- **Docker**

---
<br>

## 🖼️ Captura de tela

![Exemplo](assets/print_rcg.png)


---

## ✨ Autor
**Reinaldo C. G.**  
[Perfil no Docker Hub](https://hub.docker.com/u/deldotore)

---

