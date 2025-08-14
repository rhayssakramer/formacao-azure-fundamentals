# 📊 Otimizando Custos no Azure

Este repositório corresponde ao Desafio #08 da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification) para fornecer instruções sobre utilizar a Calculadora de TCO do Microsoft Azure.

## 📑 Índice
- [Introdução]()
- [Tecnologias Utilizadas]()
- [Desafio de Projeto]()
- [Objetivos]()
  - [x] [Pré-requisitos]()
  - [x] [Estrutura do Repositório]()
  - [x] [Ferramentas e Tecnologias]()
  - [x] [O que será feito?]()
- [Usando a Calculadora de TCO]()
- [Monitoramento de Custos no Azure]()
- [Adicionando TAGs a Resource Groups]()
- [Recursos Adicionais]()
- [Créditos]
- [Autora]()

### ▶️ Introdução
Otimizar custos no Azure significa planejar, estimar e controlar gastos desde a migração até a operação diária. Neste guia, você usará a `Calculadora de TCO` para comparar custos on-premises x nuvem, aprenderá a monitorar despesas com `Cost Management + Billing` e organizará recursos com Tags e alertas de orçamento para manter seu ambiente sob controle financeiro.

### 💻 Tecnologias Utilizadas

| Linguagens de Programação | Ferramentas e Tecnologias |
| :-----------------: | :-----------------------: |
| | <img height="40" src="https://skillicons.dev/icons?i=azure"> |

### 🎯 Desafio de Projeto

O objetivo é praticar planejamento e controle de custos no Azure, passando da estimativa (TCO) ao acompanhamento operacional (Cost Management).

### 🛠️ Objetivos
- Aprender a estimar o custo total de propriedade (TCO) ao migrar workloads para a nuvem.
- Configurar e interpretar relatórios de Cost Management no Azure.
- Criar e gerenciar tags para organizar e otimizar custos de recursos.

#### 📌 Pré-requisitos
- Conta no [Microsoft Azure](https://portal.azure.com/).
- Conhecimentos básicos sobre serviços de nuvem.
- Noções iniciais de redes, armazenamento e máquinas virtuais no Azure.

#### 📁 Estrutura do Repositório
```
📁 Otimizando-Custos-no-Azure/
│── img/                # Imagens utilizadas no guia
│── README.md           # Documentação principal
```

#### ⚙️ Ferramentas e Tecnologias
- Microsoft Azure Portal
- Calculadora de TCO (Total Cost of Ownership)
- Azure Cost Management + Billing
- Azure Resource Groups e Tags
- Navegador Web

#### 🧠 O que será feito?
1. Utilização da **Calculadora de TCO** para comparar custos on-premises e na nuvem.
2. Monitoramento de custos no **Cost Management** do Azure.
3. Configuração de alertas de custo.
4. Criação e gerenciamento de **tags** em Resource Groups.

### 🧮 Usando a Calculadora de TCO 🧮
A [Calculadora de TCO](https://azure.microsoft.com/pt-br/pricing/tco/calculator/) (Total Cost of Ownership) do Azure é uma ferramenta útil para estimar o custo total de propriedade ao migrar para a nuvem. Para utilizar a **Calculadora de TCO**, siga estes passos:

- **Acesse a Calculadora de TCO:** visite o site oficial da [Calculadora de TCO](https://azure.microsoft.com/pt-br/pricing/tco/calculator/).

![Imagem 1](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2308-Otimizando-Custos-no-Azure/img/img1.png)

- **Configure o Cenário Atual:** insira informações sobre seu ambiente atual, como servidores, armazenamento e redes. O objetivo é fornecer uma visão geral dos custos atuais para comparar com os custos na nuvem.

![Imagem 2](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2308-Otimizando-Custos-no-Azure/img/img2.png)
![Imagem 3](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2308-Otimizando-Custos-no-Azure/img/img3.png)
![Imagem 4](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2308-Otimizando-Custos-no-Azure/img/img4.png)
![Imagem 5](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2308-Otimizando-Custos-no-Azure/img/img5.png)

- **Configure o Cenário no Azure:** adicione as mesmas capacidades no Azure para estimar o custo equivalente. Escolha os serviços e recursos que correspondem aos seus requisitos atuais.

- **Compare os Custos:** a ferramenta fornecerá uma comparação entre o custo atual e o custo estimado na nuvem. Analise os resultados para tomar decisões informadas sobre a migração para o Azure.
 
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2308-Otimizando-Custos-no-Azure/img/img6.png" alt="Imagem 6" width="350">  
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2308-Otimizando-Custos-no-Azure/img/img7.png" alt="Imagem 7" width="650">  
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2308-Otimizando-Custos-no-Azure/img/img8.png" alt="Imagem 8" width="350">

### 🔍 Monitoramento de Custos no Azure
O Azure oferece várias ferramentas para monitorar e gerenciar seus custos. Aqui está um guia básico para monitorar seus gastos:

- **Acesse o Portal do Azure:** faça login no [Portal do Azure](https://portal.azure.com/). Navegue para `Cost Management + Billing`. No menu de navegação à esquerda, selecione `Cost Management + Billing`.

><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2308-Otimizando-Custos-no-Azure/img/img9.png" alt="Imagem 9" width="250">

 - **Visualize os Custos:** em `Cost Management`, você pode ver um resumo dos seus custos e despesas. Utilize o `Cost Analysis` para explorar detalhes mais profundos sobre como os recursos estão gerando custos.

- **Configure Alertas de Custo:** configure alertas para notificar quando seus gastos atingirem certos limites. Em `Alerts`, você pode definir regras e limites para ser informado proativamente.
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2308-Otimizando-Custos-no-Azure/img/img10.png" alt="Imagem 10" width="350">

### 🏷️ Adicionando uma TAG a um Resource Group
Tags são uma maneira eficaz de organizar e gerenciar recursos no Azure. Siga estes passos para adicionar uma tag a um Resource Group:

- **Acesse o Portal do Azure:** faça login no [Portal do Azure](https://portal.azure.com/). No menu de navegação à esquerda, selecione `Resource groups`. Escolha o Resource Group ao qual você deseja adicionar uma tag.

- **Edite as Tags:** no menu do Resource Group, selecione `Tags`. Clique em `Adicionar tag`.

><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2308-Otimizando-Custos-no-Azure/img/img11.png" alt="Imagem 11" width="350">

- **Insira a Tag:** adicione um par de chave e valor para a tag.  
**Exemplo: Chave = Environment, Valor = Production.**
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2308-Otimizando-Custos-no-Azure/img/img12.png" alt="Imagem 12" width="350">

- **Salvar Alterações:** clique em `Salvar` para aplicar as tags ao Resource Group.  

**Com essas tags, você pode organizar e gerenciar seus recursos de maneira mais eficiente, além de facilitar a criação de relatórios e a gestão de custos.**  

**Certifique-se de sempre definir regras de segurança e monitoramento apropriadas para proteger seus recursos e otimizar o gerenciamento de custos.** 

## 🗒️ Recursos Adicionais
- [Documentação Oficial do Microsoft Azure](https://docs.microsoft.com/azure)
- [Tutoriais de Introdução ao Azure](https://docs.microsoft.com/learn/paths/azure-fundamentals/)

## 🔗 Créditos
Este guia serve como repositório de estudos, desafios e projetos da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification), para avaliar o ensinado no curso de introdução básica para utilizar a Calculadora de TCO do Microsoft Azure.

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