# Projeto de Redes: Condomínio de Laboratórios - Campus Laranjeiras

Este documento apresenta a infraestrutura técnica e o planejamento de redes dos cinco laboratórios integrados ao Condomínio de Laboratórios de Campus Laranjeiras. A solução foi projetada para garantir alta disponibilidade, segurança perimetral e integração via nuvem para suporte à pesquisa acadêmica avançada e preservação patrimonial.

**Acesso ao Condomínio (Portal Integrado): [http://nlb-instance-e52025b731f159c2.elb.us-east-1.amazonaws.com:8080/](http://nlb-instance-e52025b731f159c2.elb.us-east-1.amazonaws.com:8080/)** 

---

## 1. AMA - Arqueologia do Mundo Atlântico
**Descrição Técnica:**
Implementação de rede resiliente focada em geoprocessamento (GIS) e catalogação digital. A arquitetura utiliza uma topologia em estrela hierárquica centralizada em um Gateway de Segurança Integrado (UDM Pro), que consolida as funções de roteador de borda, firewall e controlador de rede.

**Perfil:** Central de processamento e segurança de dados.
* **Hardware de Rede:** 01 Gateway (Ata 09341233), 01 Switch Gerenciável, 02 Access Points.
* **Mobiliário:** 06 Mesas, 06 Cadeiras, 01 Armário.
* **Infraestrutura:** 01 Rack, 01 No-break 1200Va, Cabeamento Cat6.
* **Computação:** 02 Workstations de alto desempenho.
* **Investimento Estimado:** **R$ 72.450,00**

* **Link AWS: [http://54.243.16.146](http://54.243.16.146/)** 

## 2. CEPUR - Planejamento e Práticas Urbanas e Regionais
**Descrição Técnica:**
Infraestrutura de alta performance desenhada para manipulação de grandes volumes de dados (QGIS e imagens de satélite) utilizando a linha corporativa TP-Link Omada para gerenciamento centralizado.

**Perfil:** Análise de dados e planejamento regional.
* **Hardware de Rede:** 01 Firewall, 01 Switch Gerenciável, 02 Access Points.
* **Mobiliário:** 10 Mesas, 10 Cadeiras, 02 Armários.
* **Climatização:** 01 Ar-condicionado.
* **Computação:** 04 Computadores padrão.
* **Investimento Estimado:** **R$ 48.200,00**

* **Link AWS: [http://100.53.139.17)** 

## 3. Tecnologias em Arquitetura e Urbanismo
**Descrição Técnica:**
Planejamento focado no suporte a fluxos de trabalho de modelagem 3D (BIM), nuvens de pontos e geoprocessamento para projetos de preservação do patrimônio histórico.

**Perfil:** Modelagem BIM e digitalização 3D.
* **Hardware de Rede:** 01 Switch PoE, 03 Access Points, Fibra Óptica para interconexão.
* **Mobiliário:** 12 Mesas, 12 Cadeiras, 02 Armários.
* **Computação:** 03 Workstations, 01 Monitor adicional para render.
* **Periféricos:** 01 Impressora técnica.
* **Investimento Estimado:** **R$ 52.136,76**

* **Link AWS:[http://nlb-instance-e52025b731f159c2.elb.us-east-1.amazonaws.com:80/](http://nlb-instance-e52025b731f159c2.elb.us-east-1.amazonaws.com:80)
* /)** 

## 4. Arqueologia e Bioarqueologia: Patrimônio Cultural e Ambiental
**Descrição Técnica:**
Modernização voltada ao suporte de dados massivos de escavações e análises bioantropológicas, integrando segurança lógica e monitoramento de ativos físicos.

**Perfil:** Conservação e análise técnica de materiais.
* **Hardware de Rede:** 01 Switch, 02 Access Points.
* **Equipamento Técnico:** 01 Microscópio (Ata específica), 01 Balança de precisão.
* **Mobiliário:** 08 Mesas, 08 Cadeiras, 02 Armários para reserva técnica.
* **Climatização:** 01 Ar-condicionado (Essencial para conservação).
* **Investimento Estimado:** **R$ 44.500,00*

* **Link AWS: [http://52.200.222.233/](http://52.200.222.233/)** 

## 5. Gemps - Memória e Patrimônio Sergipano
**Descrição Técnica:**
Infraestrutura de alto padrão corporativo baseada na linha TP-Link Omada, dimensionada para preservação e digitalização de acervos multimídia de grande volume.

**Perfil:** Preservação multimídia e acervo digital massivo.
* **Hardware de Rede:** 01 Firewall, 01 Gateway de alta performance, 05 Access Points.
* **Mobiliário:** 15 Mesas, 15 Cadeiras, 02 Armários.
* **Computação:** 05 Computadores, 01 Unidade de Armazenamento (NAS) para acervo.
* **Investimento Estimado:** **R$ 68.000,00**

* **Link AWS: [http://3.234.144.119/]** 

---

### Resumo da Distribuição Orçamentária

| Laboratório | Vocação Principal | Valor (R$) |
| :--- | :--- | :--- |
| **AMA** | Núcleo de Segurança e Dados | R$ 72.450,00 |
| **CEPUR** | Planejamento Urbano | R$ 48.200,00 |
| **TAU** | Modelagem e BIM | R$ 52.136,76 |
| **Arqueologia** | Bioarqueologia e Conservação | R$ 44.500,00 |
| **GEMPS** | Acervo e Memória | R$ 68.000,00 |
| **TOTAL** | | **R$ 285.286,76** |

---













