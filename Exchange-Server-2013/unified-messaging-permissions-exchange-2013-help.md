﻿---
title: 'Autorizzazioni della messaggistica unificate: Exchange 2013 Help'
TOCTitle: Autorizzazioni della messaggistica unificate
ms:assetid: d326c3bc-8f33-434a-bf02-a83cc26a5498
ms:mtpsurl: https://technet.microsoft.com/it-it/library/Dd638193(v=EXCHG.150)
ms:contentKeyID: 50481731
ms.date: 05/22/2018
mtps_version: v=EXCHG.150
ms.translationtype: MT
---

# Autorizzazioni della messaggistica unificate

 

_**Si applica a:**Exchange Server 2013_

_**Ultima modifica dell'argomento:**2015-03-09_

Le autorizzazioni richieste per eseguire attività sui server Accesso client su cui è in esecuzione il servizio di routing delle chiamate di messaggistica unificata di Microsoft Exchange e sui server Cassette postali su cui è in esecuzione il servizio Messaggistica unificata di Microsoft Exchange dipendono dalla procedura di esecuzione o dal cmdlet che si intende eseguire.

Per individuare le autorizzazioni necessarie per eseguire la procedura o il cmdlet, procedere come segue:

1.  Nella tabella seguente individuare la funzionalità più pertinente alla procedura o al cmdlet che si vuole eseguire.

2.  Esaminare quindi le autorizzazioni necessarie per la funzionalità. È necessario ricevere l'assegnazione di uno di questi gruppi di ruoli, di un gruppo di ruoli personalizzato equivalente o di un ruolo di gestione equivalente. È inoltre possibile fare clic su un gruppo di ruoli per visualizzarne i ruoli di gestione. Se per una determinata funzionalità sono elencati più gruppi di ruoli, per usarla è necessario essere assegnati a uno di questi gruppi. Per altre informazioni sui gruppi di ruoli e sui ruoli di gestione, vedere [Controllo di accesso basato sui ruoli](understanding-role-based-access-control-exchange-2013-help.md).

3.  A questo punto, eseguire il cmdlet **Get-ManagementRoleAssignment** per individuare i gruppi di ruoli o i ruoli di gestione a cui si è assegnati e verificare se si dispone delle autorizzazioni necessarie per gestire la funzionalità.
    

    > [!NOTE]
    > Per eseguire il cmdlet <STRONG>Get-ManagementRoleAssignment</STRONG> è necessario ricevere l'assegnazione del ruolo di gestione dei ruoli. Se non si hanno le autorizzazioni per eseguire il cmdlet <STRONG>Get-ManagementRoleAssignment</STRONG>, chiedere all'amministratore di Exchange di recuperare i gruppi di ruoli o i ruoli di gestione assegnati.



Se si desidera delegare la gestione di una funzionalità a un altro utente, vedere [Delegare le assegnazioni di ruolo](delegate-role-assignments-exchange-2013-help.md).

## Autorizzazioni del componente di messaggistica unificata

È possibile configurare le impostazioni per i componenti e le funzionalità della messaggistica unificata nella seguente tabella.

Gli utenti a cui viene assegnato il gruppo di ruoli di gestione in sola visualizzazione possono visualizzare la configurazione delle funzionalità nella tabella seguente. Per altre informazioni, vedere Gestione dell'organizzazione in sola visualizzazione[Gestione organizzazione sola visualizzazione](view-only-organization-management-exchange-2013-help.md).


<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Funzionalità</th>
<th>Autorizzazioni necessarie</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Operatori automatici di messaggistica unificata</p></td>
<td><p><a href="organization-management-exchange-2013-help.md">Gestione organizzazione</a></p>
<p><a href="um-management-exchange-2013-help.md">Gestione messaggistica unificata</a></p></td>
</tr>
<tr class="even">
<td><p>Regole di risposta alle chiamate di messaggistica unificata</p></td>
<td><p><a href="organization-management-exchange-2013-help.md">Gestione organizzazione</a></p>
<p><a href="um-management-exchange-2013-help.md">Gestione messaggistica unificata</a></p></td>
</tr>
<tr class="odd">
<td><p>Dati relativi alle chiamate di messaggistica unificata e report di riepilogo</p></td>
<td><p><a href="organization-management-exchange-2013-help.md">Gestione organizzazione</a></p>
<p><a href="um-management-exchange-2013-help.md">Gestione messaggistica unificata</a></p></td>
</tr>
<tr class="even">
<td><p>Server Accesso client (servizio di routing delle chiamate di messaggistica unificata)</p></td>
<td><p><a href="organization-management-exchange-2013-help.md">Gestione organizzazione</a></p>
<p><a href="um-management-exchange-2013-help.md">Gestione messaggistica unificata</a></p></td>
</tr>
<tr class="odd">
<td><p>Dial plan di messaggistica unificata</p></td>
<td><p><a href="organization-management-exchange-2013-help.md">Gestione organizzazione</a></p>
<p><a href="um-management-exchange-2013-help.md">Gestione messaggistica unificata</a></p></td>
</tr>
<tr class="even">
<td><p>Gruppi di risposta di messaggistica unificata</p></td>
<td><p><a href="organization-management-exchange-2013-help.md">Gestione organizzazione</a></p>
<p><a href="um-management-exchange-2013-help.md">Gestione messaggistica unificata</a></p></td>
</tr>
<tr class="odd">
<td><p>Gateway IP di messaggistica unificata</p></td>
<td><p><a href="organization-management-exchange-2013-help.md">Gestione organizzazione</a></p>
<p><a href="um-management-exchange-2013-help.md">Gestione messaggistica unificata</a></p></td>
</tr>
<tr class="even">
<td><p>Criteri cassetta postale di messaggistica unificata</p></td>
<td><p><a href="organization-management-exchange-2013-help.md">Gestione organizzazione</a></p>
<p><a href="um-management-exchange-2013-help.md">Gestione messaggistica unificata</a></p></td>
</tr>
<tr class="odd">
<td><p>Cassette postali di messaggistica unificata</p></td>
<td><p><a href="organization-management-exchange-2013-help.md">Gestione organizzazione</a></p>
<p><a href="um-management-exchange-2013-help.md">Gestione messaggistica unificata</a></p></td>
</tr>
<tr class="even">
<td><p>Prompt di messaggistica unificata</p></td>
<td><p><a href="organization-management-exchange-2013-help.md">Gestione organizzazione</a></p>
<p><a href="um-management-exchange-2013-help.md">Gestione messaggistica unificata</a></p></td>
</tr>
<tr class="odd">
<td><p>Server Cassette postali (servizio di messaggistica unificata)</p></td>
<td><p><a href="organization-management-exchange-2013-help.md">Gestione organizzazione</a></p>
<p><a href="server-management-exchange-2013-help.md">Server Management</a></p></td>
</tr>
</tbody>
</table>

