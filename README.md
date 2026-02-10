# Projeto de Redes: Condomínio de Laboratórios - Campus Laranjeiras

Este documento apresenta a infraestrutura técnica e o planejamento de redes dos cinco laboratórios integrados ao Condomínio de Laboratórios de Campus Laranjeiras. A solução foi projetada para garantir alta disponibilidade, segurança perimetral e integração via nuvem para suporte à pesquisa acadêmica avançada e preservação patrimonial.

**Acesso ao Condomínio (Portal Integrado): [http://nlb-instance-e52025b731f159c2.elb.us-east-1.amazonaws.com:8080/](http://nlb-instance-e52025b731f159c2.elb.us-east-1.amazonaws.com:8080/)** 

---

## 1. AMA - Arqueologia do Mundo Atlântico
**Descrição Técnica:**
Implementação de rede resiliente focada em geoprocessamento (GIS) e catalogação digital. A arquitetura utiliza uma topologia em estrela hierárquica centralizada em um Gateway de Segurança Integrado (UDM Pro), que consolida as funções de roteador de borda, firewall e controlador de rede.

* **Segurança e Segmentação:** Implementação de VLANs para isolamento do tráfego administrativo e estações GIS, mitigando riscos de segurança lateral.
* **Integração e Nuvem:** Migração do processamento pesado e do portal Urbes Invisibilia para infraestrutura AWS (Docker). A conectividade inter-campus é assegurada por um túnel VPN Site-to-Site.
* **Infraestrutura Local:** Armazenamento NAS para alta disponibilidade de arquivos cartográficos e Access Points Wi-Fi 6 para mobilidade no acervo.
* **Investimento Estimado:** R$ 50.000,00.
* **Link AWS: [http://ec2-54-243-16-146.compute-1.amazonaws.com/](http://ec2-54-243-16-146.compute-1.amazonaws.com/)  54.243.16.146 ** 

## 2. CEPUR - Planejamento e Práticas Urbanas e Regionais
**Descrição Técnica:**
Infraestrutura de alta performance desenhada para manipulação de grandes volumes de dados (QGIS e imagens de satélite) utilizando a linha corporativa TP-Link Omada para gerenciamento centralizado.

* **Núcleo da Rede:** Switch Core SG5452XMPP com 48 portas PoE++ e uplinks de 10Gbps (SFP+), garantindo vazão máxima para servidores de arquivos (NAS).
* **Gerenciamento:** Roteador VPN ER7212PC atuando como controladora central e gateway, permitindo acesso remoto seguro aos pesquisadores.
* **Continuidade Operacional:** Proteção elétrica via No-break Senoidal Puro de 2200VA, garantindo a integridade de equipamentos com fontes de PFC ativo.
* **Investimento Estimado:** R$ 19.500,00.
* **Link AWS:[http://nlb-instance-e52025b731f159c2.elb.us-east-1.amazonaws.com:8085/](http://nlb-instance-e52025b731f159c2.elb.us-east-1.amazonaws.com:8085/)** 

## 3. Tecnologias em Arquitetura e Urbanismo
**Descrição Técnica:**
Planejamento focado no suporte a fluxos de trabalho de modelagem 3D (BIM), nuvens de pontos e geoprocessamento para projetos de preservação do patrimônio histórico.

* **Performance de Processamento:** Integração ao condomínio de laboratórios para execução de renderizações de alto desempenho em ambiente de nuvem, reduzindo a carga do hardware local.
* **Resiliência e Backup:** Estratégia de redundância para o acervo digital de projetos como EMAU TRAPICHE e Cidade MIL através da infraestrutura central da UFS.
* **Conectividade:** Otimização de banda para tráfego de arquivos pesados de escaneamento a laser e fotogrametria.
* **Link AWS:[http://nlb-instance-e52025b731f159c2.elb.us-east-1.amazonaws.com:8084/](http://nlb-instance-e52025b731f159c2.elb.us-east-1.amazonaws.com:8084/)** 

## 4. Arqueologia e Bioarqueologia: Patrimônio Cultural e Ambiental
**Descrição Técnica:**
Modernização voltada ao suporte de dados massivos de escavações e análises bioantropológicas, integrando segurança lógica e monitoramento de ativos físicos.

* **Isolamento de Dados:** Utilização de VLANs para garantir a confidencialidade e integridade do banco de dados de patrimônio histórico sensível.
* **Monitoramento IoT:** Infraestrutura preparada para sensores de monitoramento ambiental remoto (temperatura e umidade) aplicados à conservação da reserva técnica.
* **Arquitetura:** Rede projetada para suportar alta demanda de processamento de imagens e registros catalográficos digitais.
* **Link AWS: [http://nlb-instance-e52025b731f159c2.elb.us-east-1.amazonaws.com:8081/](http://nlb-instance-e52025b731f159c2.elb.us-east-1.amazonaws.com:8081/)** 

## 5. Gemps - Memória e Patrimônio Sergipano
**Descrição Técnica:**
Infraestrutura de alto padrão corporativo baseada na linha TP-Link Omada, dimensionada para preservação e digitalização de acervos multimídia de grande volume.

* **Núcleo Layer 3:** Switch Gerenciável SG6654XHP com 48 portas PoE+ e capacidade de 10Gbps, permitindo roteamento inter-VLAN eficiente e alta velocidade de backbone.
* **Segurança de Borda:** Gateway VPN Multi-Gigabit ER7412-M2 para estabelecimento de túneis criptografados e proteção de banco de dados.
* **Conectividade Sem Fio:** 8 Access Points EAP265 HD estrategicamente distribuídos para cobertura estável de alta densidade.
* **Investimento Estimado:** R$ 35.844,86.
* **Link AWS: [http://nlb-instance-e52025b731f159c2.elb.us-east-1.amazonaws.com:8082/](http://nlb-instance-e52025b731f159c2.elb.us-east-1.amazonaws.com:8082/)** 

---

### Resumo Executivo da Infraestrutura
| Item | Especificação Padronizada |
| :--- | :--- |
| **Topologia** | Estrela Hierárquica com Segmentação por VLANs |
| **Tecnologia Wireless** | Wi-Fi 6 / Access Points de Alta Densidade |
| **Segurança** | Firewalls de Borda e VPNs Site-to-Site (AES-256) |
| **Capacidade de Uplink** | 10 Gbps SFP+ (Fibra Óptica) |
| **Proteção Elétrica** | No-breaks Senoidais com Gerenciamento |

---



