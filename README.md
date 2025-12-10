# 🔗 Ajax-Promise

## 📌 Descrição
Projeto simples que demonstra o uso de **Ajax** e **Promises** em JavaScript.  
Ao abrir o site, o usuário vê o título **"Ajax e Promise"** e três links: **Página 1**, **Página 2** e **Página 3**.  
Ao clicar em qualquer link, o conteúdo da respectiva página HTML é carregado dinamicamente na mesma página, sem recarregar o navegador.

---

## ⚙️ Funcionalidades
- Exibe título inicial: **Ajax e Promise**.
- Links para três páginas:
  - Página 1
  - Página 2
  - Página 3
- Ao clicar em um link:
  - O conteúdo da página correspondente é carregado via **Ajax**.
  - O resultado aparece logo abaixo do título principal.
- Cada página contém apenas um `<h1>` com seu título (ex.: "Página 1").

---

## 🛠️ Tecnologias utilizadas
- **HTML5** → estrutura da página  
- **CSS3** → estilização básica  
- **JavaScript (JS)**:
  - Manipulação do DOM (`document.querySelector`, `innerHTML`)  
  - Eventos (`addEventListener`) para capturar cliques nos links  
  - **Promises** para lidar com requisições assíncronas  
  - **XMLHttpRequest** (implementação inicial, depois comentada)  
  - **Fetch API** com `async/await` para carregar páginas dinamicamente  
  - Tratamento de erros com `try/catch`  

---

## 📸 Preview
![Ajax e Promise](./ajax.jpg)

---

## 🚀 Como visualizar

Você pode abrir o projeto localmente:

1. Baixe ou clone este repositório:
   - Clique em **Code > Download ZIP** e extraia os arquivos  
   - ou use o comando:
     ```bash
     git clone https://github.com/WellingthonSchuh/ajax-promise.git
     ```

2. Abra o arquivo `index.html` em qualquer navegador moderno.

Ou

1. Acesse o site:
   - https://wellingthonschuh.github.io/Ajax-Promise/

> ⚠️ O projeto é totalmente seguro. Nenhum dado é armazenado — o carregamento é feito apenas localmente via Ajax.

---

## 📚 Aprendizados
- Uso de **Ajax** para carregar conteúdo sem recarregar a página  
- Implementação de **Promises** para controlar fluxo assíncrono  
- Manipulação dinâmica do DOM para inserir conteúdo carregado  
- Estruturação de páginas simples para testes de requisições  

---

## 👨‍💻 Autor
Feito por **Wellingthon Schuh**  
🔗 [LinkedIn](https://www.linkedin.com/in/wellingthonschuh)
