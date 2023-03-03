---
title: Adicionar certificados SSL
description: Saiba como adicionar certificados SSL para proteger seus subdomínios.
feature: Control Panel
kt: 4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 7937499a-8267-4ce6-a93c-65c0c5e4e582
source-git-commit: d12902547ffde67838b326c93162d0937ff438a6
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 58%

---

# Adicionar certificados SSL

O Adobe Campaign [!UICONTROL Control Panel] permite adicionar certificados SSL para proteger seus subdomínios.

## Acesso ao gerenciamento de subdomínio do Painel de controle

Para acessar o gerenciamento de subdomínio no Painel de controle, acesse:

* [Experience Cloud Home](https://experience.adobe.com/#/home) > Solution picker: **[!DNL Campaign]** > **[!UICONTROL Control Panel]** card > **[!UICONTROL Subdomains & Certificates]** card

   ou
* Diretamente do URL: [https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## Etapas para adicionar certificados SSL

A adição de certificados SSL requer três etapas:

### 1. Gerar solicitações de assinatura de certificado

A Solicitação de assinatura de certificado (CSR) é necessária para a compra de um certificado SSL. Ela deve ser gerada para a instância e os subdomínios que você pretende proteger.

O vídeo abaixo descreve como gerar uma solicitação de assinatura de certificado no Painel de controle.

>[!VIDEO](https://video.tv.adobe.com/v/31317?quality=12)

*Gerar solicitações de assinatura de certificado (02:36 min)*

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
>Consulte a [documentação do produto](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renew-ssl/renewing-subdomain-certificate.html?lang=en) para saber mais.

### 2. Adquirir o certificado SSL

Depois de obter a CSR, você deve comprar o certificado SSL de uma autoridade de certificação aprovada pela organização.

### 3. Instalar os certificados SSL

Depois de obter o certificado SSL, ele deverá ser instalado para os subdomínios que você pretende proteger.

O vídeo abaixo explica como instalar certificados SSL em [!UICONTROL Control Panel].

>[!VIDEO](https://video.tv.adobe.com/v/31166?quality=12)

*Instalar certificados SSL (01:25 min)*


