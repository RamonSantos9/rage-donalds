# Rage-Donalds

![Pré-visualização do Site](public/Thumbnail.png)

Rage-Donalds é um projeto desenvolvido para websites mobile, oferecendo uma experiência única e otimizada para dispositivos móveis. Com foco em performance e escalabilidade, este projeto demonstra a união de tecnologias modernas para criar interfaces atraentes e responsivas.

## Descrição

Concebido para exemplificar o desenvolvimento de websites mobile com uma estrutura modular e de fácil manutenção, o Rage-Donalds adota uma abordagem mobile-first. Ele serve como base para quem deseja experimentar e aprender novas técnicas no desenvolvimento web, e em breve também contará com uma versão para desktop, ampliando suas possibilidades de uso.

## Demonstração

Experimente a versão ao vivo: [rage-donalds.vercel.app/rage-donalds](https://rage-donalds.vercel.app/rage-donalds)

## Tecnologias Utilizadas

- **Next.js:** Framework React para construção de aplicações web escaláveis e performáticas.
- **TypeScript:** Linguagem com tipagem estática que aumenta a robustez do código.
- **Tailwind CSS:** Framework CSS que possibilita estilizações rápidas e customizadas.
- **Prisma:** ORM para gerenciamento e migração do banco de dados.
- **ESLint & Prettier:** Ferramentas para manter a padronização e qualidade do código.
- **Vercel:** Plataforma de deploy otimizada para aplicações Next.js.

## Funcionalidades

- **Estrutura Modular:** Facilita a manutenção e evolução do projeto.
- **Design Responsivo e Mobile-First:** Garante uma experiência excelente em dispositivos móveis.
- **Componentização Simplificada:** Permite um desenvolvimento ágil.
- **Integração com Next.js e Tailwind CSS:** Oferece estilos customizados de forma prática.
- **Ferramentas de Lint e Formatação:** Mantêm a consistência e a qualidade do código.
- **Otimizações de Performance:** Asseguram uma navegação fluida.

## Instalação

Siga os passos abaixo para rodar o projeto localmente:

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/RamonSantos9/rage-donalds.git

2. **Entre na pasta do projeto:**

    ```bash
    cd rage-donalds

3. **Configure as variáveis de ambiente**

    > Crie um arquivo .env na raiz do projeto e adicione a seguinte linha:
    ```bash

    DATABASE_URL="postgresql://<usuário>:<senha>@<host>.neon.tech/<nome_do_banco>?sslmode=require"

Substitua <usuário>, <senha>, <host> e <nome_do_banco> pelas informações correspondentes do seu banco de dados no Neon. Para obter a string de conexão correta, acesse o painel do Neon, selecione seu projeto e clique em "Connect". Mais informações podem ser encontradas na documentação do Neon.

4. **Instale as dependências**

    ```bash
    npm install

5. **Inicie o servidor de desenvolvimento**

    ```bash
    npm run dev

6. **Acesse o projeto: Abra seu navegador e digite**

    http://localhost:3000/rage-donalds

7. **Visualização Mobile**

    Como este projeto é mobile-first e ainda não possui uma versão adaptada para desktop, utilize as ferramentas de desenvolvedor do seu navegador (pressione CTRL + SHIFT + C ou selecione "Inspecionar Elemento") para simular a visualização em dispositivos móveis.

**Observações Importantes:**

- **Configuração do Banco de Dados com Neon:** O Neon é um serviço de banco de dados PostgreSQL gerenciado que oferece uma camada gratuita generosa. Para configurar o `DATABASE_URL` corretamente, siga as instruções fornecidas no painel do Neon após a criação do seu projeto. Mais detalhes estão disponíveis na [documentação oficial do Neon](https://neon.tech/docs/guides/nextjs).

- **Segurança:** Nunca compartilhe suas credenciais sensíveis publicamente. Certifique-se de que o arquivo `.env` esteja listado no `.gitignore` para evitar que seja versionado.

- **Deploy:** Para fazer o deploy do projeto, considere utilizar a Vercel, que oferece integração simplificada com projetos Next.js. Durante o processo de deploy, configure as variáveis de ambiente no painel da Vercel, incluindo o `DATABASE_URL`.

Seguindo essas instruções, você estará pronto para rodar e desenvolver o projeto Rage-Donalds localmente, além de estar preparado para futuras implementações e contribuições.