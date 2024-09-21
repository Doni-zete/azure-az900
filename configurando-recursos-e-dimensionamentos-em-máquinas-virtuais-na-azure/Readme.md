# Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure



Este repositório apresenta como Configurar Recursos e Dimensionamentos em Máquinas Virtuais na Azure.

## Índice

- [Introdução](#introdução)
- [Acessando o Portal do Azure](#acessando-o-portal-do-azure)
- [Criar um Banco de Dados SQL](#criar-um-banco-de-dados-sQL)
- [Conclusão](#conclusão)

## Introdução

O Microsoft Azure é uma plataforma de computação em nuvem que oferece uma ampla gama de serviços para atender às necessidades de diferentes tipos de aplicativos e cargas de trabalho. Este guia ajudará você a navegar pelo portal do Azure e localizar os serviços essenciais organizados por categoria.

## Acessando o Portal do Azure

1. **Visite o site do Azure**: [Acesse](https://portal.azure.com).
2. **Faça login**: Insira suas credenciais (e-mail e senha) para acessar o portal.
3. **Navegue pelo portal**: Após o login, você será direcionado ao painel principal, onde poderá visualizar recursos, alertas e outras informações relevantes.

![Dashboard](https://github.com/Doni-zete/azure-az900/blob/main/localizando-servicos-por-categoria/img/img1.png)

## Configurar a Máquina Virtual


- **Assinatura**: Selecione a assinatura apropriada.
- **Grupo de Recursos**: Escolha um grupo de recursos existente ou crie um novo.
- **Nome da VM**: Dê um nome à sua máquina virtual.
- **Região**: Selecione a região onde a VM será hospedada. 
- **Escolher Imagem e Tamanho da VM
   Imagem:** Escolha o sistema operacional (Windows, Linux, etc.) que você deseja instalar.
   Tamanho da VM: Clique em "Selecionar tamanho" para escolher a série e o tamanho da VM. O Azure fornece informações sobre a capacidade de CPU, memória e custos. 
- **Configurações de Rede**
   1. **Rede Virtual:** Selecione uma VNet existente ou crie uma nova.
   2. **Sub-rede:** Escolha a sub-rede na qual a VM será conectada.
   3. **IP Público:** Decida se deseja atribuir um IP público à VM.
   4. **Grupo de Segurança de Rede (NSG):** Configure as regras de firewall para controlar o tráfego de entrada e saída.
- **Configurações de Armazenamento
   Tipo de Disco:** Escolha entre disco gerenciado SSD, HDD ou outro tipo. Considere o desempenho e o custo.
   Disco Adicional: Adicione discos adicionais, se necessário.
- **Configurações Adicionais
   Identidade:** Se necessário, configure a identidade da VM para acesso a outros recursos.
   Monitoramento: Ative o monitoramento, como o Azure Monitor e os logs de diagnóstico.
- **Revisar e Criar:**
   Revise todas as configurações e clique em "Criar". Aguarde a implantação da VM.

- **Dimensionar a Máquina Virtual:**
Para ajustar a capacidade da VM, vá até o painel da VM.
Clique em "Dimensionar" no menu.
Selecione um novo tamanho de VM e clique em "Dimensionar". A VM será reiniciada durante esse processo.
- **Exclusão da Máquina Virtual:**
    Para excluir a VM, vá até o painel da VM e clique em "Excluir".

![Dashboard](https://github.com/Doni-zete/azure-az900/blob/main/configurando-recursos-e-dimensionamentos-em-máquinas-virtuais-na-azure/img/img1.png)


## Conclusão
Este guia  fornece as informações necessárias para Configurar Recursos e Dimensionamentos em Máquinas Virtuais na Azure
 de forma eficaz.
