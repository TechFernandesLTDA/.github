# Estrutura de Times e Responsabilidades

Esta estrutura organizacional define os papéis, responsabilidades e focos de atuação de cada time dentro da Tech Fernandes LTDA no GitHub.

---

## Visão Geral dos Times

| Time | Slug GitHub | Foco Principal |
|------|-------------|----------------|
| **Core Admin** | `@TechFernandesLTDA/core` | Gestão, Governança e Decisões Estratégicas |
| **Development** | `@TechFernandesLTDA/development` | Produtos, APIs e Software |
| **DevOps** | `@TechFernandesLTDA/devops` | CI/CD, Automação e Developer Experience |
| **Infrastructure** | `@TechFernandesLTDA/infrastructure` | Cloud (OCI/AWS), Redes e Segurança Base |
| **Data & AI** | `@TechFernandesLTDA/data-ai` | Dados, Analytics e Inteligência Artificial |

---

## Detalhamento das Responsabilidades

### 1. Core Admin (`core`)

**Descrição:** Equipe de liderança técnica e administração da organização.
**Foco:** Estratégia, Governança e Decisões de Alto Nível.

**Responsabilidades:**

- ✅ Gerenciamento de acessos e permissões globais.
- ✅ Criação e arquivamento de repositórios.
- ✅ Gestão de custos e billing (Cloud & Services).
- ✅ Definição de padrões de arquitetura corporativa.
- ✅ Aprovação final em mudanças críticas de produção.

---

### 2. Development (`development`)

**Descrição:** Equipe responsável pela construção e manutenção de produtos de software.
**Foco:** Entrega de valor para o cliente final através de código.

**Responsabilidades:**

- ✅ Desenvolvimento de funcionalidades (Frontend, Backend, Mobile).
- ✅ Manutenção de APIs e microsserviços.
- ✅ Escrita de testes unitários e de integração.
- ✅ Documentação de funcionalidades e regras de negócio.
- ✅ Code review de pares para qualidade de software.

**Tecnologias Comuns:** Python, Node.js, React, Java, Go.

---

### 3. DevOps (`devops`)

**Descrição:** Equipe focada na eficiência operacional, automação e experiência do desenvolvedor.
**Foco:** "Como o software chega em produção" e automação de processos.

**Responsabilidades:**

- ✅ Pipelines de CI/CD (GitHub Actions).
- ✅ Automação de releases e versionamento.
- ✅ Ferramentas de qualidade de código (Linters, Sonar).
- ✅ Scripts de automação interna.
- ✅ Observabilidade de aplicações (Logs, APM).

**Lema:** *"Se você precisa fazer mais de duas vezes, automatize."*

---

### 4. Infrastructure (`infrastructure`)

**Descrição:** Equipe guardiã da fundação tecnológica e recursos de nuvem.
**Foco:** Estabilidade, Segurança, Redes e Recursos Base.

**Responsabilidades:**

- ✅ Gerenciamento de Cloud Providers (OCI, AWS, Azure).
- ✅ Infrastructure as Code (Terraform, Ansible) para recursos base.
- ✅ Configuração de Redes (VCN, Subnets, DNS, VPN).
- ✅ Segurança de infraestrutura (Firewalls, WAF, IAM).
- ✅ Gerenciamento de Bancos de Dados (DBA tasks).

**Tecnologias Comuns:** Terraform, Kubernetes, OCI, Linux, Networking.

---

### 5. Data & AI (`data-ai`)

**Descrição:** Equipe especializada em transformar dados em inteligência.
**Foco:** Engenharia de Dados, Modelos de ML e Análise.

**Responsabilidades:**

- ✅ Pipelines de ETL/ELT e Engenharia de Dados.
- ✅ Criação e treinamento de modelos de IA/ML.
- ✅ Implementação de agentes autônomos e LLMs.
- ✅ Análise de dados e criação de dashboards.
- ✅ Governança de dados e compliance.

**Tecnologias Comuns:** Python (Pandas/NumPy), SQL, Spark, LLMs, Vector DBs.

---

## Matriz de Colaboração

Como os times interagem entre si:

- **Development ↔ DevOps**: Devs escrevem código, DevOps garante que ele chegue em produção seguro e testado.
- **DevOps ↔ Infrastructure**: Infra provê os recursos (K8s, VMs), DevOps automatiza o uso desses recursos.
- **Data & AI ↔ Infrastructure**: Data precisa de recursos computacionais pesados (GPUs, Storage) providos pela Infra.
- **Development ↔ Data & AI**: Devs integram modelos de IA em aplicações finais; Data fornece as APIs/Modelos.

---

## Como usar as Menções de Time

Use as menções no GitHub para solicitar revisão ou atenção:

- Precisa de review em código de app? -> `@TechFernandesLTDA/development`
- Falha no pipeline de deploy? -> `@TechFernandesLTDA/devops`
- Novo banco de dados ou erro de rede? -> `@TechFernandesLTDA/infrastructure`
- Dúvida sobre modelo de IA? -> `@TechFernandesLTDA/data-ai`
