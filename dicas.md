# 💡 Dicas de Arquitetura com Microsoft Azure

Algumas boas práticas e recomendações ao projetar arquiteturas em nuvem na Azure:

## 📐 Princípios Fundamentais

- **Escalabilidade**: Use escalonamento automático (Auto-Scaling) para lidar com variações de carga.

- **Alta Disponibilidade**: Distribua recursos entre zonas de disponibilidade.

- **Segurança**: Use Azure Key Vault, NSG (Network Security Groups), e políticas de RBAC.

- **Desempenho**: Utilize cache (ex: Azure Redis) e otimize recursos com Monitoramento.

- **Custos**: Analise consumo e defina alertas com o Azure Cost Management.


## 🔧 Ferramentas para Arquitetar

- **Azure Architecture Center** – Modelos e boas práticas.

- **Microsoft Visio / draw.io** – Para desenhar arquiteturas.

- **Azure Diagrams (Visual Studio Code)** – Plugin com ícones oficiais.

## 🧱 Componentes Frequentes em Arquiteturas

| Categoria       | Serviço Azure Exemplo                 |
|----------------|----------------------------------------|
| Compute         | Azure Virtual Machines, App Services   |
| Banco de Dados  | Azure SQL, Cosmos DB, PostgreSQL       |
| Armazenamento   | Blob Storage, Files, Disks             |
| Rede            | VNet, Load Balancer, Application Gateway |
| Segurança       | Azure Firewall, Key Vault, NSG         |
