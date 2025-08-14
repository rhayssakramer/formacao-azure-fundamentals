# 🖥️ Guia de Criação de Máquina Virtual em Azure 

Este repositório corresponde ao Desafio #02 da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification) para fornecer instruções sobre como criar uma máquina virtual dentro do portal do Microsoft Azure.

## 📑 Índice
- [Introdução]()
- [Tecnologias Utilizadas]()
- [Desafios de Projeto]()
- [Objetivos]()
  - [x] [Pré-requisitos]()
  - [x] [Estrutura do Repositório]()
  - [x] [Ferramentas e Tecnologias]()
  - [x] [O que será feito?]()
  - [x] [Passo a Passo]()
- [Acessando o Portal do Azure]()
- [Localizando Serviços por Categoria]()
- [Recursos Adicionais]()
- [Créditos]()
- [Autora]()

### ▶️ Introdução
O Microsoft Azure é uma plataforma de nuvem que permite criar, gerenciar e hospedar serviços na nuvem. Este guia ensina a criar sua primeira Máquina Virtual (VM), configurando computação, rede e armazenamento de forma prática.

### 💻 Tecnologias Utilizadas

| Linguagens de Programação | Ferramentas e Tecnologias |
| :-----------------: | :-----------------------: |
| <img height="40" src="https://skillicons.dev/icons?i=py"> | <img height="40" src="https://skillicons.dev/icons?i=github"> <img height="40" src="https://skillicons.dev/icons?i=git"> <img height="40" src="https://skillicons.dev/icons?i=vscode"> <img height="40" src="https://skillicons.dev/icons?i=azure">

### 🎯 Desafios de Projeto
- Aprender a criar e configurar uma Máquina Virtual no Azure.
- Entender conceitos de computação, rede e armazenamento na nuvem.
- Praticar segurança, login e configuração de credenciais.
- Publicar o ambiente e testar acesso remoto (RDP/SSH).

### 🛠️ Objetivos
- Capacitar usuários a criar e gerenciar VMs no Azure.
- Demonstrar boas práticas de configuração de rede e armazenamento.
- Facilitar a experimentação prática de serviços de computação na nuvem.

#### 📌 Pré-requisitos
1. Conta Microsoft ativa.
2. Acesso ao [Portal do Azure](https://portal.azure.com/).
3. Conhecimento básico de sistemas operacionais Windows ou Linux.
4. Navegador atualizado.

#### 📁 Estrutura do Repositório
```
📂 azure-vm-guide/
│
├── 📄 README.md                # Guia completo de criação da VM
├── 📂 img/                     # Imagens usadas no guia
│    ├── imagem1.png
│    ├── imagem2.png
│    └── imagem3.png
├── 📂 scripts/                 # Scripts de configuração, se houver
│    └── config-vm.ps1
├── 📂 docs/                    # Documentação extra
│    └── passo_a_passo.pdf
└── 📄 LICENSE                  # Licença do projeto
```

#### ⚙️ Ferramentas e Tecnologias
- Python
- Azure Portal
- VS Code 
- Git
- GitHub

#### 🧠 O que será feito?
- Criar uma VM no Azure com sistema Windows ou Linux.
- Configurar rede e segurança usando NSG.
- Definir credenciais de acesso.
- Validar conexão via RDP ou SSH.
- Explorar o portal do Azure para gerenciar recursos da VM.

### 🌐 Acesse o Portal do Azure
Primeiro, faça seu cadastro e depois login no [Portal do Azure](https://portal.azure.com/). É onde você vai gerenciar todos os seus recursos.
![Imagem 1](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2302-Criacao-de-VM-em-Azure/img/imagem1.png)

### ➕ Criação da VM
No painel do Azure, procure por `Máquinas Virtuais` ou `Virtual Machines` na barra de pesquisa. Clique em `Criar` para começar a configuração.
![Imagem 2](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2302-Criacao-de-VM-em-Azure/img/imagem2.png)

### 📝 Preencha os Detalhes Básicos Necessários 📝
**Nome da VM:** Escolha um nome que ajude você a identificar a VM facilmente.  
**Região:** Selecione a região onde a VM será criada. É uma boa ideia escolher uma que esteja perto dos seus usuários ou da sua localização.  
**Imagem:** Escolha o sistema operacional que você deseja instalar na VM, como Windows ou Linux.  
**Tamanho:** Selecione o tamanho da VM com base nas suas necessidades de CPU, memória e armazenamento.
![Imagem 3](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2302-Criacao-de-VM-em-Azure/img/imagem3.png)

### 🌐 Configure as Opções de Rede
**Rede Virtual:** Crie uma nova rede ou selecione uma existente.  
**Sub-rede:** Escolha a sub-rede onde a VM será conectada.  
**Grupo de Segurança de Rede (NSG):** Defina as regras de firewall para a sua VM.
![Imagem 4](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2302-Criacao-de-VM-em-Azure/img/imagem4.png)

### 🔑 Defina as Credenciais de Login
**Nome de Usuário e Senha:** Configure um nome de usuário e senha para acessar a VM. Certifique-se de escolher uma senha segura.

### 🔍 Revise e Crie
Revise todas as configurações para garantir que tudo esteja correto. Clique em `Criar` e aguarde alguns minutos enquanto o Azure provisiona sua máquina virtual.
![Imagem 5](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2302-Criacao-de-VM-em-Azure/img/imagem5.png)

### 🌟 Conecte-se à Sua VM
Depois que a VM estiver criada, você pode se conectar a ela. Para VMs Windows, use o `Remote Desktop (RDP)`. Para VMs Linux, você pode usar `SSH`.

## 🗒️ Recursos Adicionais
- [Documentação Oficial do Microsoft Azure](https://docs.microsoft.com/azure)
- [Tutoriais de Introdução ao Azure](https://docs.microsoft.com/learn/paths/azure-fundamentals/)

## 🔗 Créditos
Este guia serve como repositório de estudos, desafios e projetos da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification), para avaliar o ensinado no curso de sobre criação de VM em Azure.

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