# Projeto de Redes: Condomínio de Laboratórios - Campus Laranjeiras

Este documento apresenta a infraestrutura técnica e o planejamento de redes dos cinco laboratórios integrados ao Condomínio de Laboratórios de Campus Laranjeiras. A solução foi projetada para garantir alta disponibilidade, segurança perimetral e integração via nuvem para suporte à pesquisa acadêmica avançada e preservação patrimonial.

**Acesso ao Condomínio (Portal Integrado): [http://nlb-instance-e52025b731f159c2.elb.us-east-1.amazonaws.com:8080/](http://nlb-instance-e52025b731f159c2.elb.us-east-1.amazonaws.com:8080/)** 

---

## 1. AMA - Arqueologia do Mundo Atlântico
**Descrição Técnica:**
Implementação de rede resiliente focada em geoprocessamento (GIS) e catalogação digital. A arquitetura utiliza uma topologia em estrela hierárquica centralizada em um Gateway de Segurança Integrado (UDM Pro), que consolida as funções de roteador de borda, firewall e controlador de rede.

* **Gateway de Segurança:** 01 Unidade UDM Pro (Firewall, Roteador e Controladora).
* **Armazenamento:** 02 Unidades NAS (2-Bay) com discos Enterprise para redundância local.
* **Rede Sem Fio:** 04 Access Points Wi-Fi 6 (U6-Lite) para cobertura total do acervo.
* **Infraestrutura:** 01 Rack 6U, Patch Panel e Kit de organização de cabos.

**Subtotal:** R$ 57.057,35

* **Link AWS: [http://54.243.16.146](http://54.243.16.146/)** 

## 2. CEPUR - Planejamento e Práticas Urbanas e Regionais
**Descrição Técnica:**
Infraestrutura de alta performance desenhada para manipulação de grandes volumes de dados (QGIS e imagens de satélite) utilizando a linha corporativa TP-Link Omada para gerenciamento centralizado.

* **Switching:** 01 Switch Core Gerenciável SG5452XMPP (48 portas PoE++, 10Gbps Uplink).
* **Roteamento:** 01 Roteador VPN Corporativo ER7212PC Omada.
* **Energia:** 02 No-breaks Senoidais Puros 2200VA (Proteção para fontes PFC Ativo).
* **Conectividade:** Kit de Transceivers SFP+ e cabos ópticos para backbone de dados.

**Subtotal:** R$ 57.057,35

* **Link AWS: [http://100.53.139.17)** 

## 3. Tecnologias em Arquitetura e Urbanismo
**Descrição Técnica:**
Planejamento focado no suporte a fluxos de trabalho de modelagem 3D (BIM), nuvens de pontos e geoprocessamento para projetos de preservação do patrimônio histórico.

* **Switching:** 02 Switches Gerenciáveis 24 portas PoE+ (Distribuição para ilhas de modelagem).
* **Rede Sem Fio:** 03 Access Points Wi-Fi 6 High Range (U6-LR) para nuvens de pontos.
* **Cabeamento:** Bobina de cabo Cat6 blindado e conectores RJ45 blindados para 24 pontos.
* **Armazenamento:** 01 Unidade NAS dedicada para backup de curta duração (Hot Storage).

**Subtotal:** R$ 57.057,35

* **Link AWS:[http://nlb-instance-e52025b731f159c2.elb.us-east-1.amazonaws.com:80/](http://nlb-instance-e52025b731f159c2.elb.us-east-1.amazonaws.com:80)
* /)** 

## 4. Arqueologia e Bioarqueologia: Patrimônio Cultural e Ambiental
**Descrição Técnica:**
Modernização voltada ao suporte de dados massivos de escavações e análises bioantropológicas, integrando segurança lógica e monitoramento de ativos físicos.

* **Switching:** 02 Switches Gerenciáveis 16 portas PoE (Segurança lógica via VLANs).
* **IoT/Monitoramento:** Kit de Sensores de Temperatura e Umidade com Gateway dedicado.
* **Vigilância:** 06 Câmeras IP Full HD para monitoramento da reserva técnica.
* **Armazenamento:** 01 Unidade NAS de Alta Disponibilidade para registros bioantropológicos.

**Subtotal:** R$ 57.057,35

* **Link AWS: [http://52.200.222.233/](http://52.200.222.233/)** 

## 5. Gemps - Memória e Patrimônio Sergipano
**Descrição Técnica:**
Infraestrutura de alto padrão corporativo baseada na linha TP-Link Omada, dimensionada para preservação e digitalização de acervos multimídia de grande volume.

* **Switching:** 01 Switch Layer 3 Gerenciável SG6654XHP (Backbone de alta performance).
* **Roteamento:** 01 Gateway VPN Multi-Gigabit ER7412-M2.
* **Rede Sem Fio:** 06 Access Points EAP265 HD (Alta densidade de usuários simultâneos).
* **Armazenamento:** 01 Unidade NAS de 4 baias para acervo multimídia bruto.

**Subtotal:** R$ 57.057,36

* **Link AWS: [http://3.234.144.119/]** 

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












