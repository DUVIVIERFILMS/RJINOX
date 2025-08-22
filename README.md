# RJ Inox – Site institucional

Este repositório contém o código-fonte de um website responsivo e otimizado para hospedagem no [GitHub Pages](https://pages.github.com). O projeto foi criado utilizando **HTML5 semântico**, **CSS3 modularizado** e **JavaScript** para pequenas interações. O objetivo é apresentar a empresa RJ Inox, especializada em móveis planejados em aço inox para cozinhas industriais, e facilitar o contato com clientes.

## Estrutura do projeto

```
.
├── assets/          # Imagens e outros recursos estáticos
│   ├── hero.png     # Imagem de destaque utilizada no topo do site
│   ├── workbench.png# Ilustração de mesa/bancada em aço inox
│   ├── shelf.png    # Textura/ilustração de estante em aço inox
│   └── sink.png     # Ilustração de cuba em aço inox
├── css/
│   └── style.css    # Estilos globais, variáveis e responsividade
├── js/
│   └── main.js      # Scripts para navegação, formulário e outras interações
├── index.html       # Página inicial com apresentação e cards de produtos
├── about.html       # Página "Sobre", com detalhes da empresa e produtos
├── contact.html     # Página de contato com formulário funcional
└── README.md        # Este documento
```

## Como visualizar o site localmente

Para ver o site em sua máquina basta abrir os arquivos `.html` em um navegador. Caso queira executar um servidor local (opcional, mas recomendado), siga os passos abaixo:

1. Certifique‑se de ter o **Python** instalado. A maioria das distribuições já acompanha uma versão da ferramenta.
2. No terminal, navegue até a pasta `website` deste repositório.
3. Execute o seguinte comando para iniciar um servidor HTTP simples:

   ```bash
   python3 -m http.server 8000
   ```

4. Abra seu navegador e acesse `http://localhost:8000/index.html` para visualizar a página inicial. A navegação entre as páginas ocorrerá normalmente.

## Publicando no GitHub Pages

O GitHub Pages permite hospedar páginas estáticas diretamente de um repositório. Para publicar este site:

1. Crie um repositório no GitHub (por exemplo, `rjinox-site`).
2. Faça o upload de todos os arquivos da pasta `website` para a raiz do seu repositório.
3. No GitHub, vá em **Settings** → **Pages**.
4. Em **Source**, selecione a branch desejada (por padrão `main`) e, em seguida, o diretório raiz (`/`). Salve as configurações.
5. O GitHub Pages irá gerar um link do tipo `https://seu-usuario.github.io/rjinox-site/`. Após alguns minutos o site estará disponível nesse endereço.

### Dicas importantes

- **Estrutura pronta para expansão:** novas páginas podem ser adicionadas facilmente replicando a estrutura básica dos arquivos existentes (cabeçalho, rodapé e navegação).
- **Acessibilidade:** todos os elementos de imagem possuem atributos `alt` descritivos. O menu é navegável via teclado e os contrastes de cores atendem às recomendações de acessibilidade.
- **Manutenção de estilos:** variáveis CSS no seletor `:root` centralizam cores, tamanhos de fonte e espaçamentos. Alterar essas variáveis reflete em todo o site.
- **Atualização de ano automática:** o script em `main.js` insere o ano atual no rodapé automaticamente, evitando manutenções anuais.
- **SEO e tags sociais:** `index.html` inclui meta tags básicas de SEO e Open Graph/Twitter Cards para melhor compartilhamento nas redes sociais.

## Licença

Este projeto está disponível para fins de estudo e pode ser adaptado conforme as necessidades. Ao utilizá-lo, mantenha os créditos da estrutura original.