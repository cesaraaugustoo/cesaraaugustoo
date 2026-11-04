<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=26&pause=1000&color=58A6FF&center=true&vCenter=true&width=640&lines=Desenvolvedor+de+Software+J%C3%BAnior;Automa%C3%A7%C3%A3o%2C+RPA+%26+Dados" alt="Desenvolvedor de Software Júnior · Automação, RPA & Dados" />

</div>

---

## 🔬 Sobre Mim

🎓 **Análise e Desenvolvimento de Sistemas**<br>
💼 **Desenvolvedor de Software Júnior na American Bulls** · 🤖 **Automação, RPA & Dados**

Transformo processos manuais e repetitivos em rotinas que rodam sozinhas, com conferência e alerta quando algo sai do esperado. Atuo do levantamento à entrega: estudo o processo com quem o opera, escrevo os **estudos de viabilidade** e a **documentação técnica**, implemento, testo e coloco para rodar em servidor Linux.

---

## 🚀 Projetos & Focos Atuais

Na **American Bulls**, hamburgueria com duas lojas e um centro de distribuição, automatizo o ciclo de compras e estoque, da nota fiscal à planilha de balanço.

- 📊 **American Bulls Dashboard:** sistema de gestão de estoque e compras em **React**, **TypeScript**, **Express** e **Supabase** (PostgreSQL com RLS). Casa cada item da nota fiscal com o insumo do estoque por regras de conversão, calcula o consumo e o CMV da semana e gera o contas a pagar. Em volta dele, rotinas que conferem a nota contra o pedido numa agenda de compras no **Notion**, conferem o balanço de segunda e montam o relatório de sexta. Mais de 1.300 testes automatizados em **Vitest**.
- 🧠 **GBrain, o Brain de compras:** memória pesquisável das regras de compra, construída sobre o [gbrain](https://github.com/garrytan/gbrain). Áudios, fotos e PDFs dos fornecedores são lidos com a **API da OpenAI** e indexados com **busca semântica**. Roda como servidor **MCP** numa VPS Linux, acessível só pela rede privada (**Tailscale**) e com chave de leitura por pessoa, e o **Claude Code** consulta essa base no dia a dia.
- 🧾 **[RPA NF Espião](https://github.com/cesaraaugustoo/rpa-nf-espiao):** robô em **Python** e **Playwright** que baixa o DANFE e o XML de cada nota fiscal recebida e salva na pasta da loja certa, sem duplicidade. Roda de hora em hora pelo **systemd**, com alertas por e-mail e testes no **GitHub Actions**.
- 📈 **[alerta-preco-nfe](https://github.com/cesaraaugustoo/alerta-preco-nfe):** relatório semanal dos itens que subiram de preço, calculado a partir do XML das NF-e de entrada, em Python só com a biblioteca padrão.

---

## 🏢 Experiência Anterior: Única Promotora

Na **Única Promotora**, empresa de crédito e correspondência bancária, desenvolvi sistemas internos e automações para a operação. Os projetos dessa fase estão no perfil **[@DevCesarUnica](https://github.com/DevCesarUnica)**.

- 🛡️ **[Antifraude Única](https://github.com/DevCesarUnica/antifraude-unica):** análise de propostas de crédito com motor de regras antifraude, perfis de acesso e processamento assíncrono. **FastAPI**, **SQLAlchemy**, **PostgreSQL**, **Celery** com **Redis**, **React** e **Docker**, com autenticação **JWT**.
- 📱 **[App de Acordos](https://github.com/DevCesarUnica/app-acordos-unica):** aplicativo mobile que calcula a viabilidade e acompanha os acordos financeiros com parceiros. **React Native** (Expo), **TypeScript** e **Firebase** (Auth e Firestore com regras por perfil).
- 🤖 **RPAs em Python e Playwright:** aprovação de propostas no portal [Hope/Titan](https://github.com/DevCesarUnica/rpa-aprovar-propostas-hope) e extração de leads do [Astor Tech](https://github.com/DevCesarUnica/automacao-astortech-novavida) e da [API da UY3 Credit](https://github.com/DevCesarUnica/automacao-UY3-novavida) (OAuth2), com higienização no Nova Vida e envio da base para a operação por e-mail.
- 📄 **[RPA de contratos no D4Sign](https://github.com/cesaraaugustoo/RPAcontrato):** mais de **4.000 contratos** baixados automaticamente, antes feitos à mão. E o [RPA de cadastro de usuários no Storm](https://github.com/cesaraaugustoo/Automa-o-adicionar-usu-rio-Python-Pandas-Selenium-), com **Selenium** e **Pandas**, que tirou da equipe de processos uma tarefa diária.
- 🌐 **Landing pages de captação de leads** para a [MDV Soluções](https://github.com/DevCesarUnica/egv-mdv-landing) e a [Realiza Empréstimos](https://github.com/DevCesarUnica/realiza-emprestimos-lp), em **React**, **Vite**, **Tailwind CSS** e **Framer Motion**.

---

## 🛠️ Tecnologias e Ferramentas

### 💻 Desenvolvimento (Front-end, Mobile & Back-end)

<img src="https://skillicons.dev/icons?i=py,ts,js,react,vite,tailwind,nodejs,express,fastapi" alt="Python, TypeScript, JavaScript, React, Vite, Tailwind CSS, Node.js, Express e FastAPI" />

![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white) ![Zod](https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white)

### 🗄️ Dados & Bancos

<img src="https://skillicons.dev/icons?i=postgres,supabase,redis,firebase,sqlite" alt="PostgreSQL, Supabase, Redis, Firebase e SQLite" />

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

### 🤖 Automação, IA & Integrações

<img src="https://skillicons.dev/icons?i=selenium,notion" alt="Selenium e Notion" />

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge) ![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge) ![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white) ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white) ![Google Apps Script](https://img.shields.io/badge/Google_Apps_Script-4285F4?style=for-the-badge&logo=googleappsscript&logoColor=white)

### ⚙️ Infra, DevOps & Testes

<img src="https://skillicons.dev/icons?i=linux,ubuntu,docker,git,github,githubactions,vitest" alt="Linux, Ubuntu, Docker, Git, GitHub, GitHub Actions e Vitest" />

![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=for-the-badge&logo=tailscale&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)

### 🧩 Engenharia de Requisitos & Documentação

![Documentação Técnica](https://img.shields.io/badge/Documenta%C3%A7%C3%A3o-T%C3%A9cnica-1F6FEB) ![Estudos de Viabilidade](https://img.shields.io/badge/Estudos-de_Viabilidade-1F6FEB) ![Regras de Negócio](https://img.shields.io/badge/Regras-de_Neg%C3%B3cio-1F6FEB)

---

## 📫 Contato

[<img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn" />](https://www.linkedin.com/in/cesaraugusto1602) [<img src="https://skillicons.dev/icons?i=gmail" alt="E-mail" />](mailto:cesar.augusto1618m@gmail.com)
