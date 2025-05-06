# Resumo-do-labDio
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

As a Service (Modelo de negócio)
Modelo Local (On-Premise)
Hybrid Model -> Mescla entre On-Premise e Cloud
Desvantagens: Latência; Regras de funcionsmento; custo em dolar; Stream é mais caro.

Nuvem privada -> On-premise
Nuvem Pública -> Iaas; Paas; Saas...
Nuvem Híbrida -> Privada + Pública

Plataformas: AWS; AZURE; ORACLE; GCP
Solução para latência: Regions & Zones

Benefícios da núvem:
Alta disponibilidade; Escalabilidade; Previsibilidade; Governança; Elasticidade; Confiabilidade; Segurança; Gerenciabilidade.

Tipos de Serviços da Nuvem:
IaaS (Infraestrutura como serviço) Ex: Armazenamento; Redes Virtuais; Máquinas Virtuais...
PaaS (Plataforma como serviço) Ex: Sistemas operacionais; Ferramentas p/ Devs; Análise de negócio, Gerenciamento e Database.
SaaS (Software como serviço) Ex: Apps como, Office 365; Canva; Miro...

Benefícios da Nuvem Azure:
Quando o serviço fica indisponível, não tem o que fazer, a não ser monitorar o retorno do serviço. Este tempo indisponível é descontado no valor cobrado mensalemnte.

Alta disponibilidade
Acordos de nível de serviço / SLA

Escalabilidade:
Capacidade de ajustar recursos EX: Adicionar mais recursos para lidar com a demanda.

Elasticidade:
Posso dimensionar meu ambiente com base em requisições, de forma automatizada de preferência.

Confiabilidade:
Ter um sistema que se recupera de falhas e continua funcionando. Um ambiente confiável.

Previsibilidade:
Confiança, desempenho o custo.

Segurança:
Regras, modelo, segurança de recursos.

Governança:
Auditoria para mitigar e sinalizar coisas que estejam fora de conformidade, definir padrões de gestão.

Gerenciabilidade:
A nuvem facilita a gerenciabilidade escalar automaticamente a implantação de recursos com base na necessidade, pode ser feito por meio de um portal Web.
-Usando uma interface de linha de comando.
-Usando APIs
-Usando PowerShell.

Regiões e Zonas
Região: Ponto geográfico que tem 3 zonas de disponibilidade: Pares de regiões; Regiões soberanas (EUA e China); Zona de disponibilidade.

Grupos de Recursos: assinaturas; Gerenciamento de Recursos(Acessos).

Serviços de Contêineres Azure
Instancias de conteiners; Aplicativos de conteiners; Serviço de Kubernetes(AKS); Azure functions; Serviços de aplicativos; Serviços de rede; DNS -> "lmoura.com"

Azure VM -> Para criar máquinas virtuais.

Armazenamento: Domínio de objeto
Redundância: LRS; ZRS; GRS; GZRS.

Serviços de Armazenamento: Blob; Disco; Fila; Arquivos; Tabelas.

Camadas de acesso de Armazenamento:
Frequente -> Acessado frequentemente
Esporádico -> Acessado nos últimos 30 dias
Frio -> Acessado nos últimos 90 dias
Arquivo Morto -> Acessado nos últimos 180 dias

Azure Data Box:
Uma caixa para transferir grande volume de dados de forma física.

IaaS (Infraestrutura como serviço) 
Infra de TI -> pago somente o que eu usar 
- Mais flexível.
- Você configura e gerencia o Hardware para o seu aplicativo.

PaaS (Plataforma como serviço) 
Banco de dados (Aplicação)
Ferramentas para Devs; Sistema operacional; Gerenciamento de Banco de dados.
- Focado no Desenvolvimento de Aplicativos
- Gerenciamento e plataforma por conta do provedor da nuvem

SaaS (Software como serviço)
Aplicativos
Os usuários se conectam e usam aplicativos com base em nuvem pela internet.
Ex: Office 365; Email e calendários.
- Pagamento conforme o uso
- Usuários pagam pelo software que utilizam em um modelo de assinatura.
