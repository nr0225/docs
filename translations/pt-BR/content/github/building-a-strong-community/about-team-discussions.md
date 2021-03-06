---
title: Sobre discussões de equipe
intro: 'Sua equipe pode planejar em conjunto, atualizar uns aos outros ou falar sobre qualquer tópico que desejar em postagens de discussão na página de equipe em uma organização.'
redirect_from:
  - /articles/about-team-discussions
versions:
  free-pro-team: '*'
  enterprise-server: '*'
  github-ae: '*'
---

{% data reusables.organizations.team-discussions-purpose %}

Qualquer integrante da organização pode postar na página da equipe ou participar de uma discussão pública. {% data reusables.organizations.team-discussions-permissions %}

![Guia Discussions (Discussões) da página de equipe com discussões públicas e privadas](/assets/images/help/organizations/team-page-discussions-tab.png)

Você pode se vincular a qualquer discussão de equipe para fazer referência a ela em qualquer lugar. É possível fixar postagens importantes na página da equipe para referência rápida posterior. Para obter mais informações, consulte "[Fixar uma discussão de equipe](/articles/pinning-a-team-discussion)".

![Guia de discussões fixada da página de equipe com discussão fixada](/assets/images/help/organizations/team-discussions-pinned.png)

{% data reusables.organizations.team-discussions-default %} Os proprietários podem desabilitar as discussões de equipe para a organização inteira. Para obter mais informações, consulte "[Desabilitar discussões de equipe para sua organização](/articles/disabling-team-discussions-for-your-organization)".

### Notificações para discussões de equipe

Quando alguém posta ou responde a uma discussão pública na página de uma equipe, os integrantes da equipe e os integrantes de qualquer equipe secundária recebem notificações da web ou de e-mail. Quando alguém posta ou responde a uma discussão privada na página de uma equipe, somente os integrantes da equipe recebem notificações.

{% tip %}

**Dica:** dependendo das suas configurações de notificação, você receberá atualizações por e-mail, pela página de notificações da web no {% data variables.product.product_name %}, ou por ambos. For more information, see {% if currentVersion == "free-pro-team@latest" or currentVersion == "github-ae@latest" or currentVersion ver_gt "enterprise-server@2.20" %}"[Configuring notifications](/github/managing-subscriptions-and-notifications-on-github/configuring-notifications){% else %}"[About email notifications](/github/receiving-notifications-about-activity-on-github/about-email-notifications)" and "[About web notifications](/github/receiving-notifications-about-activity-on-github/about-web-notifications){% endif %}."

{% endtip %}

Por padrão, se seu nome de usuário for mencionado em uma discussão de equipe, você receberá notificações para a postagem mencionando seu nome de usuário e todas as respostas a essa postagem. Além disso, por padrão, se você responder a uma postagem, notificações serão enviadas para outras respostas à postagem.

Para desativar notificações de discussões de equipe, você pode cancelar a assinatura de uma postagem de discussão específica ou alterar as configurações de notificação para cancelar a inspeção ou ignorar completamente discussões de uma equipe específica. É possível assinar para receber notificações de uma postagem de discussão específica se você estiver cancelando a inspeção de discussões dessa equipe.

For more information, see {% if currentVersion == "free-pro-team@latest" or currentVersion == "github-ae@latest" or currentVersion ver_gt "enterprise-server@2.20" %}"[Viewing your subscriptions](/github/managing-subscriptions-and-notifications-on-github/viewing-your-subscriptions){% else %}"[Subscribing to and unsubscribing from notifications](/github/receiving-notifications-about-activity-on-github/subscribing-to-and-unsubscribing-from-notifications){% endif %}" and "[Nested teams](/articles/about-teams/#nested-teams)."

### Leia mais

- "[Sobre conversas no {% data variables.product.prodname_dotcom %}](/articles/about-conversations-on-github)"
- "[Sobre equipes](/articles/about-teams)"
- "[Criar uma discussão de equipe](/articles/creating-a-team-discussion)"
- "[Editar ou excluir uma discussão de equipe](/articles/editing-or-deleting-a-team-discussion)"
