、
    - [Skills samples](#skills-samples)
    - [Experimental / preview samples](#experimental--preview-samples)
  - [Contributing](#contributing)
  - [Reporting security issues](#reporting-security-issues)

### Bot essentials

|    | Sample Name           | Description                                                                      | .NET    | JavaScript   | Python  |
|:--:|:----------------------|:---------------------------------------------------------------------------------|:--------|:-------------|:--------|
|2|Echo bot             | Demonstrates how to receive and send messages.                                 |[.NET&nbsp;Core][cs#2] |[JavaScript][js#2], [TypeScript][ts#2]|[Python][py#2]
|3|Welcome user         | Introduces activity types and provides a welcome message on conversation update activity. |[.NET&nbsp;Core][cs#3] |[JavaScript][js#3], [TypeScript][ts#3]|[Python][py#3]
|5|Multi&nbsp;turn&nbsp;prompts    | Demonstrates how to use waterfall dialog, prompts, and component dialog to create a simple interaction that asks the user for name, age, and prints back that information.          |[.NET&nbsp;Core][cs#5] |[JavaScript][js#5], [TypeScript][ts#5] |[Python][py#5]
|6|Using cards          | Introduces all card types including thumbnail, audio, media etc. Builds on Welcoming user + multi-prompt bot by presenting a card with buttons in welcome message that route to appropriate dialog.     |[.NET&nbsp;Core][cs#6] |[JavaScript][js#6], [TypeScript][ts#6] |[Python][py#6]
|7|Adaptive cards | Demonstrates how the multi-turn dialog can use a card to get user input for name and age. |[.NET&nbsp;Core][cs#7] |[JavaScript][js#7] |[Python][py#7]
|8|Suggested actions    | Demonstrates how to enable your bot to present buttons that the user can tap to provide input.                                      |[.NET&nbsp;Core][cs#8] |[JavaScript][js#8] |[Python][py#8]
|15|Handling&nbsp;attachments| Demonstrates how to listen for/handle user provided attachments.                |[.NET&nbsp;Core][cs#15]|[JavaScript][js#15]|[Python][py#15]
|40|TIMEX resolution    | Demonstrates various ways to parse and manipulate the TIMEX expressions you get from LUIS and the [DateTimeRecognizer](https://github.com/Microsoft/recognizers-text) used by the DateTimePrompt. |[.NET&nbsp;Core][cs#40] |[JavaScript][js#40]|[Python][py#40]
|43|Complex dialogs      | Demonstrates different ways for composing dialogs. |[.NET&nbsp;Core][cs#43]|[JavaScript][js#43] |[Python][py#43]
|45|State management    | Demonstrates how to use state management and storage objects to manage and persist state. | [.NET&nbsp;Core][cs#45] | [JavaScript][js#45]   |[Python][py#45]

### Advanced bots

|    | Sample Name           | Description                                                                      | .NET    | JavaScript   | Python  |
|:--:|:----------------------|:---------------------------------------------------------------------------------|:--------|:-------------|:--------|
|1|Console&nbsp;echo&nbsp;bot         | Introduces the concept of adapter and demonstrates a simple echo bot on console adapter and how to send a reply and access the incoming message.           |[.NET&nbsp;Core][cs#1] |[JavaScript][js#1], [TypeScript][ts#1] |[Python][py#1]
|1|Browser echo bot         | Demonstrates how to host a bot in the browser using Web Chat and a custom Web Chat Adapter.   |  | [ECMAScript&nbsp;6][es#1]  |
|16|Proactive&nbsp;messages  | Demonstrates how to send proactive messages to users.                           |[.NET&nbsp;Core][cs#16]|[JavaScript][js#16], [TypeScript][ts#16]|[Python][py#16]
|17|Multilingual bot    | Using translate middleware to support a multi-lingual bot. Demonstrates custom middleware. |[.NET&nbsp;Core][cs#17]|[JavaScript][js#17]|[Python][py#17]
|19|Custom dialogs      | Demonstrates complex conversation flow using the Dialogs library. |[.NET&nbsp;Core][cs#19]|[JavaScript][js#19]|[Python][py#19]
|23|Facebook events     | Integrate and consume Facebook specific payloads, such as post-backs, quick replies and opt-in events.|[.NET&nbsp;Core][cs#23] |[JavaScript][js#23] |[Python][py#23]
|42|Scale out            | Demonstrates how you can build your own state solution from the ground up that supports scaled out deployment with ETag based optimistic locking. |[.NET&nbsp;Core][cs#42] |    |[Python][py#42]
|44|Basic custom prompts | Demonstrates how to implement your own _basic_ prompts to ask the user for information. |[.NET&nbsp;Core][cs#44]|[JavaScript][js#44]|[Python][py#44]
|47|Inspection&nbsp;middleware    | Demonstrates how to use middleware to allow the Bot Framework Emulator to debug traffic into and out of the bot in addition to looking at the current state of the bot. | [.NET&nbsp;Core][cs#47] | [JavaScript][js#47]   |[Python][py#47]
|49| Proxy echo bot    | Demonstrates how to configure the bot to use it behind a corporative proxy. | | [JavaScript][js#49]   ||
|70|Styling webchat     | This sample shows how to create a web page with custom Web Chat component.|         | [ECMAScript&nbsp;6][es#70]         |

### Authentication samples

|    | Sample Name           | Description                                                                      | .NET    | JavaScript   | Python  |
|:--:|:----------------------|:---------------------------------------------------------------------------------|:--------|:-------------|:--------|
|18|OAuth authentication  | Bot that demonstrates how to integrate OAuth providers.                  |[.NET&nbsp;Core][cs#18]|[JavaScript][js#18]|[Python][py#18]
|24|MSGraph&nbsp;authentication    | Demonstrates bot authentication capabilities of Azure Bot Service. Demonstrates utilizing the Microsoft Graph API to retrieve data about the user.|[.NET&nbsp;Core][cs#24] |[JavaScript][js#24] |[Python][py#24]
|46|Teams authentication    | Demonstrates how to use authentication for a bot running in Microsoft Teams. | [.NET&nbsp;Core](https://github.com/OfficeDev/Microsoft-Teams-Samples/tree/main/samples/bot-teams-authentication/csharp) | [JavaScript](https://github.com/OfficeDev/Microsoft-Teams-Samples/tree/main/samples/bot-conversation-sso-quickstart/js)   |[Python](https://github.com/OfficeDev/Microsoft-Teams-Samples/tree/main/samples/bot-teams-authentication/python)
|84|Certificate authentication            | Demonstrates how to use Certificates to authenticate the bot     | [.NET&nbsp;Core][cs#84] |[JavaScript][js#84] | |
|85|Subject name/issuer authentication            | Demonstrates how to use the subject name/issuer authentication in a bot     | [.NET&nbsp;Core][cs#85] | [JavaScript][js#85] | |
|86|Federated Credentials authentication            | Demonstrates how to use the FIC in a bot authentication     | [.NET&nbsp;Core][cs#86] | [JavaScript][js#86] | |

### Custom question answering samples

|    | Sample Name           | Description                                                                      | .NET    | JavaScript   | Python  |
|:--:|:----------------------|:---------------------------------------------------------------------------------|:--------|:-------------|:--------|
|12|Custom question answering&nbsp;(simple)             | Demonstrates how to use Custom question answering to have simple single-turn conversations     |[.NET&nbsp;Core][cs#12]|[JavaScript][js#12]      | | 
|48|Custom question answering&nbsp;(advanced) | Demonstrates how to integrate Multiturn and Active learning in a Custom question answering bot |[.NET&nbsp;Core][cs#48]|[JavaScript][js#48]     | | 

### Skills samples

|    | Sample Name                          | Description                                                   | .NET Core           | JavaScript         | Python            |
|:--:|:-------------------------------------|:--------------------------------------------------------------|:--------------------|:-------------------|:------------------|
| 80 | Skills&nbsp;-&nbsp;simple&nbsp;bot&nbsp;to&nbsp;bot           | This sample shows how to connect a skill to a skill consumer. | [.NET&nbsp;Core][cs#80]  | [JavaScript][js#80]     | [Python][py#80]   |
| 81 | Skills - skill dialog                | This sample shows how to connect a skill to a skill dialog consumer. | [.NET&nbsp;Core][cs#81]  | [JavaScript][js#81]     | [Python][py#81]   |
| 82 | Skills - SSO with CloudAdapter       | This sample shows how to use SSO with skills and CloudAdapter. | [.NET&nbsp;Core][cs#82]  | [JavaScript][js#82]     | NA                |

### Experimental / preview samples

A [collection of **experimental** samples](./experimental) exist, intended to provide samples for features currently in preview or as a way to solicit feedback on a given design, approach, or technology being considered by the Bot Framework Team.

[cs#1]:samples/csharp_dotnetcore/01.console-echo
[cs#2]:samples/csharp_dotnetcore/02.echo-bot
[cs#3]:samples/csharp_dotnetcore/03.welcome-user
[cs#5]:samples/csharp_dotnetcore/05.multi-turn-prompt
[cs#6]:samples/csharp_dotnetcore/06.using-cards
[cs#7]:samples/csharp_dotnetcore/07.using-adaptive-cards
[cs#8]:samples/csharp_dotnetcore/08.suggested-actions
[cs#12]:samples/csharp_dotnetcore/12.customQABot
[cs#15]:samples/csharp_dotnetcore/15.handling-attachments
[cs#16]:samples/csharp_dotnetcore/16.proactive-messages
[cs#17]:samples/csharp_dotnetcore/17.multilingual-bot
[cs#18]:samples/csharp_dotnetcore/18.bot-authentication
[cs#19]:samples/csharp_dotnetcore/19.custom-dialogs
[cs#23]:samples/csharp_dotnetcore/23.facebook-events
[cs#24]:samples/csharp_dotnetcore/24.bot-authentication-msgraph
[cs#40]:samples/csharp_dotnetcore/40.timex-resolution
[cs#42]:samples/csharp_dotnetcore/42.scaleout
[cs#43]:samples/csharp_dotnetcore/43.complex-dialog
[cs#44]:samples/csharp_dotnetcore/44.prompt-users-for-input
[cs#45]:samples/csharp_dotnetcore/45.state-management
[cs#47]:samples/csharp_dotnetcore/47.inspection
[cs#48]:samples/csharp_dotnetcore/48.customQABot-all-features
[cs#60]:samples/csharp_dotnetcore/60.slack-adapter
[cs#61]:samples/csharp_dotnetcore/61.facebook-adapter
[cs#62]:samples/csharp_dotnetcore/62.webex-adapter
[cs#63]:samples/csharp_dotnetcore/63.twilio-adapter
[cs#80]:samples/csharp_dotnetcore/80.skills-simple-bot-to-bot
[cs#81]:samples/csharp_dotnetcore/81.skills-skilldialog
[cs#82]:samples/csharp_dotnetcore/82.skills-sso-cloudadapter
[cs#84]:samples/csharp_dotnetcore/84.bot-authentication-certificate
[cs#85]:samples/csharp_dotnetcore/85.bot-authentication-sni
[cs#86]:samples/csharp_dotnetcore/86.bot-authentication-fic

[es#1]:samples/javascript_es6/01.browser-echo
[es#70]:samples/javascript_es6/70.styling-webchat

[ts#0]:samples/typescript_nodejs/00.empty-bot
[ts#1]:samples/typescript_nodejs/01.console-echo
[ts#2]:samples/typescript_nodejs/02.echo-bot
[ts#3]:samples/typescript_nodejs/03.welcome-users
[ts#5]:samples/typescript_nodejs/05.multi-turn-prompt
[ts#6]:samples/typescript_nodejs/06.using-cards
[ts#16]:samples/typescript_nodejs/16.proactive-messages
[ts#52]:https://github.com/Microsoft/AI/tree/master/templates/Enterprise-Template


[js#1]:samples/javascript_nodejs/01.console-echo
[js#2]:samples/javascript_nodejs/02.echo-bot
[js#3]:samples/javascript_nodejs/03.welcome-users
[js#5]:samples/javascript_nodejs/05.multi-turn-prompt
[js#6]:samples/javascript_nodejs/06.using-cards
[js#7]:samples/javascript_nodejs/07.using-adaptive-cards
[js#8]:samples/javascript_nodejs/08.suggested-actions
[js#12]:samples/javascript_nodejs/12.customQABot
[js#15]:samples/javascript_nodejs/15.handling-attachments
[js#16]:samples/javascript_nodejs/16.proactive-messages
[js#17]:samples/javascript_nodejs/17.multilingual-bot
[js#18]:samples/javascript_nodejs/18.bot-authentication
[js#19]:samples/javascript_nodejs/19.custom-dialogs
[js#23]:samples/javascript_nodejs/23.facebook-events
[js#24]:samples/javascript_nodejs/24.bot-authentication-msgraph
[js#40]:samples/javascript_nodejs/40.timex-resolution
[js#43]:samples/javascript_nodejs/43.complex-dialog
[js#44]:samples/javascript_nodejs/44.prompt-for-user-input
[js#45]:samples/javascript_nodejs/45.state-management
[js#47]:samples/javascript_nodejs/47.inspection
[js#48]:samples/javascript_nodejs/48.customQABot-all-features
[js#49]:samples/javascript_nodejs/49.echo-proxy-bot
[js#80]:samples/javascript_nodejs/80.skills-simple-bot-to-bot
[js#81]:samples/javascript_nodejs/81.skills-skilldialog
[js#82]:samples/javascript_nodejs/82.skills-sso-cloudadapter
[js#84]:samples/javascript_nodejs/84.bot-authentication-certificate
[js#85]:samples/javascript_nodejs/85.bot-authentication-sni
[js#86]:samples/javascript_nodejs/86.bot-authentication-fic

[py#1]:samples/python/01.console-echo
[py#2]:samples/python/02.echo-bot
[py#3]:samples/python/03.welcome-user
[py#5]:samples/python/05.multi-turn-prompt
[py#6]:samples/python/06.using-cards
[py#7]:samples/python/07.using-adaptive-cards
[py#8]:samples/python/08.suggested-actions
[py#15]:samples/python/15.handling-attachments
[py#16]:samples/python/16.proactive-messages
[py#17]:samples/python/17.multilingual-bot
[py#18]:samples/python/18.bot-authentication
[py#19]:samples/python/19.custom-dialogs
[py#23]:samples/python/23.facebook-events
[py#24]:samples/python/24.bot-authentication-msgraph
[py#40]:samples/python/40.timex-resolution
[py#42]:samples/python/42.scaleout
[py#43]:samples/python/43.complex-dialog
[py#44]:samples/python/44.prompt-for-user-input
[py#45]:samples/python/45.state-management
[py#47]:samples/python/47.inspection
[py#60]:samples/python/60.slack-adapter
[py#80]:samples/python/80.skills-simple-bot-to-bot
[py#81]:samples/python/81.skills-skilldialog

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.
This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Reporting security issues

Security issues and bugs should be reported privately, via email, to the Microsoft Security Response Center (MSRC) at [secure@microsoft.com](mailto:secure@microsoft.com). You should receive a response within 24 hours. If for some reason you do not, please follow up via email to ensure we received your original message. Further information, including the [MSRC PGP](https://technet.microsoft.com/en-us/security/dn606155) key, can be found in the [Security TechCenter](https://technet.microsoft.com/en-us/security/default).

Copyright (c) Microsoft Corporation. All rights reserved.
