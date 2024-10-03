## ⚙️ Dominando Armazenamento no Azure

Este repositório corresponde ao Desafio #06 da Bootcamp Microsoft Azure Essentials para fornecer instruções sobre como configurar `Contas de Armazenamento` dentro do portal do Microsoft Azure.

### 1. Faça login na sua Conta no Azure ▶️

Se você ainda não tem uma conta no Azure, você vai precisar de uma! Visite o [Portal do Azure](https://portal.azure.com/) faça seu cadastro gratuitamente e siga o processo para criar uma conta. Após o cadastro, faça login com sua conta no Portal.

### 2. Configure a Conta de Armazenamento ➕
**Nome da Conta:** Escolha um nome único para sua conta de armazenamento.  
**Região:** Selecione a região mais próxima para melhor performance.  
**Tipo de Conta:** Escolha "Armazenamento General Purpose v2".  
**Replicação:** Selecione o tipo de replicação desejado (ex: LRS - Locally Redundant Storage).  
**Proteção de Dados:** Importante habilitar exclusão temporária para blobs.

![Imagem 1](https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img1.png)
![Imagem 2](https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img2.png)
![Imagem 3](https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img3.png)
![Imagem 4](https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img4.png)  

><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img5.png" alt="Imagem 5" width="550">  
><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img6.png" alt="Imagem 6" width="550">  
><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img7.png" alt="Imagem 7" width="550">  
><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img8.png" alt="Imagem 8" width="550">  

### 3. Criar um Compartilhamento de Arquivos 📁

**Acesse Sua Conta de Armazenamento:** No portal, vá para `Recursos` e selecione sua conta de armazenamento.  
**Criar um Compartilhamento de Arquivos:** No menu de `Serviços`, clique em `Compartilhamento de Arquivos`. Clique em `Adicionar compartilhamento de arquivos`. Nomeie o compartilhamento e defina o tamanho, depois clique em `Criar`.

![Imagem 9](https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img9.png)  
![Imagem 10](https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img10.png)  

><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img11.png" alt="Imagem 11" width="550">  
><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img12.png" alt="Imagem 12" width="550">
><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img13.png" alt="Imagem 13" width="550">
><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img14.png" alt="Imagem 14" width="550">

### 4. Migrar Dados para o Azure ☁️
**Criar um projeto:** Antes de tudo deve criar um projeto de migração para Azure.  

![Imagem 15](https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img15.png)

><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img16.png" alt="Imagem 16" width="550">
><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img17.png" alt="Imagem 17" width="550">  
><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img18.png" alt="Imagem 18" width="550">  


**Instalar o AzCopy:** Baixe e instale o AzCopy do site oficial [AzCopy Download](https://docs.microsoft.com/azure/storage/common/storage-use-azcopy-v10).

><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img19.png" alt="Imagem 19" width="550">  

**Autenticar com o Azure:**
~~~
 azcopy login
azcopy copy 'caminho/local/do/arquivo' 'https://<sua-conta>.file.core.windows.net/<compartilhamento>/<pasta>?<SAS-token>' --recursive
~~~~

><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img20.png" alt="Imagem 20" width="550">
><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img21.png" alt="Imagem 21" width="550">  
><img src="https://github.com/rhayssakramer/desafios-dio-azure-essentials/blob/main/Desafio%2306%20-%20Dominando%20Armazenamento%20no%20Azure/img/img22.png" alt="Imagem 22" width="550">      

**Certifique-se de sempre definir regras de segurança e monitoramento apropriadas para proteger seus recursos e otimizar o gerenciamento de custos.** 

### ▶️ Conclusão
Este guia serve como uma introdução básica para criar arquiteturas no Azure. Explore outros recursos conforme necessário para atender às suas necessidades de nuvem.

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
