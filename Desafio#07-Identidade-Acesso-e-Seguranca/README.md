# 🛡️ Identidade, Acesso e Segurança

Este repositório corresponde ao Desafio #07 da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification) para fornecer instruções sobre Microsoft Entra ID e Microsoft Defender for Cloud dentro do portal do Microsoft Azure.

## 📑 Índice
- [Introdução]()
- [Tecnologias Utilizadas]()
- [Desafio de Projeto]()
- [Objetivos]()
  - [x] [Pré-requisitos]()
  - [x] [Estrutura do Repositório]()
  - [x] [Ferramentas e Tecnologias]()
  - [x] [O que será feito]()
- [Explore o Microsoft Entra ID]()
- [Acesse o Microsoft Defender for Cloud]()
- [Boas Práticas em Segurança no Azure]()
- [Recursos Adicionais]()
- [Créditos]()
- [Autora]()

### ▶️ Introdução
No Azure, gerenciar identidade, acesso e segurança é essencial para proteger recursos e dados sensíveis. Este guia ensina como utilizar o **Microsoft Entra ID** e o **Microsoft Defender for Cloud** para gerenciamento de usuários, grupos, acessos e monitoramento de segurança.

### 💻 Tecnologias Utilizadas

| Linguagens de Programação | Ferramentas e Tecnologias |
| :-----------------: | :-----------------------: |
| <img height="40" src="https://skillicons.dev/icons?i=py"> | <img height="40" src="https://skillicons.dev/icons?i=github"> <img height="40" src="https://skillicons.dev/icons?i=git"> <img height="40" src="https://skillicons.dev/icons?i=vscode"> <img height="40" src="https://skillicons.dev/icons?i=azure">

### 🎯 Desafio de Projeto
O objetivo deste desafio é praticar a gestão de identidade, controle de acesso e segurança no Azure, incluindo:
- Criação e gerenciamento de usuários e grupos
- Configuração de permissões e políticas de acesso
- Monitoramento de segurança e incidentes usando Microsoft Defender for Cloud

### 🛠️ Objetivos
- Aprender a gerenciar identidades e acessos no Azure
- Configurar políticas de segurança e monitoramento
- Aplicar boas práticas em gerenciamento de usuários e grupos

#### 📌 Pré-requisitos
- Conta ativa no [Azure](https://portal.azure.com/)
- Conhecimentos básicos em nuvem e segurança
- Navegador atualizado

#### 📁 Estrutura do Repositório
```
Desafio#07-Identidade-Acesso-e-Seguranca/
│
├── img/                # Imagens do passo a passo
├── README.md           # Guia completo do desafio
└── documentação/       # Links e PDFs adicionais (opcional)
```

#### ⚙️ Ferramentas e Tecnologias
- Microsoft Azure
- Visual Studio Code
- Git
- GitHub

#### 🧠 O que será feito?
- Gerenciamento de usuários e grupos no Microsoft Entra ID
- Configuração de controles de acesso baseados em funções (RBAC)
- Aplicação de políticas de acesso condicional
- Monitoramento e gerenciamento de incidentes no Microsoft Defender for Cloud
- Configuração de alertas e recomendações de segurança

### 🔍 Explore o Microsoft Entra ID 🔍
O **Microsoft Entra ID** (anteriormente conhecido como Azure Active Directory) é um serviço de identidade e gerenciamento de acesso baseado na nuvem que ajuda a proteger e gerenciar o acesso aos recursos da sua organização.

![Imagem 1](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2307-Identidade-Acesso-e-Seguranca/img/img1.png)
![Imagem 2](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2307-Identidade-Acesso-e-Seguranca/img/img2.png)

><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2307-Identidade-Acesso-e-Seguranca/img/img3.png" alt="Imagem 3" width="250">

![Imagem4](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2307-Identidade-Acesso-e-Seguranca/img/img4.png)
  
**Gerenciamento de Usuários**
- **Adicionar Usuários:** Clique em `Usuários` e depois em `Novo usuário` para adicionar novos usuários ao diretório.  
- **Editar Usuários:** Selecione um usuário para atualizar suas informações ou permissões.
- **Grupos:** Crie e gerencie grupos para facilitar a atribuição de permissões e acesso.

>IMPORTANTE!  
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2307-Identidade-Acesso-e-Seguranca/img/img5.png" alt="Imagem 5" width="550">   

**Gerenciamento de Acessos**
- **Controle de Acesso Baseado em Funções (RBAC):** Atribua papéis e permissões específicas aos usuários e grupos para controlar o acesso aos recursos.
- **Políticas de Acesso Condicional:** Configure políticas para definir condições sob as quais os usuários podem acessar determinados recursos.

><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2307-Identidade-Acesso-e-Seguranca/img/img6.png" alt="Imagem 6" width="550"> 

### 🔐 Acesse o Microsoft Defender for Cloud 🔐
No portal do Azure, procure por `Microsoft Defender for Cloud` e selecione o serviço.

O Microsoft Defender for Cloud é uma solução de monitoramento e segurança que fornece visibilidade e proteção para suas cargas de trabalho na nuvem e em ambientes locais.

![Imagem 7](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2307-Identidade-Acesso-e-Seguranca/img/img7.png)
![Imagem 8](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2307-Identidade-Acesso-e-Seguranca/img/img8.png)

**Principais Funções**
- **Monitoramento de Segurança:** Oferece uma visão unificada da postura de segurança de suas implementações, identificando vulnerabilidades e riscos.
- **Gerenciamento de Incidentes:** Permite o gerenciamento e a resposta a incidentes de segurança com alertas e recomendações práticas.
- **Avaliação de Conformidade:** Avalia a conformidade com políticas e regulamentos de segurança, fornecendo relatórios detalhados.

><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2307-Identidade-Acesso-e-Seguranca/img/img9.png" alt="Imagem 9" width="550">
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2307-Identidade-Acesso-e-Seguranca/img/img10.png" alt="Imagem 10" width="550"> 

**Configuração de Alertas e Recomendações**
- **Alertas:** Configure alertas para notificar sobre atividades suspeitas e vulnerabilidades.
- **Recomendações:** Siga as recomendações fornecidas para melhorar a segurança e conformidade do seu ambiente.

**Cuidados Importantes para Segurança e Monitoramento**
1. Segurança
- **Controle de Acesso:** Certifique-se de que as permissões sejam configuradas corretamente para proteger seus recursos.
- **Monitoramento Regular:** Use o Microsoft Defender for Cloud para monitorar continuamente e ajustar suas configurações de segurança conforme necessário.
2. Gerenciamento de Acesso
- **Políticas de Acesso Condicional:** Configure políticas para gerenciar o acesso de forma granular e com base em condições específicas.
- **Revisão de Acessos:** Realize revisões periódicas das permissões e grupos para garantir que apenas usuários autorizados tenham acesso aos recursos.
3. Monitoramento e Resposta
- **Alertas de Segurança:** Configure alertas no Microsoft Defender for Cloud para detectar e responder rapidamente a possíveis ameaças.
- **Plano de Resposta a Incidentes:** Desenvolva um plano para responder a incidentes de segurança e minimizar os impactos.   

### 💡 Boas Práticas em Segurança no Azure
1. Controle de Acesso: Permissões configuradas corretamente
2. Monitoramento Regular: Ajuste configurações usando Defender for Cloud
3. Políticas de Acesso Condicional: Revise periodicamente
4. Alertas de Segurança: Detecte e responda a ameaças rapidamente

*Certifique-se de sempre definir regras de segurança e monitoramento apropriadas para proteger seus recursos e otimizar o gerenciamento de custos.*

## 🗒️ Recursos Adicionais
- [Documentação Oficial do Microsoft Azure](https://docs.microsoft.com/azure)
- [Tutoriais de Introdução ao Azure](https://docs.microsoft.com/learn/paths/azure-fundamentals/)

## 🔗 Créditos
Este guia serve como repositório de estudos, desafios e projetos da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification), para avaliar o ensinado no curso de introdução básica para fornecer instruções sobre Microsoft Entra ID e Microsoft Defender for Cloud dentro do portal do Microsoft Azure.

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