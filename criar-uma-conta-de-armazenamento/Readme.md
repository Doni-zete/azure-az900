# Criar uma conta de armazenamentos


Este repositório apresenta como Criar uma conta de armazenamento na Azure.

## Índice

- [Introdução](#introdução)
- [Acessando o Portal do Azure](#acessando-o-portal-do-azure)
- [Criar uma conta de armazenamento](#criar-uma-conta-de-armazenamento)
- [Conclusão](#conclusão)

## Introdução

O Microsoft Azure é uma plataforma de computação em nuvem que oferece uma ampla gama de serviços paraatender 
às necessidades de diferentes tipos de aplicativos e cargas de trabalho. Este guia ajudará você a navegar pelo portal do Azure.

## Acessando o Portal do Azure

1. **Visite o site do Azure**: [Acesse](https://portal.azure.com).
2. **Faça login**: Insira suas credenciais (e-mail e senha) para acessar o portal.
3. **Navegue pelo portal**: Após o login, você será direcionado ao painel principal, onde poderá visualizar recursos, alertas e outras informações relevantes.

![Dashboard](https://github.com/Doni-zete/azure-az900/blob/main/localizando-servicos-por-categoria/img/img1.png)

## Criar uma conta de armazenamento

- **Assinatura:** Selecione a assinatura onde deseja criar a conta de armazenamento.
- **Grupo de Recursos:** Escolha um grupo de recursos existente ou crie um novo.
- **Nome da Conta de Armazenamento:** Dê um nome único (minúsculas, de 3 a 24 caracteres, e apenas letras e números).
- **Região:** Selecione a região onde a conta de armazenamento será criada.
- **Escolher o Tipo de Conta de Armazenamento
   Tipo de Conta:** Escolha entre os tipos disponíveis, como:
   Conta de Armazenamento General Purpose v2: Para armazenamento de blobs, arquivos, filas, tabelas, etc.
   Conta de Armazenamento de Blobs: Para armazenamento otimizado para dados não estruturados.
   Conta de Armazenamento de Arquivos: Para compartilhamento de arquivos SMB.
- **Configurações Adicionais**
   **Desempenho:** Escolha entre Standard (HDD) ou Premium (SSD).
   **Replicação:** Escolha a opção de replicação, como LRS (Locally Redundant Storage), GRS (Geo-Redundant Storage), etc.
   **Acesso:** Defina se a conta será pública ou privada.
- **Configurações de Rede (Opcional)**
   Você pode configurar regras de firewall e redes virtuais se desejar restringir o acesso.
- **Revisar e Criar**
   Após preencher todas as informações, clique em "Revisar + criar".
   Revise as configurações e clique em "Criar".
- **Gerenciar a Conta de Armazenamento**
   Após a criação, você pode acessar a conta de armazenamento no painel do Azure para gerenciar blobs, arquivos, tabelas e filas.
- **Exclusão da Conta de Armazenamento**
    Para excluir a conta de armazenamento, vá até a conta no portal e clique em "Excluir".

![Criar uma conta de armazenamento](https://github.com/Doni-zete/azure-az900/blob/main/criar-uma-conta-de-armazenamento/img/img1.png)


## Conclusão
Este guia  fornece as informações necessárias para Criar uma conta de armazenamento na Azure
 de forma eficaz.
