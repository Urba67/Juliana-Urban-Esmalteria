[README.md](https://github.com/user-attachments/files/33292420/README.md)# Juliana Urban Esmalteria

Site institucional da **Juliana Urban Esmalteria**, desenvolvido para apresentar o salão, destacar serviços e trabalhos reais de unhas e facilitar o contato para agendamentos.

## ✨ Sobre o projeto

O site tem uma identidade visual elegante e moderna, com foco em beleza, cuidado e atenção aos detalhes. Ele reúne informações sobre a esmalteria em uma página de navegação simples e adaptável a diferentes tamanhos de tela.

## 🖥️ Funcionalidades

- **Página inicial:** apresentação da esmalteria e chamada para agendamento.
- **Serviços:** cartões com categorias de serviços, como manicure, esmaltação, nail art e cuidados com as unhas.
- **Galeria:** espaço para visualizar fotos reais dos trabalhos realizados.
- **Contato e agendamento:** acesso ao WhatsApp para consultar disponibilidade, serviços e valores.
- **Redes sociais:** links para Instagram e Facebook.
- **Navegação por seções:** acesso rápido às áreas principais da página.

> **Importante:** as categorias de serviços exibidas no site são sugestões e devem ser confirmadas com o estabelecimento. Consulte diretamente a esmalteria para confirmar serviços, preços e disponibilidade.

## 🧰 Tecnologias utilizadas

- **React** — construção da interface.
- **TypeScript** — tipagem e organização do código.
- **Vite** — ferramentas de desenvolvimento e build.
- **Tailwind CSS** — suporte à estilização.
- **Express** — servidor da aplicação.
- **tRPC** — comunicação tipada entre cliente e servidor.
- **Drizzle ORM** — integração com banco de dados, quando utilizada.

## 📁 Estrutura principal

```text
.
├── client/
│   ├── public/
│   │   └── assets/          # Imagens dos trabalhos de unhas
│   └── src/
│       ├── components/     # Componentes reutilizáveis
│       ├── pages/           # Páginas da aplicação
│       └── App.tsx          # Configuração principal da interface
├── server/                  # Servidor e rotas da aplicação
├── package.json             # Dependências e scripts
└── README.md                # Documentação do projeto
```

## 🚀 Como executar localmente

### Requisitos

- Node.js compatível com as dependências do projeto.
- [pnpm](https://pnpm.io/) instalado.

### Instalação

1. Baixe ou clone este repositório.
2. Abra um terminal na pasta do projeto.
3. Instale as dependências:

   ```bash
   pnpm install
   ```

4. Inicie o ambiente de desenvolvimento:

   ```bash
   pnpm dev
   ```

5. Acesse o endereço local exibido no terminal.

## 📦 Scripts disponíveis

| Comando | Descrição |
| --- | --- |
| `pnpm dev` | Inicia o servidor de desenvolvimento. |
| `pnpm build` | Gera a versão de produção. |
| `pnpm start` | Executa a versão compilada. |
| `pnpm check` | Verifica os tipos TypeScript. |
| `pnpm test` | Executa os testes automatizados. |
| `pnpm format` | Formata os arquivos com Prettier. |

## 🖼️ Imagens

As imagens utilizadas na galeria ficam em `client/public/assets/`. Para substituir ou adicionar trabalhos, mantenha os arquivos nessa pasta e atualize as referências correspondentes no código.

Utilize imagens autorizadas pelo estabelecimento e evite publicar fotografias sem permissão.

## 📍 Informações de contato

- **Nome:** Juliana Urban Esmalteria
- **Localização:** Joinville, Santa Catarina
- **WhatsApp:** +55 (47) 99949-4270
- **Instagram:** [@julianaurbanesmalteria](https://www.instagram.com/julianaurbanesmalteria/)
- **Facebook:** [julyesmalteria2013](https://www.facebook.com/julyesmalteria2013/)

## 📄 Licença

O `package.json` declara a licença MIT para o projeto. Antes de distribuir ou reutilizar o site, confirme se essa licença também cobre todos os elementos, imagens, marcas e conteúdos de terceiros incluídos no projeto.
