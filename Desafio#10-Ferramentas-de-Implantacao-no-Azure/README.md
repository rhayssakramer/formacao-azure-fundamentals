## ⚙️ Ferramentas de Implantação no Azure
Este repositório corresponde ao Desafio #10 da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification) para fornecer instruções sobre as Ferramentas de Implantação no Microsoft Azure.

### 1. Acessando o Shell no Azure 🗃️
O `Azure Cloud Shell` é uma ferramenta baseada em navegador que oferece um ambiente de linha de comando para gerenciar seus recursos no Azure. Você pode usar o `Cloud Shell` diretamente no Portal do Azure, sem precisar instalar ferramentas localmente.

- **Acesse o Portal do Azure:** faça login no [Portal do Azure](https://portal.azure.com/). Inicie o Cloud Shell. Clique no ícone de `Cloud Shell` no canto superior direito do portal, que se parece com um terminal.

<img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2310-Ferramentas-de-Implantacao-no-Azure/img/img1.png" alt="Imagem 1" width="250">  

<img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2310-Ferramentas-de-Implantacao-no-Azure/img/img4.png" alt="Imagem 4" width="550">


- **Escolha o Tipo de Shell:** o Cloud Shell oferece suporte para Bash e PowerShell. Selecione o ambiente que melhor se adapta às suas necessidades.

<img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2310-Ferramentas-de-Implantacao-no-Azure/img/img3.png" alt="Imagem 3" width="250">

- **Use o Shell:** após iniciar o Shell, você pode executar comandos diretamente no navegador para gerenciar seus recursos Azure.

<img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2310-Ferramentas-de-Implantacao-no-Azure/img/img2.png" alt="Imagem 2" width="250">

### 2. Área de Automação no Azure 🖥
A `Área de Automação no Azure` é um conjunto de ferramentas e serviços que permite automatizar tarefas e processos de gerenciamento de recursos. Isso inclui:

- **Azure Automation:** Um serviço que oferece automação de tarefas recorrentes, gerenciamento de atualizações e configuração de ambientes.

- **Runbooks:** Scripts que automatizam tarefas administrativas, como o gerenciamento de atualizações e a automação de processos.

- **Azure Logic Apps:** Uma ferramenta para criar fluxos de trabalho automáticos entre aplicativos e serviços para integrar e automatizar processos de negócios.

<img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2310-Ferramentas-de-Implantacao-no-Azure/img/img5.png" alt="Imagem 5" width="250">  

<img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2310-Ferramentas-de-Implantacao-no-Azure/img/img6.png" alt="Imagem 6" width="550">  

<img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2310-Ferramentas-de-Implantacao-no-Azure/img/img7.png" alt="Imagem 7" width="550">  

<img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2310-Ferramentas-de-Implantacao-no-Azure/img/img8.png" alt="Imagem 8" width="550">  


Essas ferramentas ajudam a melhorar a eficiência e a consistência na administração de ambientes Azure, permitindo a criação de soluções personalizadas para suas necessidades.

### 3. Azure Bicep ⌨️
O `Azure Bicep` é uma linguagem de infraestrutura como código (IaC) que simplifica a criação e o gerenciamento de recursos Azure. É uma alternativa ao Azure Resource Manager (ARM) templates, oferecendo uma sintaxe mais simples e legível.

<img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2310-Ferramentas-de-Implantacao-no-Azure/img/img9.png" alt="Imagem 9" width="550">  

<img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2310-Ferramentas-de-Implantacao-no-Azure/img/img10.png" alt="Imagem 10" width="550">  

**Características do Azure Bicep**

- **Sintaxe Simples:** Reduz a complexidade dos templates ARM com uma sintaxe mais amigável.
- **Integração com o Azure:** Funciona diretamente com o Azure Resource Manager para provisionar e gerenciar recursos.
- **Modularidade:** Permite a criação de módulos reutilizáveis para simplificar a definição de recursos.

Para começar com Azure Bicep, você pode escrever arquivos .bicep e implantá-los usando o Azure CLI ou o Azure PowerShell.

```bicep
resource storageAccount 'Microsoft.Storage/storageAccounts@2021-04-01' = {
  name: 'mystorageaccount'
  location: resourceGroup().location
  sku: {
    name: 'Standard_LRS'
  }
  kind: 'StorageV2'
  properties: {}
}
```

### 4. Azure Arc
O `Azure Arc` é uma solução que estende os serviços do Azure para ambientes locais e outras nuvens, permitindo que você gerencie recursos híbridos e multi-nuvem como se estivessem no Azure.

<img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2310-Ferramentas-de-Implantacao-no-Azure/img/img11.png" alt="Imagem 11" width="650">  

**Principais Recursos do Azure Arc**
- **Gerenciamento Centralizado:** Oferece uma visão unificada para gerenciar recursos em ambientes locais, em outras nuvens e no Azure.
- **Aplicações e Kubernetes:** Permite a implantação e a gestão de aplicativos em Kubernetes, seja no Azure ou fora dele.
- **Políticas e Segurança:** Aplica políticas e controles de segurança consistentes em todos os seus recursos, independentemente de onde eles estejam.

O Azure Arc proporciona flexibilidade e controle adicional, ajudando a criar uma experiência híbrida e multi-nuvem coesa. Com essas ferramentas e serviços, você pode automatizar processos, gerenciar recursos de forma eficiente e integrar ambientes diversos, otimizando sua administração no Azure e além.

<img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2310-Ferramentas-de-Implantacao-no-Azure/img/img12.png" alt="Imagem 12" width="650">  

<img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2310-Ferramentas-de-Implantacao-no-Azure/img/img13.png" alt="Imagem 13" width="650">  

**Com essas ferramentas e serviços, você pode automatizar processos, gerenciar recursos de forma eficiente e integrar ambientes diversos, otimizando sua administração no Azure e além.**

**Certifique-se de sempre definir regras de segurança e monitoramento apropriadas para proteger seus recursos e otimizar o gerenciamento de custos.**

### ▶️ Conclusão
Este guia serve como uma introdução básica para fornecer instruções sobre as Ferramentas de Implantação no Microsoft Azure. Explore outros recursos conforme necessário para atender às suas necessidades de nuvem.

### 🗒️ Recursos Adicionais
- [Documentação Oficial do Microsoft Azure](https://docs.microsoft.com/azure)
- [Tutoriais de Introdução ao Azure](https://docs.microsoft.com/learn/paths/azure-fundamentals/)

## 🔗 Créditos
Este projeto foi desenvolvido como parte de Desafio de Projeto da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification), para avaliar o ensinado no curso de Conceito Iniciais de Cloud com Azure.

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