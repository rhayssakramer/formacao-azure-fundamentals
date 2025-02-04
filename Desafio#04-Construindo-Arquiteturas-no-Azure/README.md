## ⚙️ Construindo Arquiteturas no Azure

Este repositório corresponde ao Desafio #04 da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification) para fornecer instruções sobre como criar Arquiteturas dentro do portal do Microsoft Azure.

### 1. Faça login na sua Conta no Azure ▶️

Se você ainda não tem uma conta no Azure, você vai precisar de uma! Visite o [Portal do Azure](https://portal.azure.com/) faça seu cadastro gratuitamente e siga o processo para criar uma conta. Após o cadastro, faça login com sua conta no Portal.

### 2. Criação do Grupo de Recursos📁

Depois de fazer login no portal, vá até o painel principal e pesquise por `Grupos de Recursos` ou `Resource Groups` na barra de pesquisa e Clique em `Criar`para iniciar a criação de um novo grupo de recursos.
![Imagem 1](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2304-Construindo-Arquiteturas-no-Azure/img/img1.png)
![Imagem 2](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2304-Construindo-Arquiteturas-no-Azure/img/img2.png)

- **Preencha as seguintes informações:**  
**Nome do Grupo de Recursos:** Dê um nome que identifique facilmente o grupo e seu propósito.  
**Região:** Selecione a região onde o grupo será criado. É recomendado escolher a mesma região para todos os recursos relacionados para reduzir a latência e os custos.  
- Clique em `Revisar + Criar` e depois em `Criar`.
![Imagem 3](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2304-Construindo-Arquiteturas-no-Azure/img/img3.png)

### 3. Criação da Rede Virtual 🛜
No painel do Azure, busque por `Redes Virtuais` ou `Virtual Networks`. Clique em `Criar` para iniciar a configuração de uma nova rede virtual.
![Imagem 4](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2304-Construindo-Arquiteturas-no-Azure/img/img4.png)
![Imagem 5](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2304-Construindo-Arquiteturas-no-Azure/img/img5.png)

- **Preencha os detalhes:**    
**Nome da Rede Virtual:** Escolha um nome que facilite a identificação da rede.  
**Grupo de Recursos:** Selecione o grupo de recursos criado anteriormente.  
**Região:** Escolha a mesma região do grupo de recursos.  
**Endereço IP:** Defina o intervalo de endereços IP para a rede virtual.  
- Clique em `Revisar + Criar` e depois em `Criar`.
![Imagem 6](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2304-Construindo-Arquiteturas-no-Azure/img/img6.png)
![Imagem 7](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2304-Construindo-Arquiteturas-no-Azure/img/img7.png)

### 4. Boas Práticas em Segurança no Azure

- **Criação de Regras no Grupo de Recursos**  
Para garantir a segurança e a eficiência dos seus recursos, é fundamental configurar regras apropriadas no Grupo de Recursos. Aqui está como você pode criar e gerenciar essas regras:

- **Acesso do Grupo de Recursos:** No painel do Azure, busque por `Grupos de Recursos` e selecione o grupo que você deseja configurar.  

- **Configuração de Regras de Segurança**  
**Grupo de Segurança de Rede (NSG):** Adicione ou configure regras de segurança para controlar o tráfego de entrada e saída. No painel de NSG, você pode definir regras para permitir ou negar tráfego com base em IPs, portas e protocolos.  
**Regras de Acesso:** Configure permissões e políticas para usuários e serviços que acessam o grupo de recursos. Utilize funções e permissões apropriadas para garantir que apenas usuários autorizados possam modificar ou visualizar os recursos.  

- **Monitoramento e Alertas:** 
**Configuração de Alertas:** Defina alertas para monitorar atividades e possíveis violação de políticas de segurança. Configure notificações para ações suspeitas ou uso não autorizado de recursos.  

- **Revisão e Atualização**  
**Revisão Periódica:** Realize revisões periódicas das regras e políticas para garantir que estejam atualizadas com as melhores práticas e os requisitos de segurança atuais.

- **Exemplo de Vulnerabilidades com Falta de Regras em Grupo de Recursos 🚨**  
Caso você não crie regras apropriadas em um Grupo de Recursos, pode enfrentar as seguintes vulnerabilidades.  
**Acesso Não Controlado:** Recursos dentro do grupo podem ser acessados por usuários não autorizados, expondo dados sensíveis e comprometendo a segurança.  
**Ataques de Rede:** Sem regras de segurança adequadas, suas redes podem estar suscetíveis a ataques externos, como DDoS ou acesso não autorizado a portas abertas.  
**Custo Excessivo:** Recursos não monitorados podem ser utilizados de maneira inadequada, resultando em custos inesperados e elevados.  
**Falta de Monitoramento:** A ausência de configuração apropriada pode levar à falta de visibilidade sobre o uso e estado dos recursos, dificultando a identificação de problemas e a realização de auditorias.  

**Certifique-se de sempre definir regras de segurança e monitoramento apropriadas para proteger seus recursos e otimizar o gerenciamento de custos.** 

### ▶️ Conclusão
Este guia serve como uma introdução básica para criar arquiteturas no Azure. Explore outros recursos conforme necessário para atender às suas necessidades de nuvem.

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

### <div align="center">Feito por <a href="https://github.com/rhayssakramer">@devrhakramer</a></div>
