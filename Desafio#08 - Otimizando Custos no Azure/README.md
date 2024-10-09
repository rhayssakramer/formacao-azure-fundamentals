## ⚙️ Otimizando Custos no Azure
Este repositório corresponde ao Desafio #08 da Bootcamp Microsoft Azure Essentials para fornecer instruções sobre utilizar a Calculadora de TCO do Microsoft Azure.

### 1. Usando a Calculadora de TCO 🧮
A [Calculadora de TCO](https://azure.microsoft.com/pt-br/pricing/tco/calculator/) (Total Cost of Ownership) do Azure é uma ferramenta útil para estimar o custo total de propriedade ao migrar para a nuvem. Para utilizar a Calculadora de TCO, siga estes passos:

- **Acesse a Calculadora de TCO:** visite o site oficial da [Calculadora de TCO](https://azure.microsoft.com/pt-br/pricing/tco/calculator/).

![Imagem 1](https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2308%20-%20Otimizando%20Custos%20no%20Azure/img/img1.png)

- **Configure o Cenário Atual:** insira informações sobre seu ambiente atual, como servidores, armazenamento e redes. O objetivo é fornecer uma visão geral dos custos atuais para comparar com os custos na nuvem.

![Imagem 2](https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2308%20-%20Otimizando%20Custos%20no%20Azure/img/img2.png)
![Imagem 3](https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2308%20-%20Otimizando%20Custos%20no%20Azure/img/img3.png)
![Imagem 4](https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2308%20-%20Otimizando%20Custos%20no%20Azure/img/img4.png)
![Imagem 5](https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2308%20-%20Otimizando%20Custos%20no%20Azure/img/img5.png)

- **Configure o Cenário no Azure:** adicione as mesmas capacidades no Azure para estimar o custo equivalente. Escolha os serviços e recursos que correspondem aos seus requisitos atuais.

- **Compare os Custos:** a ferramenta fornecerá uma comparação entre o custo atual e o custo estimado na nuvem. Analise os resultados para tomar decisões informadas sobre a migração para o Azure.
- 
><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2308%20-%20Otimizando%20Custos%20no%20Azure/img/img6.png" alt="Imagem 6" width="350">  
><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2308%20-%20Otimizando%20Custos%20no%20Azure/img/img7.png" alt="Imagem 7" width="650">  
><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2308%20-%20Otimizando%20Custos%20no%20Azure/img/img8.png" alt="Imagem 8" width="350">

### 2. Monitoramento de Custos no Azure 🔍
O Azure oferece várias ferramentas para monitorar e gerenciar seus custos. Aqui está um guia básico para monitorar seus gastos:

- **Acesse o Portal do Azure:** Faça login no [Portal do Azure](https://portal.azure.com/). Navegue para `Cost Management + Billing`. No menu de navegação à esquerda, selecione `Cost Management + Billing`.

><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2308%20-%20Otimizando%20Custos%20no%20Azure/img/img9.png" alt="Imagem 9" width="250">

 - **Visualize os Custos:** em `Cost Management`, você pode ver um resumo dos seus custos e despesas. Utilize o `Cost Analysis` para explorar detalhes mais profundos sobre como os recursos estão gerando custos.

- **Configure Alertas de Custo:** configure alertas para notificar quando seus gastos atingirem certos limites. Em `Alerts`, você pode definir regras e limites para ser informado proativamente.
><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2308%20-%20Otimizando%20Custos%20no%20Azure/img/img10.png" alt="Imagem 10" width="350">

### 3. Adicionando uma TAG a um Resource Group 🏷️
Tags são uma maneira eficaz de organizar e gerenciar recursos no Azure. Siga estes passos para adicionar uma tag a um Resource Group:

- **Acesse o Portal do Azure:** Faça login no [Portal do Azure](https://portal.azure.com/). No menu de navegação à esquerda, selecione `Resource groups`. Escolha o Resource Group ao qual você deseja adicionar uma tag.

- **Edite as Tags:** no menu do Resource Group, selecione `Tags`. Clique em `Adicionar tag`.

><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2308%20-%20Otimizando%20Custos%20no%20Azure/img/img11.png" alt="Imagem 11" width="350">

- **Insira a Tag:** adicione um par de chave e valor para a tag.  
**Exemplo: Chave = Environment, Valor = Production.**
><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2308%20-%20Otimizando%20Custos%20no%20Azure/img/img12.png" alt="Imagem 12" width="350">

- **Salvar Alterações:** clique em `Salvar` para aplicar as tags ao Resource Group.  

**Com essas tags, você pode organizar e gerenciar seus recursos de maneira mais eficiente, além de facilitar a criação de relatórios e a gestão de custos.**  

**Certifique-se de sempre definir regras de segurança e monitoramento apropriadas para proteger seus recursos e otimizar o gerenciamento de custos.** 

### ▶️ Conclusão
Este guia serve como uma introdução básica para utilizar a Calculadora de TCO do Microsoft Azure. Explore outros recursos conforme necessário para atender às suas necessidades de nuvem.

### 🗒️ Recursos Adicionais
- [Documentação Oficial do Microsoft Azure](https://docs.microsoft.com/azure)
- [Tutoriais de Introdução ao Azure](https://docs.microsoft.com/learn/paths/azure-fundamentals/)

## 🔗 Créditos
Este projeto foi desenvolvido como parte de Desafio de Projeto da [Bootcamp Microsoft Azure Essentials da DIO](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9), para avaliar o ensinado no curso de Conceito Iniciais de Cloud com Azure.

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

### <div align="center">Feito por <a href="https://github.com/rhayssakramer">@devrhakramer</a></div>
