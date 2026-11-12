<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:06b6d4&height=190&section=header&text=Diego%20Fabro&fontSize=46&fontColor=e8f1f5&fontAlignY=36&desc=Desenvolvedor%20Back-end%20Java&descSize=18&descAlignY=58" alt="Diego Fabro - Desenvolvedor Back-end Java" />
</p>

<p align="center">
  <a href="https://github.com/fabrodiego">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=22D3EE&center=true&vCenter=true&width=620&lines=Java+21+%C2%B7+Spring+Boot+%C2%B7+PostgreSQL;APIs+REST+e+sistemas+escal%C3%A1veis;Deploy+no+meu+pr%C3%B3prio+cluster+k3s;CI%2FCD%2C+observabilidade+e+automa%C3%A7%C3%A3o" alt="Java 21, Spring Boot, PostgreSQL, k3s" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/fabrodiego/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-06B6D4?style=for-the-badge&logo=linkedin&logoColor=03212A" alt="LinkedIn" />
  </a>
  <a href="https://github.com/fabrodiego?tab=repositories">
    <img src="https://img.shields.io/badge/Reposit%C3%B3rios-0E7490?style=for-the-badge&logo=github&logoColor=E8F1F5" alt="Repositórios" />
  </a>
</p>

---

### 👨‍💻 Sobre mim

Construo APIs em **Java e Spring Boot** e cuido de todo o caminho até a produção: banco, CI/CD, container, cluster e monitoramento. Meus projetos rodam num **cluster k3s próprio**, publicados via Cloudflare Tunnel.

```java
public class DiegoFabro {

    String cargo      = "Desenvolvedor Back-end";
    String foco       = "APIs REST, sistemas escaláveis e automação";

    String[] backend  = {"Java 21", "Spring Boot", "Spring Security", "JPA/Hibernate"};
    String[] dados    = {"PostgreSQL", "MySQL", "MongoDB", "Kafka", "RabbitMQ"};
    String[] infra    = {"Docker", "k3s", "Helm", "GitHub Actions (ARC)", "Cloudflare Tunnel", "Prometheus"};
    String[] extras   = {"Angular", "TypeScript", "Python", "Selenium"};

    String agora      = "Evoluindo o MoneyGuard e a observabilidade da minha VPS";
}
```

---

### 🛠️ Stack

**Back-end e dados**

<p align="left">
  <img src="https://skillicons.dev/icons?i=java,spring,postgres,mysql,mongodb,kafka,rabbitmq&theme=dark" alt="Java, Spring, PostgreSQL, MySQL, MongoDB, Kafka, RabbitMQ" />
</p>

**Infra e DevOps**

<p align="left">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,helm,githubactions,cloudflare,prometheus,linux,ubuntu,gcp,git&theme=dark" alt="Docker, Kubernetes, Helm, GitHub Actions, Cloudflare, Prometheus, Linux, Ubuntu, GCP, Git" />
</p>

**Front-end e automação**

<p align="left">
  <img src="https://skillicons.dev/icons?i=ts,angular,nodejs,python,selenium&theme=dark" alt="TypeScript, Angular, Node.js, Python, Selenium" />
</p>

---

### 📌 Projetos em destaque

| Projeto | O que é | Stack |
|---|---|---|
| 💰 **MoneyGuard**<br>[API](https://github.com/fabrodiego/moneyguard-api) · [Front](https://github.com/fabrodiego/moneyguard-frontend) · [Bot](https://github.com/fabrodiego/moneyguard-discord-bot) | Controle financeiro pessoal com API, painel web e bot no Discord. | Java 21 · Spring Boot · Angular · TypeScript · PostgreSQL |
| 🤖 **Chatbot RGC**<br>[Repo](https://github.com/fabrodiego/api_academia_rgc_chatbot) · [No ar](https://chatbot-rgc.fabrodiego.com) | Chatbot de atendimento para academia, com classificador TF-IDF próprio e Swagger. | Java 17 · Spring Boot · PostgreSQL |
| 📈 **VPS Monitor**<br>[API](https://github.com/fabrodiego/vps-monitor-api) · [Front](https://github.com/fabrodiego/vps-monitor-frontend) | Painel de observabilidade da minha VPS, alimentado pelo Prometheus, com login senha + TOTP. | Java 21 · Spring Boot · Angular · Prometheus |
| 📚 **VibeBooks**<br>[API](https://github.com/fabrodiego/VibeBooks-api) · [Front](https://github.com/fabrodiego/VibeBooks-frontend) | Rede social de livros com API RESTful. | Java · Spring Boot · Angular |
| 📝 **FormsToNotion**<br>[Repo](https://github.com/fabrodiego/FormsToNotion) | Automação que leva respostas do Microsoft Forms para o Notion. | Python · Selenium |

---

### ☁️ Como meus projetos vão para produção

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'background': '#07090d', 'primaryColor': '#0d1218', 'primaryTextColor': '#e8f1f5', 'primaryBorderColor': '#22d3ee', 'lineColor': '#22d3ee', 'secondaryColor': '#131a22', 'tertiaryColor': '#131a22'}}}%%
flowchart LR
    A[git push] --> B[GitHub Actions<br/>runner ARC no cluster]
    B --> C[Build + imagem Docker]
    C --> D[(GHCR)]
    D --> E[k3s<br/>chart Helm padrão]
    E --> F[Traefik]
    F --> G[Cloudflare Tunnel]
    G --> H((Internet))
    E -. métricas .-> P[Prometheus]
    P -.-> M[VPS Monitor]
```

---

### 📊 Atividade no GitHub

<p align="center">
  <img src="https://streak-stats.demolab.com?user=fabrodiego&locale=pt_br&border=164E63&border_radius=12&background=0D1218&ring=22D3EE&fire=22D3EE&currStreakNum=E8F1F5&sideNums=E8F1F5&currStreakLabel=22D3EE&sideLabels=A3B3BF&dates=6F8190&stroke=223040" alt="Sequência de contribuições" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/fabrodiego/fabrodiego/output/github-snake-dark.svg" alt="Cobrinha comendo o gráfico de contribuições" />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,100:0d1117&height=110&section=footer" width="100%" alt="" />
