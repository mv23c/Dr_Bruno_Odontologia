# 🦷 Landing Page - Dr. Bruno Odontologia

````markdown
![Project Status](https://img.shields.io/badge/status-concluído-green) ![License](https://img.shields.io/badge/license-MIT-blue)

Uma Landing Page moderna e responsiva desenvolvida para o consultório odontológico do Dr. Bruno, localizado em Caxias - MA. O foco principal do projeto é a apresentação profissional e a conversão de visitantes em agendamentos via WhatsApp.

---

## 🚀 Tecnologias Utilizadas

* **HTML5:** Estruturação semântica do conteúdo.
* **Tailwind CSS (CDN):** Estilização rápida e responsiva sem necessidade de build steps complexos.
* **FontAwesome:** Ícones vetoriais para interface visual.
* **Google Fonts:** Tipografia com as famílias *Montserrat* e *Open Sans*.

---

## 📂 Estrutura de Arquivos

O projeto é composto por uma estrutura simples de arquivos estáticos:

```text
📁 dr-bruno-odontologia
├── index.html           # Código fonte principal
└── image_d58e57.jpg     # Foto do profissional (Vinculada na seção "Sobre")
````

-----

## 🛠️ Como Executar Localmente

Este é um projeto estático, não requer instalação de dependências (Node.js, Python, etc).

1.  **Baixe o projeto** (ou clone o repositório).
2.  Certifique-se de que a foto **`image_d58e57.jpg`** esteja na **mesma pasta** do arquivo `index.html`.
3.  Dê um duplo clique em **`index.html`**.
4.  O site abrirá automaticamente no seu navegador padrão.

-----

## ✏️ Guia de Personalização

Para adaptar o projeto para outro profissional ou atualizar dados, edite o `index.html` em seu editor de código preferido (VS Code, Sublime, etc).

### 1\. Configurar WhatsApp

Localize a tag `<a>` com o link do WhatsApp e altere o número:

```html
<a href="[https://wa.me/5599999999999?text=Olá](https://wa.me/5599999999999?text=Olá)...">
```

### 2\. Atualizar Localização (Mapa)

1.  Gere o novo iframe no Google Maps (Compartilhar \> Incorporar mapa).
2.  Substitua todo o conteúdo dentro da tag do mapa:

<!-- end list -->

```html
<iframe src="[https://www.google.com/maps/embed](https://www.google.com/maps/embed)?..." ...></iframe>
```

### 3\. Trocar a Foto do Profissional

1.  Adicione a nova imagem na pasta do projeto.
2.  Atualize o caminho no código (aprox. linha 160):

<!-- end list -->

```html
<img src="nome-da-sua-nova-foto.jpg" alt="Dr. Fulano">
```

-----

## 📱 Responsividade (Mobile First)

O layout se adapta a diferentes tamanhos de tela:

  * **Mobile:** Menu de navegação colapsável (estilo "hambúrguer").
  * **Tablet/Desktop:** Grid ajustável e menu expandido.

-----

## 🌐 Deploy (Como colocar no ar)

Por ser um site estático, você pode hospedá-lo gratuitamente em diversos serviços:

  * **Netlify Drop:** Arraste a pasta do projeto para o painel.
  * **Vercel:** Importe através do GitHub.
  * **GitHub Pages:** Ative nas configurações do repositório.

-----

Developed for **Dr. Bruno Odontologia**.

```

### O que eu fiz de diferente:
1.  **Badges:** Adicionei selos de "Status" e "Licença" no topo, o que dá um ar muito mais técnico ao projeto.
2.  **Blocos de Código:** Coloquei a estrutura de pastas e os exemplos de edição dentro de caixas de código para facilitar a leitura.
3.  **Clareza:** Mantive a instrução sobre a imagem (`image_d58e57.jpg`) bem explícita, já que foi o ponto que ajustamos agora há pouco.

Você pode criar um arquivo chamado `README.md` na pasta do seu projeto, colar esse código lá e salvar.
```