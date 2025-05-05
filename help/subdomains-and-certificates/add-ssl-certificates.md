---
title: Adicionar certificados SSL
description: Saiba como adicionar certificados SSL para proteger seus subdomínios.
feature: Control Panel
jira: KT-4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 7937499a-8267-4ce6-a93c-65c0c5e4e582
source-git-commit: 81c5210502e719d6dfe0a000c511e3da4b17275a
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 86%

---

# Adicionar certificados SSL

O [!UICONTROL Painel de Controle] do Adobe Campaign permite adicionar certificados SSL para proteger seus subdomínios.

## Acesso ao gerenciamento de subdomínio do Painel de controle

Para acessar o gerenciamento de subdomínio no Painel de controle, acesse:

* [Página Inicial do Experience Cloud](https://experience.adobe.com/#/home) > Seletor de solução: **[!DNL Campaign]** > cartão **[!UICONTROL Painel de Controle]** > **[!UICONTROL Subdomínios e Certificados]**

  ou
* Diretamente do URL: [https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## Etapas para adicionar certificados SSL

A adição de certificados SSL requer três etapas:

### 1. Gerar solicitações de assinatura de certificado

A Solicitação de assinatura de certificado (CSR) é necessária para a aquisição de um certificado SSL. Ele deve ser gerado para a instância e os subdomínios que você pretende proteger.

O vídeo abaixo descreve como gerar uma Solicitação de assinatura de certificado no Painel de controle.

>[!VIDEO](https://video.tv.adobe.com/v/36145?learn=on&captions=por_br){transcript=true}

*Gerar Solicitações de assinatura de certificado (02:36 min)*

>[!NOTE]
>
>Foram feitos vários aprimoramentos no processo de geração de CSR:
>
>* Ao gerar uma CSR, agora você pode selecionar um dos subdomínios incluídos como o Nome comum.
>* Agora você pode copiar o resumo da CSR antes de gerá-la.
>* Depois que uma CSR é gerada, você pode baixá-la novamente nos logs do processo. Esse recurso não se aplica a certificados gerados antes desta versão.
>
>![Baixar CSR](/help/assets/download-csr.gif)
>
>Consulte a [documentação do produto](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renew-ssl/renewing-subdomain-certificate.html?lang=pt-BR) para saber mais.
>

### 2. Adquirir o certificado SSL

Após obter o CSR, será necessário comprar o certificado SSL de uma autoridade de certificação aprovada pela sua organização.

### 3. Instalar os certificados SSL

Após obter o certificado SSL, será necessário instalá-lo para os subdomínios que você pretende proteger.

O vídeo abaixo explica como instalar certificados SSL no [!UICONTROL Painel de Controle].

>[!VIDEO](https://video.tv.adobe.com/v/36144?learn=on&captions=por_br){transcript=true}

*Instalar certificados SSL (01:25 min)*


