# resumo_lab_7
Resumo do aprendizado Identidade, Acesso e Segurança (mod.2)
## Bootcamp Microsoft Azure Essentials - Arquitetura e Serviços do Azure
Identidade Acesso e Segurança
- Serviços de Diretório: Microsoft Entra ID e Entra Microsoft Domain Service
- Métodos de Autenticação: Logon único (SSO) e Autenticação Multifator (MFA)
- Modelos de Segurança
ID do Microsoft Entra - Log in: serviço de gerenciamento de identidade e acesso baseado em nuvem do Azure.
  - Autenticação: Logon único (SSO), gerenciamento de aplicativos, Negócio para Negócios (B2B), Gerenciamento de dispositivos. Garantir a autenticação e sincronizar identidades.
Microsoft Entra Domain Service: domínio gerenciado para fazer uma transação de migração on-premisses para nuvem, com autenticação para replicação (unidirecional). Inf. sincronizadas automaticamente.
- Comparar Autenticação e Autorização -diferença
  - Autenticação: identifica a pessoa ou serviço buscando acesso a um recurso, solicita credenciais de acesso legítimo, base para criar princípios de identidade e controle de acesso seguro
  - Autorização: após autenticado, verificar o nível de acesso à que recurso. Definir quais dados acessar e para fazer o que.
  - Autenticação Multifatorial (MFA): segurança adicional para identidades, exige 2 ou mais elementos autenticação completa, por celular, token ou cartão. (Windows hello)
  - B2B do Microsoft entra External ID: Colaboração BusinesstoBusiness para identidade externa (convite ou inscrição para autoatendimento) autenticação em diretório separado para validação
  - B2C Identidades Externas do Azure AD B2C: BusinesstoCostumers: Consumidores do seu app publicado - fluxo dos usuários de inscrição e entradas, políticas personalizadas. Evita criar uma nova autenticação do usuário e o provedor vai validar e confirmar a autenticação (identidade externa = consumidores).
  - Acesso Condicional: ferramenta do Microsoft Entra ID usa tanto para permitir, quanto para negar (IF=condicional) o acesso à recursos baseado em sinais de identidade, como:
  -   Associação de usuário ou grupo
  -   Local do IP
  -   Dispositivo
  -   Aplicativo
  -   Detecção de risco
- Controle de acesso baseado em função (RBAC): Gerencia o permissionamento de acesso, de granulidade fina, com divisão das tarefas da equipe, confiança zero, permitir apenas no necessário.
- Segurança - modelo Proteção completa em todas as camadas: Segurança física (datacenters), Identidade e acesso, Perímetro, Rede, Computação, Aplicativo, dados.
- Microsoft Defender for Could: é um serviço de controle e monitoramento que oferece proteção contra ameaças nos datacenters do azure e locais.Aponta problemas, estratégias de remediação e correção. Pode-se ativar e definir a profundidade de proteção por camadas (storage, BD, servidor). Melhor desempenho, recomendações de segurança e análise. Ajuda a detectar e bloquear malware. Analisar e identificar ataques potenciais. Controle de acesso just-in-time para portas (filtros). 
