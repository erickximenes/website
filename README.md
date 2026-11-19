<div id="inicio"></div>
<h1 align="center">🚀 website · Erick Ximenes Vasconcelos</h1>

<p align="center">
  <a href="https://erickximenes.github.io/website"><b>erickximenes.github.io/website</b></a>
</p>

> Meu portfólio profissional: quem sou, serviços, projetos, stack e experiência. É uma página única em HTML, CSS e JavaScript puros, sem build, hospedada no GitHub Pages.

## ✨ O que tem no site

- Visual escuro e responsivo (celular, tablet e desktop)
- Português e inglês, com troca por botão (a escolha fica salva no navegador)
- Seções: Sobre, Serviços, Projetos em destaque, Skills, Experiência, Formação e Contato
- SEO: meta tags, Open Graph e dados estruturados (`schema.org/Person`)
- Sem dependências: os ícones são SVG inline e as fontes vêm do Google Fonts

## 🗂️ Estrutura

```
index.html        # página completa (HTML + CSS + JS)
images/user-3.jpg # foto de perfil
images/icon.ico   # favicon
```

Os textos em inglês ficam no objeto `en` no fim do `index.html`. Para editar um texto, altere o HTML (português) e a chave correspondente em `en` (o atributo `data-i18n` liga os dois).

## 💻 Rodando localmente

Basta abrir o `index.html` no navegador ou subir um servidor estático:

```bash
npx serve .
```

## 🚀 Publicando no GitHub Pages

No repositório, vá em `Settings` → `Pages` e use a branch `main`, pasta `/ (root)`:

![Configuração do GitHub Pages](images/config.png)

O site fica disponível em `https://{usuario}.github.io/{repositorio}`, por exemplo `erickximenes.github.io/website`.

## 🤝 Autor

<table>
  <tr>
    <td align="center">
      <a href="https://www.linkedin.com/in/erick-vasconcelos-50baa8150/" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/67069017?v=4" width="100px;" alt="Foto do Erick no GitHub"/><br>
        <sub><b>Erick Ximenes Vasconcelos</b></sub>
      </a><br>
      <a href="https://www.buymeacoffee.com/erickzaunlab" target="_blank"><img src="https://raw.githubusercontent.com/appcraftstudio/buymeacoffee/master/Images/snapshot-bmc-button.png" width="100px;"></a>
    </td>
  </tr>
</table>

[⬆ Voltar ao topo](#inicio)
