---
title: Solução de problemas do Painel de controle
description: Saiba como solucionar problemas do Painel de controle.
feature: Control Panel
jira: KT-2938
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 92d32589-7763-4895-8117-abfd47d808e3
TQID: https://experienceleague.adobe.com/EDjVds-2tuOo0ZwbJOBzM7marwmcIeIYuqGnMFjisv0
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
source-git-commit: 9b8483fbaa7dce7f908c79e929d3b9628fd8fa44
workflow-type: tm+mt
source-wordcount: 353
ht-degree: 70%

---

# Solução de problemas do [!UICONTROL Painel de controle]

## Logon e página inicial

### Sintoma: não é possível fazer logon na Experience Cloud

**O que fazer:**
O usuário precisa localizar a ID organizacional IMS (xxx). O administrador precisa adicionar o usuário ao perfil de produto &quot;Campaign-xxx-Admins&quot; para cada instância que será gerenciada. Ainda que o usuário seja um administrador de todas as instâncias, será necessário adicioná-lo como usuário.

### Sintoma: os links na página inicial da Experience Cloud para acessar o [!UICONTROL Painel de Controle do Campaign] não são mostrados para o usuário

**Causa:**
Os usuários não verão os links até que sejam adicionados como usuários ao Perfil de Produto _Campaign-xxx-Administrators/Admin_.

**O que fazer:**
O administrador precisa adicionar o usuário ao Perfil de produto _Campaign-xxx-Admins_ para cada instância que será gerenciada. Ainda que o usuário seja um administrador de todas as instâncias, será necessário adicioná-lo como usuário.

### Sintoma: uma instância não está listada no [!UICONTROL Painel de Controle do Campaign]

**Causa:**
O mais provável é que o usuário precise ser adicionado como um *usuário* Perfil de Produto _Campanha-xxx-Administradores/Administrador_ para a instância que estiver ausente

**O que fazer:**
O administrador precisa adicionar o usuário ao Perfil de produto _Campaign-xxx-Admins_ para cada instância que será gerenciada. Se o usuário for um administrador de todas as instâncias, será necessário adicioná-lo como &quot;usuário&quot;.

### Vídeos úteis

>[!VIDEO](https://video.tv.adobe.com/v/27183?learn=on){transcript=true}

*Verificar ID da Org de IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?learn=on){transcript=true}

*Como adicionar um administrador aos administradores do perfil do produto para utilizar o [!UICONTROL Painel de controle] (01:03 min)*

### Documentação útil

* [Conheça o Painel de controle](https://experienceleague.adobe.com/pt-br/docs/control-panel/using/control-panel-home)
* [Gerenciamento de permissões do [!UICONTROL Painel de controle]](https://experienceleague.adobe.com/pt-br/docs/control-panel/using/control-panel-home)

## Estabelecer conexão com o servidor SFTP (cliente ou API)

A conexão com servidores SFTP requer:

* [!UICONTROL Permitir a listagem] do endereço IP do qual você está se conectando ao servidor SFTP
* Par de chave privada/pública que precisa ser registrado com o Adobe Campaign
* Se você se conectar diretamente ao servidor SFTP, precisará também do software cliente SFTP

### Documentação útil {#helpful-docs}

* [Logon no servidor SFTP](https://experienceleague.adobe.com/pt-br/docs/control-panel/using/control-panel-home)
