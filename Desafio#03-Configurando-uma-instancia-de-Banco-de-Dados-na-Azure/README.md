# 🛢️ Configurando uma Instância de Banco de Dados na Azure

Este repositório corresponde ao Desafio #03 da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification) para fornecer instruções sobre como criar uma instância de Banco de Dados dentro do portal do Microsoft Azure.

## 📑 Índice
- [Introdução]()
- [Tecnologias Utilizadas]()
- [Desafio de Projeto]()
- [Objetivos]()
  - [x] [Pré-requisitos]()
  - [x] [Estrutura do Repositório]()
  - [x] [Ferramentas e Tecnologias]()
  - [x] [O que será feito?]()
  - [x] [Passo a Passo]()
- [Recursos Adicionais]()
- [Créditos]()
- [Autora]()

## ▶️ Introdução
O Microsoft Azure oferece serviços de Banco de Dados na nuvem, permitindo criar, gerenciar e escalar bancos de dados de forma segura e eficiente. Este guia tem como objetivo ensinar como configurar uma instância de SQL Database no Azure, desde a criação da conta até a conexão com ferramentas externas como SSMS ou Azure Data Studio. Ele é ideal para quem está iniciando na nuvem e deseja entender os conceitos básicos de banco de dados no Azure.

## 💻 Tecnologias Utilizadas

| Linguagens de Programação | Ferramentas e Tecnologias |
| :-----------------: | :-----------------------: |
| | <img height="40" src="https://skillicons.dev/icons?i=github"> <img height="40" src="https://skillicons.dev/icons?i=git"> <img height="40" src="https://skillicons.dev/icons?i=vscode"> <img height="40" src="https://skillicons.dev/icons?i=azure"> <img height="40" src="https://github.com/rhayssakramer/rhayssakramer/blob/main/img/sqlserver.svg"> |

### 🎯 Desafio de Projeto
Aprender a criar, configurar e gerenciar uma instância de banco de dados no Azure, garantindo boas práticas de criação, segurança, backup e acesso a dados.

### 🛠️ Objetivos
- Criar uma instância de Banco de Dados no Azure.
- Configurar corretamente servidor, grupo de recursos e credenciais.
- Garantir backup e recuperação do banco.
- Conectar e testar a instância via SSMS ou Azure Data Studio.
- Explorar consultas e operações básicas em SQL Database.

#### 📌 Pré-requisitos
1. Conta Microsoft ativa.
2. Acesso ao [Portal do Azure](https://portal.azure.com/).
3. Conhecimento básico em SQL (opcional, mas recomendado).
4. Ferramentas de conexão instaladas (SSMS ou Azure Data Studio).

#### 📁 Estrutura do Repositório
```
📂 nome-do-repositorio/
│
├── 📄 README.md                 # Guia completo de criação de Banco de Dados na Azure
├── 📂 assets/                   # Imagens e recursos visuais usados no README
│    ├── img1.png
│    ├── img2.png
│    └── img3.png
├── 📂 scripts/                  # Scripts SQL de exemplo (opcional)
│    ├── criar_tabelas.sql
│    └── inserir_dados.sql
├── 📂 docs/                     # Documentos extras
│    └── guia_sql_azure.pdf
└── 📄 LICENSE                    # Licença do projeto
```

#### ⚙️ Ferramentas e Tecnologias
- Microsoft Azure Portal
- SQL Database (Azure SQL)
- SQL Server Management Studio (SSMS)
- Azure Data Studio
- Git
- GitHub

#### 🧠 O que será feito?
1. Criar uma conta e acessar o Azure.
2. Configurar grupo de recursos e servidor de banco de dados.
3. Criar instância de SQL Database.
4. Configurar plano de tarifação e backup.
5. Conectar via ferramentas externas (SSMS ou Azure Data Studio).
6. Testar operações básicas (inserir, consultar, atualizar dados).

🚀 Passo a Passo
1. Crie sua Conta no Azure
   - [Portal do Azure](https://portal.azure.com/)
2. Navegue até o Portal do Azure
   - Pesquise SQL Database ou vá em Criar um recurso > Banco de Dados.
3. Crie um Novo Banco de Dados
   - Preencha Nome do Banco, Assinatura, Grupo de Recursos e Servidor.
4. Configurações de Banco de Dados
   - Escolha o tipo de banco (SQL Database).
   - Defina plano de tarifação e backup.
5. Revise e Crie
   - Confirme todas as configurações e clique em Criar.
6. Conecte-se ao Seu Banco de Dados
   - Use SSMS ou Azure Data Studio com credenciais configuradas.
7. Explore e Use Seu Banco de Dados
   - Execute consultas, crie tabelas e teste operações.

### 🆕 Crie sua Conta no Azure
Se você ainda não tem uma conta no Azure, você vai precisar de uma! Visite o [Portal do Azure](https://portal.azure.com/) faça seu cadastro gratuitamente e siga o processo para criar uma conta. Após o cadastro, faça login com sua conta no Portal.

### 🌐 Navegue até o Portal do Azure
Depois de fazer login no portal, vá até o painel principal e pesquise por `SQL Database` na barra de pesquisa ou clique em `Criar um recurso` e depois em `Banco de Dados`.
![Imagem 1](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2303-Configurando-uma-instancia-de-Banco-de-Dados-na-Azure/img/Imagem1.png)
![Imagem 2](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2303-Configurando-uma-instancia-de-Banco-de-Dados-na-Azure/img/Imagem%202.png)

### 🆕 Crie um Novo Banco de Dados
Clique em `Criar`, isso iniciará o assistente de criação do banco de dados.  

**Preencha os Detalhes:** Preencha todos os detalhes necessários.
**Nome do Banco de Dados:** Escolha um nome único.
**Assinatura:** Selecione a assinatura que você está usando.
**Grupo de Recursos:** Crie um novo grupo ou use um existente.
**Servidor:** Crie um novo servidor ou selecione um já existente. Se você está criando um novo, preencha o nome do servidor, localização e credenciais de administrador.

![Imagem 3](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2303-Configurando-uma-instancia-de-Banco-de-Dados-na-Azure/img/Imagem%203.png)
![Imagem 4](https://github.com/rhayssakramer/formacao-azure-fundamentals/blob/main/Desafio%2303-Configurando-uma-instancia-de-Banco-de-Dados-na-Azure/img/Imagem%204.png)

### 🔨 Configurações de Banco de Dados
Escolha o tipo de banco de dados que deseja usar. O Azure oferece opções como SQL Database entre outros. Aqui, vamos criar um `SQL Database`.

**Plano de Tarifação (Importante):** Selecione o plano que se adapta às suas necessidades. Se você está apenas testando, o plano gratuito pode ser suficiente.
**Backup e Recuperação (Importante):** Configure as opções de backup conforme necessário para garantir que seus dados estejam seguros.

### ✅ Revise e Crie
Revise todas as configurações para garantir que está tudo certo. Se estiver, clique em `Criar` e aguarde alguns minutos enquanto o Azure configura seu banco de dados.

### 🌟 Conecte-se ao Seu Banco de Dados
Após a criação, você pode se conectar ao banco de dados usando ferramentas como `SQL Server Management Studio (SSMS)` ou `Azure Data Studio`. Use as credenciais que você configurou anteriormente para se conectar.

### 🔍 Explore e Use Seu Banco de Dados!
Agora que seu banco de dados está pronto, você pode começar a adicionar dados, executar consultas e explorar o que o Azure SQL Database tem a oferecer!

## 🗒️ Recursos Adicionais
- [Documentação Oficial do Microsoft Azure](https://docs.microsoft.com/azure)
- [Tutoriais de Introdução ao Azure](https://docs.microsoft.com/learn/paths/azure-fundamentals/)

## 🔗 Créditos
Este guia serve como repositório de estudos, desafios e projetos da [Bootcamp Microsoft Azure Essentials](https://www.dio.me/bootcamp/microsoft-azure-essentials?ref=AFOXWYVRXGV9) e da [Formação Microsoft AZ-900 Certification](https://web.dio.me/track/formacao-microsoft-az-900-certification), para avaliar o ensinado no curso de sobre configuração de instâncias no Azure.

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