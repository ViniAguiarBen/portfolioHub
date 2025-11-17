# PortfolioHUB - [Bootcamp I CEUB]

Este é o repositório do projeto "PortfolioHUB", um hub centralizado para meus projetos acadêmicos e profissionais.

[cite_start]Este projeto foi desenvolvido como a "Entrega Final" do Bootcamp I (Prof. Marcelo Carboni Gomes)[cite: 1, 4], com foco na implantação, integração com GitHub Pages e práticas de segurança.

## 🚀 Site em Produção (Live)

O site está implantado e disponível publicamente no seguinte link, utilizando GitHub Pages:

**[https://viniaguiarben.github.io/portfolioHub/](https://viniaguiarben.github.io/portfolioHub/)**

---

## 🛠️ Documentação do Processo (Entrega Final)

[cite_start]Conforme solicitado pelo desafio[cite: 6], esta seção documenta o processo de implantação e as práticas de colaboração implementadas.

### 1. Implantação e Integração (GitHub Pages + Actions)

* **Tecnologia:** O site é implantado usando **GitHub Pages** e **GitHub Actions**.
* **Fluxo de Trabalho:** Utilizamos o workflow `Static HTML` do GitHub Actions. Esse fluxo é acionado automaticamente a cada `merge` ou `push` no branch `main`, garantindo a integração contínua (CI/CD).
* **Processo:** O workflow "constrói" o site (publicando os arquivos HTML/CSS) e o disponibiliza no link de produção.

### [cite_start]2. Gestão de Usuários e Segurança [cite: 36]

[cite_start]Para garantir a estabilidade do site em produção e aderir às "melhores práticas"[cite: 39]:

* **Proteção de Branch (Branch Protection Rule):** Está ativa a regra **"Require a pull request before merging"** (Exigir um pull request antes de mesclar) no branch `main`.
* [cite_start]**Controle de Acesso[cite: 40]:** Nenhuma alteração pode ser enviada (pushed) diretamente para o `main`. Todas as modificações, mesmo de administradores, devem ser feitas em um branch separado e propostas via **Pull Request (PR)** para revisão e merge.

[cite_start]Isso cumpre os requisitos de "Gestão de Usuários" e "Controle de Acesso com Git"[cite: 37, 41].

### 3. Tecnologias Utilizadas no Hub
* HTML5
* Tailwind CSS (via CDN)
* Git / GitHub
* GitHub Pages
* GitHub Actions
