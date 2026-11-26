<div align="center">
  <img src="./assets/header-banner.jpg" width="100%" alt="Vanshaj Verma — Senior Software Engineer, AI Systems and Integrations" />

  <br /><br />

  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&amp;weight=600&amp;size=20&amp;duration=2800&amp;pause=900&amp;color=38BDF8&amp;center=true&amp;vCenter=true&amp;width=400&amp;lines=Enterprise+AI+%26+Agent+Systems;AI+Governance+at+5%2C000%2B+Scale;Cloud+%26+Developer+Platforms" alt="Enterprise AI and agent systems, AI governance at 5,000+ scale, and cloud and developer platforms" />
  <br /><br />

  <a href="https://www.linkedin.com/in/vanshaj-verma/"><img src="https://img.shields.io/badge/LET%27S_CONNECT-LinkedIn-0A66C2?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" alt="Connect on LinkedIn" /></a>
  <a href="mailto:verma.vanshaj.vv@gmail.com"><img src="https://img.shields.io/badge/SAY_HELLO-Email-1E3A5F?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="Send me an email" /></a>
  <img src="https://img.shields.io/badge/BASED_IN-Toronto%2C_Canada-1E3A5F?style=for-the-badge&amp;logo=googlemaps&amp;logoColor=white" alt="Based in Toronto, Canada" />
  <img src="https://komarev.com/ghpvc/?username=VanshajVerma&amp;style=for-the-badge&amp;color=0284C7&amp;label=PROFILE+VIEWS" alt="Profile views" />
</div>

---

### ⚡ Core AI &amp; Platform Impact

<table>
  <tr>
    <td width="33%" valign="top">
      <h4>🌐 AI Systems</h4>
      <p>AI gateways with <strong>semantic caching</strong>, dynamic routing, and local LLMs.</p>
    </td>
    <td width="33%" valign="top">
      <h4>🛡️ AI at Scale</h4>
      <p><strong>5,000+ developer machines</strong> covered by AI policy, guardrails, and audit trails.</p>
    </td>
    <td width="33%" valign="top">
      <h4>🔀 AI Agents</h4>
      <p><strong>Isolated agents</strong> and LLM bots for <strong>30+</strong> workflows.</p>
    </td>
  </tr>
</table>

---

### 🧠 AI Systems &amp; Platform Architecture

An architecture I build for enterprise agentic workflows:

```mermaid
%%{init: {"theme": "base", "look": "classic", "layout": "dagre", "htmlLabels": false, "flowchart": {"curve": "basis", "padding": 14, "nodeSpacing": 100, "rankSpacing": 35, "diagramPadding": 16, "wrappingWidth": 190, "minNodeWidth": 80}, "themeVariables": {"fontFamily": "Arial, sans-serif", "fontSize": "20px", "edgeLabelBackground": "#0F172A", "textColor": "#F8FAFC", "primaryTextColor": "#F8FAFC", "lineColor": "#38BDF8"}}}%%
flowchart LR
    A["🤖 Agents &<br/>developers"] --> S["🔒 Sandboxed<br/>workflows"]
    S --> B{"🛡️ Governance<br/>& guardrails"}
    B --> H["⚡ Tenant-scoped<br/>semantic cache"]
    H -->|Cache miss| C["🔀 Dynamic router<br/>Models / providers"]
    H -.->|Cache hit| A
    C -->|Fast & efficient| D["⚡ Lightweight<br/>LLMs"]
    C -->|Complex reasoning| E["🧠 Frontier<br/>LLMs"]
    C -->|On-premises| L["💻 Local<br/>LLMs"]
    B -->|Scoped access| F[("🗄️ Data &<br/>vector search")]
    B -.-> G["📊 Telemetry<br/>& audit"]
    style A fill:#0F172A,stroke:#38BDF8,color:#fff
    style S fill:#1E3A5F,stroke:#38BDF8,color:#fff
    style B fill:#1E3A8A,stroke:#38BDF8,color:#fff
    style H fill:#1E3A5F,stroke:#38BDF8,color:#fff
    style C fill:#0F172A,stroke:#38BDF8,color:#fff
    style D fill:#1E3A5F,stroke:#38BDF8,color:#fff
    style E fill:#1E3A5F,stroke:#38BDF8,color:#fff
    style L fill:#1E3A5F,stroke:#38BDF8,color:#fff
    style F fill:#0F172A,stroke:#38BDF8,color:#fff
    style G fill:#075985,stroke:#38BDF8,color:#fff
```

<sub>On smaller screens, use the diagram's zoom controls for a closer look.</sub>

---

### 🛠️ Tech Stack

<div align="center">

<strong>AI &amp; developer platforms</strong><br />
<img src="https://img.shields.io/badge/LLM_Orchestration-1E293B?style=for-the-badge" alt="LLM orchestration" />
<img src="https://img.shields.io/badge/MCP-1E293B?style=for-the-badge" alt="Model Context Protocol" />
<img src="https://img.shields.io/badge/Semantic_Caching-1E293B?style=for-the-badge" alt="Semantic caching" />
<img src="https://img.shields.io/badge/Local_LLMs-1E293B?style=for-the-badge" alt="Local LLMs" />
<img src="https://img.shields.io/badge/AWS_Bedrock-1E293B?style=for-the-badge" alt="AWS Bedrock" />
<img src="https://img.shields.io/badge/OpenSearch-1E293B?style=for-the-badge&amp;logo=opensearch&amp;logoColor=white" alt="OpenSearch" />
<br /><br />

<strong>Languages &amp; application development</strong><br />
<img src="https://img.shields.io/badge/Python-1E293B?style=for-the-badge&amp;logo=python&amp;logoColor=3776AB" alt="Python" />
<img src="https://img.shields.io/badge/TypeScript-1E293B?style=for-the-badge&amp;logo=typescript&amp;logoColor=3178C6" alt="TypeScript" />
<img src="https://img.shields.io/badge/Go-1E293B?style=for-the-badge&amp;logo=go&amp;logoColor=00ADD8" alt="Go" />
<img src="https://img.shields.io/badge/Java-1E293B?style=for-the-badge" alt="Java" />
<img src="https://img.shields.io/badge/SQL-1E293B?style=for-the-badge" alt="SQL" />
<img src="https://img.shields.io/badge/Node.js-1E293B?style=for-the-badge&amp;logo=nodedotjs&amp;logoColor=5FA04E" alt="Node.js" />
<img src="https://img.shields.io/badge/React-1E293B?style=for-the-badge&amp;logo=react&amp;logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Next.js-1E293B?style=for-the-badge&amp;logo=nextdotjs&amp;logoColor=white" alt="Next.js" />
<br /><br />

<strong>Cloud &amp; infrastructure</strong><br />
<img src="https://img.shields.io/badge/AWS-1E293B?style=for-the-badge" alt="AWS" />
<img src="https://img.shields.io/badge/Google_Cloud-1E293B?style=for-the-badge&amp;logo=googlecloud&amp;logoColor=4285F4" alt="Google Cloud" />
<img src="https://img.shields.io/badge/Azure-1E293B?style=for-the-badge" alt="Azure" />
<img src="https://img.shields.io/badge/Terraform-1E293B?style=for-the-badge&amp;logo=terraform&amp;logoColor=844FBA" alt="Terraform" />
<img src="https://img.shields.io/badge/Kubernetes-1E293B?style=for-the-badge&amp;logo=kubernetes&amp;logoColor=326CE5" alt="Kubernetes" />
<img src="https://img.shields.io/badge/Kafka-1E293B?style=for-the-badge&amp;logo=apachekafka&amp;logoColor=white" alt="Apache Kafka" />
<img src="https://img.shields.io/badge/Redis-1E293B?style=for-the-badge&amp;logo=redis&amp;logoColor=FF4438" alt="Redis" />
<img src="https://img.shields.io/badge/PostgreSQL-1E293B?style=for-the-badge&amp;logo=postgresql&amp;logoColor=4169E1" alt="PostgreSQL" />

</div>

---

### 📊 GitHub Telemetry &amp; Activity

<div align="center">
  <img width="400" src="https://github-readme-stats.vercel.app/api?username=VanshajVerma&amp;card_width=400&amp;hide_rank=true&amp;line_height=24&amp;show_icons=true&amp;theme=tokyonight&amp;hide_border=true&amp;bg_color=0D1117&amp;title_color=38BDF8&amp;icon_color=38BDF8" alt="GitHub statistics based on publicly accessible data; commits from the last year" />
  <img width="400" src="https://github-readme-stats.vercel.app/api/top-langs/?username=VanshajVerma&amp;card_width=400&amp;layout=compact&amp;langs_count=8&amp;theme=tokyonight&amp;hide_border=true&amp;bg_color=0D1117&amp;title_color=38BDF8" alt="Most used languages in public repositories" />
  <br /><br />
  <img src="https://streak-stats.demolab.com?user=VanshajVerma&amp;theme=tokyonight&amp;hide_border=true&amp;background=0D1117&amp;ring=38BDF8&amp;fire=38BDF8&amp;currStreakLabel=38BDF8" alt="GitHub contribution streak" />
  <br /><br />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=VanshajVerma&amp;theme=tokyo-night&amp;hide_border=true&amp;bg_color=0D1117&amp;color=38BDF8&amp;line=38BDF8&amp;point=ffffff" width="100%" alt="GitHub contribution activity graph" />
</div>

---

### 🤝 Let's connect

<div align="center">
  <a href="https://www.linkedin.com/in/vanshaj-verma/"><strong>Connect on LinkedIn</strong></a>
  &nbsp; · &nbsp;
  <a href="mailto:verma.vanshaj.vv@gmail.com"><strong>Drop me an email</strong></a>
  <br /><br />
  <img src="./assets/footer-banner.jpg" width="100%" alt="Building reliable AI systems and developer platforms" />
</div>