# Módulo 6 | Data as a service

## O que é DaaS

### Benefícios do DaaS para organizações -> É uma variedade de soluções baseadas em nuvem usadas para trabalhar com dados.

- Maior acessibilidade
    - O DaaS permite que qualquer pessoa com acesso à internet acesse conjuntos de dados valiosos, independentemente de sua localização, dispositivo ou conhecimento técnico.
    - O DaaS elimina a necessidade de infraestrutura local robusta para armazenar, processar e analisar dados.
    - Usuários e empresas podem acessar dados de forma simples e rápida, sem precisar investir em hardware e software caros.
    - O DaaS oferece escalabilidade sob demanda, o que significa que os usuários podem acessar a quantidade de dados que precisam, quando precisam.
    - Em resumo, o DaaS oferece diversos benefícios que aumentam a acessibilidade dos dados, democratizando o acesso à informação, quebrando barreiras de infraestrutura, facilitando a colaboração, escalando sob demanda, oferecendo flexibilidade e personalização, aprimorando a segurança e reduzindo custos.
  
- Produtos melhores
    - Clareza sobre os pontos fortes e fracos na empresa. 

- Custo-benefício
    - Menor custo com manutenção e gerenciamento de dados.
    - São os engenheiro de dados que orientam sobre a projeção da utilização de dados.

- Tempo de configuração
    - Começam a armazenar e processar dados imediatamente ao empregar DaaS.
    - Dependendo do volume dos dados, é interessante ajustar com a empresa a desnecessidade de colocar tudo na cloud.
    - Sempre indentificar a necessidade da empresa.

- Experiência do usuário aprimorada
    - Dados existem para enriquecer o negócio.

- Tradicional x DaaS
    - Acesso aos dados
    - Armazenamento de dados
    - Gerenciamento e manutenção
    - Custos e flexibilidade

| Característica | Sistema Tradicional de Armazenamento de Dados | DaaS (Dados como Serviço) |
|---|---|---|
| Localização dos dados | Armazenados em servidores físicos no local da empresa. | Armazenados em data centers remotos gerenciados por um provedor de serviços em nuvem. |
| Acesso aos dados | Acessível apenas a partir da rede local da empresa ou através de VPN. | Acessível a partir de qualquer lugar com acesso à internet. |
| Escalabilidade | Escalabilidade limitada, exigindo investimento em hardware e software adicionais. | Altamente escalável, podendo ser dimensionado para cima ou para baixo de acordo com as necessidades da empresa. |
| Manutenção | A empresa é responsável pela manutenção do hardware, software e infraestrutura do sistema. | O provedor de serviços em nuvem é responsável pela manutenção da infraestrutura e do software. |
| Segurança | A empresa é responsável pela segurança dos dados e da infraestrutura. | O provedor de serviços em nuvem implementa medidas de segurança rígidas para proteger os dados. |
| Custos | Alto investimento inicial em hardware, software e infraestrutura. | Custos previsíveis e mensais, com base no uso. |
| Flexibilidade | Menos flexível, com opções limitadas de personalização. | Altamente flexível, com diversas opções de personalização e integração com outros aplicativos. |
| Confiabilidade | Suscetível a falhas de hardware e software. | Alta disponibilidade e redundância para garantir o acesso contínuo aos dados. |
| Atualizações | As atualizações de software e hardware precisam ser gerenciadas pela empresa. | As atualizações de software são gerenciadas pelo provedor de serviços em nuvem. |
| Suporte técnico | A empresa precisa ter sua própria equipe de TI ou contratar um serviço de suporte técnico externo. | Suporte técnico 24/7 incluso no plano de serviço. |

- Benefícios para empresa
    - Acesso fácil a conjuntos de dados
        - API simples e interface web
    - Exemplo de uso: empresas de entrega que utilizam API do Google Maps Platform.

- Eliminação de custos de infraestrutura
    - Sem custos com infraestrutura para armazenamento.
    - Exmplo de uso: empresa de comércio eletrônico usa o Amazon Redshift para armazenar e analisar grandes volumes de dados de transações de clientes, histórico de compras e comportamento de nevagação na web.
    - O DaaS pode reduzir significativamente os custos de armazenamento, processamento e análise de dados.
    - As empresas não precisam investir em infraestrutura local, software ou pessoal de TI dedicado para gerenciar seus dados.

- Agilidade e flexibilidade
    - Adicionam novos conjuntos de dados, altera os requisitos de processamento ou análise e integrar-se a novas ferramentas ou plataformas conforme necessário.
    - Exemplo de uso: Snowflake Data Cloud, para armazenamento e analise de dados de vendas.

## Arquitetura do DaaS

### Segurança e privacidade

- Integração de dados
    - Os dados são integrados a partir de diversas fontes, como bancos de dados internos, sistemas legados, feeds de dados externos, etc.     

- Implementação de segurança
    - As medidas de segurança são implementadas para proteger os dados contra acesso não autorizado, perda de dados e outros riscos de segurança.
 
- Testes e validação
  - O ambiente de produção não pode ser alterado. Antes deve ser testado a aplicação.

- Implantação e disponibilização
  - Após os testes, é implantado e disponibilizados para uso pelos usuários finais.

- Monitoramento e manutenção
  - Após a implantação, os serviços de dados são monitorados continuamente para garantir seu desempenho, disponibilidade e segurança.

- Otimização contínua
  - Provisionamento e gerenciamente de serviços de dados é um ciclo contínuo.
    - Atualização quando necessária.
