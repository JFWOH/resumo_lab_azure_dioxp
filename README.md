# Resumo de Computação em Nuvem

## O que é Cloud e Pré-requisitos para entender
A **computação em nuvem** é o fornecimento de serviços de computação, como servidores, armazenamento, bancos de dados, rede, software, análise e inteligência, pela Internet ("a nuvem"). Isso permite inovações mais rápidas, recursos flexíveis e economias de escala. Para entender a computação em nuvem, é importante ter conhecimentos básicos de TI, como **redes**, **sistemas operacionais**, **virtualização** e **segurança da informação**. Esses conhecimentos são aplicáveis a qualquer plataforma de cloud.

## Custos de Modelo local
O modelo local (**On-Premise**) envolve altos custos de capital (**CapEx**) com a compra de hardware e software, configuração e execução de data centers locais, além de custos operacionais (**OpEx**) contínuos com eletricidade, refrigeração e especialistas de TI.

## On-Premise vs Ambiente Cloud
No ambiente **On-Premise**, a empresa é responsável por toda a infraestrutura e manutenção. No ambiente **Cloud**, os serviços são fornecidos pela Internet, permitindo maior flexibilidade, escalabilidade e redução de custos operacionais. A nuvem pública, privada e híbrida são opções de implantação que oferecem diferentes níveis de controle e segurança.

## Hybrid Model
O modelo **híbrido** combina infraestrutura local com nuvem pública, permitindo que dados e aplicativos se movam entre os dois ambientes. Isso oferece maior flexibilidade, segurança e conformidade, além de otimizar custos ao escalar recursos conforme necessário.

## Qual Modelo Escolher
A escolha do modelo depende das necessidades específicas da empresa. Pequenas empresas podem se beneficiar do **SaaS** pela simplicidade e baixo custo inicial. Empresas de médio porte podem optar pelo **PaaS** para desenvolver aplicativos personalizados. Grandes empresas podem usar **IaaS** para maior controle sobre a infraestrutura. O modelo híbrido é ideal para setores regulamentados que precisam manter dados confidenciais localmente.

## As a Service (usando a comparação do modelo cloud com o de Laundry)
Os modelos de serviço em nuvem são frequentemente comparados ao serviço de lavanderia. Assim como você pode lavar suas roupas em casa (**On-Premise**) ou usar uma lavanderia (**Cloud**), na computação em nuvem você pode optar por diferentes níveis de serviço:
- **IaaS (Infrastructure as a Service)**: Você aluga infraestrutura de TI (servidores, máquinas virtuais, armazenamento, redes) e paga conforme o uso.
- **PaaS (Platform as a Service)**: Fornece ferramentas para desenvolver e hospedar aplicativos web sem se preocupar com a infraestrutura subjacente.
- **SaaS (Software as a Service)**: Aplicativos baseados na web são hospedados e gerenciados pelo provedor de nuvem.

## Comparar os modelos e preços de nuvem
Os preços dos serviços de nuvem variam conforme o tipo de serviço e a região. O **Azure** oferece uma calculadora de preços para estimar os custos com base nas necessidades específicas.

## Platform
Os principais provedores de nuvem oferecem plataformas abertas e flexíveis que permitem a criação de aplicativos inteligentes em escala empresarial. Cada plataforma possui uma ampla gama de serviços, incluindo **IA**, **análise**, **computação**, **contêineres**, **bancos de dados** e muito mais.

- **Azure**: A plataforma de computação em nuvem do Azure é aberta e flexível, permitindo a criação de aplicativos inteligentes em escala empresarial. Oferece serviços como IA, análise, computação, contêineres, bancos de dados e muito mais.
- **AWS**: Oferece uma ampla gama de serviços de computação em nuvem, incluindo IA, análise, computação, contêineres, bancos de dados, armazenamento e muito mais. A plataforma é altamente escalável e flexível, permitindo que as empresas criem e implementem aplicativos de forma eficiente.
- **Oracle Cloud**: Oferece serviços de IA, análise, computação, contêineres, bancos de dados e muito mais. A plataforma é projetada para ser altamente segura e escalável, permitindo que as empresas criem e implementem aplicativos de forma eficiente.
- **GCP**: Oferece serviços de IA, análise, computação, contêineres, bancos de dados e muito mais. A plataforma é conhecida por sua capacidade de processamento de dados em grande escala e alta disponibilidade.

## Regions & Zones
Os principais provedores de nuvem, como **Azure**, **AWS**, **Oracle** e **GCP**, possuem uma infraestrutura global robusta com várias regiões e zonas de disponibilidade para garantir alta disponibilidade e continuidade dos negócios. Cada região é composta por vários data centers, e as zonas de disponibilidade são projetadas para eliminar pontos únicos de falha e garantir a replicação síncrona de dados.

- **Azure**: Possui mais de 60 regiões anunciadas, mais do que qualquer outro provedor de nuvem. Cada região contém várias zonas de disponibilidade, garantindo alta disponibilidade e continuidade dos negócios.
- **AWS (Amazon Web Services)**: Oferece 26 regiões geográficas e 84 zonas de disponibilidade. As zonas de disponibilidade são projetadas para serem isoladas umas das outras, mas conectadas por redes de alta velocidade e baixa latência.
- **Oracle Cloud**: Possui 37 regiões de nuvem em todo o mundo. Cada região oferece várias zonas de disponibilidade para garantir alta disponibilidade e recuperação de desastres.
- **GCP (Google Cloud Platform)**: Oferece 35 regiões e 106 zonas de disponibilidade. As zonas de disponibilidade são projetadas para fornecer alta disponibilidade e baixa latência.

## Comparação entre CapEx e OpEx
**CapEx** refere-se a despesas de capital, como compra de hardware e software. **OpEx** são despesas operacionais contínuas, como manutenção e eletricidade. A computação em nuvem reduz **CapEx** ao eliminar a necessidade de grandes investimentos iniciais e transforma esses custos em **OpEx**, permitindo que as empresas paguem apenas pelos recursos que usam.

## SLA (Service Level Agreement)
**SLA** é um acordo de nível de serviço que define os padrões de desempenho e disponibilidade que o provedor de nuvem deve cumprir. Os principais provedores de nuvem oferecem **SLAs** robustos para garantir alta disponibilidade e confiabilidade dos serviços.

- **Azure**: Oferece um SLA de alta disponibilidade de 99,99% para a maioria dos serviços.

| **Nível de SLA** | **Inatividade por semana** | **Inatividade por mês** | **Inatividade por ano** |
|------------------|----------------------------|-------------------------|-------------------------|
| **99%**          | 1,68 horas                 | 7,2 horas               | 87,6 horas              |
| **99,5%**        | 0,84 horas                 | 3,6 horas               | 43,8 horas              |
| **99,99%**       | 1,01 minutos               | 4,38 minutos            | 52,56 minutos           |

## Benefícios da Nuvem Azure
A nuvem **Azure** oferece vários benefícios:
- **Escalabilidade**: Capacidade de aumentar ou diminuir recursos conforme necessário.
- **Elasticidade**: Ajuste automático de recursos para atender à demanda.
- **Confiabilidade**: Alta disponibilidade e recuperação de desastres.
- **Previsibilidade**: Custos previsíveis com pagamento conforme o uso.
- **Segurança**: Medidas robustas de segurança e conformidade.
- **Governança**: Controle e conformidade com políticas de TI.
- **Gerenciabilidade**: Ferramentas para gerenciar e monitorar recursos de nuvem.

## Criação de Máquina Virtual no Azure

Com base nas orientações existentes em https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal?WT.mc_id=UI_empg, foi criada uma máquina virtual no portal Azure conforme segue:

### Opções de disponibilidade
- **Zona de disponibilidade**: Zona auto-selecionada
- **Zona de disponibilidade**: 1

### Tipo de segurança
- **Computadores virtuais de inicialização confiável**
  - Habilitar inicialização segura: Sim
  - Habilitar vTPM: Sim
  - Monitoramento de integridade: Não

### Imagem
- **Windows Server 2022 Datacenter: Azure Edition Hotpatch – Gen2**
- **Arquitetura de VM**: x64
- **Tamanho**: Standard B1s (1 vcpu, 1 GiB memória)
- **Habilitar Hibernação**: Não

### Configurações de acesso
- **Nome de usuário**: JWOH
- **Portas de entrada públicas**: RDP
- **Já possui uma licença do Windows?**: Não
- **Azure Spot**: Não

### Discos
- **Tamanho do disco do SO**: Padrão de imagem
- **Tipo de disco de SO**: LRS do SSD Premium
- **Usar discos gerenciados**: Sim
- **Excluir o disco do SO com a VM**: Habilitado
- **Disco de SO efêmero**: Não

Como até o momento não foi trabalhado no curso nenhum aspecto prático do uso da máquina virtual ou detalhes de configuração, o laboratório se baseou nas instruções da página e das informações genéricas da instrutura no curso. Foi testado também o copilot dentro do ambiente de configuração da Azure.

## Referências
- *https://learn.microsoft.com/pt-br/training/modules/describe-benefits-use-cloud-services/2-high-availability-scalability-cloud*
- *https://learn.microsoft.com/pt-br/training/modules/describe-benefits-use-cloud-services/3-reliability-predictability-cloud*
- *https://learn.microsoft.com/pt-br/training/modules/describe-benefits-use-cloud-services/4-security-governance-cloud*
- *https://learn.microsoft.com/pt-br/training/modules/describe-benefits-use-cloud-services/5-manageability-cloud*




