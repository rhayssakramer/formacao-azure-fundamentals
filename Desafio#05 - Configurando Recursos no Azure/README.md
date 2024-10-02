## ⚙️ Configurando Recursos no Azure

Este repositório corresponde ao Desafio #05 da Bootcamp Microsoft Azure Essentials para fornecer instruções sobre como criar Arquiteturas dentro do portal do Microsoft Azure.

### 1. Faça login na sua Conta no Azure ▶️

Se você ainda não tem uma conta no Azure, você vai precisar de uma! Visite o [Portal do Azure](https://portal.azure.com/) faça seu cadastro gratuitamente e siga o processo para criar uma conta. Após o cadastro, faça login com sua conta no Portal.

### 2. Configure a Máquina Virtual ➕

**Nome da VM:** Escolha um nome fácil de lembrar.  
**Região:** Selecione a região mais próxima dos seus usuários para melhor performance.  
**Imagem:** Escolha o sistema operacional (Windows ou Linux) que você quer usar.  
**Tamanho:** Selecione o tamanho da VM com base nas suas necessidades de CPU e memória.  

![Imagem 1](/img/img1.png)
![Imagem 2](/img/img2.png)
![Imagem 3](/img/img3.png)

>Escolha o tipo de VMs que deseja criar.  
>![Imagem 4](/img/img4.png)

![Imagem 5](/img/img5.png)  

>Escolha a assinatura e o grupo de recursos, podendo escolher um existente o criar um novo.   
>![Imagem 6](/img/img6.png)  

>Clique em `Criar novo` para criar o conjunto de dimensionamento de máquinas virtuais e configurar a orquestração.
>![Imagem 7](/img/img7.png)  

>Configure os detalhes da instância criada. Clique em `Ver todos os tamanhos` para visualizar todos os tamanhos das instâncias.
>![Imagem 8](/img/img8.png)

>Escolha o tamanho da sua VM.  
>**IMPORTANTE!** Sempre selecionar a opção **Excluir com VM**, pois com essa opção marcada os discos são todos excluídos juntamente com as máquinas virtuais que forem excluídas também.  
>![Imagem 9](/img/img9.png)

### 3. Configure o Dimensionamento da Máquina Virtual 📏

**Dimensionamento Manual:** Escolha um tamanho de VM baseado na carga de trabalho que você espera. O Azure oferece uma variedade de tamanhos de VM, desde opções básicas para tarefas leves até opções robustas para aplicações exigentes.  
**Dimensionamento Automático:** Configure a autoescala para ajustar automaticamente os recursos da VM com base na demanda. Isso é útil se você tem variações significativas no uso ou precisa garantir que a VM possa lidar com picos de carga.  
**Utilize o Azure Advisor:** O Azure Advisor fornece recomendações de dimensionamento com base no desempenho atual da sua VM. Ele pode sugerir ajustes para economizar custos ou melhorar o desempenho.

![Imagem 10](/img/img10.png)
![Imagem 11](/img/img11.png)

### 4. Configure a Rede 🌐
**Rede Virtual:** Crie uma nova rede ou escolha uma existente.  
**Sub-rede:** Escolha a sub-rede para conectar sua VM.  
**Grupo de Segurança de Rede (NSG):** Defina regras para controlar o tráfego de entrada e saída da VM. Só permita o tráfego que você realmente precisa.  

![Imagem 12](/img/img12.png)

### 5. Defina Credenciais 🔑
**Nome de Usuário e Senha:** Configure um usuário e senha fortes para acessar sua VM.  
**Chaves SSH (para Linux):** Se for Linux, use chaves SSH para se conectar com mais segurança.

![Imagem 13](/img/img13.png)

### 6. Configurações Adicionais 🛠️
**Monitoramento:** Habilite o monitoramento para ficar de olho no desempenho da VM.  
**Tags:** Adicione tags para organizar melhor seus recursos.

![Imagem 14](/img/img14.png)

### 7. Revise e Crie 🔍
Confira todas as configurações e clique em `Criar` e aguarde enquanto o Azure prepara sua VM.

![Imagem 15](/img/img15.png)

### 8. Conecte-se à Sua VM 🌟
**Para Windows:** Use Remote Desktop (RDP) para se conectar.
**Para Linux:** Use SSH para acessar a VM.

## Cuidados Importantes para Produção
- **Segurança**  
<u>Configuração do NSG:</u> Defina regras de firewall para proteger sua VM. Bloqueie tudo que não é necessário.  
<u>Atualizações:</u> Mantenha o sistema e aplicativos atualizados.  
<u>Gerenciamento de Credenciais:</u> Use senhas fortes e considere ferramentas como Azure Key Vault para gerenciar segredos.  

- **Desempenho**  
<u>Tamanho Adequado:</u> Escolha o tamanho certo da VM para evitar problemas de desempenho.  
<u>Autoescala:</u> Configure o dimensionamento automático se sua carga de trabalho variar muito.  

- **Backup**  
<u>Backups Regulares:</u> Garanta que backups sejam feitos frequentemente.  
<u>Plano de Recuperação:</u> Tenha um plano de recuperação em caso de falhas.  

- **Monitoramento**  
<u>Acompanhe o Desempenho:</u> Use ferramentas de monitoramento para verificar como a VM está funcionando.  
<u>Relatórios:</u> Gere relatórios para ficar de olho no uso e na segurança.  

- **Custo**  
<u>Controle de Custos:</u> Acompanhe o uso e ajuste suas configurações para não gastar mais do que o necessário.  

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