# 🏗️ Construindo Arquiteturas no Azure

Este repositório corresponde ao Desafio #04 da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification) para fornecer instruções sobre como criar Arquiteturas dentro do portal do Microsoft Azure.

## 📑 Índice
- [Introdução]()
- [Tecnologias Utilizadas]()
- [Desafio de Projeto]()
- [Objetivos ]()
  - [x] [Pré-requisitos]()
  - [x] [Estrutura do Repositório]()
  - [x] [Ferramentas e Tecnologias]()
  - [x] [O que será feito?]()
  - [x] [Passo a Passo]()
- [Acesse sua Conta no Azure]()
- [Criação do Grupo de Recursos]()
- [Criação da Rede Virtual]()
- [Boas Práticas em Segurança]()
- [Recursos Adicionais]()
- [Créditos]()
- [Autora]()

### ▶️ Introdução
No Azure, a construção de arquiteturas envolve organizar recursos como máquinas virtuais, redes virtuais e bancos de dados de forma eficiente e segura. Este guia irá ajudá-lo a criar grupos de recursos, redes virtuais e aplicar boas práticas de segurança para arquiteturas na nuvem.

### 💻 Tecnologias Utilizadas

| Linguagens de Programação | Ferramentas e Tecnologias |
| :-----------------: | :-----------------------: |
| <img height="40" src="https://skillicons.dev/icons?i=py"> | <img height="40" src="https://skillicons.dev/icons?i=github"> <img height="40" src="https://skillicons.dev/icons?i=git"> <img height="40" src="https://skillicons.dev/icons?i=vscode"> <img height="40" src="https://skillicons.dev/icons?i=azure"> <img height="40" src="https://github.com/rhayssakramer/rhayssakramer/blob/main/img/sqlserver.svg"> |

### 🎯 Desafio de Projeto
O objetivo deste desafio é praticar a criação de arquiteturas no Azure, incluindo:
- Criação de grupos de recursos
- Configuração de redes virtuais
- Aplicação de boas práticas de segurança
- Planejamento da infraestrutura de forma organizada e escalável

### 🛠️ Objetivos
- Aprender a criar e organizar recursos no Azure
- Configurar redes virtuais e sub-redes
- Aplicar regras de segurança usando NSG e monitoramento
- Seguir boas práticas de arquitetura de nuvem

#### 📌 Pré-requisitos
- Conta ativa no [Azure](https://portal.azure.com/)
- Conhecimentos básicos em nuvem e infraestrutura
- Navegador atualizado
- Noções de redes e segurança

#### 📁 Estrutura do Repositório
```
Desafio#04-Construindo-Arquiteturas/
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
- Python 
- SQL Server Management Studio (SSMS)

#### 🧠 O que será feito?
- Criação de grupos de recursos no Azure
- Configuração de redes virtuais e sub-redes
- Aplicação de regras de segurança (NSG)
- Monitoramento e alertas para recursos
- Práticas de boas arquiteturas e organização de recursos

#### 🚀 Passo a Passo
1. Fazer login no [Azure](https://portal.azure.com/)
2. Criar um Grupo de Recursos
3. Criar uma Rede Virtual
4. Configurar regras de segurança
5. Revisar todas as configurações
6. Criar os recursos e testar a conectividade

### 🌐 Faça login na sua Conta no Azure
Se você ainda não tem uma conta no Azure, você vai precisar de uma! Visite o [Portal do Azure](https://portal.azure.com/) faça seu cadastro gratuitamente e siga o processo para criar uma conta. Após o cadastro, faça login com sua conta no Portal.

### ➕ Criação do Grupo de Recursos
Depois de fazer login no portal, vá até o painel principal e pesquise por `Grupos de Recursos` ou `Resource Groups` na barra de pesquisa e Clique em `Criar`para iniciar a criação de um novo grupo de recursos.  
![Imagem 1](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2304-Construindo-Arquiteturas-no-Azure/img/img1.png)
![Imagem 2](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2304-Construindo-Arquiteturas-no-Azure/img/img2.png)

- **Preencha as seguintes informações:**  
**Nome do Grupo de Recursos:** Dê um nome que identifique facilmente o grupo e seu propósito.  
**Região:** Selecione a região onde o grupo será criado. É recomendado escolher a mesma região para todos os recursos relacionados para reduzir a latência e os custos.  
- Clique em `Revisar + Criar` e depois em `Criar`.  
![Imagem 3](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2304-Construindo-Arquiteturas-no-Azure/img/img3.png)

### 🛜 Criação da Rede Virtual
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

### 💡 Boas Práticas em Segurança no Azure

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

## 🗒️ Recursos Adicionais
- [Documentação Oficial do Microsoft Azure](https://docs.microsoft.com/azure)
- [Tutoriais de Introdução ao Azure](https://docs.microsoft.com/learn/paths/azure-fundamentals/)

## 🔗 Créditos
Este guia serve como repositório de estudos, desafios e projetos da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification), para avaliar o ensinado no curso de introdução básica para criar arquiteturas no Azure.

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