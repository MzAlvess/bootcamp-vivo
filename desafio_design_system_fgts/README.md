# Caso de uso: Design System antecipação FGTS

Desenvolva um System Design, para um projeto que aplicativo mobile onde o parceiro está desenvolvendo uma solução para Antecipação do FGTS para seus clientes.  

## Premissas

Para desenvolver o Design System deste projeto, deve seguir as seguintes premissas:

#### 1. Autenticação do Usuário com as APIs do Parceiro:
- A solução deve fornecer autenticação com todas as APIs do parceiro que estão hospedadas no ambiente em nuvem.
- Isso pode ser alcançado implementando mecanismos de autenticação como OAuth 2.0 ou OpenID Connect.
- Deve considerar o uso de bibliotecas e pacotes de autenticação fornecidos pela plataforma em nuvem, como as bibliotecas de autenticação do Google Cloud.
- Deve explorar a possibilidade de usar URLs assinadas para acesso limitado no tempo a recursos específicos, como o Armazenamento em Nuvem, se aplicável.

#### 2. Armazenamento de Dados:
- A solução deve ter a capacidade de armazenar os documentos recebidos dos endpoints.
- Isso pode ser realizado aproveitando os serviços de armazenamento em nuvem, como o Google Cloud Storage ou o AWS S3.
- Deve ser considerado os aspectos de segurança do armazenamento de documentos sensíveis e garantir que os controles de acesso apropriados sejam implementados.
- Deve ser salvo todas as informações do usuário na base de dados.

#### 3. Pipeline de CI/CD para Ambientes de Desenvolvimento, Homologação e Produção:
- A solução deve ter um pipeline de CI/CD para automatizar o processo de implantação em diferentes ambientes.
- Deve ser considerado o uso de ferramentas de CI/CD como GitLab CI/CD ou Jenkins para orquestrar o pipeline.
- O pipeline deve incluir etapas para construção, teste e implantação do código do aplicativo.
- Deve ser considerado a incorporação de práticas de segurança no pipeline de CI/CD, como análise de composição de origem para identificar vulnerabilidades em módulos ou bibliotecas de terceiros.

#### 4. Ambiente Seguro de CI/CD:
- O candidato deve garantir que o ambiente de CI/CD seja isolado e protegido contra acessos não autorizados.
- O sistema de CI/CD deve ser implantado em redes internas e protegidas e não exposto a partes externas.
- É recomendado a configuração de VPNs ou outras tecnologias de controle de acesso à rede para restringir o acesso apenas a operadores autenticados.
- Deve ser considerado a implementação de melhores práticas para proteger o pipeline de CI/CD, como o manejo de credenciais comprometidas e a configuração de autenticação de dois fatores.


### Exemplo:

![MicrosoftTeams-image (11)](https://github.com/MzAlvess/bootcamp-vivo/assets/131389847/05b59b8d-3554-476b-ac5d-47546a4a738a)
