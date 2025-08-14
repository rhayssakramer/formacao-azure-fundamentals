# ⚙️ Monitoramento Inteligente no Azure

Este repositório corresponde ao Desafio #11 da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification) para fornecer instruções sobre o Monitoramento Inteligente no Microsoft Azure.

## 📑 Índice
- [Introdução]()
- [Tecnologias Utilizadas]()
- [Desafio de Projeto]()
- [Objetivos]()
  - [x] [Pré-requisitos]()
  - [x] [Estrutura do Repositório]()
  - [x] [Ferramentas e Tecnologias]()
  - [x] [Passo a Passo]()
- [Azure Monitor]()
- [Service Health do Azure]()
- [Azure Advisor]()
- [Recursos Adicionais]()
- [Créditos]()
- [Autora]()

### ▶️ Introdução  
Neste desafio, você irá explorar o `Monitoramento Inteligente no Azure`, utilizando ferramentas como `Azure Monitor`, `Service Health` e `Azure Advisor`, aplicando boas práticas de monitoramento, análise de desempenho e otimização de recursos.

### 💻 Tecnologias Utilizadas

| Linguagens de Programação | Ferramentas e Tecnologias |
| :-----------------: | :-----------------------: |
| | <img height="40" src="https://skillicons.dev/icons?i=github"> <img height="40" src="https://skillicons.dev/icons?i=git"> <img height="40" src="https://skillicons.dev/icons?i=vscode"> <img height="40" src="https://skillicons.dev/icons?i=azure">

### 🎯 Desafio de Projeto
- Explorar e utilizar Azure Monitor para análise de desempenho e telemetria.
- Configurar alertas e insights em Service Health.
- Analisar recomendações e otimizar recursos com Azure Advisor.

### 🛠️ Objetivos
- Obter visibilidade completa dos recursos e aplicativos.
- Automatizar alertas e notificações para incidentes e manutenção.
- Melhorar a disponibilidade, performance e segurança dos recursos.
- Otimizar custos e eficiência no uso do Azure.

#### 📌 Pré-requisitos
1. Conta ativa no [Azure](https://portal.azure.com/).
2. Navegador atualizado.
3. Conhecimentos básicos em nuvem e monitoramento.
4. Noções de métricas e logs.

#### 📁 Estrutura do Repositório
```
Desafio#11-Monitoramento-Inteligente/
│
├── img/                # Imagens do passo a passo
├── README.md           # Guia completo do desafio
└── documentação/       # Links e PDFs adicionais (opcional)
```

#### ⚙️ Ferramentas e Tecnologias
- Azure Monitor
- Service Health
- Azure Advisor
- Visual Studio Code
- Git
- GitHub

#### 🚀 Passo a Passo
1. Acesse sua Conta no Azure
   - [Portal do Azure](https://portal.azure.com/)
2. Azure Monitor
   - No portal, pesquise por `Monitor` ou selecione no menu lateral.
   - Explore `Logs`, `Insights` e `Alertas` para acompanhar métricas e desempenho.
3. Service Health do Azure
   - Pesquise por `Service Health` no portal.
   - Visualize o estado dos serviços, incidentes e programações de manutenção.
   - Configure alertas para notificações automáticas.
4. Azure Advisor
  - Pesquise por `Advisor` no portal.
  - Revise recomendações personalizadas para `High Availability`, `Security`, `Performance` e `Cost`.
  - Aplique melhorias e siga orientações para otimização.
5. Monitoramento Contínuo e Otimização
   - Acompanhe métricas regularmente.
   - Configure alertas e políticas de segurança.
   - Analise recomendações do Advisor para otimizar recursos e reduzir custos.

### 1. Azure Monitor 💻
O `Azure Monitor` é uma plataforma abrangente de monitoramento que fornece insights completos sobre o desempenho e a integridade dos recursos do Azure. Ele coleta, analisa e atua sobre dados de telemetria de seus aplicativos e recursos para ajudar a manter e melhorar a disponibilidade e o desempenho.

- **Acesse o Portal do Azure:** faça login no [Portal do Azure](https://portal.azure.com/). No menu de navegação à esquerda, selecione `Monitor` ou use a barra de pesquisa para encontrar `Azure Monitor`.  
![Imagem 1](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2311-Monitoramento-Inteligente-no-Azure/img/img1.png)

- **Explore as Ferramentas:** no Azure Monitor, você pode acessar diversas funcionalidades, como `Logs` para consultas detalhadas, `Insights` para métricas e desempenho, e `Alertas` para configurar notificações e ações automatizadas.  
<img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2311-Monitoramento-Inteligente-no-Azure/img/img2.png" alt="Imagem 2" width="350">  

<img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2311-Monitoramento-Inteligente-no-Azure/img/img3.png" alt="Imagem 3" width="550">


### 2. Service Health do Azure 🩺
O `Service Health do Azure` oferece informações sobre o status dos serviços do Azure e possíveis problemas que podem afetar seus recursos. Ele fornece atualizações em tempo real sobre o estado dos serviços e eventos que possam impactar a disponibilidade e a performance dos recursos.

- **Acesse o Portal do Azure:** faça login no [Portal do Azure](https://portal.azure.com/). No menu de navegação à esquerda, selecione `Service Health` ou use a barra de pesquisa para encontrar `Service Health`.  
![Imagem 4](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2311-Monitoramento-Inteligente-no-Azure/img/img4.png)

- **Visualize o Status e Eventos:** aqui você pode visualizar o estado atual dos serviços, histórico de incidentes e programações de manutenção. Configure alertas para ser notificado sobre quaisquer eventos que possam impactar seus recursos.  
<img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2311-Monitoramento-Inteligente-no-Azure/img/img5.png" alt="Imagem 5" width="350">

### 3. Azure Advisor 🔍
O `Azure Advisor` é um serviço de recomendação que fornece conselhos personalizados para ajudar a otimizar o uso de recursos do Azure. Ele analisa suas configurações e práticas recomendadas, fornecendo recomendações para melhorar a segurança, o desempenho e a eficiência de custo.

- **Acesse o Portal do Azure:** faça login no [Portal do Azure](https://portal.azure.com/). No menu de navegação à esquerda, selecione `Advisor` ou use a barra de pesquisa para encontrar `Azure Advisor`.  
![Imagem 6](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2311-Monitoramento-Inteligente-no-Azure/img/img6.png)

- **Revise as Recomendações:** no Azure Advisor, você encontrará recomendações agrupadas em categorias como `High Availability`, `Security`, `Performance` e `Cost`.
Analise as recomendações e siga as orientações para aplicar melhorias.

**Certifique-se de sempre definir regras de segurança e monitoramento apropriadas para proteger seus recursos e otimizar o gerenciamento de custos.**

### 🗒️ Recursos Adicionais
- [Documentação Oficial do Microsoft Azure](https://docs.microsoft.com/azure)
- [Tutoriais de Introdução ao Azure](https://docs.microsoft.com/learn/paths/azure-fundamentals/)

## 🔗 Créditos
Este guia serve como repositório de estudos, desafios e projetos da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification), para avaliar o ensinado no curso de introdução básica para fornecer instruções sobre o Monitoramento Inteligente no Microsoft Azure.

*Nota: Este projeto é apenas para fins educacionais e não possui nenhuma afiliação oficial com a franquia DIO ou suas empresas associadas.*

## 👩🏼‍💻 Autoria:
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