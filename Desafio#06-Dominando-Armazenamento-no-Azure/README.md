# 🏗️ Dominando Armazenamento no Azure

Este repositório corresponde ao Desafio #06 da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification) para fornecer instruções sobre como configurar Contas de Armazenamento dentro do portal do Microsoft Azure.

## 📑 Índice
- [Introdução]()
- [Tecnologias Utilizadas]()
- [Desafio de Projeto]()
- [Objetivos]()
  - [x] [Pré-requisitos]()
  - [x] [Estrutura do Repositório]()
  - [x] [Ferramentas e Tecnologias]()
  - [x] [O que será feito?]()
- [Acesse sua Conta no Azure]()
- [Acesse sua Conta no Azure]()
- [Configure a Conta de Armazenamento]()
- [Criar um Compartilhamento de Arquivos]()
- [Migrar Dados para o Azure]()
- [Boas Práticas de Segurança]()
- [Recursos Adicionais]()
- [Créditos]()
- [Autora]()

### ▶️ Introdução
Este guia fornece instruções passo a passo para configurar Contas de Armazenamento no Azure, criando compartilhamentos de arquivos e migrando dados para a nuvem de forma organizada e segura.

### 💻 Tecnologias Utilizadas

| Linguagens de Programação | Ferramentas e Tecnologias |
| :-----------------: | :-----------------------: |
| <img height="40" src="https://skillicons.dev/icons?i=py"> | <img height="40" src="https://skillicons.dev/icons?i=github"> <img height="40" src="https://skillicons.dev/icons?i=git"> <img height="40" src="https://skillicons.dev/icons?i=vscode"> <img height="40" src="https://skillicons.dev/icons?i=azure">

### 🎯 Desafio de Projeto
- Configurar Contas de Armazenamento no portal do Azure.
- Criar compartilhamentos de arquivos.
- Migrar dados do ambiente local para o Azure usando AzCopy.
- Aplicar boas práticas de segurança e monitoramento.

### 🛠️ Objetivos
- Aprender a criar e configurar contas de armazenamento.
- Organizar compartilhamentos de arquivos.
- Migrar dados para o Azure com segurança.
- Seguir boas práticas de gestão e monitoramento de recursos.

#### 📌 Pré-requisitos
1. Conta ativa no [Azure](https://portal.azure.com/)
2. Conhecimentos básicos em nuvem
3. Navegador atualizado

#### 📁 Estrutura do Repositório
```
Desafio#06-Dominando-Armazenamento-no-Azure/
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
- AzCopy

#### 🧠 O que será feito?
- Criar contas de armazenamento no Azure
- Configurar replicação e proteção de dados
- Criar compartilhamentos de arquivos
- Migrar dados usando AzCopy
- Aplicar regras de segurança e monitoramento

### 🌐 Acesse sua Conta no Azure

Se você ainda não tem uma conta no Azure, você vai precisar de uma! Visite o [Portal do Azure](https://portal.azure.com/) faça seu cadastro gratuitamente e siga o processo para criar uma conta. Após o cadastro, faça login com sua conta no Portal.

### 🔨 Configure a Conta de Armazenamento 
Configurações recomendadas:
**Nome da Conta:** Escolha um nome único para sua conta de armazenamento.  
**Região:** Selecione a região mais próxima para melhor performance.  
**Tipo de Conta:** Escolha "Armazenamento General Purpose v2".  
**Replicação:** Selecione o tipo de replicação desejado (ex: LRS - Locally Redundant Storage).  
**Proteção de Dados:** Importante habilitar exclusão temporária para blobs.

![Imagem 1](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img1.png)
![Imagem 2](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img2.png)
![Imagem 3](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img3.png)
![Imagem 4](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img4.png)  

><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img5.png" alt="Imagem 5" width="550">  
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img6.png" alt="Imagem 6" width="550">  
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img7.png" alt="Imagem 7" width="550">  
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img8.png" alt="Imagem 8" width="550">  

### 📂 Criar um Compartilhamento de Arquivos
**Acesse Sua Conta de Armazenamento:** No portal, vá para `Recursos` e selecione sua conta de armazenamento.  
**Criar um Compartilhamento de Arquivos:** No menu de `Serviços`, clique em `Compartilhamento de Arquivos`. Clique em `Adicionar compartilhamento de arquivos`. Nomeie o compartilhamento e defina o tamanho, depois clique em `Criar`.

![Imagem 9](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img9.png)  
![Imagem 10](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img10.png)  

><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img11.png" alt="Imagem 11" width="550">  
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img12.png" alt="Imagem 12" width="550">
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img13.png" alt="Imagem 13" width="550">
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img14.png" alt="Imagem 14" width="550">

### ☁️ Migrar Dados para o Azure
1. Criar um projeto:** Antes de tudo deve criar um projeto de migração para Azure.  
2. Instale o [AzCopy](https://docs.microsoft.com/azure/storage/common/storage-use-azcopy-v10).
3. Autentique e copie arquivos:

![Imagem 15](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img15.png)

><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img16.png" alt="Imagem 16" width="550">
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img17.png" alt="Imagem 17" width="550">  
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img18.png" alt="Imagem 18" width="550">  


**Instalar o AzCopy:** Baixe e instale o AzCopy do site oficial [AzCopy Download](https://docs.microsoft.com/azure/storage/common/storage-use-azcopy-v10).

><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img19.png" alt="Imagem 19" width="550">  

**Autenticar com o Azure:**
~~~
 azcopy login
azcopy copy 'caminho/local/do/arquivo' 'https://<sua-conta>.file.core.windows.net/<compartilhamento>/<pasta>?<SAS-token>' --recursive
~~~~

><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img20.png" alt="Imagem 20" width="550">
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img21.png" alt="Imagem 21" width="550">  
><img src="https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2306-Dominando-Armazenamento-no-Azure/img/img22.png" alt="Imagem 22" width="550">      

**Certifique-se de sempre definir regras de segurança e monitoramento apropriadas para proteger seus recursos e otimizar o gerenciamento de custos.**

### 💡 Boas Práticas de Segurança
- Crie regras de acesso e NSG (Network Security Group).
- Configure alertas e monitoramento. 
- Revise periodicamente as regras de segurança.
- Evite exposição de dados sensíveis e acessos não autorizados.

## 🗒️ Recursos Adicionais
- [Documentação Oficial do Microsoft Azure](https://docs.microsoft.com/azure)
- [Tutoriais de Introdução ao Azure](https://docs.microsoft.com/learn/paths/azure-fundamentals/)

*Dica: Sempre defina regras de segurança e monitoramento para proteger os recursos e controlar custos.*

## 🔗 Créditos
Este guia serve como repositório de estudos, desafios e projetos da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification), para avaliar o ensinado sobre introdução básica para fornecer instruções sobre como configurar Contas de Armazenamento dentro do portal do Microsoft Azure.

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