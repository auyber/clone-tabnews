# clone-tabnews

> 🚧 **Em andamento** — projeto do [Curso.dev](https://curso.dev), feito aula a aula.

Implementação do [TabNews](https://www.tabnews.com.br) para estudar desenvolvimento web de ponta a ponta: do ambiente e do deploy até o back-end com banco de dados, testes e autenticação.

**No ar:** https://clone-tabnews-ten-rho.vercel.app

## Stack

- **Next.js 13** e **React 18**
- **Node.js** (versão LTS Hydrogen, definida no `.nvmrc`)
- **Git e GitHub** para versionamento
- **Vercel** para o deploy, que acontece a cada push na `main`

## Como rodar

Pré-requisitos: [nvm](https://github.com/nvm-sh/nvm) e Git.

```bash
git clone https://github.com/auyber/clone-tabnews.git
cd clone-tabnews

# usa a versão do Node definida no .nvmrc
nvm install
nvm use

npm install
npm run dev
```

O site sobe em `http://localhost:3000`.

## Feito até agora

- [x] Ambiente com Node fixado pelo `.nvmrc`
- [x] Projeto Next.js com a primeira página
- [x] Deploy na Vercel

## Próximas etapas

- [ ] Testes automatizados com Jest (TDD)
- [ ] PostgreSQL em Docker, com migrations
- [ ] Integração contínua com GitHub Actions e padrão de commits
- [ ] Cadastro de usuários, senha com hash, sessões e autorização
- [ ] E-mails de ativação de conta

---

Projeto de estudo e portfólio, por [@auyber](https://github.com/auyber).
