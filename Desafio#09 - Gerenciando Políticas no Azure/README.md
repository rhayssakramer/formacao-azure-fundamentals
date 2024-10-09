## ⚙️ Gerenciando Políticas no Azure
Este repositório corresponde ao Desafio #09 da Bootcamp Microsoft Azure Essentials para fornecer instruções sobre como Gerenciar Políticas no Microsoft Azure.

### 1. Portal de Confiança do Azure 🔐
O `Portal de Confiança do Azure` é uma plataforma que oferece visibilidade e controle sobre a conformidade e a segurança dos seus recursos no Azure.  Ele fornece informações sobre práticas recomendadas, conformidade com normas e a segurança dos dados.   

Para acessar e utilizar o Portal de Confiança, siga estes passos:

- **Acesse o Portal de Confiança:** acesse o link do [Portal de Confiança](https://servicetrust.microsoft.com/). Este portal facilita a gestão de políticas de conformidade e ajuda a garantir que seus recursos estejam alinhados com as melhores práticas de segurança e as exigências regulatórias. O Portal de Confiança inclui uma visão geral das certificações e do cumprimento de normas do Azure, permitindo que você avalie rapidamente o estado de conformidade e identifique áreas que necessitam de atenção.  

![Imagem 1](https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2309%20-%20Gerenciando%20Pol%C3%ADticas%20no%20Azure/img/img1.png)

## 2. Preview do Azure 🔮
O Preview do Azure permite que você experimente novos serviços e funcionalidades antes de serem lançados oficialmente.   

Para começar a usar um recurso em Preview, siga estes passos:

- **Acesse o Portal do Azure:** faça login no [Portal do Azure](https://portal.azure.com/). E navegue para `Microsoft Purview`.

><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2309%20-%20Gerenciando%20Pol%C3%ADticas%20no%20Azure/img/img2.png" alt="Imagem 2" width="550">  

- **Navegue para `Todas as funções`:** no menu de navegação à esquerda, selecione `Todos os serviços` e procure por recursos em Preview.

><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2309%20-%20Gerenciando%20Pol%C3%ADticas%20no%20Azure/img/img3.png" alt="Imagem 3" width="550">  

- **Selecione e Ative o Preview:** escolha o recurso que você deseja experimentar e siga as instruções para ativar o Preview. Esteja ciente de que recursos em Preview podem não ser totalmente estáveis e podem ter funcionalidades limitadas.

><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2309%20-%20Gerenciando%20Pol%C3%ADticas%20no%20Azure/img/img4.png" alt="Imagem 4" width="550">  
><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2309%20-%20Gerenciando%20Pol%C3%ADticas%20no%20Azure/img/img5.png" alt="Imagem 5" width="550"> 

### 3. Bloqueio de Recursos 🔒
O `Bloqueio de Recursos no Azure` permite que você impeça a exclusão ou modificação acidental de recursos críticos. Para criar um bloqueio de recurso, siga estes passos:

- **Acesse o Portal do Azure:** faça login no [Portal do Azure](https://portal.azure.com/). No menu de navegação à esquerda, selecione `Recursos` e escolha o recurso que você deseja proteger.

><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2309%20-%20Gerenciando%20Pol%C3%ADticas%20no%20Azure/img/img6.png" alt="Imagem 6" width="450">  

- **Configure o Bloqueio:** no painel do recurso, selecione `Bloqueios`.
Clique em `Adicionar bloqueio` e escolha um tipo de bloqueio:
    - **ReadOnly:** impede alterações, mas permite leitura.
    - **CanNotDelete:** impede exclusão do recurso.

><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2309%20-%20Gerenciando%20Pol%C3%ADticas%20no%20Azure/img/img7.png" alt="Imagem 7" width="450"> 

- **Defina o Nome e Descrição:** insira um nome e uma descrição para o bloqueio. Clique em `Salvar` para aplicar o bloqueio ao recurso.

><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2309%20-%20Gerenciando%20Pol%C3%ADticas%20no%20Azure/img/img8.png" alt="Imagem 8" width="450">  

><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2309%20-%20Gerenciando%20Pol%C3%ADticas%20no%20Azure/img/img9.png" alt="Imagem 9" width="450"> 

### 4. Gerenciamento de Policies 🚨
O `Gerenciamento de Políticas no Azure` ajuda a garantir que os recursos estejam em conformidade com as normas e regulamentos da sua organização. Para criar uma política, siga estes passos:

- **Acesse o Portal do Azure:** faça login no [Portal do Azure](https://portal.azure.com/). E navegue para `Azure Policy`. No menu de navegação à esquerda, selecione `Azure Policy`.

![Imagem 10](https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2309%20-%20Gerenciando%20Pol%C3%ADticas%20no%20Azure/img/img10.png)

- **Crie uma Nova Política:** selecione `Definitions` e clique em `New Policy Definition`. Defina os critérios e a política que você deseja aplicar.

><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2309%20-%20Gerenciando%20Pol%C3%ADticas%20no%20Azure/img/img11.png" alt="Imagem 11" width="250">  
><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2309%20-%20Gerenciando%20Pol%C3%ADticas%20no%20Azure/img/img12.png" alt="Imagem 12" width="450"> 


- **Aplique a Política:** após definir a política, selecione `Assignments` e clique em `Assign Policy`. Escolha a política criada e defina o escopo de aplicação (como um grupo de recursos ou uma assinatura).

><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2309%20-%20Gerenciando%20Pol%C3%ADticas%20no%20Azure/img/img13.png" alt="Imagem 13" width="450">  

>**Importante: Selecione se quer deixar ativado a policy ou não.**
>
><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2309%20-%20Gerenciando%20Pol%C3%ADticas%20no%20Azure/img/img14.png" alt="Imagem 14" width="450">  

><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2309%20-%20Gerenciando%20Pol%C3%ADticas%20no%20Azure/img/img15.png" alt="Imagem 15" width="450">   

><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2309%20-%20Gerenciando%20Pol%C3%ADticas%20no%20Azure/img/img16.png" alt="Imagem 16" width="450"> 

- **Revise e Salve:** revise os detalhes e clique em `Create` para aplicar a política.

### ▶️ Conclusão
Este guia serve como uma introdução básica para fornecer instruções sobre como Gerenciar Políticas no Microsoft Azure. Explore outros recursos conforme necessário para atender às suas necessidades de nuvem.

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
