Saas = Software as a Service

# Single Tenant vs Multi Tenant

## Single
- Um software que é utilizado por UMA empresa
- (delphi/java) PDV - Cópias ZIP - TeamViewer - Instalação manual
- Infraestrutura única p/cliente

## Multi
- Um software que é usado por mais uma empresa com a mesma infraestrutura
- NÃO QUER DIZER multi subdomínios
empresa1app.com
empresa2app.com
- NÃO QUER DIZER um banco por empresa
- A GRANDE MAIORIA dos Saas que são Multi Tenant não usam UM BANCO POR EMPRESA. Só usaremos um banco por empresa caso:
  1. Público (governo)
  2. LGPD / Contrato Individual (Itaú)
- Estratégia de subdomínios: Páginas públicas

# Autorização

## RBAC
- Role Based Authorization Control
- Role: Admin, Billing, Developer, Member

## ABAC
- Attribute Based Authorization Control
- Admin pode editar um projeto
- membro pode editar o título de um projeto