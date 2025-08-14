## ⚙️ Gerenciando Políticas no Azure
Este repositório corresponde ao Desafio #09 da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification) para fornecer instruções sobre como Gerenciar Políticas no Microsoft Azure.

## 📑 Índice
- [Introdução]()
- [Tecnologias Utilizadas]()
- [Desafio de Projeto]()
- [Objetivos]()
  - [x] [Pré-requisitos]()
  - [x] [Estrutura do Repositório]()
  - [x] [Ferramentas e Tecnologias]()
  - [x] [O que será feito?]()
  - [x] [Passo a Passo]()
- [Portal de Confiança do Azure]()
- [Preview do Azure]()
- [Bloqueio de Recursos]()
- [Gerenciamento de Policies]()
- [Recursos Adicionais]()
- [Créditos]()
- [Autora]()

### ▶️ Introdução
Neste desafio, você aprenderá a utilizar ferramentas essenciais de governança e segurança no Azure, incluindo Portal de Confiança, Recursos em Preview, Bloqueio de Recursos e Gerenciamento de Policies, garantindo maior conformidade e segurança no ambiente de nuvem.

### 💻 Tecnologias Utilizadas

| Linguagens de Programação | Ferramentas e Tecnologias |
| :-----------------: | :-----------------------: |
| | <img height="40" src="https://skillicons.dev/icons?i=github"> <img height="40" src="https://skillicons.dev/icons?i=git"> <img height="40" src="https://skillicons.dev/icons?i=vscode"> <img height="40" src="https://skillicons.dev/icons?i=azure">

### 🎯 Desafio de Projeto
Explorar e aplicar políticas de governança no Azure, com foco em:
- Acesso ao Portal de Confiança
- Uso de funcionalidades em Preview
- Criação de bloqueios para proteção de recursos
- Criação e aplicação de políticas no Azure Policy

### 🛠️ Objetivos
- Garantir a conformidade e segurança de recursos no Azure
- Aprender a criar e gerenciar políticas
- Proteger recursos críticos contra alterações ou exclusões acidentais
- Avaliar recursos e funcionalidades ainda em Preview

#### 📌 Pré-requisitos
- Conta ativa no [Microsoft Azure](https://portal.azure.com/)
- Noções básicas de governança em nuvem
- Conhecimentos introdutórios sobre `Azure Policy`

### 📁 Estrutura do Repositório
```
Desafio#09-Gerenciando-Politicas-no-Azure/
│
├── img/                # Imagens do passo a passo
├── README.md           # Guia completo do desafio
└── documentação/       # Arquivos e links complementares (opcional)
```

#### ⚙️ Ferramentas e Tecnologias
- Microsoft Azure
- Azure Policy
- Portal de Confiança do Azure
- Visual Studio Code
- Git
- GitHub

#### 🧠 O que será feito?
1. Acesso e uso do Portal de Confiança
2. Exploração de recursos em Preview
3. Criação e configuração de bloqueios de recursos
4. Definição e atribuição de políticas no `Azure Policy`

#### 🚀 Passo a Passo
1. Acesse sua Conta no Azure
   - Entre no [Portal do Azure](https://portal.azure.com/).
2. Abra o Portal de Confiança do Azure
   - Acesse o [Service Trust Portal](https://servicetrust.microsoft.com/) para verificar conformidade, certificações e relatórios.
3. Explore Recursos em Preview (opcional)
   - No Portal do Azure, vá em **Todos os serviços** e filtre por Preview para avaliar funcionalidades em fase prévia.
4. Selecione o Recurso a Proteger
   - Abra o **Grupo de Recursos** ou **Assinatura**, escolha o recurso alvo e vá em Configurações > Bloqueios.
5. Crie um Bloqueio de Recurso
   - Clique em Adicionar e escolha **ReadOnly** (somente leitura) ou **CanNotDelete** (impedir exclusão). Defina nome e descrição e **Salve**
6. Abra o `Azure Policy`
   - No Portal, pesquise **Policy**. Revise o painel **Compliance** para ver o estado atual dos recursos.
7. Escolha uma Definição (Built-in) ou Crie a Sua
   - Em **Definitions**, use uma política pronta ou clique em + **Policy definition** para criar: nome, descrição, categoria e **Policy Rule (JSON)**.
8. Configure Parâmetros e Efeito da Política
   - Defina **parameters** (ex.: regiões permitidas) e o **effect** adequado: **Deny**, **Audit**, **Append**, **Modify** ou **DeployIfNotExists**.
9. (Opcional) Agrupe em uma Iniciativa
   - Em **Initiatives (Policy Set Definitions)**, crie um conjunto que reúna várias políticas com um objetivo comum (ex.: baseline de segurança).
10. Faça a Atribuição (Assign Policy/Initiative)
    - Em **Assignments > Assign**, defina **Scope** (Management Group/Assinatura/Resource Group), **Exclusions**, **Parameters** e **Identidade Gerenciada** (se necessário).
11. Habilite Remediation (Correção Automática)
- Marque **Create a remediation task** quando o efeito suportar correção **(DeployIfNotExists/Modify)** para ajustar recursos não conformes.
12. Revise, Crie e Monitore
    - Clique em **Review** + **Create**. Depois acompanhe **Compliance**, execute **Remediate** quando houver itens não conformes e exporte relatórios conforme necessário.

### 🔐 Portal de Confiança do Azure
O `Portal de Confiança do Azure` é uma plataforma que oferece visibilidade e controle sobre a conformidade e a segurança dos seus recursos no Azure.  Ele fornece informações sobre práticas recomendadas, conformidade com normas e a segurança dos dados. Acesse o [Portal de Confiança](https://servicetrust.microsoft.com/) e explore relatórios, práticas recomendadas e requisitos regulatórios.

Para acessar e utilizar o Portal de Confiança, siga estes passos:
- **Acesse o Portal de Confiança:** acesse o link do [Portal de Confiança](https://servicetrust.microsoft.com/). Este portal facilita a gestão de políticas de conformidade e ajuda a garantir que seus recursos estejam alinhados com as melhores práticas de segurança e as exigências regulatórias. O Portal de Confiança inclui uma visão geral das certificações e do cumprimento de normas do Azure, permitindo que você avalie rapidamente o estado de conformidade e identifique áreas que necessitam de atenção.  

![Imagem 1](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2309-Gerenciando-Politicas-no-Azure/img/img1.png)

## 🔮 Preview do Azure
O Preview do Azure permite que você experimente novos serviços e funcionalidades antes de serem lançados oficialmente.   

Para começar a usar um recurso em Preview, siga estes passos:
- **Acesse o Portal do Azure:** faça login no [Portal do Azure](https://portal.azure.com/). E navegue para `Microsoft Purview`.
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2309-Gerenciando-Politicas-no-Azure/img/img2.png" alt="Imagem 2" width="550">  

- **Navegue para `Todas as funções`:** no menu de navegação à esquerda, selecione `Todos os serviços` e procure por recursos em Preview.
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2309-Gerenciando-Politicas-no-Azure/img/img3.png" alt="Imagem 3" width="550">  

- **Selecione e Ative o Preview:** escolha o recurso que você deseja experimentar e siga as instruções para ativar o Preview. Esteja ciente de que recursos em Preview podem não ser totalmente estáveis e podem ter funcionalidades limitadas.
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2309-Gerenciando-Politicas-no-Azure/img/img4.png" alt="Imagem 4" width="550">  
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2309-Gerenciando-Politicas-no-Azure/img/img5.png" alt="Imagem 5" width="550"> 

### 🔒 Bloqueio de Recursos
O `Bloqueio de Recursos no Azure` permite que você impeça a exclusão ou modificação acidental de recursos críticos. Para criar um bloqueio de recurso, siga estes passos:

- **Acesse o Portal do Azure:** faça login no [Portal do Azure](https://portal.azure.com/). No menu de navegação à esquerda, selecione `Recursos` e escolha o recurso que você deseja proteger.
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2309-Gerenciando-Politicas-no-Azure/img/img6.png" alt="Imagem 6" width="450">  

- **Configure o Bloqueio:** no painel do recurso, selecione `Bloqueios`.
Clique em `Adicionar bloqueio` e escolha um tipo de bloqueio:
    - **ReadOnly:** impede alterações, mas permite leitura.
    - **CanNotDelete:** impede exclusão do recurso.
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2309-Gerenciando-Politicas-no-Azure/img/img7.png" alt="Imagem 7" width="450"> 

- **Defina o Nome e Descrição:** insira um nome e uma descrição para o bloqueio. Clique em `Salvar` para aplicar o bloqueio ao recurso.
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2309-Gerenciando-Politicas-no-Azure/img/img8.png" alt="Imagem 8" width="450">  

><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2309-Gerenciando-Politicas-no-Azure/img/img9.png" alt="Imagem 9" width="450"> 

### 🚨 Gerenciamento de Policies
O `Gerenciamento de Políticas no Azure` ajuda a garantir que os recursos estejam em conformidade com as normas e regulamentos da sua organização. Para criar uma política, siga estes passos:

- **Acesse o Portal do Azure:** faça login no [Portal do Azure](https://portal.azure.com/). E navegue para `Azure Policy`. No menu de navegação à esquerda, selecione `Azure Policy`.
![Imagem 10](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2309-Gerenciando-Politicas-no-Azure/img/img10.png)

- **Crie uma Nova Política:** selecione `Definitions` e clique em `New Policy Definition`. Defina os critérios e a política que você deseja aplicar.
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2309-Gerenciando-Politicas-no-Azure/img/img11.png" alt="Imagem 11" width="250">  
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2309-Gerenciando-Politicas-no-Azure/img/img12.png" alt="Imagem 12" width="450"> 

- **Aplique a Política:** após definir a política, selecione `Assignments` e clique em `Assign Policy`. Escolha a política criada e defina o escopo de aplicação (como um grupo de recursos ou uma assinatura).
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2309-Gerenciando-Politicas-no-Azure/img/img13.png" alt="Imagem 13" width="450">  

>**Importante: Selecione se quer deixar ativado a policy ou não.**
>
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2309-Gerenciando-Politicas-no-Azure/img/img14.png" alt="Imagem 14" width="450">  

><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2309-Gerenciando-Politicas-no-Azure/img/img15.png" alt="Imagem 15" width="450">   

><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2309-Gerenciando-Politicas-no-Azure/img/img16.png" alt="Imagem 16" width="450"> 

- **Revise e Salve:** revise os detalhes e clique em `Create` para aplicar a política.

### 🗒️ Recursos Adicionais
- [Documentação Oficial do Microsoft Azure](https://docs.microsoft.com/azure)
- [Tutoriais de Introdução ao Azure](https://docs.microsoft.com/learn/paths/azure-fundamentals/)

## 🔗 Créditos
Este guia serve como repositório de estudos, desafios e projetos da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification), para avaliar o ensinado no curso de introdução básica para fornecer instruções sobre como Gerenciar Políticas no Microsoft Azure.

*Nota: Este projeto é apenas para fins educacionais e não possui nenhuma afiliação oficial com a franquia DIO ou suas empresas associadas.*

## 👩🏼‍💻 Autora:
<table style="border=0">
  <tr>
    <td align="left">
      <a href="https://github.com/rhayssakramer">
        <span><b>Rhayssa Kramer</b></span>
      </a>
      <br>
      <span>Assoc, Full-Stack Development</span>
    </td>
  </tr>
</table>

<div align="center"><a href="https://github.com/rhayssakramer"><img src="https://github.com/rhayssakramer/rhayssakramer/blob/main/img/rodape.png"></a></div>