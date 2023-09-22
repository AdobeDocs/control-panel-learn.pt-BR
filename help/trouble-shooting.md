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
source-git-commit: 81c5210502e719d6dfe0a000c511e3da4b17275a
workflow-type: tm+mt
source-wordcount: '324'
ht-degree: 98%

---

# Resolução de problemas do [!UICONTROL Control Panel]

## Logon e página inicial

### Sintoma: não é possível fazer logon na Experience Cloud

**O que fazer:**
o usuário precisa localizar a ID organizacional IMS (xxx). O administrador precisa adicionar o usuário ao perfil de produto &quot;Campaign-xxx-Admins&quot; para cada instância que será gerenciada. Ainda que o usuário seja um administrador de todas as instâncias, será necessário adicioná-lo como usuário.

### Sintoma: os links na página inicial da Experience Cloud para acessar o [!UICONTROL Control Panel] não aparecem para um usuário

**Causa:**
Os usuários não verão os links até que sejam adicionados como usuários ao Perfil do produto _Campaign-xxx-Administrators/Admin_.

**O que fazer:**
o administrador precisa adicionar o usuário ao perfil do produto _Campaign-xxx-Admins_ para cada instância que deseja gerenciar. Ainda que o usuário seja um administrador de todas as instâncias, será necessário adicioná-lo como usuário.

### Sintoma: uma instância não está listada no [!UICONTROL Control Panel]

**Causa:**
o mais provável é que o usuário precise ser adicionado como um *usuário do* Perfil de produto _Campaign-xxx-Administrators/Admin_ para a instância que estiver ausente.

**O que fazer:**
o administrador precisa adicionar o usuário ao Perfil de produto _Campaign-xxx-Admins_ para cada instância que deseja gerenciar. Se o usuário for um administrador de todas as instâncias, será necessário adicioná-lo como &quot;usuário&quot;.

### Vídeos úteis

>[!VIDEO](https://video.tv.adobe.com/v/27183?learn=on){transcript=true}

*Verificar IMS Org ID (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?learn=on){transcript=true}

*Como adicionar um administrador aos administradores do perfil do produto para utilizar o [!UICONTROL Control panel] (01:03 min)*

### Documentação útil

* [Conheça o Painel de controle](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=br)
* [Gerenciamento de permissões para o [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=br)

## Estabelecer conexão com o servidor SFTP (cliente ou API)

A conexão com servidores SFTP requer:

* [!UICONTROL Allow listing] o endereço IP a partir do qual você está se conectando ao servidor SFTP
* Par de chave privada/pública que precisa ser registrado com o Adobe Campaign
* Se você se conectar diretamente ao servidor SFTP, precisará também do software cliente SFTP

### Documentação útil {#helpful-docs}

* [Fazer logon no servidor SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=br)
