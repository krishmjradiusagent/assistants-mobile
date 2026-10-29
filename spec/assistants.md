# Assistants mobile

Mel chat on mobile: intro, sign-up, CRM, Marketing, Campaign and Client Experience skills, plus SMS, email and WhatsApp channel flows. Light and dark.

Screens: 483. Each screen has a static HTML page (`/screens/assistants/<File>.html`), a PNG (`/screens/assistants/png/<File>.png`) and its raw design source (`/source/assistants/<File>.dc.html`).
Tokens and components: see `/design-system/README.md`. Copy shown is real UI copy unless it says placeholder.

## Onboarding

Designer notes:

- **Mel welcome: dark and light**
- **Sign up with phone number**
- **Connectors**

### Welcome, dark
`Main` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/Main.html) · [PNG](/screens/assistants/png/Main.png)

```text
MEL

Your AI assistant for real estate.

Manage clients

CRM. Import contacts, update records, follow up.

Create marketing

Marketing. Posts, flyers, email, yard signs.

Explore listings

MLS. Search homes, pull comps.

Check compliance

Compliance. Flag what a file is missing.

Review documents

Document. Summarise, prepare for signing.

Built for agents & teams

10K

free credits

Try MEL for free
Sign in
```

Accessible labels: Mel; What MEL can do; Chat, text, WhatsApp, email

### Welcome, light
`Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/Light.html) · [PNG](/screens/assistants/png/Light.png)

```text
MEL

Your AI assistant for real estate.

Manage clients

CRM. Import contacts, update records, follow up.

Create marketing

Marketing. Posts, flyers, email, yard signs.

Explore listings

MLS. Search homes, pull comps.

Check compliance

Compliance. Flag what a file is missing.

Review documents

Document. Summarise, prepare for signing.

Built for agents & teams

10K

free credits

Try MEL for free
Sign in
```

Accessible labels: Mel; What MEL can do; Chat, text, WhatsApp, email

### Sign up phone, dark
`SignupPhoneDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/SignupPhoneDark.html) · [PNG](/screens/assistants/png/SignupPhoneDark.png)

```text
MEL

Your AI assistant for real estate.

Manage clients

CRM. Import contacts, update records, follow up.

Create marketing

Marketing. Posts, flyers, email, yard signs.

Explore listings

MLS. Search homes, pull comps.

Check compliance

Compliance. Flag what a file is missing.

Review documents

Document. Summarise, prepare for signing.

Built for agents & teams

10K

free credits

Try MEL for free
Sign in
Sign up
Enter your phone number
Phone number (+1)
Send code
```

Accessible labels: Mel; What MEL can do; Chat, text, WhatsApp, email; Close

### Sign up phone, light
`SignupPhoneLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/SignupPhoneLight.html) · [PNG](/screens/assistants/png/SignupPhoneLight.png)

Same content as `SignupPhone` in the other theme.

### Sign up code, dark
`SignupCodeDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/SignupCodeDark.html) · [PNG](/screens/assistants/png/SignupCodeDark.png)

```text
MEL

Your AI assistant for real estate.

Manage clients

CRM. Import contacts, update records, follow up.

Create marketing

Marketing. Posts, flyers, email, yard signs.

Explore listings

MLS. Search homes, pull comps.

Check compliance

Compliance. Flag what a file is missing.

Review documents

Document. Summarise, prepare for signing.

Built for agents & teams

10K

free credits

Try MEL for free
Sign in
Verify your number
Enter the code sent to +1 5550100123.
4-digit code
Verify number
Change number
```

Accessible labels: Mel; What MEL can do; Chat, text, WhatsApp, email; Close; Digit 1 of 4; Digit 2 of 4; Digit 3 of 4; Digit 4 of 4

### Sign up code, light
`SignupCodeLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/SignupCodeLight.html) · [PNG](/screens/assistants/png/SignupCodeLight.png)

Same content as `SignupCode` in the other theme.

### Connectors, dark
`ConnectorsDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/ConnectorsDark.html) · [PNG](/screens/assistants/png/ConnectorsDark.png)

```text
Your MEL, one message away
Let’s stay connected

Message me wherever you prefer.

Chat with MEL
In the app
Text MEL
+1 (202) 555-0147
WhatsApp
+1 (202) 555-0147
Email MEL
hello@mel.example
Connect your tools

Connect now, or do it later.

Gmail
Email
Connect
Google Calendar
Calendar
Connect
Follow Up Boss
CRM
Connect
Facebook
Marketing
Connect
Instagram
Marketing
Connect
ChatGPT
AI
Connect
Browse all connectors
```

Accessible labels: Mel; Chat with MEL; Text MEL; Copy Text MEL number; WhatsApp; Copy WhatsApp number; Email MEL; Copy Email MEL address; Connect Gmail; Connect Google Calendar; Connect Follow Up Boss; Connect Facebook; Connect Instagram; Connect ChatGPT

### Connectors, light
`ConnectorsLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/ConnectorsLight.html) · [PNG](/screens/assistants/png/ConnectorsLight.png)

Same content as `Connectors` in the other theme.

## Mel chat

Designer notes:

- **Main chat, all skills**
- **In-app chat, dark, end to end**
- First chat after connectors. Mel speaks first: intro, what it can do, one question. Left to right = what happens next. In-app: cards fill the box, suggestions send. Other paths: text only, agent replies a number. Priority when several states are true: 1 > 2 > 3.
- Other starts. States 1 and 2: Mel leads with what it found. Agent says yes. Rest of the flow continues as on the left.
- **In-app chat, light, end to end**
- Other starts. States 1 and 2: Mel leads with what it found. Agent says yes. Rest of the flow continues as on the left.
- **WhatsApp, end to end**
- Other starts. States 1 and 2: Mel leads with what it found. Agent says yes. Rest of the flow continues as on the left.
- **Messages, end to end**
- Other starts. States 1 and 2: Mel leads with what it found. Agent says yes. Rest of the flow continues as on the left.
- **Email, end to end**
- Other starts. States 1 and 2: Mel leads with what it found. Agent says yes. Rest of the flow continues as on the left.

### Chat live, dark
`ChatLiveDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/ChatLiveDark.html) · [PNG](/screens/assistants/png/ChatLiveDark.png)

```text
Hey, I’m MEL, your AI assistant. I can:

Add and manage your clients
Market a listing
Run follow-up campaigns
Keep clients updated
Check transaction files
Prepare documents

Which one do you want to start with? Reply a number or just tell me.

K
Mel
```

Accessible labels: MEL message; What MEL can do; Mel; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Main; Dashboard; Clients; Transactions; Inbox

### Chat live, light
`ChatLiveLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/ChatLiveLight.html) · [PNG](/screens/assistants/png/ChatLiveLight.png)

Same content as `ChatLive` in the other theme.

### Chat, skill routes itself, dark
`ChatAutoRouteDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/ChatAutoRouteDark.html) · [PNG](/screens/assistants/png/ChatAutoRouteDark.png)

```text
Hi, I’m MEL, your real estate assistant. I can help with your listings, clients and everyday tasks. What would you like to work on first?

Manage clients

Let’s bring your contacts together so I can help you manage relationships and follow-ups.

How would you like to add your contacts?

Make a post for 124 Oak Street

I create the full marketing package for a listing: posts, reels, flyers, email, website and yard sign.

Which listing do you want to market?

Market my newest listing
Pick from my active listings
K
Mel
```

Accessible labels: MEL message; Your message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Chat, skill routes itself, light
`ChatAutoRouteLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/ChatAutoRouteLight.html) · [PNG](/screens/assistants/png/ChatAutoRouteLight.png)

Same content as `ChatAutoRoute` in the other theme.

### Chat, switches to Marketing, dark
`ChatSwitchDark` · 390×844 · [HTML](/screens/assistants/ChatSwitchDark.html) · [PNG](/screens/assistants/png/ChatSwitchDark.png)

```text
Your listing at 124 Oak Street went live today. I can create its marketing package: posts, reels, flyers, email, website and yard sign.

Want me to start?

Not now. Help me manage my clients first

Let’s bring your contacts together so I can help you manage relationships and follow-ups.

How would you like to add your contacts?

Upload a CSV
Import from another CRM
I’ll add contacts later
K
Mel
```

Accessible labels: MEL message; Your message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Chat, switches to Marketing, light
`ChatSwitchLight` · 390×844 · [HTML](/screens/assistants/ChatSwitchLight.html) · [PNG](/screens/assistants/png/ChatSwitchLight.png)

Same content as `ChatSwitch` in the other theme.

### 1 Intro, state 3, dark
`IntroAppADark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/IntroAppADark.html) · [PNG](/screens/assistants/png/IntroAppADark.png)

```text
Hey, I’m MEL, your AI assistant. I can:

Add and manage your clients
Market a listing
Run follow-up campaigns
Keep clients updated
Check transaction files
Prepare documents

Which one do you want to start with? Reply a number or just tell me.

K
Mel
```

Accessible labels: MEL message; What MEL can do; Mel; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Main; Dashboard; Clients; Transactions; Inbox

### 2 Card tapped, box filled, dark
`FlowAppDarkS1` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/FlowAppDarkS1.html) · [PNG](/screens/assistants/png/FlowAppDarkS1.png)

```text
Hey, I’m MEL, your AI assistant. I can:

Add and manage your clients
Market a listing
Run follow-up campaigns
Keep clients updated
Check transaction files
Prepare documents

Which one do you want to start with? Reply a number or just tell me.

K
Mel
```

Accessible labels: MEL message; What MEL can do; Mel; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Main; Dashboard; Clients; Transactions; Inbox

### 3 Sent, Mel working, dark
`FlowAppDarkS2` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/FlowAppDarkS2.html) · [PNG](/screens/assistants/png/FlowAppDarkS2.png)

```text
Add and manage your clients

Checking your CRM
Checked your CRM · 0 contacts
K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 4 Mel reply, trace, suggestions, dark
`FlowAppDarkS3` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/FlowAppDarkS3.html) · [PNG](/screens/assistants/png/FlowAppDarkS3.png)

```text
Add and manage your clients

Checked 2 things

Let’s bring your contacts together so I can help you manage relationships and follow-ups.

How would you like to add your contacts?

Upload a CSV
Import from another CRM
I’ll add contacts later
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 5 Suggestion tapped, sent, dark
`FlowAppDarkS4` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/FlowAppDarkS4.html) · [PNG](/screens/assistants/png/FlowAppDarkS4.png)

```text
Upload a CSV

Thinking…

K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 6 Mel next step, dark
`FlowAppDarkS5` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/FlowAppDarkS5.html) · [PNG](/screens/assistants/png/FlowAppDarkS5.png)

```text
Upload a CSV

Attach your contacts file here. Any CSV works, I read the columns myself.

K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### State 1 intro, listing live, dark
`IntroAppCDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/IntroAppCDark.html) · [PNG](/screens/assistants/png/IntroAppCDark.png)

```text
Hey, I’m MEL, your AI assistant. I can:

Add and manage your clients
Market a listing
Run follow-up campaigns
Keep clients updated
Check transaction files
Prepare documents

Your listing at 124 Oak Street went live today. Want me to build its marketing package? Or pick a number.

K
Mel
```

Accessible labels: MEL message; What MEL can do; Mel; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Main; Dashboard; Clients; Transactions; Inbox

### State 1, yes, Mel reply, dark
`BranchApp1DarkR` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/BranchApp1DarkR.html) · [PNG](/screens/assistants/png/BranchApp1DarkR.png)

```text
Yes

Checked 2 things

I create the full marketing package for a listing: posts, reels, flyers, email, website and yard sign.

Which listing do you want to market?

Market my newest listing
Pick from my active listings
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 1 Intro, state 3, light
`IntroAppALight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/IntroAppALight.html) · [PNG](/screens/assistants/png/IntroAppALight.png)

Same content as `IntroAppA` in the other theme.

### 2 Card tapped, box filled, light
`FlowAppLightS1` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/FlowAppLightS1.html) · [PNG](/screens/assistants/png/FlowAppLightS1.png)

Same content as `FlowAppS1` in the other theme.

### 3 Sent, Mel working, light
`FlowAppLightS2` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/FlowAppLightS2.html) · [PNG](/screens/assistants/png/FlowAppLightS2.png)

Same content as `FlowAppS2` in the other theme.

### 4 Mel reply, trace, suggestions, light
`FlowAppLightS3` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/FlowAppLightS3.html) · [PNG](/screens/assistants/png/FlowAppLightS3.png)

Same content as `FlowAppS3` in the other theme.

### 5 Suggestion tapped, sent, light
`FlowAppLightS4` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/FlowAppLightS4.html) · [PNG](/screens/assistants/png/FlowAppLightS4.png)

Same content as `FlowAppS4` in the other theme.

### 6 Mel next step, light
`FlowAppLightS5` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/FlowAppLightS5.html) · [PNG](/screens/assistants/png/FlowAppLightS5.png)

Same content as `FlowAppS5` in the other theme.

### State 1 intro, listing live, light
`IntroAppCLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/IntroAppCLight.html) · [PNG](/screens/assistants/png/IntroAppCLight.png)

Same content as `IntroAppC` in the other theme.

### State 1, yes, Mel reply, light
`BranchApp1LightR` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/BranchApp1LightR.html) · [PNG](/screens/assistants/png/BranchApp1LightR.png)

Same content as `BranchApp1R` in the other theme.

### 1 Intro, state 3
`IntroWaA` · 390×844 · [HTML](/screens/assistants/IntroWaA.html) · [PNG](/screens/assistants/png/IntroWaA.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Which one do you want to start with? Reply a number or just tell me.

10:02
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 2 Agent replies 1
`FlowWaS1` · 390×844 · [HTML](/screens/assistants/FlowWaS1.html) · [PNG](/screens/assistants/png/FlowWaS1.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Which one do you want to start with? Reply a number or just tell me.

10:02

1

10:03
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 3 Mel says it is working
`FlowWaS2` · 390×844 · [HTML](/screens/assistants/FlowWaS2.html) · [PNG](/screens/assistants/png/FlowWaS2.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Which one do you want to start with? Reply a number or just tell me.

10:02

1

10:03

On it. Checking your CRM.

10:03
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 4 Mel reply, numbered options
`FlowWaS3` · 390×844 · [HTML](/screens/assistants/FlowWaS3.html) · [PNG](/screens/assistants/png/FlowWaS3.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Which one do you want to start with? Reply a number or just tell me.

10:02

1

10:03

On it. Checking your CRM.

10:03

Let’s bring your contacts together so I can help you manage relationships and follow-ups.
How would you like to add your contacts?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### State 1 intro, listing live
`BranchWa1` · 390×844 · [HTML](/screens/assistants/BranchWa1.html) · [PNG](/screens/assistants/png/BranchWa1.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Your listing at 124 Oak Street went live today. Want me to build its marketing package? Or pick a number.

10:02
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### State 1, yes, Mel reply
`BranchWa1R` · 390×844 · [HTML](/screens/assistants/BranchWa1R.html) · [PNG](/screens/assistants/png/BranchWa1R.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Your listing at 124 Oak Street went live today. Want me to build its marketing package? Or pick a number.

10:02

Yes

10:03

On it. Pulling 124 Oak Street from the MLS.

10:03

Starting the package for 124 Oak Street: posts, reels, flyers, email, website and yard sign.
Pick a style first.
1 Modern
2 Classic
3 Bold

10:03
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### State 2 intro, CRM empty
`BranchWa2` · 390×844 · [HTML](/screens/assistants/BranchWa2.html) · [PNG](/screens/assistants/png/BranchWa2.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### State 2, yes, Mel reply
`BranchWa2R` · 390×844 · [HTML](/screens/assistants/BranchWa2R.html) · [PNG](/screens/assistants/png/BranchWa2R.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Let’s bring your contacts together so I can help you manage relationships and follow-ups.
How would you like to add your contacts?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 1 Intro, state 3
`IntroSmsA` · 390×844 · [HTML](/screens/assistants/IntroSmsA.html) · [PNG](/screens/assistants/png/IntroSmsA.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Which one do you want to start with? Reply a number or just tell me.

Delivered
Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 2 Agent replies 1
`FlowSmsS1` · 390×844 · [HTML](/screens/assistants/FlowSmsS1.html) · [PNG](/screens/assistants/png/FlowSmsS1.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Which one do you want to start with? Reply a number or just tell me.

1

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 3 Mel says it is working
`FlowSmsS2` · 390×844 · [HTML](/screens/assistants/FlowSmsS2.html) · [PNG](/screens/assistants/png/FlowSmsS2.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Which one do you want to start with? Reply a number or just tell me.

1

On it. Checking your CRM.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 4 Mel reply, numbered options
`FlowSmsS3` · 390×844 · [HTML](/screens/assistants/FlowSmsS3.html) · [PNG](/screens/assistants/png/FlowSmsS3.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Which one do you want to start with? Reply a number or just tell me.

1

On it. Checking your CRM.

Let’s bring your contacts together so I can help you manage relationships and follow-ups.
How would you like to add your contacts?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### State 1 intro, listing live
`BranchSms1` · 390×844 · [HTML](/screens/assistants/BranchSms1.html) · [PNG](/screens/assistants/png/BranchSms1.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Your listing at 124 Oak Street went live today. Want me to build its marketing package? Or pick a number.

Delivered
Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### State 1, yes, Mel reply
`BranchSms1R` · 390×844 · [HTML](/screens/assistants/BranchSms1R.html) · [PNG](/screens/assistants/png/BranchSms1R.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Your listing at 124 Oak Street went live today. Want me to build its marketing package? Or pick a number.

Yes

On it. Pulling 124 Oak Street from the MLS.

Starting the package for 124 Oak Street: posts, reels, flyers, email, website and yard sign.
Pick a style first.
1 Modern
2 Classic
3 Bold

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### State 2 intro, CRM empty
`BranchSms2` · 390×844 · [HTML](/screens/assistants/BranchSms2.html) · [PNG](/screens/assistants/png/BranchSms2.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Delivered
Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### State 2, yes, Mel reply
`BranchSms2R` · 390×844 · [HTML](/screens/assistants/BranchSms2R.html) · [PNG](/screens/assistants/png/BranchSms2R.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Let’s bring your contacts together so I can help you manage relationships and follow-ups.
How would you like to add your contacts?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 1 Intro, state 3
`IntroMailA` · 390×844 · [HTML](/screens/assistants/IntroMailA.html) · [PNG](/screens/assistants/png/IntroMailA.png)

```text
Hey from MEL
MEL
to me
10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Which one do you want to start with? Reply a number or just tell me.

MEL

Reply
Forward
```

Accessible labels: Back; Archive; More; MEL

### 2 Agent replies 1
`FlowMailS1` · 390×844 · [HTML](/screens/assistants/FlowMailS1.html) · [PNG](/screens/assistants/png/FlowMailS1.png)

```text
Hey from MEL
MEL
to me
10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Which one do you want to start with? Reply a number or just tell me.

MEL

J
me
to MEL
10:03 AM

1

Reply
Forward
```

Accessible labels: Back; Archive; More; MEL

### 3 Mel says it is working
`FlowMailS2` · 390×844 · [HTML](/screens/assistants/FlowMailS2.html) · [PNG](/screens/assistants/png/FlowMailS2.png)

```text
Hey from MEL
MEL
to me
10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Which one do you want to start with? Reply a number or just tell me.

MEL

J
me
to MEL
10:03 AM

1

MEL
to me
10:03 AM

On it. Checking your CRM.

MEL

Reply
Forward
```

Accessible labels: Back; Archive; More; MEL

### 4 Mel reply, numbered options
`FlowMailS3` · 390×844 · [HTML](/screens/assistants/FlowMailS3.html) · [PNG](/screens/assistants/png/FlowMailS3.png)

```text
Hey from MEL
MEL
to me
10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Which one do you want to start with? Reply a number or just tell me.

MEL

J
me
to MEL
10:03 AM

1

MEL
to me
10:04 AM

On it. Checking your CRM.

Let’s bring your contacts together so I can help you manage relationships and follow-ups.
How would you like to add your contacts?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

MEL

Reply
Forward
```

Accessible labels: Back; Archive; More; MEL

### State 1 intro, listing live
`BranchMail1` · 390×844 · [HTML](/screens/assistants/BranchMail1.html) · [PNG](/screens/assistants/png/BranchMail1.png)

```text
Hey from MEL
MEL
to me
10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Your listing at 124 Oak Street went live today. Want me to build its marketing package? Or pick a number.

MEL

Reply
Forward
```

Accessible labels: Back; Archive; More; MEL

### State 1, yes, Mel reply
`BranchMail1R` · 390×844 · [HTML](/screens/assistants/BranchMail1R.html) · [PNG](/screens/assistants/png/BranchMail1R.png)

```text
Hey from MEL
MEL
to me
10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Your listing at 124 Oak Street went live today. Want me to build its marketing package? Or pick a number.

MEL

J
me
to MEL
10:03 AM

Yes

MEL
to me
10:04 AM

On it. Pulling 124 Oak Street from the MLS.

Starting the package for 124 Oak Street: posts, reels, flyers, email, website and yard sign.
Pick a style first.
1 Modern
2 Classic
3 Bold

MEL

Reply
Forward
```

Accessible labels: Back; Archive; More; MEL

### State 2 intro, CRM empty
`BranchMail2` · 390×844 · [HTML](/screens/assistants/BranchMail2.html) · [PNG](/screens/assistants/png/BranchMail2.png)

```text
Hey from MEL
MEL
to me
10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

MEL

Reply
Forward
```

Accessible labels: Back; Archive; More; MEL

### State 2, yes, Mel reply
`BranchMail2R` · 390×844 · [HTML](/screens/assistants/BranchMail2R.html) · [PNG](/screens/assistants/png/BranchMail2R.png)

```text
Hey from MEL
MEL
to me
10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

MEL

J
me
to MEL
10:03 AM

Yes

MEL
to me
10:04 AM

On it. Checking your CRM.

Let’s bring your contacts together so I can help you manage relationships and follow-ups.
How would you like to add your contacts?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

MEL

Reply
Forward
```

Accessible labels: Back; Archive; More; MEL

## Home screen

Designer notes:

- **Home screen · port of Implemented Home, Mel brand mark**
- Copy not from Biju: "Ask Mel" placeholder in the search bar. Floating orb hidden, bar replaces it (Rec, pending KJ).

### Home, dark
`HomeDark` · 390×844 · [HTML](/screens/assistants/HomeDark.html) · [PNG](/screens/assistants/png/HomeDark.png)

```text
K
Krish
krish@radiusagent.com
Profile
Collaborators
Talk to us
Billings & AI credits
Settings
Radius Office
9:41
K
Dashboard
Search properties
Mel suggests
Follow up with Sarah Reynolds
No reply in 5 days
Sign 412 Marina Blvd envelope
Listing agreement · S. Reynolds
Check in with Grace Lee
No contact in 11 days
Market 124 Oak Street
Listing went live today
Update David Muñoz on closing
Closing moved to Sep 3
Priority clients
SR
Sarah Reynolds
DM
David Muñoz
AP
Anita Patel
GL
Grace Lee
MM
Mason Martinez
View all10
Active transactions
118 Maple St, Fremont, CA
$1,150,000
Buyer
In escrow
Close Sep 12
42 Oak Ln, Fremont, CA
$980,000
Seller
Inspection due
Offer review
All transactions6
Commissions
118 Maple St
Closes Sep 12
Review
42 Oak Ln
Closes Sep 15
Team lead pending
640 Alma St
Closes Sep 20
Group lead pending
All commissions3
Appointments
11:00 AM
in 48m
Listing consultation
CB
Carla Boyd
·
640 Alma St
2:30 PM
·
Buyer tour — three homes
DR
Daniel Ruiz
·
275 Miramar Ave
4:00 PM
Lender call — pre-approval
PN
Priya Nair
·
Virtual
All appointments
Tasks
Grace Lee has not heard from you in 11 days — send a market update
GL
Grace Lee
·
Send the disclosure packet to Anita Patel
AP
Anita Patel
Review the Muñoz inspection report
42 Oak Ln
·
Fremont
Overdue
Confirm Saturday tour with Mason Martinez
MM
Three homes
·
10:00 AM
Order photography for 640 Alma St
CB
Carla Boyd
Upcoming tasks3
Documents to sign
Due today
Sign
118 Maple St
SR
Sarah Reynolds
Overdue
Sign
42 Oak Ln
DM
David Muñoz
Tomorrow
Sign
No property linked
AP
Anita Patel
All documents
Campaigns
Spring sellers — Inland Empire
Needs review
·
1,532 contacts
6.3%
reply rate
Referral ask after closing
Needs review
·
268 contacts
15.3%
reply rate
Follow up to initial contact
1,378 contacts
4.6%
reply rate
Bel Air Crest — off-market listing
318 contacts
3.5%
reply rate
All campaigns2 to resolve
Shortcuts
Ask Mel anything…
Listening…
Mel
Today
Where did the Reynolds file get stuck?
The 412 Marina Blvd envelope is waiting on your signature since Monday. Nothing else is blocking closing.
Open envelope
Draft follow-up
Show timeline
Message Mel…
SR
Sarah Reynolds
View full profile
```

Accessible labels: Profile; Notifications, new; Search properties; CRM: Follow up with Sarah Reynolds; Documents: Sign 412 Marina Blvd envelope; Campaigns: Check in with Grace Lee; Marketing: Market 124 Oak Street; Client experience: Update David Muñoz on closing; Hide Priority clients; Reorder Priority clients — use arrow keys; New updates; View all 10 priority clients; Hide Active transactions; Reorder Active transactions — use arrow keys; All 6 active transactions; Hide Commissions; Reorder Commissions — use arrow keys; 118 Maple St, closes September 12, review and approve commission; 42 Oak Lane, closes September 15, team lead pending; 640 Alma Street, closes September 20, group lead pending; All commissions, 3 need attention; Hide Appointments; Reorder Appointments — use arrow keys; Mel; All appointments; Hide Tasks; Reorder Tasks — use arrow keys; Mark task complete; View upcoming tasks; Hide Documents to sign; Reorder Documents to sign — use arrow keys; Sign document; All documents; Hide Campaigns; Reorder Campaigns — use arrow keys; Campaign. Spring sellers — Inland Empire. Needs review. 6.3% reply rate. 1,532 contacts.; Campaign rule; Campaign. Referral ask after closing. Needs review. 15.3% reply rate. 268 contacts.; Campaign. Follow up to initial contact. 4.6% reply rate. 1,378 contacts.; Send once. Bel Air Crest — off-market listing. 3.5% reply rate. 318 contacts.

### Home, light
`HomeLight` · 390×844 · [HTML](/screens/assistants/HomeLight.html) · [PNG](/screens/assistants/png/HomeLight.png)

Same content as `Home` in the other theme.

## CRM skill flow

Designer notes:

- **CRM skill, in-app dark, end to end**
- Moved to Mel CRM, page In-app → https://claude.ai/artifact/Wk8cmkeWjAkkksCkch2u8q
- CRM happy path from the State 2 intro. Agent says yes, uploads a CSV, imports, gets the 6 prompts. Copy from the CRM page (Biju). Traces, working lines and the View my contacts link are new.
- **CRM skill, in-app light, end to end**
- **CRM prompt: Find Jordan Lee, in-app dark**
- The 6 prompts Mel offers after import, each end to end. Every row starts from CRM board 13. Copy and cards from the CRM page (Biju). Traces and the shorter draft are new.
- **CRM prompt: Find Jordan Lee, in-app light**
- **CRM prompt: Update preferences, in-app dark**
- **CRM prompt: Update preferences, in-app light**
- **CRM prompt: Draft a message, in-app dark**
- **CRM prompt: Draft a message, in-app light**
- **CRM prompt: Remind me Tuesday, in-app dark**
- **CRM prompt: Remind me Tuesday, in-app light**
- **CRM prompt: Check-in campaign, in-app dark**
- **CRM prompt: Check-in campaign, in-app light**
- **CRM prompt: Top buyers, in-app dark**
- **CRM prompt: Top buyers, in-app light**
- **CRM skill, WhatsApp, end to end**
- Moved to Mel CRM, page WhatsApp → https://claude.ai/artifact/Wk8cmkeWjAkkksCkch2u8q
- CRM on WhatsApp, text only. Same flow and words as in-app. Options are numbered, the agent replies a number or words. Mel says it is working, then answers. Cards become lines. Links are URLs.
- **CRM prompt: Find Jordan Lee, WhatsApp**
- **CRM prompt: Update preferences, WhatsApp**
- **CRM prompt: Draft a message, WhatsApp**
- **CRM prompt: Remind me Tuesday, WhatsApp**
- **CRM prompt: Check-in campaign, WhatsApp**
- **CRM prompt: Top buyers, WhatsApp**
- **CRM skill, Messages, end to end**
- Moved to Mel CRM, page Messages → https://claude.ai/artifact/Wk8cmkeWjAkkksCkch2u8q
- CRM on Messages (SMS), text only. Same flow and words as WhatsApp. Texts can’t carry a CSV, so Mel texts a link to a branded uploader (boards 7 to 9), then picks up in Messages.
- OPEN FOR KJ
  
  Not Biju copy:
  Board 6, the upload link line.
  Boards 7 to 9, all uploader copy (title, intro, button, helper lines).
  Board 10, Mel reads the file after upload.
  
  Uploader link radiusagent.com/u/7Q4K is a placeholder.
  
  Import row is 16 boards: the CSV document bubble from WhatsApp is replaced by the uploader.
- **CRM prompt: Find Jordan Lee, Messages**
- **CRM prompt: Update preferences, Messages**
- **CRM prompt: Draft a message, Messages**
- **CRM prompt: Remind me Tuesday, Messages**
- **CRM prompt: Check-in campaign, Messages**
- **CRM prompt: Top buyers, Messages**
- Email path → Mel CRM, page Email → https://claude.ai/artifact/Wk8cmkeWjAkkksCkch2u8q

### 1 Intro, state 2, dark
`CrmFlowDarkS01` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowDarkS01.html) · [PNG](/screens/assistants/png/CrmFlowDarkS01.png)

```text
Hey, I’m MEL, your AI assistant. I can:

Add and manage your clients
Market a listing
Run follow-up campaigns
Keep clients updated
Check transaction files
Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

K
Mel
```

Accessible labels: MEL message; What MEL can do; Mel; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Main; Dashboard; Clients; Transactions; Inbox

### 2 Agent types Yes, dark
`CrmFlowDarkS02` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowDarkS02.html) · [PNG](/screens/assistants/png/CrmFlowDarkS02.png)

```text
Hey, I’m MEL, your AI assistant. I can:

Add and manage your clients
Market a listing
Run follow-up campaigns
Keep clients updated
Check transaction files
Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

K
Mel
```

Accessible labels: MEL message; What MEL can do; Mel; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Main; Dashboard; Clients; Transactions; Inbox

### 3 Sent, Mel working, dark
`CrmFlowDarkS03` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowDarkS03.html) · [PNG](/screens/assistants/png/CrmFlowDarkS03.png)

```text
Yes

Checking your CRM
Checked your CRM · 0 contacts
K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 4 CRM assistant, how to add contacts, dark
`CrmFlowDarkS04` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowDarkS04.html) · [PNG](/screens/assistants/png/CrmFlowDarkS04.png)

```text
Yes

Checked 2 things

I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.

How do you want to add them?

Upload a CSV
Import from another CRM
I’ll add contacts later
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 5 Upload a CSV sent, dark
`CrmFlowDarkS05` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowDarkS05.html) · [PNG](/screens/assistants/png/CrmFlowDarkS05.png)

```text
Upload a CSV

Thinking…

K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 6 Mel asks for the file, dark
`CrmFlowDarkS06` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowDarkS06.html) · [PNG](/screens/assistants/png/CrmFlowDarkS06.png)

```text
Upload a CSV

Attach your CSV. Any column layout works. I match the fields for you.

K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 7 File attached, sent, dark
`CrmFlowDarkS07` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowDarkS07.html) · [PNG](/screens/assistants/png/CrmFlowDarkS07.png)

```text
clients-export.csv

CSV · 1,280 rows

K
Mel
```

Accessible labels: Your file; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 8 Reading the file, dark
`CrmFlowDarkS08` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowDarkS08.html) · [PNG](/screens/assistants/png/CrmFlowDarkS08.png)

```text
clients-export.csv

CSV · 1,280 rows

Reading clients-export.csv
Read 1,280 rows
K
Mel
```

Accessible labels: Your file; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 9 Found 1,280, duplicates question, dark
`CrmFlowDarkS09` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowDarkS09.html) · [PNG](/screens/assistants/png/CrmFlowDarkS09.png)

```text
clients-export.csv

CSV · 1,280 rows

Read the file in 2 steps

I found 1,280 contacts and matched name, phone, email, address, client type and notes.

32 are duplicates. Import 1,248 and skip them?

Import and skip duplicates
Show me the duplicates
K
Mel
```

Accessible labels: Your file; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 10 Import sent, importing, dark
`CrmFlowDarkS10` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowDarkS10.html) · [PNG](/screens/assistants/png/CrmFlowDarkS10.png)

```text
Import and skip duplicates

Importing 1,248 contacts
Skipped 32 duplicates
K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 11 Imported, result card, View my contacts, dark
`CrmFlowDarkS11` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowDarkS11.html) · [PNG](/screens/assistants/png/CrmFlowDarkS11.png)

```text
Import and skip duplicates

Imported in 2 steps

Done. Here is what came in.

1,248

Imported

836

Buyers

412

Sellers

32

Duplicates skipped

12 need review · missing phone or email
View my contacts
1,248 in Radius CRM
Review the 12 contacts
What can you do with them?
K
Mel
```

Accessible labels: Your message; MEL message; Import result; View my contacts in Radius CRM; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 12 What can you do, sent, dark
`CrmFlowDarkS12` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowDarkS12.html) · [PNG](/screens/assistants/png/CrmFlowDarkS12.png)

```text
What can you do with them?

Thinking…

K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 13 Mel offers 6 prompts, dark
`CrmFlowDarkS13` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowDarkS13.html) · [PNG](/screens/assistants/png/CrmFlowDarkS13.png)

```text
What can you do with them?

Try one of these, or ask in your own words.

Find Jordan Lee
Update Jordan’s preferences to 3 beds
Draft a message to Jordan
Remind me to call Jordan on Tuesday
Start a check-in campaign for inactive clients
Show my top buyers this month
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 1 Intro, state 2, light
`CrmFlowLightS01` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowLightS01.html) · [PNG](/screens/assistants/png/CrmFlowLightS01.png)

Same content as `CrmFlowS01` in the other theme.

### 2 Agent types Yes, light
`CrmFlowLightS02` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowLightS02.html) · [PNG](/screens/assistants/png/CrmFlowLightS02.png)

Same content as `CrmFlowS02` in the other theme.

### 3 Sent, Mel working, light
`CrmFlowLightS03` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowLightS03.html) · [PNG](/screens/assistants/png/CrmFlowLightS03.png)

Same content as `CrmFlowS03` in the other theme.

### 4 CRM assistant, how to add contacts, light
`CrmFlowLightS04` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowLightS04.html) · [PNG](/screens/assistants/png/CrmFlowLightS04.png)

Same content as `CrmFlowS04` in the other theme.

### 5 Upload a CSV sent, light
`CrmFlowLightS05` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowLightS05.html) · [PNG](/screens/assistants/png/CrmFlowLightS05.png)

Same content as `CrmFlowS05` in the other theme.

### 6 Mel asks for the file, light
`CrmFlowLightS06` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowLightS06.html) · [PNG](/screens/assistants/png/CrmFlowLightS06.png)

Same content as `CrmFlowS06` in the other theme.

### 7 File attached, sent, light
`CrmFlowLightS07` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowLightS07.html) · [PNG](/screens/assistants/png/CrmFlowLightS07.png)

Same content as `CrmFlowS07` in the other theme.

### 8 Reading the file, light
`CrmFlowLightS08` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowLightS08.html) · [PNG](/screens/assistants/png/CrmFlowLightS08.png)

Same content as `CrmFlowS08` in the other theme.

### 9 Found 1,280, duplicates question, light
`CrmFlowLightS09` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowLightS09.html) · [PNG](/screens/assistants/png/CrmFlowLightS09.png)

Same content as `CrmFlowS09` in the other theme.

### 10 Import sent, importing, light
`CrmFlowLightS10` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowLightS10.html) · [PNG](/screens/assistants/png/CrmFlowLightS10.png)

Same content as `CrmFlowS10` in the other theme.

### 11 Imported, result card, View my contacts, light
`CrmFlowLightS11` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowLightS11.html) · [PNG](/screens/assistants/png/CrmFlowLightS11.png)

Same content as `CrmFlowS11` in the other theme.

### 12 What can you do, sent, light
`CrmFlowLightS12` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowLightS12.html) · [PNG](/screens/assistants/png/CrmFlowLightS12.png)

Same content as `CrmFlowS12` in the other theme.

### 13 Mel offers 6 prompts, light
`CrmFlowLightS13` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowLightS13.html) · [PNG](/screens/assistants/png/CrmFlowLightS13.png)

Same content as `CrmFlowS13` in the other theme.

### 1 Sent, searching, dark
`CrmP1DarkS1` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP1DarkS1.html) · [PNG](/screens/assistants/png/CrmP1DarkS1.png)

```text
Find Jordan Lee

Searching your CRM
Found Jordan Lee · Buyer · Active
K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 2 Contact card, dark
`CrmP1DarkS2` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP1DarkS2.html) · [PNG](/screens/assistants/png/CrmP1DarkS2.png)

```text
Find Jordan Lee

Searched in 1 step

Here is Jordan.

JL
Jordan Lee
Buyer · Active
Phone
(555) 014 2290
Email
jordan.lee@gmail.com
Looking for
3 beds · Oak Street · under [PRICE]
Last contact
12 days ago · text
Open Jordan in CRM
Notes, activity and family
Draft a message to Jordan
Remind me to call Jordan on Tuesday
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 3 Draft a message sent, dark
`CrmP1DarkS3` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP1DarkS3.html) · [PNG](/screens/assistants/png/CrmP1DarkS3.png)

```text
Draft a message to Jordan

Reading Jordan’s activity
Read Jordan Lee · 6 listing views, replied today
K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 1 Sent, searching, light
`CrmP1LightS1` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP1LightS1.html) · [PNG](/screens/assistants/png/CrmP1LightS1.png)

Same content as `CrmP1S1` in the other theme.

### 2 Contact card, light
`CrmP1LightS2` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP1LightS2.html) · [PNG](/screens/assistants/png/CrmP1LightS2.png)

Same content as `CrmP1S2` in the other theme.

### 3 Draft a message sent, light
`CrmP1LightS3` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP1LightS3.html) · [PNG](/screens/assistants/png/CrmP1LightS3.png)

Same content as `CrmP1S3` in the other theme.

### 1 Sent, reading record, dark
`CrmP2DarkS1` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP2DarkS1.html) · [PNG](/screens/assistants/png/CrmP2DarkS1.png)

```text
Update Jordan’s preferences to 3 beds

Reading Jordan’s record
Read Jordan Lee’s preferences
K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 2 Change card, save it?, dark
`CrmP2DarkS2` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP2DarkS2.html) · [PNG](/screens/assistants/png/CrmP2DarkS2.png)

```text
Update Jordan’s preferences to 3 beds

Checked 2 things

Here is the change. Save it?

Jordan Lee · preferences

Beds
2 → 3
Area
Oak Street · no change
Budget
Under [PRICE] · no change
Save it
Also add a pool
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 3 Save it sent, dark
`CrmP2DarkS3` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP2DarkS3.html) · [PNG](/screens/assistants/png/CrmP2DarkS3.png)

```text
Save it

Saving
Saved Jordan Lee · preferences
K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 4 Saved, dark
`CrmP2DarkS4` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP2DarkS4.html) · [PNG](/screens/assistants/png/CrmP2DarkS4.png)

```text
Save it

Saved in 1 step

Saved. I use this when new listings come in.

Saved · Jordan Lee

What else can you do?
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 5 What else sent, dark
`CrmP2DarkS5` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP2DarkS5.html) · [PNG](/screens/assistants/png/CrmP2DarkS5.png)

```text
What else can you do?

Thinking…

K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 6 Six prompts again, dark
`CrmP2DarkS6` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP2DarkS6.html) · [PNG](/screens/assistants/png/CrmP2DarkS6.png)

```text
What else can you do?

Try one of these, or ask in your own words.

Find Jordan Lee
Update Jordan’s preferences to 3 beds
Draft a message to Jordan
Remind me to call Jordan on Tuesday
Start a check-in campaign for inactive clients
Show my top buyers this month
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 1 Sent, reading record, light
`CrmP2LightS1` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP2LightS1.html) · [PNG](/screens/assistants/png/CrmP2LightS1.png)

Same content as `CrmP2S1` in the other theme.

### 2 Change card, save it?, light
`CrmP2LightS2` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP2LightS2.html) · [PNG](/screens/assistants/png/CrmP2LightS2.png)

Same content as `CrmP2S2` in the other theme.

### 3 Save it sent, light
`CrmP2LightS3` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP2LightS3.html) · [PNG](/screens/assistants/png/CrmP2LightS3.png)

Same content as `CrmP2S3` in the other theme.

### 4 Saved, light
`CrmP2LightS4` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP2LightS4.html) · [PNG](/screens/assistants/png/CrmP2LightS4.png)

Same content as `CrmP2S4` in the other theme.

### 5 What else sent, light
`CrmP2LightS5` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP2LightS5.html) · [PNG](/screens/assistants/png/CrmP2LightS5.png)

Same content as `CrmP2S5` in the other theme.

### 6 Six prompts again, light
`CrmP2LightS6` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP2LightS6.html) · [PNG](/screens/assistants/png/CrmP2LightS6.png)

Same content as `CrmP2S6` in the other theme.

### 1 Sent, reading activity, dark
`CrmP3DarkS1` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3DarkS1.html) · [PNG](/screens/assistants/png/CrmP3DarkS1.png)

```text
Draft a message to Jordan

Reading Jordan’s activity
Read Jordan Lee · 6 listing views, replied today
K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 2 Draft card, Send, dark
`CrmP3DarkS2` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3DarkS2.html) · [PNG](/screens/assistants/png/CrmP3DarkS2.png)

```text
Draft a message to Jordan

Checked 2 things

Here is a draft. Send it, or tell me what to change.

To
Jordan Lee · Text

Hi Jordan, two homes near Oak Street match your budget. Want to tour on Saturday?

Sends from your Radius number
Send
Make it shorter
Send it by email instead
K
Mel
```

Accessible labels: Your message; MEL message; Draft message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 3 Make it shorter sent, dark
`CrmP3DarkS3` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3DarkS3.html) · [PNG](/screens/assistants/png/CrmP3DarkS3.png)

```text
Make it shorter

Rewriting
Cut the draft to 11 words
K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 4 Shorter draft, dark
`CrmP3DarkS4` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3DarkS4.html) · [PNG](/screens/assistants/png/CrmP3DarkS4.png)

```text
Make it shorter

Rewrote in 1 step

Shorter. Send it?

To
Jordan Lee · Text

Hi Jordan, two homes near Oak Street fit. Tour Saturday?

Sends from your Radius number
Send
Send it by email instead
K
Mel
```

Accessible labels: Your message; MEL message; Draft message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 5 Send tapped, sending, dark
`CrmP3DarkS5` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3DarkS5.html) · [PNG](/screens/assistants/png/CrmP3DarkS5.png)

```text
Sending
Sent text from your Radius number
K
Mel
```

Accessible labels: MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 6 Sent and logged, dark
`CrmP3DarkS6` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3DarkS6.html) · [PNG](/screens/assistants/png/CrmP3DarkS6.png)

```text
Sent in 2 steps

Sent and logged in Jordan’s activity.

Sent · text to Jordan Lee

What else can you do?
K
Mel
```

Accessible labels: MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 7 What else sent, dark
`CrmP3DarkS7` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3DarkS7.html) · [PNG](/screens/assistants/png/CrmP3DarkS7.png)

```text
What else can you do?

Thinking…

K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 8 Six prompts again, dark
`CrmP3DarkS8` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3DarkS8.html) · [PNG](/screens/assistants/png/CrmP3DarkS8.png)

```text
What else can you do?

Try one of these, or ask in your own words.

Find Jordan Lee
Update Jordan’s preferences to 3 beds
Draft a message to Jordan
Remind me to call Jordan on Tuesday
Start a check-in campaign for inactive clients
Show my top buyers this month
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 1 Sent, reading activity, light
`CrmP3LightS1` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3LightS1.html) · [PNG](/screens/assistants/png/CrmP3LightS1.png)

Same content as `CrmP3S1` in the other theme.

### 2 Draft card, Send, light
`CrmP3LightS2` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3LightS2.html) · [PNG](/screens/assistants/png/CrmP3LightS2.png)

Same content as `CrmP3S2` in the other theme.

### 3 Make it shorter sent, light
`CrmP3LightS3` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3LightS3.html) · [PNG](/screens/assistants/png/CrmP3LightS3.png)

Same content as `CrmP3S3` in the other theme.

### 4 Shorter draft, light
`CrmP3LightS4` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3LightS4.html) · [PNG](/screens/assistants/png/CrmP3LightS4.png)

Same content as `CrmP3S4` in the other theme.

### 5 Send tapped, sending, light
`CrmP3LightS5` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3LightS5.html) · [PNG](/screens/assistants/png/CrmP3LightS5.png)

Same content as `CrmP3S5` in the other theme.

### 6 Sent and logged, light
`CrmP3LightS6` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3LightS6.html) · [PNG](/screens/assistants/png/CrmP3LightS6.png)

Same content as `CrmP3S6` in the other theme.

### 7 What else sent, light
`CrmP3LightS7` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3LightS7.html) · [PNG](/screens/assistants/png/CrmP3LightS7.png)

Same content as `CrmP3S7` in the other theme.

### 8 Six prompts again, light
`CrmP3LightS8` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3LightS8.html) · [PNG](/screens/assistants/png/CrmP3LightS8.png)

Same content as `CrmP3S8` in the other theme.

### 1 Sent, checking calendar, dark
`CrmP4DarkS1` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP4DarkS1.html) · [PNG](/screens/assistants/png/CrmP4DarkS1.png)

```text
Remind me to call Jordan on Tuesday

Checking your calendar
Read Google Calendar · Tuesday free at 10:00 AM
K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 2 Follow-up card, add it?, dark
`CrmP4DarkS2` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP4DarkS2.html) · [PNG](/screens/assistants/png/CrmP4DarkS2.png)

```text
Remind me to call Jordan on Tuesday

Checked 2 things

Here is the follow-up. Add it?

Call Jordan Lee
Tue, Oct 27 · 10:00 AM
Reminder
15 minutes before
Calendar
Google Calendar
Add it
Make it Wednesday
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 3 Add it sent, dark
`CrmP4DarkS3` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP4DarkS3.html) · [PNG](/screens/assistants/png/CrmP4DarkS3.png)

```text
Add it

Adding to Google Calendar
Added Call Jordan Lee · Tue, Oct 27 · 10:00 AM
K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 4 Added to calendar, dark
`CrmP4DarkS4` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP4DarkS4.html) · [PNG](/screens/assistants/png/CrmP4DarkS4.png)

```text
Add it

Added in 1 step

Added. I remind you 15 minutes before.

Added · Google Calendar

What else can you do?
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 5 What else sent, dark
`CrmP4DarkS5` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP4DarkS5.html) · [PNG](/screens/assistants/png/CrmP4DarkS5.png)

```text
What else can you do?

Thinking…

K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 6 Six prompts again, dark
`CrmP4DarkS6` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP4DarkS6.html) · [PNG](/screens/assistants/png/CrmP4DarkS6.png)

```text
What else can you do?

Try one of these, or ask in your own words.

Find Jordan Lee
Update Jordan’s preferences to 3 beds
Draft a message to Jordan
Remind me to call Jordan on Tuesday
Start a check-in campaign for inactive clients
Show my top buyers this month
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 1 Sent, checking calendar, light
`CrmP4LightS1` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP4LightS1.html) · [PNG](/screens/assistants/png/CrmP4LightS1.png)

Same content as `CrmP4S1` in the other theme.

### 2 Follow-up card, add it?, light
`CrmP4LightS2` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP4LightS2.html) · [PNG](/screens/assistants/png/CrmP4LightS2.png)

Same content as `CrmP4S2` in the other theme.

### 3 Add it sent, light
`CrmP4LightS3` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP4LightS3.html) · [PNG](/screens/assistants/png/CrmP4LightS3.png)

Same content as `CrmP4S3` in the other theme.

### 4 Added to calendar, light
`CrmP4LightS4` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP4LightS4.html) · [PNG](/screens/assistants/png/CrmP4LightS4.png)

Same content as `CrmP4S4` in the other theme.

### 5 What else sent, light
`CrmP4LightS5` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP4LightS5.html) · [PNG](/screens/assistants/png/CrmP4LightS5.png)

Same content as `CrmP4S5` in the other theme.

### 6 Six prompts again, light
`CrmP4LightS6` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP4LightS6.html) · [PNG](/screens/assistants/png/CrmP4LightS6.png)

Same content as `CrmP4S6` in the other theme.

### 1 Sent, finding clients, dark
`CrmP5DarkS1` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP5DarkS1.html) · [PNG](/screens/assistants/png/CrmP5DarkS1.png)

```text
Start a check-in campaign for inactive clients

Finding inactive clients
Found 12 clients not contacted in 90 days
K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 2 Plan card, start it?, dark
`CrmP5DarkS2` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP5DarkS2.html) · [PNG](/screens/assistants/png/CrmP5DarkS2.png)

```text
Start a check-in campaign for inactive clients

Checked 2 things

Here is the plan. Start it?

4-week check-in
12 inactive clients · not contacted in 90 days
Week 1
Text · “Still thinking about a move this year?”
Week 2
Email · new listings near them
Week 3
Text · market update
Week 4
Call reminder for you

Stops for anyone who replies.

Start the campaign
Make it 6 weeks
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 3 Start sent, dark
`CrmP5DarkS3` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP5DarkS3.html) · [PNG](/screens/assistants/png/CrmP5DarkS3.png)

```text
Start the campaign

Starting the campaign
Enrolled 12 clients
K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 4 Started, dark
`CrmP5DarkS4` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP5DarkS4.html) · [PNG](/screens/assistants/png/CrmP5DarkS4.png)

```text
Start the campaign

Started in 2 steps

Started. The first message goes out tomorrow at 9 AM.

Started · 12 clients

What else can you do?
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 5 What else sent, dark
`CrmP5DarkS5` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP5DarkS5.html) · [PNG](/screens/assistants/png/CrmP5DarkS5.png)

```text
What else can you do?

Thinking…

K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 6 Six prompts again, dark
`CrmP5DarkS6` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP5DarkS6.html) · [PNG](/screens/assistants/png/CrmP5DarkS6.png)

```text
What else can you do?

Try one of these, or ask in your own words.

Find Jordan Lee
Update Jordan’s preferences to 3 beds
Draft a message to Jordan
Remind me to call Jordan on Tuesday
Start a check-in campaign for inactive clients
Show my top buyers this month
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 1 Sent, finding clients, light
`CrmP5LightS1` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP5LightS1.html) · [PNG](/screens/assistants/png/CrmP5LightS1.png)

Same content as `CrmP5S1` in the other theme.

### 2 Plan card, start it?, light
`CrmP5LightS2` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP5LightS2.html) · [PNG](/screens/assistants/png/CrmP5LightS2.png)

Same content as `CrmP5S2` in the other theme.

### 3 Start sent, light
`CrmP5LightS3` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP5LightS3.html) · [PNG](/screens/assistants/png/CrmP5LightS3.png)

Same content as `CrmP5S3` in the other theme.

### 4 Started, light
`CrmP5LightS4` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP5LightS4.html) · [PNG](/screens/assistants/png/CrmP5LightS4.png)

Same content as `CrmP5S4` in the other theme.

### 5 What else sent, light
`CrmP5LightS5` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP5LightS5.html) · [PNG](/screens/assistants/png/CrmP5LightS5.png)

Same content as `CrmP5S5` in the other theme.

### 6 Six prompts again, light
`CrmP5LightS6` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP5LightS6.html) · [PNG](/screens/assistants/png/CrmP5LightS6.png)

Same content as `CrmP5S6` in the other theme.

### 1 Sent, ranking, dark
`CrmP6DarkS1` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP6DarkS1.html) · [PNG](/screens/assistants/png/CrmP6DarkS1.png)

```text
Show my top buyers this month

Ranking buyers by activity
Ranked 836 buyers by views, saves and replies
K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 2 Ranked list, dark
`CrmP6DarkS2` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP6DarkS2.html) · [PNG](/screens/assistants/png/CrmP6DarkS2.png)

```text
Show my top buyers this month

Checked 1 thing

Your top buyers this month, by activity:

JL
Jordan Lee
Buyer · 6 listing views
Replied today
PN
Priya Nair
Buyer · 4 listing views
Saved 2 homes
TB
Tom Becker
Buyer · 3 listing views
Tour booked
Draft a message to Jordan
What else can you do?
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 3 Draft a message sent, dark
`CrmP6DarkS3` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP6DarkS3.html) · [PNG](/screens/assistants/png/CrmP6DarkS3.png)

```text
Draft a message to Jordan

Reading Jordan’s activity
Read Jordan Lee · 6 listing views, replied today
K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 1 Sent, ranking, light
`CrmP6LightS1` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP6LightS1.html) · [PNG](/screens/assistants/png/CrmP6LightS1.png)

Same content as `CrmP6S1` in the other theme.

### 2 Ranked list, light
`CrmP6LightS2` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP6LightS2.html) · [PNG](/screens/assistants/png/CrmP6LightS2.png)

Same content as `CrmP6S2` in the other theme.

### 3 Draft a message sent, light
`CrmP6LightS3` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP6LightS3.html) · [PNG](/screens/assistants/png/CrmP6LightS3.png)

Same content as `CrmP6S3` in the other theme.

### 1 Intro, state 2
`CrmWaS01` · 390×844 · [HTML](/screens/assistants/CrmWaS01.html) · [PNG](/screens/assistants/png/CrmWaS01.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 2 Agent says yes
`CrmWaS02` · 390×844 · [HTML](/screens/assistants/CrmWaS02.html) · [PNG](/screens/assistants/png/CrmWaS02.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 3 Mel: on it
`CrmWaS03` · 390×844 · [HTML](/screens/assistants/CrmWaS03.html) · [PNG](/screens/assistants/png/CrmWaS03.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 4 CRM assistant, 3 options
`CrmWaS04` · 390×844 · [HTML](/screens/assistants/CrmWaS04.html) · [PNG](/screens/assistants/png/CrmWaS04.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 5 Agent picks 1
`CrmWaS05` · 390×844 · [HTML](/screens/assistants/CrmWaS05.html) · [PNG](/screens/assistants/png/CrmWaS05.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 6 Mel asks for the file
`CrmWaS06` · 390×844 · [HTML](/screens/assistants/CrmWaS06.html) · [PNG](/screens/assistants/png/CrmWaS06.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 7 File sent
`CrmWaS07` · 390×844 · [HTML](/screens/assistants/CrmWaS07.html) · [PNG](/screens/assistants/png/CrmWaS07.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 8 Mel: reading
`CrmWaS08` · 390×844 · [HTML](/screens/assistants/CrmWaS08.html) · [PNG](/screens/assistants/png/CrmWaS08.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 9 Found 1,280, duplicates question
`CrmWaS09` · 390×844 · [HTML](/screens/assistants/CrmWaS09.html) · [PNG](/screens/assistants/png/CrmWaS09.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 10 Agent picks 1
`CrmWaS10` · 390×844 · [HTML](/screens/assistants/CrmWaS10.html) · [PNG](/screens/assistants/png/CrmWaS10.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 11 Mel: importing
`CrmWaS11` · 390×844 · [HTML](/screens/assistants/CrmWaS11.html) · [PNG](/screens/assistants/png/CrmWaS11.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 12 Done, counts, Radius link
`CrmWaS12` · 390×844 · [HTML](/screens/assistants/CrmWaS12.html) · [PNG](/screens/assistants/png/CrmWaS12.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 13 What can you do
`CrmWaS13` · 390×844 · [HTML](/screens/assistants/CrmWaS13.html) · [PNG](/screens/assistants/png/CrmWaS13.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 14 Six prompts
`CrmWaS14` · 390×844 · [HTML](/screens/assistants/CrmWaS14.html) · [PNG](/screens/assistants/png/CrmWaS14.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 1 Agent picks 1
`CrmWaP1S1` · 390×844 · [HTML](/screens/assistants/CrmWaP1S1.html) · [PNG](/screens/assistants/png/CrmWaP1S1.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

1

10:08
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 2 Mel: searching
`CrmWaP1S2` · 390×844 · [HTML](/screens/assistants/CrmWaP1S2.html) · [PNG](/screens/assistants/png/CrmWaP1S2.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

1

10:08

On it. Searching your CRM.

10:08
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 3 Contact in text, next question
`CrmWaP1S3` · 390×844 · [HTML](/screens/assistants/CrmWaP1S3.html) · [PNG](/screens/assistants/png/CrmWaP1S3.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

1

10:08

On it. Searching your CRM.

10:08

Here is Jordan.
Jordan Lee · Buyer · Active
Phone (555) 014 2290
Email jordan.lee@gmail.com
Looking for 3 beds · Oak Street · under [PRICE]
Last contact 12 days ago, by text
Open in Radius: radiusagent.com/crm/jordan-lee
Want me to draft him a message, or remind you to call him?

10:08
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 1 Agent picks 2
`CrmWaP2S1` · 390×844 · [HTML](/screens/assistants/CrmWaP2S1.html) · [PNG](/screens/assistants/png/CrmWaP2S1.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

2

10:08
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 2 Mel: reading
`CrmWaP2S2` · 390×844 · [HTML](/screens/assistants/CrmWaP2S2.html) · [PNG](/screens/assistants/png/CrmWaP2S2.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

2

10:08

On it. Reading Jordan’s record.

10:08
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 3 Change in text, save it?
`CrmWaP2S3` · 390×844 · [HTML](/screens/assistants/CrmWaP2S3.html) · [PNG](/screens/assistants/png/CrmWaP2S3.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

2

10:08

On it. Reading Jordan’s record.

10:08

Here is the change for Jordan:
Beds 2 → 3
Area Oak Street, no change
Budget under [PRICE], no change
Save it?

10:08
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 4 Agent says yes
`CrmWaP2S4` · 390×844 · [HTML](/screens/assistants/CrmWaP2S4.html) · [PNG](/screens/assistants/png/CrmWaP2S4.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

2

10:08

On it. Reading Jordan’s record.

10:08

Here is the change for Jordan:
Beds 2 → 3
Area Oak Street, no change
Budget under [PRICE], no change
Save it?

10:08

Yes

10:09
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 5 Mel: saving
`CrmWaP2S5` · 390×844 · [HTML](/screens/assistants/CrmWaP2S5.html) · [PNG](/screens/assistants/png/CrmWaP2S5.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

2

10:08

On it. Reading Jordan’s record.

10:08

Here is the change for Jordan:
Beds 2 → 3
Area Oak Street, no change
Budget under [PRICE], no change
Save it?

10:08

Yes

10:09

On it. Saving.

10:09
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 6 Saved, anything else
`CrmWaP2S6` · 390×844 · [HTML](/screens/assistants/CrmWaP2S6.html) · [PNG](/screens/assistants/png/CrmWaP2S6.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

2

10:08

On it. Reading Jordan’s record.

10:08

Here is the change for Jordan:
Beds 2 → 3
Area Oak Street, no change
Budget under [PRICE], no change
Save it?

10:08

Yes

10:09

On it. Saving.

10:09

Saved. I use this when new listings come in.

10:09

Anything else? Pick a number from the list, or just tell me.

10:12
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 1 Agent picks 3
`CrmWaP3S1` · 390×844 · [HTML](/screens/assistants/CrmWaP3S1.html) · [PNG](/screens/assistants/png/CrmWaP3S1.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

3

10:08
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 2 Mel: reading
`CrmWaP3S2` · 390×844 · [HTML](/screens/assistants/CrmWaP3S2.html) · [PNG](/screens/assistants/png/CrmWaP3S2.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

3

10:08

On it. Reading Jordan’s activity.

10:08
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 3 Draft in text, send it?
`CrmWaP3S3` · 390×844 · [HTML](/screens/assistants/CrmWaP3S3.html) · [PNG](/screens/assistants/png/CrmWaP3S3.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

3

10:08

On it. Reading Jordan’s activity.

10:08

Here is a draft for Jordan, as a text:
“Hi Jordan, two homes near Oak Street match your budget. Want to tour on Saturday?”
Send it, or want something changed?

10:08
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 4 Make it shorter
`CrmWaP3S4` · 390×844 · [HTML](/screens/assistants/CrmWaP3S4.html) · [PNG](/screens/assistants/png/CrmWaP3S4.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

3

10:08

On it. Reading Jordan’s activity.

10:08

Here is a draft for Jordan, as a text:
“Hi Jordan, two homes near Oak Street match your budget. Want to tour on Saturday?”
Send it, or want something changed?

10:08

Make it shorter

10:09
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 5 Mel: on it
`CrmWaP3S5` · 390×844 · [HTML](/screens/assistants/CrmWaP3S5.html) · [PNG](/screens/assistants/png/CrmWaP3S5.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

3

10:08

On it. Reading Jordan’s activity.

10:08

Here is a draft for Jordan, as a text:
“Hi Jordan, two homes near Oak Street match your budget. Want to tour on Saturday?”
Send it, or want something changed?

10:08

Make it shorter

10:09

On it.

10:09
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 6 Shorter draft, send it?
`CrmWaP3S6` · 390×844 · [HTML](/screens/assistants/CrmWaP3S6.html) · [PNG](/screens/assistants/png/CrmWaP3S6.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

3

10:08

On it. Reading Jordan’s activity.

10:08

Here is a draft for Jordan, as a text:
“Hi Jordan, two homes near Oak Street match your budget. Want to tour on Saturday?”
Send it, or want something changed?

10:08

Make it shorter

10:09

On it.

10:09

Shorter:
“Hi Jordan, two homes near Oak Street fit. Tour Saturday?”
Send it?

10:09
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 7 Agent: send it
`CrmWaP3S7` · 390×844 · [HTML](/screens/assistants/CrmWaP3S7.html) · [PNG](/screens/assistants/png/CrmWaP3S7.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

3

10:08

On it. Reading Jordan’s activity.

10:08

Here is a draft for Jordan, as a text:
“Hi Jordan, two homes near Oak Street match your budget. Want to tour on Saturday?”
Send it, or want something changed?

10:08

Make it shorter

10:09

On it.

10:09

Shorter:
“Hi Jordan, two homes near Oak Street fit. Tour Saturday?”
Send it?

10:09

Send it

10:10
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 8 Mel: sending
`CrmWaP3S8` · 390×844 · [HTML](/screens/assistants/CrmWaP3S8.html) · [PNG](/screens/assistants/png/CrmWaP3S8.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

3

10:08

On it. Reading Jordan’s activity.

10:08

Here is a draft for Jordan, as a text:
“Hi Jordan, two homes near Oak Street match your budget. Want to tour on Saturday?”
Send it, or want something changed?

10:08

Make it shorter

10:09

On it.

10:09

Shorter:
“Hi Jordan, two homes near Oak Street fit. Tour Saturday?”
Send it?

10:09

Send it

10:10

On it. Sending.

10:10
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 9 Sent and logged, anything else
`CrmWaP3S9` · 390×844 · [HTML](/screens/assistants/CrmWaP3S9.html) · [PNG](/screens/assistants/png/CrmWaP3S9.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

3

10:08

On it. Reading Jordan’s activity.

10:08

Here is a draft for Jordan, as a text:
“Hi Jordan, two homes near Oak Street match your budget. Want to tour on Saturday?”
Send it, or want something changed?

10:08

Make it shorter

10:09

On it.

10:09

Shorter:
“Hi Jordan, two homes near Oak Street fit. Tour Saturday?”
Send it?

10:09

Send it

10:10

On it. Sending.

10:10

Sent from your Radius number and logged in Jordan’s activity.

10:10

Anything else? Pick a number from the list, or just tell me.

10:12
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 1 Agent picks 4
`CrmWaP4S1` · 390×844 · [HTML](/screens/assistants/CrmWaP4S1.html) · [PNG](/screens/assistants/png/CrmWaP4S1.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

4

10:08
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 2 Mel: checking calendar
`CrmWaP4S2` · 390×844 · [HTML](/screens/assistants/CrmWaP4S2.html) · [PNG](/screens/assistants/png/CrmWaP4S2.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

4

10:08

On it. Checking your calendar.

10:08
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 3 Follow-up in text, add it?
`CrmWaP4S3` · 390×844 · [HTML](/screens/assistants/CrmWaP4S3.html) · [PNG](/screens/assistants/png/CrmWaP4S3.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

4

10:08

On it. Checking your calendar.

10:08

Tuesday at 10 AM is free. Here is the follow-up:
Call Jordan Lee · Tue, Oct 27 · 10:00 AM
Reminder 15 minutes before, on Google Calendar
Add it?

10:08
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 4 Agent says yes
`CrmWaP4S4` · 390×844 · [HTML](/screens/assistants/CrmWaP4S4.html) · [PNG](/screens/assistants/png/CrmWaP4S4.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

4

10:08

On it. Checking your calendar.

10:08

Tuesday at 10 AM is free. Here is the follow-up:
Call Jordan Lee · Tue, Oct 27 · 10:00 AM
Reminder 15 minutes before, on Google Calendar
Add it?

10:08

Yes

10:09
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 5 Mel: adding
`CrmWaP4S5` · 390×844 · [HTML](/screens/assistants/CrmWaP4S5.html) · [PNG](/screens/assistants/png/CrmWaP4S5.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

4

10:08

On it. Checking your calendar.

10:08

Tuesday at 10 AM is free. Here is the follow-up:
Call Jordan Lee · Tue, Oct 27 · 10:00 AM
Reminder 15 minutes before, on Google Calendar
Add it?

10:08

Yes

10:09

On it. Adding it to Google Calendar.

10:09
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 6 Added, anything else
`CrmWaP4S6` · 390×844 · [HTML](/screens/assistants/CrmWaP4S6.html) · [PNG](/screens/assistants/png/CrmWaP4S6.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

4

10:08

On it. Checking your calendar.

10:08

Tuesday at 10 AM is free. Here is the follow-up:
Call Jordan Lee · Tue, Oct 27 · 10:00 AM
Reminder 15 minutes before, on Google Calendar
Add it?

10:08

Yes

10:09

On it. Adding it to Google Calendar.

10:09

Added. I remind you 15 minutes before.

10:09

Anything else? Pick a number from the list, or just tell me.

10:12
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 1 Agent picks 5
`CrmWaP5S1` · 390×844 · [HTML](/screens/assistants/CrmWaP5S1.html) · [PNG](/screens/assistants/png/CrmWaP5S1.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

5

10:08
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 2 Mel: finding clients
`CrmWaP5S2` · 390×844 · [HTML](/screens/assistants/CrmWaP5S2.html) · [PNG](/screens/assistants/png/CrmWaP5S2.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

5

10:08

On it. Finding inactive clients.

10:08
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 3 Plan in text, start it?
`CrmWaP5S3` · 390×844 · [HTML](/screens/assistants/CrmWaP5S3.html) · [PNG](/screens/assistants/png/CrmWaP5S3.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

5

10:08

On it. Finding inactive clients.

10:08

12 clients have not heard from you in 90 days. Here is a 4-week check-in:
Week 1 · Text · “Still thinking about a move this year?”
Week 2 · Email · new listings near them
Week 3 · Text · market update
Week 4 · Call reminder for you
It stops for anyone who replies. Start it?

10:08
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 4 Agent: start it
`CrmWaP5S4` · 390×844 · [HTML](/screens/assistants/CrmWaP5S4.html) · [PNG](/screens/assistants/png/CrmWaP5S4.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

5

10:08

On it. Finding inactive clients.

10:08

12 clients have not heard from you in 90 days. Here is a 4-week check-in:
Week 1 · Text · “Still thinking about a move this year?”
Week 2 · Email · new listings near them
Week 3 · Text · market update
Week 4 · Call reminder for you
It stops for anyone who replies. Start it?

10:08

Start it

10:09
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 5 Mel: starting
`CrmWaP5S5` · 390×844 · [HTML](/screens/assistants/CrmWaP5S5.html) · [PNG](/screens/assistants/png/CrmWaP5S5.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

5

10:08

On it. Finding inactive clients.

10:08

12 clients have not heard from you in 90 days. Here is a 4-week check-in:
Week 1 · Text · “Still thinking about a move this year?”
Week 2 · Email · new listings near them
Week 3 · Text · market update
Week 4 · Call reminder for you
It stops for anyone who replies. Start it?

10:08

Start it

10:09

On it. Starting the campaign.

10:09
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 6 Started, anything else
`CrmWaP5S6` · 390×844 · [HTML](/screens/assistants/CrmWaP5S6.html) · [PNG](/screens/assistants/png/CrmWaP5S6.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

5

10:08

On it. Finding inactive clients.

10:08

12 clients have not heard from you in 90 days. Here is a 4-week check-in:
Week 1 · Text · “Still thinking about a move this year?”
Week 2 · Email · new listings near them
Week 3 · Text · market update
Week 4 · Call reminder for you
It stops for anyone who replies. Start it?

10:08

Start it

10:09

On it. Starting the campaign.

10:09

Started. The first message goes out tomorrow at 9 AM.

10:09

Anything else? Pick a number from the list, or just tell me.

10:12
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 1 Agent picks 6
`CrmWaP6S1` · 390×844 · [HTML](/screens/assistants/CrmWaP6S1.html) · [PNG](/screens/assistants/png/CrmWaP6S1.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

6

10:08
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 2 Mel: ranking
`CrmWaP6S2` · 390×844 · [HTML](/screens/assistants/CrmWaP6S2.html) · [PNG](/screens/assistants/png/CrmWaP6S2.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

6

10:08

On it. Ranking buyers by activity.

10:08
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 3 Ranked list in text, next question
`CrmWaP6S3` · 390×844 · [HTML](/screens/assistants/CrmWaP6S3.html) · [PNG](/screens/assistants/png/CrmWaP6S3.png)

```text
MEL
online
Today

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

10:02

Do you want to start by adding your clients? Reply yes, or pick a number.

10:02

Yes

10:03

On it. Checking your CRM.

10:03

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

10:03

1

10:04

Send me the CSV here. Any column layout works, I match the fields for you.

10:04
clients-export.csv
CSV · 1,280 rows · 212 KB
10:05

On it. Reading clients-export.csv.

10:05

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

10:05

1

10:06

On it. Importing 1,248 contacts.

10:06

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

10:06

What can you do with them?

10:07

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

10:07

6

10:08

On it. Ranking buyers by activity.

10:08

Your top buyers this month, by activity:
1 Jordan Lee · 6 listing views · replied today
2 Priya Nair · 4 listing views · saved 2 homes
3 Tom Becker · 3 listing views · tour booked
Want me to draft a message to Jordan?

10:08
Message
```

Accessible labels: Back; MEL; Video call; Voice call; More options; Record voice message

### 1 Intro, state 2
`CrmSmS01` · 390×844 · [HTML](/screens/assistants/CrmSmS01.html) · [PNG](/screens/assistants/png/CrmSmS01.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 2 Agent says yes
`CrmSmS02` · 390×844 · [HTML](/screens/assistants/CrmSmS02.html) · [PNG](/screens/assistants/png/CrmSmS02.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 3 Mel: on it
`CrmSmS03` · 390×844 · [HTML](/screens/assistants/CrmSmS03.html) · [PNG](/screens/assistants/png/CrmSmS03.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 4 CRM assistant, 3 options
`CrmSmS04` · 390×844 · [HTML](/screens/assistants/CrmSmS04.html) · [PNG](/screens/assistants/png/CrmSmS04.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 5 Agent picks 1
`CrmSmS05` · 390×844 · [HTML](/screens/assistants/CrmSmS05.html) · [PNG](/screens/assistants/png/CrmSmS05.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 6 Mel texts the upload link
`CrmSmS06` · 390×844 · [HTML](/screens/assistants/CrmSmS06.html) · [PNG](/screens/assistants/png/CrmSmS06.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 7 Uploader opens from the link
`CrmSmU01` · 390×844 · [HTML](/screens/assistants/CrmSmU01.html) · [PNG](/screens/assistants/png/CrmSmU01.png)

```text
radiusagent.com
CRM
Send me your contacts

Hi, I’m MEL. Texts can’t carry files, so drop your CSV here. Any column layout works, I match the fields for you.

Choose a CSV

I text you back in Messages once it’s in.
```

Accessible labels: MEL

### 8 Uploading
`CrmSmU02` · 390×844 · [HTML](/screens/assistants/CrmSmU02.html) · [PNG](/screens/assistants/png/CrmSmU02.png)

```text
radiusagent.com
CRM
Uploading
clients-export.csv
136 of 212 KB

Keep this page open until it’s done.
```

Accessible labels: MEL; Upload progress

### 9 Done, back to Messages
`CrmSmU03` · 390×844 · [HTML](/screens/assistants/CrmSmU03.html) · [PNG](/screens/assistants/png/CrmSmU03.png)

```text
radiusagent.com
CRM
Got it

I’m reading your file now. I’ll text you what I find.

clients-export.csv
212 KB · uploaded
Back to Messages
```

Accessible labels: MEL; Uploaded

### 10 Back in Messages, Mel reads the file
`CrmSmS07` · 390×844 · [HTML](/screens/assistants/CrmSmS07.html) · [PNG](/screens/assistants/png/CrmSmS07.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 11 Found 1,280, duplicates question
`CrmSmS08` · 390×844 · [HTML](/screens/assistants/CrmSmS08.html) · [PNG](/screens/assistants/png/CrmSmS08.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 12 Agent picks 1
`CrmSmS09` · 390×844 · [HTML](/screens/assistants/CrmSmS09.html) · [PNG](/screens/assistants/png/CrmSmS09.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 13 Mel: importing
`CrmSmS10` · 390×844 · [HTML](/screens/assistants/CrmSmS10.html) · [PNG](/screens/assistants/png/CrmSmS10.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 14 Done, counts, Radius link
`CrmSmS11` · 390×844 · [HTML](/screens/assistants/CrmSmS11.html) · [PNG](/screens/assistants/png/CrmSmS11.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 15 What can you do
`CrmSmS12` · 390×844 · [HTML](/screens/assistants/CrmSmS12.html) · [PNG](/screens/assistants/png/CrmSmS12.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 16 Six prompts
`CrmSmS13` · 390×844 · [HTML](/screens/assistants/CrmSmS13.html) · [PNG](/screens/assistants/png/CrmSmS13.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 1 Agent picks 1
`CrmSmP1S1` · 390×844 · [HTML](/screens/assistants/CrmSmP1S1.html) · [PNG](/screens/assistants/png/CrmSmP1S1.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

1

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 2 Mel: searching
`CrmSmP1S2` · 390×844 · [HTML](/screens/assistants/CrmSmP1S2.html) · [PNG](/screens/assistants/png/CrmSmP1S2.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

1

On it. Searching your CRM.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 3 Contact in text, next question
`CrmSmP1S3` · 390×844 · [HTML](/screens/assistants/CrmSmP1S3.html) · [PNG](/screens/assistants/png/CrmSmP1S3.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

1

On it. Searching your CRM.

Here is Jordan.
Jordan Lee · Buyer · Active
Phone (555) 014 2290
Email jordan.lee@gmail.com
Looking for 3 beds · Oak Street · under [PRICE]
Last contact 12 days ago, by text
Open in Radius: radiusagent.com/crm/jordan-lee
Want me to draft him a message, or remind you to call him?

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 1 Agent picks 2
`CrmSmP2S1` · 390×844 · [HTML](/screens/assistants/CrmSmP2S1.html) · [PNG](/screens/assistants/png/CrmSmP2S1.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

2

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 2 Mel: reading
`CrmSmP2S2` · 390×844 · [HTML](/screens/assistants/CrmSmP2S2.html) · [PNG](/screens/assistants/png/CrmSmP2S2.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

2

On it. Reading Jordan’s record.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 3 Change in text, save it?
`CrmSmP2S3` · 390×844 · [HTML](/screens/assistants/CrmSmP2S3.html) · [PNG](/screens/assistants/png/CrmSmP2S3.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

2

On it. Reading Jordan’s record.

Here is the change for Jordan:
Beds 2 → 3
Area Oak Street, no change
Budget under [PRICE], no change
Save it?

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 4 Agent says yes
`CrmSmP2S4` · 390×844 · [HTML](/screens/assistants/CrmSmP2S4.html) · [PNG](/screens/assistants/png/CrmSmP2S4.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

2

On it. Reading Jordan’s record.

Here is the change for Jordan:
Beds 2 → 3
Area Oak Street, no change
Budget under [PRICE], no change
Save it?

Yes

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 5 Mel: saving
`CrmSmP2S5` · 390×844 · [HTML](/screens/assistants/CrmSmP2S5.html) · [PNG](/screens/assistants/png/CrmSmP2S5.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

2

On it. Reading Jordan’s record.

Here is the change for Jordan:
Beds 2 → 3
Area Oak Street, no change
Budget under [PRICE], no change
Save it?

Yes

On it. Saving.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 6 Saved, anything else
`CrmSmP2S6` · 390×844 · [HTML](/screens/assistants/CrmSmP2S6.html) · [PNG](/screens/assistants/png/CrmSmP2S6.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

2

On it. Reading Jordan’s record.

Here is the change for Jordan:
Beds 2 → 3
Area Oak Street, no change
Budget under [PRICE], no change
Save it?

Yes

On it. Saving.

Saved. I use this when new listings come in.

Anything else? Pick a number from the list, or just tell me.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 1 Agent picks 3
`CrmSmP3S1` · 390×844 · [HTML](/screens/assistants/CrmSmP3S1.html) · [PNG](/screens/assistants/png/CrmSmP3S1.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

3

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 2 Mel: reading
`CrmSmP3S2` · 390×844 · [HTML](/screens/assistants/CrmSmP3S2.html) · [PNG](/screens/assistants/png/CrmSmP3S2.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

3

On it. Reading Jordan’s activity.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 3 Draft in text, send it?
`CrmSmP3S3` · 390×844 · [HTML](/screens/assistants/CrmSmP3S3.html) · [PNG](/screens/assistants/png/CrmSmP3S3.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

3

On it. Reading Jordan’s activity.

Here is a draft for Jordan, as a text:
“Hi Jordan, two homes near Oak Street match your budget. Want to tour on Saturday?”
Send it, or want something changed?

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 4 Make it shorter
`CrmSmP3S4` · 390×844 · [HTML](/screens/assistants/CrmSmP3S4.html) · [PNG](/screens/assistants/png/CrmSmP3S4.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

3

On it. Reading Jordan’s activity.

Here is a draft for Jordan, as a text:
“Hi Jordan, two homes near Oak Street match your budget. Want to tour on Saturday?”
Send it, or want something changed?

Make it shorter

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 5 Mel: on it
`CrmSmP3S5` · 390×844 · [HTML](/screens/assistants/CrmSmP3S5.html) · [PNG](/screens/assistants/png/CrmSmP3S5.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

3

On it. Reading Jordan’s activity.

Here is a draft for Jordan, as a text:
“Hi Jordan, two homes near Oak Street match your budget. Want to tour on Saturday?”
Send it, or want something changed?

Make it shorter

On it.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 6 Shorter draft, send it?
`CrmSmP3S6` · 390×844 · [HTML](/screens/assistants/CrmSmP3S6.html) · [PNG](/screens/assistants/png/CrmSmP3S6.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

3

On it. Reading Jordan’s activity.

Here is a draft for Jordan, as a text:
“Hi Jordan, two homes near Oak Street match your budget. Want to tour on Saturday?”
Send it, or want something changed?

Make it shorter

On it.

Shorter:
“Hi Jordan, two homes near Oak Street fit. Tour Saturday?”
Send it?

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 7 Agent: send it
`CrmSmP3S7` · 390×844 · [HTML](/screens/assistants/CrmSmP3S7.html) · [PNG](/screens/assistants/png/CrmSmP3S7.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

3

On it. Reading Jordan’s activity.

Here is a draft for Jordan, as a text:
“Hi Jordan, two homes near Oak Street match your budget. Want to tour on Saturday?”
Send it, or want something changed?

Make it shorter

On it.

Shorter:
“Hi Jordan, two homes near Oak Street fit. Tour Saturday?”
Send it?

Send it

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 8 Mel: sending
`CrmSmP3S8` · 390×844 · [HTML](/screens/assistants/CrmSmP3S8.html) · [PNG](/screens/assistants/png/CrmSmP3S8.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

3

On it. Reading Jordan’s activity.

Here is a draft for Jordan, as a text:
“Hi Jordan, two homes near Oak Street match your budget. Want to tour on Saturday?”
Send it, or want something changed?

Make it shorter

On it.

Shorter:
“Hi Jordan, two homes near Oak Street fit. Tour Saturday?”
Send it?

Send it

On it. Sending.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 9 Sent and logged, anything else
`CrmSmP3S9` · 390×844 · [HTML](/screens/assistants/CrmSmP3S9.html) · [PNG](/screens/assistants/png/CrmSmP3S9.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

3

On it. Reading Jordan’s activity.

Here is a draft for Jordan, as a text:
“Hi Jordan, two homes near Oak Street match your budget. Want to tour on Saturday?”
Send it, or want something changed?

Make it shorter

On it.

Shorter:
“Hi Jordan, two homes near Oak Street fit. Tour Saturday?”
Send it?

Send it

On it. Sending.

Sent from your Radius number and logged in Jordan’s activity.

Anything else? Pick a number from the list, or just tell me.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 1 Agent picks 4
`CrmSmP4S1` · 390×844 · [HTML](/screens/assistants/CrmSmP4S1.html) · [PNG](/screens/assistants/png/CrmSmP4S1.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

4

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 2 Mel: checking calendar
`CrmSmP4S2` · 390×844 · [HTML](/screens/assistants/CrmSmP4S2.html) · [PNG](/screens/assistants/png/CrmSmP4S2.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

4

On it. Checking your calendar.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 3 Follow-up in text, add it?
`CrmSmP4S3` · 390×844 · [HTML](/screens/assistants/CrmSmP4S3.html) · [PNG](/screens/assistants/png/CrmSmP4S3.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

4

On it. Checking your calendar.

Tuesday at 10 AM is free. Here is the follow-up:
Call Jordan Lee · Tue, Oct 27 · 10:00 AM
Reminder 15 minutes before, on Google Calendar
Add it?

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 4 Agent says yes
`CrmSmP4S4` · 390×844 · [HTML](/screens/assistants/CrmSmP4S4.html) · [PNG](/screens/assistants/png/CrmSmP4S4.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

4

On it. Checking your calendar.

Tuesday at 10 AM is free. Here is the follow-up:
Call Jordan Lee · Tue, Oct 27 · 10:00 AM
Reminder 15 minutes before, on Google Calendar
Add it?

Yes

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 5 Mel: adding
`CrmSmP4S5` · 390×844 · [HTML](/screens/assistants/CrmSmP4S5.html) · [PNG](/screens/assistants/png/CrmSmP4S5.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

4

On it. Checking your calendar.

Tuesday at 10 AM is free. Here is the follow-up:
Call Jordan Lee · Tue, Oct 27 · 10:00 AM
Reminder 15 minutes before, on Google Calendar
Add it?

Yes

On it. Adding it to Google Calendar.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 6 Added, anything else
`CrmSmP4S6` · 390×844 · [HTML](/screens/assistants/CrmSmP4S6.html) · [PNG](/screens/assistants/png/CrmSmP4S6.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

4

On it. Checking your calendar.

Tuesday at 10 AM is free. Here is the follow-up:
Call Jordan Lee · Tue, Oct 27 · 10:00 AM
Reminder 15 minutes before, on Google Calendar
Add it?

Yes

On it. Adding it to Google Calendar.

Added. I remind you 15 minutes before.

Anything else? Pick a number from the list, or just tell me.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 1 Agent picks 5
`CrmSmP5S1` · 390×844 · [HTML](/screens/assistants/CrmSmP5S1.html) · [PNG](/screens/assistants/png/CrmSmP5S1.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

5

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 2 Mel: finding clients
`CrmSmP5S2` · 390×844 · [HTML](/screens/assistants/CrmSmP5S2.html) · [PNG](/screens/assistants/png/CrmSmP5S2.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

5

On it. Finding inactive clients.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 3 Plan in text, start it?
`CrmSmP5S3` · 390×844 · [HTML](/screens/assistants/CrmSmP5S3.html) · [PNG](/screens/assistants/png/CrmSmP5S3.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

5

On it. Finding inactive clients.

12 clients have not heard from you in 90 days. Here is a 4-week check-in:
Week 1 · Text · “Still thinking about a move this year?”
Week 2 · Email · new listings near them
Week 3 · Text · market update
Week 4 · Call reminder for you
It stops for anyone who replies. Start it?

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 4 Agent: start it
`CrmSmP5S4` · 390×844 · [HTML](/screens/assistants/CrmSmP5S4.html) · [PNG](/screens/assistants/png/CrmSmP5S4.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

5

On it. Finding inactive clients.

12 clients have not heard from you in 90 days. Here is a 4-week check-in:
Week 1 · Text · “Still thinking about a move this year?”
Week 2 · Email · new listings near them
Week 3 · Text · market update
Week 4 · Call reminder for you
It stops for anyone who replies. Start it?

Start it

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 5 Mel: starting
`CrmSmP5S5` · 390×844 · [HTML](/screens/assistants/CrmSmP5S5.html) · [PNG](/screens/assistants/png/CrmSmP5S5.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

5

On it. Finding inactive clients.

12 clients have not heard from you in 90 days. Here is a 4-week check-in:
Week 1 · Text · “Still thinking about a move this year?”
Week 2 · Email · new listings near them
Week 3 · Text · market update
Week 4 · Call reminder for you
It stops for anyone who replies. Start it?

Start it

On it. Starting the campaign.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 6 Started, anything else
`CrmSmP5S6` · 390×844 · [HTML](/screens/assistants/CrmSmP5S6.html) · [PNG](/screens/assistants/png/CrmSmP5S6.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

5

On it. Finding inactive clients.

12 clients have not heard from you in 90 days. Here is a 4-week check-in:
Week 1 · Text · “Still thinking about a move this year?”
Week 2 · Email · new listings near them
Week 3 · Text · market update
Week 4 · Call reminder for you
It stops for anyone who replies. Start it?

Start it

On it. Starting the campaign.

Started. The first message goes out tomorrow at 9 AM.

Anything else? Pick a number from the list, or just tell me.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 1 Agent picks 6
`CrmSmP6S1` · 390×844 · [HTML](/screens/assistants/CrmSmP6S1.html) · [PNG](/screens/assistants/png/CrmSmP6S1.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

6

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 2 Mel: ranking
`CrmSmP6S2` · 390×844 · [HTML](/screens/assistants/CrmSmP6S2.html) · [PNG](/screens/assistants/png/CrmSmP6S2.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

6

On it. Ranking buyers by activity.

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

### 3 Ranked list in text, next question
`CrmSmP6S3` · 390×844 · [HTML](/screens/assistants/CrmSmP6S3.html) · [PNG](/screens/assistants/png/CrmSmP6S3.png)

```text
MEL ›
Text Message · Today 10:02 AM

Hey, I’m MEL, your AI assistant.
I can:
1 Add and manage your clients
2 Market a listing
3 Run follow-up campaigns
4 Keep clients updated
5 Check transaction files
6 Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

Yes

On it. Checking your CRM.

Checked your CRM: 0 contacts.
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.
How do you want to add them?
1 Upload a CSV
2 Import from another CRM
3 I’ll add contacts later

1

Texts can’t carry files, so upload the CSV with this link. Any column layout works, I match the fields for you.
radiusagent.com/u/7Q4K

On it. Reading clients-export.csv.

Read 1,280 rows and matched name, phone, email, address, client type and notes.
32 are duplicates. Import 1,248 and skip them?
1 Yes, skip the duplicates
2 Show me the duplicates first

1

On it. Importing 1,248 contacts.

Done. Here is what came in:
1,248 imported · 836 buyers · 412 sellers
32 duplicates skipped
12 need a phone or email
See them in Radius: radiusagent.com/crm

What can you do with them?

Try one of these, or ask in your own words.
1 Find Jordan Lee
2 Update Jordan’s preferences to 3 beds
3 Draft a message to Jordan
4 Remind me to call Jordan on Tuesday
5 Start a check-in campaign for inactive clients
6 Show my top buyers this month

6

On it. Ranking buyers by activity.

Your top buyers this month, by activity:
1 Jordan Lee · 6 listing views · replied today
2 Priya Nair · 4 listing views · saved 2 homes
3 Tom Becker · 3 listing views · tour booked
Want me to draft a message to Jordan?

Text Message
```

Accessible labels: Back; MEL; Apps; Audio message

## Marketing skill flow

Designer notes:

- **Marketing happy path**
- An agent gets a full listing marketing package in minutes. Mel asks before anything goes live.
- BIJU FOOTNOTES, steps 1 to 3
  
  Step 1: Conceptual onboarding interface. Production requires an authorized MLS or brokerage listing-data integration; a license number alone does not guarantee listing access.
  
  Step 2: In production, Mel should retrieve the property photos, description, price, features, open-house information, and listing status automatically, using authorized listing data.
  
  Step 3: Visual references illustrate the five style directions, not finished listing designs.
  
  Source: Biju, Marketing Design Assistant script (Slack DM, 15 Oct). Exact footnotes.
- BIJU FOOTNOTES, steps 5 and 6
  
  Step 5 (package preview): Illustrative design references only. Actual generated assets should have working preview, edit, and download links.
  
  Step 6 (recipients and approval): All external publishing, mass emails, and vendor deliveries require connected services, appropriate permissions, and an approval step.
  
  Source: Biju, Marketing Design Assistant script (Slack DM, 15 Oct). Exact footnotes.
- BIJU FOOTNOTES, step 7
  
  Step 7 (confirm execution): After the agent approves and the relevant publishing services report success, Mel should provide an execution summary.
  Inside the report card: Example of a completed campaign report — not actual publishing activity.
  
  Steps 4, 8 and 9: no footnote in Biju's script.
  
  Source: Biju, Marketing Design Assistant script (Slack DM, 15 Oct). Exact footnotes.
- **Variant: more than 3 pieces for one destination**
- **Connections**
- **Routine**
- **Package viewer**
- Tap the package card to view every design, play the video, share or download.
- **Recovery: before designing**
- What Mel does when something is missing, fails or changes. Mel never says it is live when it is not.
- **Recovery: while designing**
- **Recovery: publishing**
- **Flow B: pick what to create**
- Mel asks what to create, then where it goes, then shows templates sized for those platforms. After B3 it joins step 4 Your brand.

### 1 Meet Mel, dark
`MktM01Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM01Dark.html) · [PNG](/screens/assistants/png/MktM01Dark.png)

```text
Hey! 👋 I’m Mel, your AI Design Assistant.

Let’s create an entire marketing package for your listings — social media posts, videos, flyers, email campaigns, websites, yard signs, and more.

I’ll design everything, customize it to your brand, and even help you publish and distribute it.

First, let’s find your listings!

What’s your real estate license number and state?

MLS
Find your listings
Connect
My license number is …
K
Mel
```

Accessible labels: MEL message; Connect MLS; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 1 Meet Mel, light
`MktM01Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM01Light.html) · [PNG](/screens/assistants/png/MktM01Light.png)

```text
Hey! 👋 I’m Mel, your AI Design Assistant.

Let’s create an entire marketing package for your listings — social media posts, videos, flyers, email campaigns, websites, yard signs, and more.

I’ll design everything, customize it to your brand, and even help you publish and distribute it.

First, let’s find your listings!

What’s your real estate license number and state?

MLS
Find your listings automatically
Connect
My license number is …
K
Mel
```

Accessible labels: MEL message; Connect MLS; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 2 Pick a listing, dark
`MktM02Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM02Dark.html) · [PNG](/screens/assistants/png/MktM02Dark.png)

```text
Pick a listing

123 Ocean View Drive
Active
San Francisco · $2.45M · 4 bd · 3 ba
456 Palm Avenue
Pending
Los Angeles · $1.88M · 3 bd · 2 ba
789 Hillcrest Lane
Coming soon
San Jose · $1.3M · 4 bd · 2.5 ba
Show all 12 listings
K
Mel
```

Accessible labels: MEL message; Your listings; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 2 Pick a listing, light
`MktM02Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM02Light.html) · [PNG](/screens/assistants/png/MktM02Light.png)

Same content as `MktM02` in the other theme.

### 3 Pick a style, dark
`MktM03Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM03Dark.html) · [PNG](/screens/assistants/png/MktM03Dark.png)

```text
Pick a style. Tap more than one to get a version in each.

Modern Minimal
Luxury Editorial
Bold & Vibrant
Classic Real Estate
Lifestyle & Storytelling
K
Mel
```

Accessible labels: MEL message; Design styles; Modern Minimal; Preview Modern Minimal; Luxury Editorial; Preview Luxury Editorial; Bold & Vibrant; Preview Bold & Vibrant; Classic Real Estate; Preview Classic Real Estate; Lifestyle & Storytelling; Preview Lifestyle & Storytelling; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 3 Pick a style, light
`MktM03Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM03Light.html) · [PNG](/screens/assistants/png/MktM03Light.png)

Same content as `MktM03` in the other theme.

### 4 Your brand, dark
`MktM04Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM04Dark.html) · [PNG](/screens/assistants/png/MktM04Dark.png)

```text
I found your brand. Change anything by telling me.

JUST LISTED

123 Ocean View Drive

Primary
Accent
Logo
Use these
Change the colours
Upload a new logo
Use a text-only brand
K
Mel
```

Accessible labels: MEL message; Your brand; Brand preview; Primary colour; Accent colour; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 4 Your brand, light
`MktM04Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM04Light.html) · [PNG](/screens/assistants/png/MktM04Light.png)

Same content as `MktM04` in the other theme.

### Instagram, more than 3 pieces, dark
`MktM05Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM05Dark.html) · [PNG](/screens/assistants/png/MktM05Dark.png)

```text
Go ahead

Let’s start with Instagram. 12 pieces are ready.

Open them to check every caption and tag, then send.

Instagram · 12 pieces

6 feed posts, 4 stories, 2 reels

+9

Posts as soon as you tap

Post all 12
Remove the stories
Post 4 now and the rest next week
Change every caption to a shorter one
K
Mel
```

Accessible labels: Your message; MEL message; Review all 12 Instagram pieces; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Instagram, more than 3 pieces, light
`MktM05Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM05Light.html) · [PNG](/screens/assistants/png/MktM05Light.png)

Same content as `MktM05` in the other theme.

### 7 Change by asking, dark
`MktM06Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM06Dark.html) · [PNG](/screens/assistants/png/MktM06Dark.png)

```text
Change the flyer headline to Ocean Views, Move-In Ready

Done. The flyer headline now reads Ocean Views, Move-In Ready.

Listing marketing package

123 Ocean View Drive · 6 designs · flyer updated

+3
Publish it
Use a different photo on the flyer
Undo that change
K
Mel
```

Accessible labels: Your message; MEL message; Open your listing marketing package; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 7 Change by asking, light
`MktM06Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM06Light.html) · [PNG](/screens/assistants/png/MktM06Light.png)

Same content as `MktM06` in the other theme.

### 8 Where it goes, dark
`MktM07Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM07Dark.html) · [PNG](/screens/assistants/png/MktM07Dark.png)

```text
Your designs are approved.

Now let’s get your listing in front of buyers. I can handle the distribution for you.

Instagram
Feed post, story and reel
Connected
Facebook
Listing post and video
Connected
Email campaign
Send to selected CRM contacts
Connected
Property website
Publish listing landing page
Connected
LinkedIn
Professional listing announcement
Connect
TikTok
Vertical property video
Connect
Go ahead
Skip Facebook
Send the flyer to my printer
K
Mel
```

Accessible labels: MEL message; Destinations; Connect LinkedIn; Connect TikTok; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 8 Where it goes, light
`MktM07Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM07Light.html) · [PNG](/screens/assistants/png/MktM07Light.png)

Same content as `MktM07` in the other theme.

### 9 Review Instagram, dark
`MktM08Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM08Dark.html) · [PNG](/screens/assistants/png/MktM08Dark.png)

```text
Go ahead

Let’s start with Instagram. This is exactly what goes out.

Instagram

3 pieces · @[YOUR HANDLE]

Just listed. 123 Ocean View Drive, [BEDS] beds, [BATHS] baths, ocean views from the living room. Tour link in bio.

#justlisted #oceanview #[CITY]homes #[YOUR BROKERAGE]

New on the market: 123 Ocean View Drive. Tap the link for the full tour.

Link sticker: property website

Walk through 123 Ocean View Drive in 30 seconds. Open house [DATE].

#realestate #housetour #justlisted

Posts as soon as you tap

Post to Instagram
Change the reel caption
Remove the story
Post it tomorrow at 9 AM
K
Mel
```

Accessible labels: Your message; MEL message; Instagram draft; Pieces; Expand piece 1; Expand piece 2; Expand piece 3; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 9 Review Instagram, light
`MktM08Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM08Light.html) · [PNG](/screens/assistants/png/MktM08Light.png)

Same content as `MktM08` in the other theme.

### 13 Campaign live, dark
`MktM09Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM09Dark.html) · [PNG](/screens/assistants/png/MktM09Dark.png)

```text
Your listing campaign is live.

Instagram
Feed post, story and reel
Published
Facebook
Listing post and video
Published
Property website
Live at [YOUR SITE]
Live
Email
Sent to 40 active buyers
Sent
Show how the posts are doing
Share the property website link
Save this as my routine
K
Mel
```

Accessible labels: MEL message; Results; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 13 Campaign live, light
`MktM09Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM09Light.html) · [PNG](/screens/assistants/png/MktM09Light.png)

Same content as `MktM09` in the other theme.

### 14 Save as routine, dark
`MktM10Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM10Dark.html) · [PNG](/screens/assistants/png/MktM10Dark.png)

```text
Your listing marketing is all set! 🎉

One last thing...

Would you like me to do all of this automatically for your active listings going forward?

I can monitor your listings and, whenever a new listing goes active, automatically:

Create all your branded marketing designs using your saved template, colors, and logo.
Generate social media posts, reels, TikTok videos, flyers, email campaigns, yard signs, and a property website.
Prepare social media posts for Instagram, Facebook, LinkedIn, and TikTok.
Identify matching buyers in your CRM and prepare targeted emails.
Prepare print-ready materials for your preferred vendors.
Publish the listing website.

I’ll take care of the preparation and ask for your approval before anything goes live or gets sent.

Want to save this as your default listing marketing routine?
Yes, automate with my approval
Yes, fully automate approved actions
No, I’ll run it manually
K
Mel
```

Accessible labels: MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 14 Save as routine, light
`MktM10Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM10Light.html) · [PNG](/screens/assistants/png/MktM10Light.png)

Same content as `MktM10` in the other theme.

### 15 Routine set, dark
`MktM11Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM11Dark.html) · [PNG](/screens/assistants/png/MktM11Dark.png)

```text
Perfect! Your Listing Marketing Routine is ready! 🚀

From now on, whenever you have a new active listing, I’ll automatically prepare its complete marketing package using your preferred designs and branding.

I’ll also keep track of listing changes, so your marketing stays current.

You’ll receive a notification when your marketing package is ready, and I’ll handle publishing and distribution according to the permissions you’ve selected.

You can change, pause, or turn off this routine anytime.

Your listings. Your brand. Your AI marketing team. All handled by Mel.
Show my routine
Pause the routine
Start a package for another listing
K
Mel
```

Accessible labels: MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 15 Routine set, light
`MktM11Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktM11Light.html) · [PNG](/screens/assistants/png/MktM11Light.png)

Same content as `MktM11` in the other theme.

### Viewer, top, dark
`MktV1Dark` · 390×844 · [HTML](/screens/assistants/MktV1Dark.html) · [PNG](/screens/assistants/png/MktV1Dark.png)

```text
Page 1 of 6

Instagram & Facebook Post

Feed post + story formats

Video
Page 2 of 6

Instagram Reel & TikTok

Vertical video with captions

PDF shows a poster frame. Play it here or download the MP4.

Page 3 of 6

Property Flyer

Print-ready PDF design

Page 4 of 6

Email Campaign

Branded email template

Page 5 of 6

Property Website

Mobile-responsive landing page

Page 6 of 6

Yard Sign

Print-ready sign artwork

Marketing Package
123 Ocean View Dr · Sample output
```

Accessible labels: Page 1 of 6; Page 2 of 6; Play video; Page 3 of 6; Page 4 of 6; Page 5 of 6; Page 6 of 6; Back to chat; Share; Download

### Viewer, top, light
`MktV1Light` · 390×844 · [HTML](/screens/assistants/MktV1Light.html) · [PNG](/screens/assistants/png/MktV1Light.png)

Same content as `MktV1` in the other theme.

### Viewer, video page, dark
`MktV2Dark` · 390×844 · [HTML](/screens/assistants/MktV2Dark.html) · [PNG](/screens/assistants/png/MktV2Dark.png)

```text
Video
Page 2 of 6

Instagram Reel & TikTok

Vertical video with captions

PDF shows a poster frame. Play it here or download the MP4.

Page 3 of 6

Property Flyer

Print-ready PDF design

Page 4 of 6

Email Campaign

Branded email template

Page 5 of 6

Property Website

Mobile-responsive landing page

Page 6 of 6

Yard Sign

Print-ready sign artwork

Marketing Package
123 Ocean View Dr · Sample output
```

Accessible labels: Page 2 of 6; Play video; Page 3 of 6; Page 4 of 6; Page 5 of 6; Page 6 of 6; Back to chat; Share; Download

### Viewer, video page, light
`MktV2Light` · 390×844 · [HTML](/screens/assistants/MktV2Light.html) · [PNG](/screens/assistants/png/MktV2Light.png)

Same content as `MktV2` in the other theme.

### Viewer, video playing, dark
`MktV3Dark` · 390×844 · [HTML](/screens/assistants/MktV3Dark.html) · [PNG](/screens/assistants/png/MktV3Dark.png)

```text
Playing
Page 2 of 6

Instagram Reel & TikTok

Vertical video with captions

PDF shows a poster frame. Play it here or download the MP4.

Page 3 of 6

Property Flyer

Print-ready PDF design

Page 4 of 6

Email Campaign

Branded email template

Page 5 of 6

Property Website

Mobile-responsive landing page

Page 6 of 6

Yard Sign

Print-ready sign artwork

Marketing Package
123 Ocean View Dr · Sample output
```

Accessible labels: Page 2 of 6; Pause video; Page 3 of 6; Page 4 of 6; Page 5 of 6; Page 6 of 6; Back to chat; Share; Download

### Viewer, video playing, light
`MktV3Light` · 390×844 · [HTML](/screens/assistants/MktV3Light.html) · [PNG](/screens/assistants/png/MktV3Light.png)

Same content as `MktV3` in the other theme.

### Share sheet, dark
`MktV4Dark` · 390×844 · [HTML](/screens/assistants/MktV4Dark.html) · [PNG](/screens/assistants/png/MktV4Dark.png)

```text
Video
Page 2 of 6

Instagram Reel & TikTok

Vertical video with captions

PDF shows a poster frame. Play it here or download the MP4.

Page 3 of 6

Property Flyer

Print-ready PDF design

Page 4 of 6

Email Campaign

Branded email template

Page 5 of 6

Property Website

Mobile-responsive landing page

Page 6 of 6

Yard Sign

Print-ready sign artwork

Marketing Package
123 Ocean View Dr · Sample output

Share

Package as PDF
All 6 assets in one file. Video pages show a poster frame.
Page as image
Page 2 of 6 as a PNG.
Video file
Instagram Reel & TikTok as MP4.
Share
```

Accessible labels: Page 2 of 6; Play video; Page 3 of 6; Page 4 of 6; Page 5 of 6; Page 6 of 6; Back to chat; Share; Download

### Share sheet, light
`MktV4Light` · 390×844 · [HTML](/screens/assistants/MktV4Light.html) · [PNG](/screens/assistants/png/MktV4Light.png)

Same content as `MktV4` in the other theme.

### Download sheet, dark
`MktV5Dark` · 390×844 · [HTML](/screens/assistants/MktV5Dark.html) · [PNG](/screens/assistants/png/MktV5Dark.png)

```text
Video
Page 2 of 6

Instagram Reel & TikTok

Vertical video with captions

PDF shows a poster frame. Play it here or download the MP4.

Page 3 of 6

Property Flyer

Print-ready PDF design

Page 4 of 6

Email Campaign

Branded email template

Page 5 of 6

Property Website

Mobile-responsive landing page

Page 6 of 6

Yard Sign

Print-ready sign artwork

Marketing Package
123 Ocean View Dr · Sample output

Download

Package PDF
6 pages, video pages as poster frames
Images
5 PNG files, one per design
Videos
1 MP4 file
Download
```

Accessible labels: Page 2 of 6; Play video; Page 3 of 6; Page 4 of 6; Page 5 of 6; Page 6 of 6; Back to chat; Share; Download

### Download sheet, light
`MktV5Light` · 390×844 · [HTML](/screens/assistants/MktV5Light.html) · [PNG](/screens/assistants/png/MktV5Light.png)

Same content as `MktV5` in the other theme.

### No listings found, dark
`MktR1Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR1Dark.html) · [PNG](/screens/assistants/png/MktR1Dark.png)

```text
CA-01234567, California

I could not find any active listings for license CA-01234567 in California.

Nothing has been created yet. Here is what we can do.

MLS
Find your listings automatically
Connect
Try another license number
Add a listing manually
Check again later
K
Mel
```

Accessible labels: Your message; MEL message; Connect MLS; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### No listings found, light
`MktR1Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR1Light.html) · [PNG](/screens/assistants/png/MktR1Light.png)

Same content as `MktR1` in the other theme.

### Several profiles, dark
`MktR2Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR2Dark.html) · [PNG](/screens/assistants/png/MktR2Dark.png)

```text
I found 2 agent profiles under this license and 12 active listings.

Which profile should I use? I show its listings next. I make one package per listing.

Jordan Lee · 9 listings
Jordan Lee Team · 3 listings
K
Mel
```

Accessible labels: MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Several profiles, light
`MktR2Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR2Light.html) · [PNG](/screens/assistants/png/MktR2Light.png)

Same content as `MktR2` in the other theme.

### Missing photos or details, dark
`MktR3Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR3Dark.html) · [PNG](/screens/assistants/png/MktR3Dark.png)

```text
123 Ocean View Drive is missing a few things I need before I design.

I only ask for what is missing. Everything else comes from your listing.

Photos
1 found, 5 recommended
Needs photos
Bedrooms
Not in listing data
Missing
Upload photos
It has 4 bedrooms
Continue with placeholders
K
Mel
```

Accessible labels: MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Missing photos or details, light
`MktR3Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR3Light.html) · [PNG](/screens/assistants/png/MktR3Light.png)

Same content as `MktR3` in the other theme.

### Missing logo, dark
`MktR4Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR4Dark.html) · [PNG](/screens/assistants/png/MktR4Dark.png)

```text
I could not find a logo on your profile.

Choose how the designs should handle it. You can change this later.

Upload a logo
Use my name as text
Continue without a logo
K
Mel
```

Accessible labels: MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Missing logo, light
`MktR4Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR4Light.html) · [PNG](/screens/assistants/png/MktR4Light.png)

Same content as `MktR4` in the other theme.

### Partial generation, dark
`MktR5Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR5Dark.html) · [PNG](/screens/assistants/png/MktR5Dark.png)

```text
4 designs are ready. The reel did not finish and the website is still generating.

I will retry only the reel. Your ready designs stay as they are.

Instagram & Facebook Post
4:5 · saved
Ready
Instagram Reel & TikTok
Video render timed out
Failed
Property Flyer
Print-ready PDF · saved
Ready
Email Campaign
Saved
Ready
Property Website
Generating
In progress
Retry reel only
Continue without the reel
K
Mel
```

Accessible labels: MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Partial generation, light
`MktR5Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR5Light.html) · [PNG](/screens/assistants/png/MktR5Light.png)

Same content as `MktR5` in the other theme.

### Edit after approval, dark
`MktR6Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR6Dark.html) · [PNG](/screens/assistants/png/MktR6Dark.png)

```text
Change the flyer headline to Ocean Views, Move-In Ready

Done. Because you already approved this package, I only reopen what this headline touches.

Nothing has been published or sent yet.

Property Flyer
Headline changes
Needs re-approval
Yard Sign
Uses the same headline
Needs re-approval
Post, Reel, Email, Website
Not affected
Approval kept
Update 2 designs
Cancel change
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Edit after approval, light
`MktR6Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR6Light.html) · [PNG](/screens/assistants/png/MktR6Light.png)

Same content as `MktR6` in the other theme.

### Expired connection, dark
`MktR7Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR7Dark.html) · [PNG](/screens/assistants/png/MktR7Dark.png)

```text
Before I publish, one connection needs attention.

I will not publish to Instagram until you reconnect it.

Instagram
Authorization expired
Reconnect
Facebook
Connected
Ready
Email
Ready
Ready
Continue without Instagram
K
Mel
```

Accessible labels: MEL message; Reconnect Instagram; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Expired connection, light
`MktR7Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR7Light.html) · [PNG](/screens/assistants/png/MktR7Light.png)

Same content as `MktR7` in the other theme.

### Partial publishing, dark
`MktR8Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR8Dark.html) · [PNG](/screens/assistants/png/MktR8Dark.png)

```text
Your campaign went out in part. It is not fully live.

Before I retry Facebook, I will check whether the post already went through, so nothing is posted twice.

Campaign partly published
Instagram
Post and story published
Published
Facebook
Post failed, status unconfirmed
Failed
Email
Sent to 38 of 40 recipients
Partly sent
Check Facebook, then retry
Review the 2 unsent emails
K
Mel
```

Accessible labels: MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Partial publishing, light
`MktR8Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR8Light.html) · [PNG](/screens/assistants/png/MktR8Light.png)

Same content as `MktR8` in the other theme.

### Listing changed, dark
`MktR9Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR9Dark.html) · [PNG](/screens/assistants/png/MktR9Dark.png)

```text
This listing changed after you approved the package.

I marked the designs that no longer match. Published posts stay as they are until you approve updates.

Price and photos changed
$2,450,000 is now $2,395,000. 2 new photos were added.
Post, Flyer, Email, Website
Show the old price
Outdated
Yard Sign
Shows the old price
Outdated
Reel
No price shown
Current
Update 5 outdated designs
Keep as is
K
Mel
```

Accessible labels: MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Listing changed, light
`MktR9Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR9Light.html) · [PNG](/screens/assistants/png/MktR9Light.png)

Same content as `MktR9` in the other theme.

### Change or pause routine, dark
`MktR10Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR10Dark.html) · [PNG](/screens/assistants/png/MktR10Dark.png)

```text
Your Listing Marketing Routine is running.

What would you like to change?

Packages already in progress will finish. Nothing already published is changed.

Change approval mode
Pause the routine
Turn the routine off
Keep it running
K
Mel
```

Accessible labels: MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Change or pause routine, light
`MktR10Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktR10Light.html) · [PNG](/screens/assistants/png/MktR10Light.png)

Same content as `MktR10` in the other theme.

### 10 Review Facebook, dark
`MktC1Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktC1Dark.html) · [PNG](/screens/assistants/png/MktC1Dark.png)

```text
Instagram · Posted

Now Facebook. This is exactly what goes out.

Facebook

2 pieces · [YOUR PAGE]

Just listed in [CITY]. 123 Ocean View Drive has [BEDS] beds, [BATHS] baths and ocean views. Message me for a private showing.

#justlisted #[CITY]realestate

Take a 30 second tour of 123 Ocean View Drive. Open house [DATE].

#housetour #openhouse

Posts as soon as you tap

Post to Facebook
Use the Instagram caption
Skip Facebook
Post it tomorrow at 9 AM
K
Mel
```

Accessible labels: MEL message; Facebook draft; Pieces; Expand piece 1; Expand piece 2; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 10 Review Facebook, light
`MktC1Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktC1Light.html) · [PNG](/screens/assistants/png/MktC1Light.png)

Same content as `MktC1` in the other theme.

### 5 Designing, dark
`MktC2Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktC2Dark.html) · [PNG](/screens/assistants/png/MktC2Dark.png)

```text
Make a marketing package for 123 Ocean View Drive

On it. Designing 6 pieces for 123 Ocean View Drive.

Designing · 2 of 6 ready

K
Mel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Message MEL; Stop Mel; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 5 Designing, light
`MktC2Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktC2Light.html) · [PNG](/screens/assistants/png/MktC2Light.png)

Same content as `MktC2` in the other theme.

### Mixed result, dark
`MktC3Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktC3Dark.html) · [PNG](/screens/assistants/png/MktC3Dark.png)

```text
Here is where your campaign stands. It is not fully live.

3 of 5 destinations complete
Instagram
Published
Published
Facebook
Published after status check
Published
Email
38 sent, 2 failed: invalid address
Partly sent
LinkedIn
Not connected, skipped
Connect
TikTok
Not connected, skipped
Connect
Fix 2 email addresses
Show the 2 failed emails
K
Mel
```

Accessible labels: MEL message; Results; Connect LinkedIn; Connect TikTok; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Mixed result, light
`MktC3Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktC3Light.html) · [PNG](/screens/assistants/png/MktC3Light.png)

Same content as `MktC3` in the other theme.

### Failed result, dark
`MktC4Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktC4Dark.html) · [PNG](/screens/assistants/png/MktC4Dark.png)

```text
Nothing went live. No post was published and no email was sent.

Your designs are saved.

Distribution failed
Instagram
Authorization expired
Reconnect
Facebook
Service did not respond
Failed
Email
Sender not verified
Verify
Retry Facebook
Retry everything
K
Mel
```

Accessible labels: MEL message; Results; Reconnect Instagram; Verify Email; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Failed result, light
`MktC4Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktC4Light.html) · [PNG](/screens/assistants/png/MktC4Light.png)

Same content as `MktC4` in the other theme.

### Routine status, dark
`MktC5Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktC5Dark.html) · [PNG](/screens/assistants/png/MktC5Dark.png)

```text
Manage my listing routine

Here is your routine.

Listing Marketing Routine
Running
Approval mode
Mel asks before anything goes out
Ask first
Destinations
Instagram, Facebook, Email
3 connected
Recipients
Active buyers matching the listing
Last run
88 Harbor Lane, waiting for your approval
Needs you
Approve 88 Harbor Lane
Change approval mode
Pause the routine
Turn the routine off
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Routine status, light
`MktC5Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktC5Light.html) · [PNG](/screens/assistants/png/MktC5Light.png)

Same content as `MktC5` in the other theme.

### Connect destinations, dark
`MktC6Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktC6Dark.html) · [PNG](/screens/assistants/png/MktC6Dark.png)

```text
To publish, each destination must be connected. I only publish to the ones that are.

Instagram
@jordanlee.homes
Connected
Facebook
Jordan Lee Realty
Connected
LinkedIn
Not connected
Connect
TikTok
Not connected
Connect
Email sender
Verify your sending address
Verify
Continue with the 2 connected
Skip TikTok for now
K
Mel
```

Accessible labels: MEL message; Destinations; Connect LinkedIn; Connect TikTok; Verify Email sender; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Connect destinations, light
`MktC6Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktC6Light.html) · [PNG](/screens/assistants/png/MktC6Light.png)

Same content as `MktC6` in the other theme.

### Chat live, dark copy
`ChatLiveDark-lo57` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/ChatLiveDark-lo57.html) · [PNG](/screens/assistants/png/ChatLiveDark-lo57.png)

```text
Hi, I’m MEL, your real estate assistant. I can help with your listings, clients and everyday tasks. What would you like to work on first?

Marketing
Posts, reels, flyers and emails for any listing.
1,216
Imported
812
Buyers
404
Sellers
32
Skipped
CRM
Import contacts, track leads and draft follow-ups.
Day 1 · Email
Day 3 · Text
Day 7 · Call reminder
Campaigns
Drip emails and texts that run on their own.
Is the open house still on Saturday?
Yes, 1 to 4 PM. I’ll send the address.
Client experience
Keep clients updated and answer their questions.
✓
Purchase agreement
✓
Seller disclosures
!
Inspection report missing
Compliance
Check transaction files and flag what is missing.
Purchase agreement.pdf
4 pages
Signed · 2 of 2
Documents
Fill, summarise and send documents for signing.
MEL
Speak
```

Accessible labels: MEL message; What Mel can do; Marketing: Posts, reels, flyers and emails for any listing.; Mel; CRM: Import contacts, track leads and draft follow-ups.; Campaigns: Drip emails and texts that run on their own.; Client experience: Keep clients updated and answer their questions.; Compliance: Check transaction files and flag what is missing.; Documents: Fill, summarise and send documents for signing.; Back to Radius home; New chat; More; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### CRM welcome, light copy
`CrmWelcomeLight-xga7` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmWelcomeLight-xga7.html) · [PNG](/screens/assistants/png/CrmWelcomeLight-xga7.png)

```text
Let’s bring your contacts together so I can help you manage relationships and follow-ups.

How would you like to add your contacts?

Upload a CSV
Import from another CRM
I’ll add contacts later
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### 6 Package ready, dark
`MktC2bDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktC2bDark.html) · [PNG](/screens/assistants/png/MktC2bDark.png)

```text
Designed · 6 of 6

Your marketing package is ready.

I made 6 designs from your listing photos, details and brand.

Take a look. Ask me to change anything.

Listing marketing package

123 Ocean View Drive · 6 designs

+3
Publish it
Change the flyer headline
Make it in another style
K
Mel
```

Accessible labels: MEL message; Open your listing marketing package; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 6 Package ready, light
`MktC2bLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktC2bLight.html) · [PNG](/screens/assistants/png/MktC2bLight.png)

Same content as `MktC2b` in the other theme.

### 12 Review email, dark
`MktPubEmailDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktPubEmailDark.html) · [PNG](/screens/assistants/png/MktPubEmailDark.png)

```text
Instagram, Facebook and website · Live

Now the email.

I found 40 active buyers that match this listing. Do you want to send it to other lists too?

Email

1 email · from [YOUR EMAIL]

To · 40 buyers

maya.chen@gmail.com, james.ortiz@outlook.com, priya.nair@yahoo.com, tom.becker@icloud.com, aisha.khan@gmail.com, luis.ramos@outlook.com, emma.walsh@yahoo.com, noah.kim@icloud.com, sofia.rossi@gmail.com, daniel.park@outlook.com, olivia.grant@yahoo.com, ravi.menon@icloud.com, hannah.lee@gmail.com, marcus.reed@outlook.com, chloe.martin@yahoo.com, ethan.brooks@icloud.com, nina.patel@gmail.com, owen.hughes@outlook.com, zara.ali@yahoo.com, ben.carter@icloud.com, lily.nguyen@gmail.com, sam.foster@outlook.com, grace.wu@yahoo.com, leo.santos@icloud.com, ava.morgan@gmail.com, kai.tanaka@outlook.com, ruby.evans@yahoo.com, omar.haddad@icloud.com, ella.price@gmail.com, jack.turner@outlook.com, mia.lopez@yahoo.com, adam.cole@icloud.com, isla.ward@gmail.com, ryan.shah@outlook.com, zoe.bennett@yahoo.com, alex.young@icloud.com, nora.fischer@gmail.com, eli.cooper@outlook.com, tara.singh@yahoo.com, max.howard@icloud.com

Show more
Upload CSV
Add a client

Subject

Just listed: 123 Ocean View Drive

Email

Hi [FIRST NAME], a home that fits what you told me just came on the market. 123 Ocean View Drive, [BEDS] beds, [BATHS] baths. Want to see it before the open house on [DATE]?

Sends when you send

Send
Remove someone
Add my sphere list
Change the subject
K
Mel
```

Accessible labels: MEL message; Email draft; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 12 Review email, light
`MktPubEmailLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktPubEmailLight.html) · [PNG](/screens/assistants/png/MktPubEmailLight.png)

Same content as `MktPubEmail` in the other theme.

### Review all, Instagram, dark
`MktPubViewerDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktPubViewerDark.html) · [PNG](/screens/assistants/png/MktPubViewerDark.png)

```text
1 of 12 · Feed post

Just listed. 123 Ocean View Drive, [BEDS] beds, [BATHS] baths. Tour link in bio.

#justlisted #oceanview #[CITY]homes

2 of 12 · Feed post

The kitchen at 123 Ocean View Drive. [FEATURE].

#justlisted #oceanview #[CITY]homes

3 of 12 · Feed post

Sunset from the deck. Open house [DATE].

#justlisted #oceanview #[CITY]homes

4 of 12 · Feed post

The primary suite. [FEATURE].

#justlisted #oceanview #[CITY]homes

5 of 12 · Feed post

Neighbourhood: [NEARBY PLACES].

#justlisted #oceanview #[CITY]homes

6 of 12 · Feed post

Priced at [PRICE]. Message me for a showing.

#justlisted #oceanview #[CITY]homes

7 of 12 · Story

New on the market. Tap for the tour.

#justlisted #oceanview #[CITY]homes

8 of 12 · Story

Open house [DATE]. Tap to save it.

#justlisted #oceanview #[CITY]homes

9 of 12 · Story

Swipe through the rooms.

#justlisted #oceanview #[CITY]homes

10 of 12 · Story

Ask me anything about this home.

#justlisted #oceanview #[CITY]homes

11 of 12 · Reel

Walk through 123 Ocean View Drive in 30 seconds.

#justlisted #oceanview #[CITY]homes

12 of 12 · Reel

Golden hour at 123 Ocean View Drive.

#justlisted #oceanview #[CITY]homes

Instagram
12 pieces · 123 Ocean View Dr
```

Accessible labels: Piece 1 of 12; Piece 2 of 12; Piece 3 of 12; Piece 4 of 12; Piece 5 of 12; Piece 6 of 12; Piece 7 of 12; Piece 8 of 12; Piece 9 of 12; Piece 10 of 12; Piece 11 of 12; Piece 12 of 12; Back to chat

### Review all, Instagram, light
`MktPubViewerLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktPubViewerLight.html) · [PNG](/screens/assistants/png/MktPubViewerLight.png)

Same content as `MktPubViewer` in the other theme.

### Stopped while designing, dark
`MktStopDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktStopDark.html) · [PNG](/screens/assistants/png/MktStopDark.png)

```text
Make a marketing package for 123 Ocean View Drive

On it. Designing 6 pieces for 123 Ocean View Drive.

Stopped · 2 of 6 ready

Stopped. 2 of 6 pieces are ready.

Tell me what to change, or I can finish the rest.

Finish the rest
Show the 2 ready
Start over
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Stopped while designing, light
`MktStopLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktStopLight.html) · [PNG](/screens/assistants/png/MktStopLight.png)

Same content as `MktStop` in the other theme.

### Typed while designing, dark
`MktNewChatDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktNewChatDark.html) · [PNG](/screens/assistants/png/MktNewChatDark.png)

```text
Make a marketing package for 123 Ocean View Drive

On it. Designing 6 pieces for 123 Ocean View Drive.

Designing · 2 of 6 ready

K
Mel

Start a new chat?

Mel is still designing in this chat. It stays in your history, so you can come back to it. Your message opens in a new chat.

New chat
Cancel
```

Accessible labels: Your message; MEL message; Profile; Notifications, new; Message composer; Message MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Typed while designing, light
`MktNewChatLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktNewChatLight.html) · [PNG](/screens/assistants/png/MktNewChatLight.png)

Same content as `MktNewChat` in the other theme.

### No clients for the email, dark
`MktNoClientsDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktNoClientsDark.html) · [PNG](/screens/assistants/png/MktNoClientsDark.png)

```text
Instagram, Facebook and website · Live

Now the email.

You have no clients in Mel yet, so this email has no one to go to. Upload a CSV or add a client, and I’ll pick the buyers who match.

Email

1 email · from [YOUR EMAIL]

To

No recipients yet

Upload CSV
Add a client

Subject

Just listed: 123 Ocean View Drive

Email

Hi [FIRST NAME], a home that fits what you told me just came on the market. 123 Ocean View Drive, [BEDS] beds, [BATHS] baths. Want to see it before the open house on [DATE]?

Needs at least 1 recipient

Send
Skip email
K
Mel
```

Accessible labels: MEL message; Email draft; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### No clients for the email, light
`MktNoClientsLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktNoClientsLight.html) · [PNG](/screens/assistants/png/MktNoClientsLight.png)

Same content as `MktNoClients` in the other theme.

### 11 Review website, dark
`MktPubWebDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktPubWebDark.html) · [PNG](/screens/assistants/png/MktPubWebDark.png)

```text
Instagram and Facebook · Posted

Now the property website. This is exactly what goes live.

Property website

1 page · public link

Copy link

Listing website

Goes live as soon as you tap

Publish website
Change the page headline
Hide the price
Use my own domain
K
Mel
```

Accessible labels: MEL message; Property website draft; Pieces; Open the listing website, mobile view; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 11 Review website, light
`MktPubWebLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktPubWebLight.html) · [PNG](/screens/assistants/png/MktPubWebLight.png)

Same content as `MktPubWeb` in the other theme.

### CSV uploaded for the email, dark
`MktCsvDoneDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktCsvDoneDark.html) · [PNG](/screens/assistants/png/MktCsvDoneDark.png)

```text
contacts.csv

CSV · 1,248 rows

Imported · contacts.csv

1,216

Imported

32

Duplicates skipped

812

Buyers

404

Sellers

18 of your buyers match this listing. I added them to the email.

Email

1 email · from [YOUR EMAIL]

To · 18 buyers

maya.chen@gmail.com, james.ortiz@outlook.com, priya.nair@yahoo.com, tom.becker@icloud.com, aisha.khan@gmail.com, luis.ramos@outlook.com, emma.walsh@yahoo.com, noah.kim@icloud.com, sofia.rossi@gmail.com, daniel.park@outlook.com, olivia.grant@yahoo.com, ravi.menon@icloud.com, hannah.lee@gmail.com, marcus.reed@outlook.com, chloe.martin@yahoo.com, ethan.brooks@icloud.com, nina.patel@gmail.com, owen.hughes@outlook.com

Show more
Upload CSV
Add a client

Subject

Just listed: 123 Ocean View Drive

Email

Hi [FIRST NAME], a home that fits what you told me just came on the market. 123 Ocean View Drive, [BEDS] beds, [BATHS] baths. Want to see it before the open house on [DATE]?

Sends when you send

Send
Show the other buyers
Remove someone
Change the subject
K
Mel
```

Accessible labels: Your message; Import result; MEL message; Email draft; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### CSV uploaded for the email, light
`MktCsvDoneLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktCsvDoneLight.html) · [PNG](/screens/assistants/png/MktCsvDoneLight.png)

Same content as `MktCsvDone` in the other theme.

### Client added for the email, dark
`MktClientAddedDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktClientAddedDark.html) · [PNG](/screens/assistants/png/MktClientAddedDark.png)

```text
Add a client: Maya Chen, maya.chen@gmail.com, buyer

Added Maya Chen as a buyer. She is on the email.

Email

1 email · from [YOUR EMAIL]

To · 1 client

maya.chen@gmail.com

Upload CSV
Add a client

Subject

Just listed: 123 Ocean View Drive

Email

Hi [FIRST NAME], a home that fits what you told me just came on the market. 123 Ocean View Drive, [BEDS] beds, [BATHS] baths. Want to see it before the open house on [DATE]?

Sends when you send

Send
Add another client
Upload a CSV
Change the subject
K
Mel
```

Accessible labels: Your message; MEL message; Email draft; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Client added for the email, light
`MktClientAddedLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktClientAddedLight.html) · [PNG](/screens/assistants/png/MktClientAddedLight.png)

Same content as `MktClientAdded` in the other theme.

### B1 What to create, dark
`MktB1Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktB1Dark.html) · [PNG](/screens/assistants/png/MktB1Dark.png)

```text
123 Ocean View Drive

What do you want to create for 123 Ocean View Drive? Pick one or more, or tell me in your own words.

Social posts
Feed and story
Reels
Short vertical video
Video
Listing tour
Emailer
To your clients
Flyer
Print-ready PDF
Property website
Mobile landing page
K
Mel
```

Accessible labels: Your message; MEL message; What to create; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### B1 What to create, light
`MktB1Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktB1Light.html) · [PNG](/screens/assistants/png/MktB1Light.png)

Same content as `MktB1` in the other theme.

### B2 Where it goes, dark
`MktB2Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktB2Dark.html) · [PNG](/screens/assistants/png/MktB2Dark.png)

```text
Create social posts and reels

Where should the posts and reels go? Pick one or more.

Instagram
Feed, story, reel
Facebook
Post and video
LinkedIn
Post
TikTok
Vertical video
K
Mel
```

Accessible labels: Your message; MEL message; Where it goes; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### B2 Where it goes, light
`MktB2Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktB2Light.html) · [PNG](/screens/assistants/png/MktB2Light.png)

Same content as `MktB2` in the other theme.

### B3 Templates for your picks, dark
`MktB3Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktB3Dark.html) · [PNG](/screens/assistants/png/MktB3Dark.png)

```text
Post them on Instagram and Facebook

Here are templates sized for Instagram and Facebook: 4:5 for feed posts, 9:16 for stories and reels. Pick one or more.

Modern Minimal
Luxury Editorial
Bold & Vibrant
Classic Real Estate
Lifestyle & Storytelling
K
Mel
```

Accessible labels: Your message; MEL message; Design styles; Modern Minimal; Preview Modern Minimal; Luxury Editorial; Preview Luxury Editorial; Bold & Vibrant; Preview Bold & Vibrant; Classic Real Estate; Preview Classic Real Estate; Lifestyle & Storytelling; Preview Lifestyle & Storytelling; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### B3 Templates for your picks, light
`MktB3Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktB3Light.html) · [PNG](/screens/assistants/png/MktB3Light.png)

Same content as `MktB3` in the other theme.

### B4 One message skips steps, dark
`MktB4Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktB4Dark.html) · [PNG](/screens/assistants/png/MktB4Dark.png)

```text
Make an Instagram post and reel for 123 Ocean View Drive

Skipped · what to create, where it goes

Got it. An Instagram post and reel for 123 Ocean View Drive.

Pick a style for them.

Modern Minimal
Luxury Editorial
Bold & Vibrant
Classic Real Estate
Lifestyle & Storytelling
K
Mel
```

Accessible labels: Your message; MEL message; Design styles; Modern Minimal; Preview Modern Minimal; Luxury Editorial; Preview Luxury Editorial; Bold & Vibrant; Preview Bold & Vibrant; Classic Real Estate; Preview Classic Real Estate; Lifestyle & Storytelling; Preview Lifestyle & Storytelling; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### B4 One message skips steps, light
`MktB4Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/MktB4Light.html) · [PNG](/screens/assistants/png/MktB4Light.png)

Same content as `MktB4` in the other theme.

### Chat live, light copy
`ChatLiveLight-lo57` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/ChatLiveLight-lo57.html) · [PNG](/screens/assistants/png/ChatLiveLight-lo57.png)

Same content as `ChatLive-lo57` in the other theme.

## Campaigns skill flow

Designer notes:

- **Campaign happy path**
- An agent sets up a client campaign by chatting with Mel. Tap a prompt to fill the box, then send to move on.
- ENGINEERING RULES
  
  Backend does the work. Frontend shows prompts, status and cards only.
  
  Audience: Mel shows the real matching count, email and text reach, and excluded contacts before launch.
  
  Playbook: real file attach. Agent never prepares a special format.
  
  Launch: validate recipients, channel consent, suppression lists, sender setup, message limits and unsubscribe handling before scheduling.
  
  No edit buttons. Changes come from chat. Approve & Launch stays, like Send.
- OPEN FOR KJ
  
  “!” stripped from Biju copy. Words kept.
  
  Biju forms (audience, goals, channels, start, frequency) are now prompts. Goals append, so several can be picked.
  
  “Run campaigns” pill added to the footer on this page only.
  
  Numbers, names and the day 3 rewrite are sample data.
- **Variant: bring your playbook**
- **Recovery**

### 1 Meet Mel, dark
`CmpH01Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH01Dark.html) · [PNG](/screens/assistants/png/CmpH01Dark.png)

```text
Run a campaign

Hey 👋 I’m Mel, your AI Campaign Assistant.

Let’s create a personalized marketing campaign to stay connected with your clients, strengthen relationships, and turn more conversations into opportunities.

I can create and manage your email and text campaigns, personalize messages for each client, and help move conversations toward your goals.

Since your contacts are already in Radius CRM, we can get started right away.

First, which clients would you like to reach?

Buyers
Sellers
Past clients
Prospects and leads
All eligible CRM contacts
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 1 Meet Mel, light
`CmpH01Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH01Light.html) · [PNG](/screens/assistants/png/CmpH01Light.png)

Same content as `CmpH01` in the other theme.

### 2 Who to reach, dark
`CmpH02Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH02Dark.html) · [PNG](/screens/assistants/png/CmpH02Dark.png)

```text
Buyers

Let’s choose who should receive this campaign. You can select a group of clients, apply filters, or simply describe the audience you have in mind.

Active and nurture buyers
Buyers in Austin
Not contacted in 90 days
Keep all buyers
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 2 Who to reach, light
`CmpH02Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH02Light.html) · [PNG](/screens/assistants/png/CmpH02Light.png)

Same content as `CmpH02` in the other theme.

### 3 Audience and playbook, dark
`CmpH03Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH03Dark.html) · [PNG](/screens/assistants/png/CmpH03Dark.png)

```text
Active and nurture buyers in Austin

Audience preview
Active and nurture buyers, Austin
Matching contacts
86
Email ready
81
Text ready
64
Excluded, no consent
5

Great. Now, do you already have a marketing campaign or follow-up sequence you’ve been using?

You can upload your existing email templates, text messages, campaign documents, or playbook. I’ll learn your messaging style, sequence, and approach and use them to build your campaign.

Don’t have one? No problem. I’ll create one for you from scratch.

Upload my playbook
Create one from scratch
K
Mel
```

Accessible labels: Your message; Audience preview; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 3 Audience and playbook, light
`CmpH03Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH03Light.html) · [PNG](/screens/assistants/png/CmpH03Light.png)

Same content as `CmpH03` in the other theme.

### 4 Campaign goals, dark
`CmpH04Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH04Dark.html) · [PNG](/screens/assistants/png/CmpH04Dark.png)

```text
Create one from scratch

Perfect. What would you like this campaign to accomplish?

You can select one or more goals. I’ll tailor the messaging and follow-ups around those outcomes.

Book a meeting
Schedule a property showing
Collect buyer search criteria
Get a listing appointment
Reconnect with clients
Generate referrals
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 4 Campaign goals, light
`CmpH04Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH04Light.html) · [PNG](/screens/assistants/png/CmpH04Light.png)

Same content as `CmpH04` in the other theme.

### 5 Channels and start, dark
`CmpH05Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH05Dark.html) · [PNG](/screens/assistants/png/CmpH05Dark.png)

```text
Collect buyer search criteria, schedule a property showing

I’ll optimize your messages around the goals you’ve selected. When clients respond, I can help qualify their interest, update their CRM profiles, and recommend the next action.

Almost done. When should we start reaching out, and how would you like me to communicate with your clients?

Email and text, start tomorrow
Email only, start today after approval
Weekly outreach
Choose a date
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 5 Channels and start, light
`CmpH05Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH05Light.html) · [PNG](/screens/assistants/png/CmpH05Light.png)

Same content as `CmpH05` in the other theme.

### 6 Writing the campaign, dark
`CmpH06Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH06Dark.html) · [PNG](/screens/assistants/png/CmpH06Dark.png)

```text
Email and text, start tomorrow. You pick the sequence.

On it. I’ll message you when your campaign is ready. Keep chatting.

Writing your sequence · 2 of 4 messages

Show me the 86 buyers
Who replied to me last week
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 6 Writing the campaign, light
`CmpH06Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH06Light.html) · [PNG](/screens/assistants/png/CmpH06Light.png)

Same content as `CmpH06` in the other theme.

### 7 Campaign ready, dark
`CmpH07Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH07Dark.html) · [PNG](/screens/assistants/png/CmpH07Dark.png)

```text
Your campaign is ready 🎉

I’ve created a personalized email and text sequence based on your clients, campaign goals, and preferred communication style.

Here’s a preview of what I’ve prepared.

Buyer Engagement Campaign
4 touchpoints · 14 days
Draft
1
Day 1
Email
Introduction

Subject: Still thinking about your next home?

Hi Sarah,

I wanted to check in and see how your home search is going. Are you still considering buying, or have your plans changed?

I’d love to hear what you’re looking for and help you find the right home.

2
Day 3
Text
Personal follow-up

Hey Sarah. Just following up on your home search. Have your preferred locations or budget changed? Happy to help.

3
Day 7
Email
Capture search criteria

Hi Sarah. I’d love to send you homes that actually match what you’re looking for. What’s your ideal location, budget, and number of bedrooms?

4
Day 14
Text
Book a showing

Hey Sarah, I have a few homes in mind that might be a great fit. Would you like to schedule a showing this week?

How does this look?

I can change the tone, adjust the frequency, add more touchpoints, or rewrite the entire sequence.

Once you approve it, I’ll get everything ready to launch.

Looks good, continue
Make the day 3 text shorter
Add a touchpoint on day 21
Make it more casual
K
Mel
```

Accessible labels: MEL message; Campaign sequence; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 7 Campaign ready, light
`CmpH07Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH07Light.html) · [PNG](/screens/assistants/png/CmpH07Light.png)

Same content as `CmpH07` in the other theme.

### 8 Change by asking, dark
`CmpH08Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH08Dark.html) · [PNG](/screens/assistants/png/CmpH08Dark.png)

```text
Make the day 3 text shorter

Done. Day 3 is shorter.

Buyer Engagement Campaign
Day 3 updated
Draft
2
Day 3
Text
Personal follow-up

Hi Sarah, still looking? Happy to help.

Anything else, or ready to launch?

Looks good, continue
Show the full sequence
Undo that change
K
Mel
```

Accessible labels: Your message; MEL message; Campaign sequence; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 8 Change by asking, light
`CmpH08Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH08Light.html) · [PNG](/screens/assistants/png/CmpH08Light.png)

Same content as `CmpH08` in the other theme.

### 9 Approve and launch, dark
`CmpH09Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH09Dark.html) · [PNG](/screens/assistants/png/CmpH09Dark.png)

```text
Looks good, continue

Everything looks great. Ready to launch?

Once you activate, I’ll schedule the messages, personalize them for your clients, track responses, and keep your CRM updated.

When someone expresses interest, I’ll help move the conversation toward your campaign goals.

Campaign Launch Summary
Awaiting approval
Campaign
Buyer Engagement
Audience
Active buyer segment
Goals
Collect criteria + book showings
Channels
Email
Text
Sequence
4 touchpoints · 14 days
Start
After approval
Approve & Launch
Start next Monday instead
Remove the texts
K
Mel
```

Accessible labels: Your message; MEL message; Campaign launch summary; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 9b Full launch summary, dark
`CmpH09bDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH09bDark.html) · [PNG](/screens/assistants/png/CmpH09bDark.png)

```text
Everything looks great. Ready to launch?

Campaign Launch Summary
Awaiting approval
Campaign
Buyer Engagement
Audience
Active buyer segment
Goals
Collect criteria + book showings
Channels
Email
Text
Sequence
4 touchpoints · 14 days
Start
After approval
Approve & Launch
Start next Monday instead
Remove the texts
K
Mel
```

Accessible labels: MEL message; Campaign launch summary; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 9 Approve and launch, light
`CmpH09Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH09Light.html) · [PNG](/screens/assistants/png/CmpH09Light.png)

Same content as `CmpH09` in the other theme.

### 9b Full launch summary, light
`CmpH09bLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH09bLight.html) · [PNG](/screens/assistants/png/CmpH09bLight.png)

Same content as `CmpH09b` in the other theme.

### 10 Campaign live, dark
`CmpH10Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH10Dark.html) · [PNG](/screens/assistants/png/CmpH10Dark.png)

```text
Your campaign is live 🚀

I’ll take it from here.

I’ll send your approved messages according to the schedule, track responses, and keep your client records updated.

When a client responds, I can help qualify their interest, collect their preferences, and prepare the next step.

I’ll also notify you when someone wants to schedule a meeting, tour a property, or discuss selling their home.

Buyer Engagement
Live
First email
Tomorrow, 9 AM
Recipients
81
64

You can ask me anytime:

How is my campaign performing?
Who responded to my campaign?
Show me clients interested in buying.
Pause the campaign.
Change the follow-up messages.
K
Mel
```

Accessible labels: MEL message; Campaign status; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 10 Campaign live, light
`CmpH10Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpH10Light.html) · [PNG](/screens/assistants/png/CmpH10Light.png)

Same content as `CmpH10` in the other theme.

### Variant: playbook uploaded, dark
`CmpV01Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpV01Dark.html) · [PNG](/screens/assistants/png/CmpV01Dark.png)

```text
buyer-followup-playbook.pdf
PDF · 2.1 MB

Reading your playbook

I read your playbook. 6 emails and 3 texts over 30 days.

I’ll keep your tone, timing and sequence, and update the messages for these 86 buyers.

Perfect. What would you like this campaign to accomplish?

Book a meeting
Schedule a property showing
Collect buyer search criteria
Get a listing appointment
Reconnect with clients
Generate referrals
K
Mel
```

Accessible labels: Your attachment; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Variant: playbook uploaded, light
`CmpV01Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpV01Light.html) · [PNG](/screens/assistants/png/CmpV01Light.png)

Same content as `CmpV01` in the other theme.

### No contacts yet, dark
`CmpE01Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpE01Dark.html) · [PNG](/screens/assistants/png/CmpE01Dark.png)

```text
Run a campaign

Your Radius CRM has no contacts yet.

Add your contacts first. Then I build your campaign.

Upload a CSV file
Import from my existing CRM
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### No contacts yet, light
`CmpE01Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpE01Light.html) · [PNG](/screens/assistants/png/CmpE01Light.png)

Same content as `CmpE01` in the other theme.

### No clients match, dark
`CmpE02Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpE02Dark.html) · [PNG](/screens/assistants/png/CmpE02Dark.png)

```text
Sellers in Miami I haven’t contacted in 30 days

No clients match that.

You have 14 sellers in Miami. All of them heard from you in the last 30 days.

All sellers in Miami
Sellers not contacted in 14 days
Past clients in Miami
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### No clients match, light
`CmpE02Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpE02Light.html) · [PNG](/screens/assistants/png/CmpE02Light.png)

Same content as `CmpE02` in the other theme.

### Connect email and texting, dark
`CmpE03Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpE03Dark.html) · [PNG](/screens/assistants/png/CmpE03Dark.png)

```text
Approve and launch

To send emails and texts as you, I need your email and a texting number.

Gmail: I send campaign emails and read replies. Calendar is separate.

Gmail
Send emails · read replies
Connect
Radius texting number
Send texts · read replies
Connect
Launch with email only
Connect later
K
Mel
```

Accessible labels: Your message; MEL message; Connect to send; Connect Gmail; Connect Radius texting number; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Connect email and texting, light
`CmpE03Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpE03Light.html) · [PNG](/screens/assistants/png/CmpE03Light.png)

Same content as `CmpE03` in the other theme.

### Playbook unreadable, dark
`CmpE04Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpE04Dark.html) · [PNG](/screens/assistants/png/CmpE04Dark.png)

```text
playbook.pages
Pages · 4.8 MB

I can’t read this file type.

Send a PDF, DOCX, TXT or CSV, or paste your messages here.

Create one from scratch
Paste my messages
K
Mel
```

Accessible labels: Your attachment; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Playbook unreadable, light
`CmpE04Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpE04Light.html) · [PNG](/screens/assistants/png/CmpE04Light.png)

Same content as `CmpE04` in the other theme.

### Some messages bounced, dark
`CmpE05Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpE05Dark.html) · [PNG](/screens/assistants/png/CmpE05Dark.png)

```text
Day 1 email sent to 79 of 81 buyers.

2 emails bounced. Their addresses look wrong.

Buyer Engagement
Day 1 · Introduction
Sent
79
Bounced
2
Next
Day 3 text, Thursday
Show the 2 bounced
Text them instead
Remove them from the campaign
K
Mel
```

Accessible labels: MEL message; Send result; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Some messages bounced, light
`CmpE05Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CmpE05Light.html) · [PNG](/screens/assistants/png/CmpE05Light.png)

Same content as `CmpE05` in the other theme.

## Client experience

Designer notes:

- **Client experience happy path**
- An agent sets up a branded client portal, invites clients and picks how Mel talks to them. All in chat. Tap a prompt to fill the box, then send to move on.
- ENGINEERING RULES
  
  Backend does the work. Frontend shows prompts, status and cards only.
  
  Portal: real URL and preview come from the created Radius portal. Branding from the Radius profile. No branding: Mel asks for logo and colors in chat (variant).
  
  Invites: respect email and SMS permissions, opt-outs and duplicate-invitation suppression. Show recipients and preview before sending.
  
  Client-facing Mel always says it is the agent’s AI assistant. Never impersonates the agent. Negotiations, contract commitments and legal questions go to the agent.
  
  No edit buttons. Changes come from chat. Approve & Send Invites stays, like Send.
- OPEN FOR KJ
  
  “!” stripped from Biju copy, words kept. Also in the invite drafts.
  
  Biju forms (who to invite, how to invite, autonomy) are now prompts. “Save Assistant Preferences”, “Preview Client Invitations” and “Edit” removed.
  
  Autonomy prompts carry Biju’s one-line description under the label. New two-line prompt row, this page only.
  
  “Build client portal” pill added to the footer on this page only. Label not from Biju.
  
  Portal preview is a placeholder. Biju’s image was a Dribbble shot.
  
  Not Biju copy: H05 count line, H08 confirm line, V01, E01–E05, chip labels. Numbers and names are sample data.
- **Variant: no branding**
- **Recovery**
- **Prototype**

### 1 Meet Mel, dark
`CxH01Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH01Dark.html) · [PNG](/screens/assistants/png/CxH01Dark.png)

```text
Build my client portal

Hey 👋 I’m Mel, your Client Experience Assistant.

What if every one of your clients had their own personalized real estate experience — and an AI assistant available to help them anytime?

I can help your buyers search for homes, your sellers understand their home’s value, and keep conversations moving through texts, emails, and your client portal.

I’ll also keep you updated on what your clients are doing, who’s actively looking, and who might be ready to make a move.

Let’s create your branded client portal.

Create My Client Portal
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 1 Meet Mel, light
`CxH01Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH01Light.html) · [PNG](/screens/assistants/png/CxH01Light.png)

Same content as `CxH01` in the other theme.

### 2 Portal ready, dark
`CxH02Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH02Dark.html) · [PNG](/screens/assistants/png/CxH02Dark.png)

```text
Create My Client Portal

Great news. I already have your logo and brand colors from your Radius profile, so there’s nothing else you need to set up.

I’ll use those to create a beautiful client portal that looks and feels like your own brand.

yourname.radiusagent.com
Live
Your Client Portal Is Ready

Your portal is ready to share. Your clients can search for properties, save favorites, request showings, and access tools to help them buy or sell their homes.

Show me what clients can do
Invite my clients
Change the portal colors
K
Mel
```

Accessible labels: Your message; MEL message; Client portal; Portal preview in your brand colors; Copy portal link; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 2 Portal ready, light
`CxH02Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH02Light.html) · [PNG](/screens/assistants/png/CxH02Light.png)

Same content as `CxH02` in the other theme.

### 3 What clients can do, dark
`CxH03Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH03Dark.html) · [PNG](/screens/assistants/png/CxH03Dark.png)

```text
Show me what clients can do

Here’s what your clients will be able to do inside your new portal.

🏡 For Buyers

Search available properties, save favorites, create searches, explore recommendations, and request property showings.

Mel can help them narrow down their preferences and find homes that fit their needs.

🏷️ For Sellers

Add their property, request a home valuation report, explore local market information, and connect with their agent about selling.

Mel can help collect property details and identify selling intent.

💬 For Every Client

Chat with Mel, ask real estate questions, request assistance, and communicate with their agent.

With agent permission, Mel can also respond through email and SMS.

Invite my clients
Open my portal
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 3 What clients can do, light
`CxH03Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH03Light.html) · [PNG](/screens/assistants/png/CxH03Light.png)

Same content as `CxH03` in the other theme.

### 4 Who to invite, dark
`CxH04Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH04Dark.html) · [PNG](/screens/assistants/png/CxH04Dark.png)

```text
Invite my clients

Now let’s invite your clients.

Since your contacts are already in Radius CRM, I can send personalized invitations and give them access to their own client experience.

Who would you like to invite?

All eligible CRM contacts
Buyers only
Sellers only
Past clients
Choose my own filters
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 4 Who to invite, light
`CxH04Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH04Light.html) · [PNG](/screens/assistants/png/CxH04Light.png)

Same content as `CxH04` in the other theme.

### 5 How to invite, dark
`CxH05Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH05Dark.html) · [PNG](/screens/assistants/png/CxH05Dark.png)

```text
All eligible CRM contacts

312 contacts can be invited.

I’ll personalize the invitation with each client’s name and your branded portal link.

Before sending, I’ll show you the recipients and message preview.

How should I invite them?

Email and text message
Email only
Text message only
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 5 How to invite, light
`CxH05Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH05Light.html) · [PNG](/screens/assistants/png/CxH05Light.png)

Same content as `CxH05` in the other theme.

### 6 Invitation preview, dark
`CxH06Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH06Dark.html) · [PNG](/screens/assistants/png/CxH06Dark.png)

```text
Email and text message

Here’s the invitation I’ve prepared. Does this look good?

Client Invitation
312 clients · Email and text
Draft
Email Invitation

Subject: Your personalized home search experience is ready

Hi Sarah,

I’ve set up a personalized real estate portal for you.

You can now explore homes, save your favorites, check your home’s estimated value, and easily connect with me whenever you need anything.

You’ll also have access to Mel, my AI assistant, who can help you explore properties and answer questions.

[Your Client Portal Link]

Looking forward to helping you with your real estate goals.

Text Invitation

Hey Sarah. I’ve created a personalized real estate portal for you. You can search homes, save favorites, and connect with me anytime. Here’s your link: [Portal Link]

Approve & Send Invites
Make the text shorter
Add my phone number to the email
Show the 312 recipients
K
Mel
```

Accessible labels: Your message; MEL message; Client invitation; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 6 Invitation preview, light
`CxH06Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH06Light.html) · [PNG](/screens/assistants/png/CxH06Light.png)

Same content as `CxH06` in the other theme.

### 6b Change by asking, dark
`CxH06bDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH06bDark.html) · [PNG](/screens/assistants/png/CxH06bDark.png)

```text
Make the text shorter

Done. The text is shorter.

Client Invitation
312 clients
Text Invitation
Draft

Hi Sarah, I made you a personal home portal. Search homes and save favorites here: [Portal Link]

Approve & Send Invites

Anything else, or ready to send?

Show the full invitation
Undo that change
K
Mel
```

Accessible labels: Your message; MEL message; Client invitation; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 6b Change by asking, light
`CxH06bLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH06bLight.html) · [PNG](/screens/assistants/png/CxH06bLight.png)

Same content as `CxH06b` in the other theme.

### 7 How Mel talks to clients, dark
`CxH07Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH07Dark.html) · [PNG](/screens/assistants/png/CxH07Dark.png)

```text
Approve and send invites

Invites sent to 312 clients
312
287

Your clients now have access to your portal.

Want me to help manage their conversations too?

I can answer property questions, respond to messages, help clients find homes, collect their preferences, and notify you when they need your personal attention.

How would you like me to communicate with your clients?

Draft replies for my approval
Mel prepares responses, but I approve before sending.
Automatically respond to clients
Mel handles authorized routine conversations and escalates important matters to me.
Portal chat only
Mel assists clients inside the portal but doesn’t independently reply by SMS or email.
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 7 How Mel talks to clients, light
`CxH07Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH07Light.html) · [PNG](/screens/assistants/png/CxH07Light.png)

Same content as `CxH07` in the other theme.

### 8 Insights, dark
`CxH08Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH08Dark.html) · [PNG](/screens/assistants/png/CxH08Dark.png)

```text
Draft replies for my approval

Got it. I’ll draft replies and you approve before anything is sent.

You’re all set 🎉

I’ll now help you understand what your clients are doing, who’s actively looking, and which relationships need attention.

Whenever someone searches for properties, saves a home, requests a showing, asks about selling, or starts a conversation, I’ll capture those insights in your CRM.

I’ll also highlight your hottest opportunities.

Client Activity Insights
24
Active clients
8
Hot prospects
5
Need follow-up

Hot prospects

SJ
Sarah Johnson
2h
Austin · Wants a showing
SJ
Sarah Johnson
Yesterday
Round Rock · Wants a home value
ML
Marcus Lee
3d
Pflugerville · No reply in 5 days
Schedule a showing with Sarah Johnson, Austin
Show all 8 hot prospects
Who needs follow-up?
K
Mel
```

Accessible labels: Your message; MEL message; Client activity insights; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 8 Insights, light
`CxH08Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH08Light.html) · [PNG](/screens/assistants/png/CxH08Light.png)

Same content as `CxH08` in the other theme.

### Variant: no branding, dark
`CxV01Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxV01Dark.html) · [PNG](/screens/assistants/png/CxV01Dark.png)

```text
Create My Client Portal

Your Radius profile has no logo or brand colors yet.

Upload your logo and pick a primary and secondary color. I’ll build the portal around them.

terra-key-logo.png
PNG · 240 KB

Reading your logo

Got your logo. Which colors should I use?

Use the colors from my logo
Primary navy, secondary gold
I’ll type the hex codes
K
Mel
```

Accessible labels: Your message; MEL message; Your attachment; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Variant: no branding, light
`CxV01Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxV01Light.html) · [PNG](/screens/assistants/png/CxV01Light.png)

Same content as `CxV01` in the other theme.

### No contacts yet, dark
`CxE01Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxE01Dark.html) · [PNG](/screens/assistants/png/CxE01Dark.png)

```text
Invite my clients

Your Radius CRM has no contacts yet, so there’s no one to invite.

Add your contacts first. Your portal stays ready.

Upload a CSV file
Import from my existing CRM
Share my portal link instead
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### No contacts yet, light
`CxE01Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxE01Light.html) · [PNG](/screens/assistants/png/CxE01Light.png)

Same content as `CxE01` in the other theme.

### Connect email and texting, dark
`CxE02Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxE02Dark.html) · [PNG](/screens/assistants/png/CxE02Dark.png)

```text
Email and text message

To send invitations as you, I need your email and a texting number.

Gmail: I send invitations and read replies. Calendar is separate.

Gmail
Invites and replies
Connect
Texting number
Texts and replies
Connect
Show me the invitation first
Connect later
K
Mel
```

Accessible labels: Your message; MEL message; Connect to send; Connect Gmail; Connect texting number; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Connect email and texting, light
`CxE02Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxE02Light.html) · [PNG](/screens/assistants/png/CxE02Light.png)

Same content as `CxE02` in the other theme.

### Some invites failed, dark
`CxE03Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxE03Dark.html) · [PNG](/screens/assistants/png/CxE03Dark.png)

```text
Approve and send invites

Invitations sent to 304 of 312 clients.

8 didn’t go through. 5 emails bounced and 3 numbers can’t receive texts.

Sent to 304 of 312
8 failed
Show the 8 clients
Text the 5 instead
Fix their contact details
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Some invites failed, light
`CxE03Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxE03Light.html) · [PNG](/screens/assistants/png/CxE03Light.png)

Same content as `CxE03` in the other theme.

### Portal build failed, dark
`CxE04Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxE04Dark.html) · [PNG](/screens/assistants/png/CxE04Dark.png)

```text
Create My Client Portal

Client Portal
Your logo and colors are saved
Not built

Your portal didn’t finish building.

Try again now, or I’ll retry and message you when it’s ready.

Try again
Retry and message me
K
Mel
```

Accessible labels: Your message; Client portal; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Portal build failed, light
`CxE04Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxE04Light.html) · [PNG](/screens/assistants/png/CxE04Light.png)

Same content as `CxE04` in the other theme.

### Legal question escalated, dark
`CxE05Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxE05Dark.html) · [PNG](/screens/assistants/png/CxE05Dark.png)

```text
Sarah Johnson asked something only you should answer.

It’s about her contract, so I didn’t reply. I told her you’ll get back to her.

Sarah Johnson
Portal chat · 2 min ago
Needs you

Sarah

Can I back out of my offer after the inspection?

Passed to your agent. They’ll reply soon.

Mel · Sent

Draft a reply to Sarah
Call Sarah
Show the full chat
K
Mel
```

Accessible labels: MEL message; Client question; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Legal question escalated, light
`CxE05Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxE05Light.html) · [PNG](/screens/assistants/png/CxE05Light.png)

Same content as `CxE05` in the other theme.

### Prototype H01 to H08, dark
`CxProtoDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxProtoDark.html) · [PNG](/screens/assistants/png/CxProtoDark.png)

```text
Build my client portal

Hey 👋 I’m Mel, your Client Experience Assistant.

What if every one of your clients had their own personalized real estate experience — and an AI assistant available to help them anytime?

I can help your buyers search for homes, your sellers understand their home’s value, and keep conversations moving through texts, emails, and your client portal.

I’ll also keep you updated on what your clients are doing, who’s actively looking, and who might be ready to make a move.

Let’s create your branded client portal.

Create My Client Portal
K
Mel
```

Accessible labels: Your message; MEL message; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### Prototype H01 to H08, light
`CxProtoLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxProtoLight.html) · [PNG](/screens/assistants/png/CxProtoLight.png)

Same content as `CxProto` in the other theme.

### 8b Insights card first, dark
`CxH08bDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH08bDark.html) · [PNG](/screens/assistants/png/CxH08bDark.png)

```text
Draft replies for my approval

Got it. I’ll draft replies and you approve before anything is sent.

You’re all set 🎉

Client Activity Insights
24
Active clients
8
Hot prospects
5
Need follow-up

Hot prospects

SJ
Sarah Johnson
2h
Austin · Wants a showing
SJ
Sarah Johnson
Yesterday
Round Rock · Wants a home value
ML
Marcus Lee
3d
Pflugerville · No reply in 5 days

I’ll now help you understand what your clients are doing, who’s actively looking, and which relationships need attention.

Whenever someone searches for properties, saves a home, requests a showing, asks about selling, or starts a conversation, I’ll capture those insights in your CRM.

I’ll also highlight your hottest opportunities.

Schedule a showing with Sarah Johnson, Austin
Show all 8 hot prospects
Who needs follow-up?
K
Mel
```

Accessible labels: Your message; MEL message; Client activity insights; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 8b Insights card first, light
`CxH08bLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CxH08bLight.html) · [PNG](/screens/assistants/png/CxH08bLight.png)

Same content as `CxH08b` in the other theme.

## Archived · CRM Skill

Designer notes:

- ARCHIVED. Old CRM design. New CRM flows, plus the edge cases and recovery boards from this page, live in Mel CRM → https://claude.ai/artifact/Wk8cmkeWjAkkksCkch2u8q
- **CRM demo, tap through end to end**
- **CRM happy path: import contacts**
- **Prompt: find a contact**
- **Prompt: update preferences**
- **Prompt: draft and send a message**
- **Prompt: schedule a follow-up**
- **Prompt: start a campaign**
- **Prompt: top buyers this month**
- **CRM other starts**
- **Agent conversations**

### 1 Welcome, dark
`CrmWelcomeDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmWelcomeDark.html) · [PNG](/screens/assistants/png/CrmWelcomeDark.png)

```text
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.

How do you want to add them?

Upload a CSV
Import from another CRM
I’ll add contacts later
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### 3 CSV read, dark
`CrmImportDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmImportDark.html) · [PNG](/screens/assistants/png/CrmImportDark.png)

```text
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.

How do you want to add them?

Upload a CSV

Attach your CSV. Any column layout works. I match the fields for you.

clients-export.csv

CSV · 1,280 rows

Read · clients-export.csv

I found 1,280 contacts and matched name, phone, email, address, client type and notes.

32 are duplicates. Import 1,248 and skip them?

Import and skip duplicates
Show me the duplicates
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### CRM demo, tap through, dark
`CrmDoneDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmDoneDark.html) · [PNG](/screens/assistants/png/CrmDoneDark.png)

```text
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.

How do you want to add them?

Upload a CSV
Import from another CRM
I’ll add contacts later
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### 6 What Mel can do, dark
`CrmSkillsDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmSkillsDark.html) · [PNG](/screens/assistants/png/CrmSkillsDark.png)

```text
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.

How do you want to add them?

Upload a CSV

Attach your CSV. Any column layout works. I match the fields for you.

clients-export.csv

CSV · 1,280 rows

Read · clients-export.csv

I found 1,280 contacts and matched name, phone, email, address, client type and notes.

32 are duplicates. Import 1,248 and skip them?

Import and skip duplicates

Imported · 1,248 contacts

Done. Here is what came in.

1,248

Imported

836

Buyers

412

Sellers

32

Duplicates skipped

12 need review · missing phone or email
Your contacts
1,248 in Radius CRM

What can you do with them?

Try one of these, or ask in your own words.

Find Jordan Lee
Update Jordan’s preferences to 3 beds
Draft a message to Jordan
Remind me to call Jordan on Tuesday
Start a check-in campaign for inactive clients
Show my top buyers this month
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Import result; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### 1 Welcome, light
`CrmWelcomeLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmWelcomeLight.html) · [PNG](/screens/assistants/png/CrmWelcomeLight.png)

Same content as `CrmWelcome` in the other theme.

### 3 CSV read, light
`CrmImportLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmImportLight.html) · [PNG](/screens/assistants/png/CrmImportLight.png)

Same content as `CrmImport` in the other theme.

### CRM demo, tap through, light
`CrmDoneLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmDoneLight.html) · [PNG](/screens/assistants/png/CrmDoneLight.png)

Same content as `CrmDone` in the other theme.

### 6 What Mel can do, light
`CrmSkillsLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmSkillsLight.html) · [PNG](/screens/assistants/png/CrmSkillsLight.png)

Same content as `CrmSkills` in the other theme.

### Step 5.1 send a client message, dark
`CrmAgentSendDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmAgentSendDark.html) · [PNG](/screens/assistants/png/CrmAgentSendDark.png)

```text
Text Sarah Johnson and ask if she’s still looking to buy a home.

Absolutely. Here’s the message I’ve prepared:

“Hey Sarah. Just checking in to see how your home search is going. Are you still looking to buy? I’d love to help you find the right place.”

Would you like me to send it?

Send message
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: Your message; MEL message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Step 5.2 update a client record, dark
`CrmAgentUpdateDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmAgentUpdateDark.html) · [PNG](/screens/assistants/png/CrmAgentUpdateDark.png)

```text
Change David Miller to Active Buyer and add a note that he’s looking in Austin under $800K.

Done. I’ve updated David’s status to Active Buyer and added his search preferences to his profile.

Want me to set up a property search for him, too?

MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: Your message; MEL message; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Step 5.3 nurture campaign, dark
`CrmAgentCampaignDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmAgentCampaignDark.html) · [PNG](/screens/assistants/png/CrmAgentCampaignDark.png)

```text
Add all my new buyer leads to a follow-up campaign.

I found 43 new buyer leads in your CRM.

I recommend a buyer nurture campaign with an introductory email, a follow-up text, and ongoing home-search updates.

Would you like to review the campaign and enroll these clients?

MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: Your message; MEL message; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Step 6 Mel closes the onboarding, dark
`CrmAgentCloseDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmAgentCloseDark.html) · [PNG](/screens/assistants/png/CrmAgentCloseDark.png)

```text
You’re all set.

Your CRM is ready, and I’m here whenever you need me.

Whether you want to follow up with a client, update their information, find your hottest leads, or launch a campaign, just ask.

I’ll also help you stay on top of important client activity so opportunities don’t slip through the cracks.

What would you like to do next?

MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Step 5.1 send a client message, light
`CrmAgentSendLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmAgentSendLight.html) · [PNG](/screens/assistants/png/CrmAgentSendLight.png)

Same content as `CrmAgentSend` in the other theme.

### Step 5.2 update a client record, light
`CrmAgentUpdateLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmAgentUpdateLight.html) · [PNG](/screens/assistants/png/CrmAgentUpdateLight.png)

Same content as `CrmAgentUpdate` in the other theme.

### Step 5.3 nurture campaign, light
`CrmAgentCampaignLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmAgentCampaignLight.html) · [PNG](/screens/assistants/png/CrmAgentCampaignLight.png)

Same content as `CrmAgentCampaign` in the other theme.

### Step 6 Mel closes the onboarding, light
`CrmAgentCloseLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmAgentCloseLight.html) · [PNG](/screens/assistants/png/CrmAgentCloseLight.png)

Same content as `CrmAgentClose` in the other theme.

### Draft: edit and review again, dark
`CrmFlowDraftEditDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowDraftEditDark.html) · [PNG](/screens/assistants/png/CrmFlowDraftEditDark.png)

```text
Text Sarah Johnson and ask if she’s still looking to buy a home.

Absolutely. Here’s the message I’ve prepared:

“Hey Sarah. Just checking in to see how your home search is going. Are you still looking to buy? I’d love to help you find the right place.”

Would you like me to send it?

Edit message

What should I change? Tell me the tone or the offer.

Make it shorter.

Sure. Here’s a shorter version:

“Hey Sarah. Are you still looking to buy a home? I’d love to help.”

Would you like me to send it?

Send message
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: Your message; MEL message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Draft: edit and review again, light
`CrmFlowDraftEditLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowDraftEditLight.html) · [PNG](/screens/assistants/png/CrmFlowDraftEditLight.png)

Same content as `CrmFlowDraftEdit` in the other theme.

### Draft: sent status, dark
`CrmFlowDraftSentDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowDraftSentDark.html) · [PNG](/screens/assistants/png/CrmFlowDraftSentDark.png)

```text
Text Sarah Johnson and ask if she’s still looking to buy a home.

Absolutely. Here’s the message I’ve prepared:

“Hey Sarah. Just checking in to see how your home search is going. Are you still looking to buy? I’d love to help you find the right place.”

Would you like me to send it?

Send message

Done. I’ve sent the message to Sarah and recorded it in her client activity.

MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: Your message; MEL message; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Draft: sent status, light
`CrmFlowDraftSentLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowDraftSentLight.html) · [PNG](/screens/assistants/png/CrmFlowDraftSentLight.png)

Same content as `CrmFlowDraftSent` in the other theme.

### Draft: email review, dark
`CrmFlowEmailReviewDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowEmailReviewDark.html) · [PNG](/screens/assistants/png/CrmFlowEmailReviewDark.png)

```text
Email Sarah Johnson and ask if she’s still looking to buy a home.

Absolutely. Here’s the email I’ve prepared:

Subject: Checking in on your home search

“Hi Sarah, I wanted to check in on your home search. Are you still looking to buy? I’d love to help you find the right place.”

Would you like me to send it?

Send email
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: Your message; MEL message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Draft: email review, light
`CrmFlowEmailReviewLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowEmailReviewLight.html) · [PNG](/screens/assistants/png/CrmFlowEmailReviewLight.png)

Same content as `CrmFlowEmailReview` in the other theme.

### Recovery: missing email, dark
`CrmFlowMissingEmailDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowMissingEmailDark.html) · [PNG](/screens/assistants/png/CrmFlowMissingEmailDark.png)

```text
Email Marcus Lee about the open house on Saturday.

I don’t have an email address for Marcus yet. What’s his email?

marcus.lee@example.com

Thanks. I’ve saved it to Marcus’s profile. Here’s the email I’ve prepared:

Subject: Open house on Saturday

“Hi Marcus, we’re hosting an open house on Saturday. I’d love for you to stop by.”

Would you like me to send it?

Send email
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: Your message; MEL message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Recovery: missing email, light
`CrmFlowMissingEmailLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowMissingEmailLight.html) · [PNG](/screens/assistants/png/CrmFlowMissingEmailLight.png)

Same content as `CrmFlowMissingEmail` in the other theme.

### Recovery: send failed, dark
`CrmFlowSendFailedDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowSendFailedDark.html) · [PNG](/screens/assistants/png/CrmFlowSendFailedDark.png)

```text
Text Sarah Johnson and ask if she’s still looking to buy a home.

Absolutely. Here’s the message I’ve prepared:

“Hey Sarah. Just checking in to see how your home search is going. Are you still looking to buy? I’d love to help you find the right place.”

Would you like me to send it?

Send message

I couldn’t send the message to Sarah. Nothing went out, so she hasn’t received it.

Would you like me to try again?

Try again
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: Your message; MEL message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Recovery: send failed, light
`CrmFlowSendFailedLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowSendFailedLight.html) · [PNG](/screens/assistants/png/CrmFlowSendFailedLight.png)

Same content as `CrmFlowSendFailed` in the other theme.

### Update: status review, dark
`CrmFlowStatusReviewDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowStatusReviewDark.html) · [PNG](/screens/assistants/png/CrmFlowStatusReviewDark.png)

```text
Change David Miller to Active Buyer and add a note that he’s looking in Austin under $800K.

Here’s what I’ll update for David:

Status: Active Buyer
Note: Looking in Austin, under $800K

Would you like me to save these changes?

Save changes
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: Your message; MEL message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Update: status review, light
`CrmFlowStatusReviewLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowStatusReviewLight.html) · [PNG](/screens/assistants/png/CrmFlowStatusReviewLight.png)

Same content as `CrmFlowStatusReview` in the other theme.

### Update: saved confirmation, dark
`CrmFlowStatusSavedDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowStatusSavedDark.html) · [PNG](/screens/assistants/png/CrmFlowStatusSavedDark.png)

```text
Change David Miller to Active Buyer and add a note that he’s looking in Austin under $800K.

Here’s what I’ll update for David:

Status: Active Buyer
Note: Looking in Austin, under $800K

Would you like me to save these changes?

Save changes

Done. I’ve updated David’s status to Active Buyer and added his note to his profile.

Want me to set up a property search for him, too?

MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: Your message; MEL message; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Update: saved confirmation, light
`CrmFlowStatusSavedLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowStatusSavedLight.html) · [PNG](/screens/assistants/png/CrmFlowStatusSavedLight.png)

Same content as `CrmFlowStatusSaved` in the other theme.

### Update: preferences review, dark
`CrmFlowPrefsReviewDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowPrefsReviewDark.html) · [PNG](/screens/assistants/png/CrmFlowPrefsReviewDark.png)

```text
Update Sarah’s preferences. Her budget is $700K and she prefers text.

Here’s what I’ll update for Sarah:

Budget: $700K
Preferred contact: Text message

Would you like me to save these changes?

Save changes
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: Your message; MEL message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Update: preferences review, light
`CrmFlowPrefsReviewLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowPrefsReviewLight.html) · [PNG](/screens/assistants/png/CrmFlowPrefsReviewLight.png)

Same content as `CrmFlowPrefsReview` in the other theme.

### Campaign: enrollment review, dark
`CrmFlowCampReviewDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowCampReviewDark.html) · [PNG](/screens/assistants/png/CrmFlowCampReviewDark.png)

```text
Add all my new buyer leads to a follow-up campaign.

I found 43 new buyer leads in your CRM. Here’s the enrollment I’ve prepared:

Campaign: Buyer Nurture
Clients: 43 new buyer leads
Steps: introductory email, follow-up text, ongoing home-search updates

Would you like me to enroll them?

Enroll clients
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: Your message; MEL message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Campaign: enrollment review, light
`CrmFlowCampReviewLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowCampReviewLight.html) · [PNG](/screens/assistants/png/CrmFlowCampReviewLight.png)

Same content as `CrmFlowCampReview` in the other theme.

### Campaign: enrolled confirmation, dark
`CrmFlowCampEnrolledDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowCampEnrolledDark.html) · [PNG](/screens/assistants/png/CrmFlowCampEnrolledDark.png)

```text
Add all my new buyer leads to a follow-up campaign.

I found 43 new buyer leads in your CRM. Here’s the enrollment I’ve prepared:

Campaign: Buyer Nurture
Clients: 43 new buyer leads
Steps: introductory email, follow-up text, ongoing home-search updates

Would you like me to enroll them?

Enroll clients

Done. I’ve enrolled 43 clients in the Buyer Nurture campaign.

MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: Your message; MEL message; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Campaign: enrolled confirmation, light
`CrmFlowCampEnrolledLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowCampEnrolledLight.html) · [PNG](/screens/assistants/png/CrmFlowCampEnrolledLight.png)

Same content as `CrmFlowCampEnrolled` in the other theme.

### Recovery: campaign unavailable, dark
`CrmFlowCampUnavailableDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowCampUnavailableDark.html) · [PNG](/screens/assistants/png/CrmFlowCampUnavailableDark.png)

```text
Add Sarah Johnson to the Buyer Nurture campaign.

I can’t enroll Sarah right now. The Buyer Nurture campaign isn’t available.

Would you like to choose a different campaign?

Choose another campaign
Not now
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: Your message; MEL message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Recovery: campaign unavailable, light
`CrmFlowCampUnavailableLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowCampUnavailableLight.html) · [PNG](/screens/assistants/png/CrmFlowCampUnavailableLight.png)

Same content as `CrmFlowCampUnavailable` in the other theme.

### Recovery: missing contact details, dark
`CrmFlowCampMissingDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowCampMissingDark.html) · [PNG](/screens/assistants/png/CrmFlowCampMissingDark.png)

```text
Add all my new buyer leads to a follow-up campaign.

I found 43 new buyer leads, but 3 have no email address or phone number, so I can’t message them.

I can enroll the other 40 in the Buyer Nurture campaign.

Would you like me to continue?

Enroll 40 clients
Review 3 clients
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: Your message; MEL message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Recovery: missing contact details, light
`CrmFlowCampMissingLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmFlowCampMissingLight.html) · [PNG](/screens/assistants/png/CrmFlowCampMissingLight.png)

Same content as `CrmFlowCampMissing` in the other theme.

### CRM add contacts later, dark
`CrmLaterDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmLaterDark.html) · [PNG](/screens/assistants/png/CrmLaterDark.png)

```text
Let’s bring your contacts together so I can help you manage relationships and follow-ups.

How would you like to add your contacts?

I’ll add contacts later

No problem. You can import contacts anytime. You can also add one contact now.

Add a contact
Import contacts
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### CRM add contacts later, light
`CrmLaterLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmLaterLight.html) · [PNG](/screens/assistants/png/CrmLaterLight.png)

Same content as `CrmLater` in the other theme.

### 5 Import result, dark
`CrmReadyDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmReadyDark.html) · [PNG](/screens/assistants/png/CrmReadyDark.png)

```text
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.

How do you want to add them?

Upload a CSV

Attach your CSV. Any column layout works. I match the fields for you.

clients-export.csv

CSV · 1,280 rows

Read · clients-export.csv

I found 1,280 contacts and matched name, phone, email, address, client type and notes.

32 are duplicates. Import 1,248 and skip them?

Import and skip duplicates

Imported · 1,248 contacts

Done. Here is what came in.

1,248

Imported

836

Buyers

412

Sellers

32

Duplicates skipped

12 need review · missing phone or email
Your contacts
1,248 in Radius CRM
Review the 12 contacts
What can you do with them?
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Import result; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### 5 Import result, light
`CrmReadyLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmReadyLight.html) · [PNG](/screens/assistants/png/CrmReadyLight.png)

Same content as `CrmReady` in the other theme.

### CRM resume unfinished import, dark
`CrmResumeDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmResumeDark.html) · [PNG](/screens/assistants/png/CrmResumeDark.png)

```text
Let’s bring your contacts together so I can help you manage relationships and follow-ups.

How would you like to add your contacts?

Unfinished import

812 of 1,248 imported.

Resume import
Upload a CSV
Import from another CRM
I’ll add contacts later
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### CRM resume unfinished import, light
`CrmResumeLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmResumeLight.html) · [PNG](/screens/assistants/png/CrmResumeLight.png)

Same content as `CrmResume` in the other theme.

### 2 Upload a CSV, dark
`CrmH2Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmH2Dark.html) · [PNG](/screens/assistants/png/CrmH2Dark.png)

```text
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.

How do you want to add them?

Upload a CSV

Attach your CSV. Any column layout works. I match the fields for you.

Attach clients-export.csv
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### 2 Upload a CSV, light
`CrmH2Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmH2Light.html) · [PNG](/screens/assistants/png/CrmH2Light.png)

Same content as `CrmH2` in the other theme.

### 4 Duplicates, dark
`CrmH4Dark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmH4Dark.html) · [PNG](/screens/assistants/png/CrmH4Dark.png)

```text
I’m your CRM assistant. Let’s bring your contacts in so I can help with follow-ups.

How do you want to add them?

Upload a CSV

Attach your CSV. Any column layout works. I match the fields for you.

clients-export.csv

CSV · 1,280 rows

Read · clients-export.csv

I found 1,280 contacts and matched name, phone, email, address, client type and notes.

32 are duplicates. Import 1,248 and skip them?

Show me the duplicates

These rows share an email or phone with another row. I keep the most complete record of each.

MC
Maya Chen
2 rows · same email
Keep 1
JO
James Ortiz
2 rows · same phone
Keep 1
PN
Priya Nair
2 rows · same email
Keep 1

+29 more

Import and skip duplicates
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### 4 Duplicates, light
`CrmH4Light` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmH4Light.html) · [PNG](/screens/assistants/png/CrmH4Light.png)

Same content as `CrmH4` in the other theme.

### Find: contact card, dark
`CrmP1aDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP1aDark.html) · [PNG](/screens/assistants/png/CrmP1aDark.png)

```text
Try one of these, or ask in your own words.

Find Jordan Lee

Here is Jordan.

JL
Jordan Lee
Buyer · Active
Phone
(555) 014 2290
Email
jordan.lee@gmail.com
Looking for
3 beds · Oak Street · under [PRICE]
Last contact
12 days ago · text
Open Jordan in CRM
Notes, activity and family
Draft a message to Jordan
Remind me to call Jordan on Tuesday
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Find: contact card, light
`CrmP1aLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP1aLight.html) · [PNG](/screens/assistants/png/CrmP1aLight.png)

Same content as `CrmP1a` in the other theme.

### Find: no match, dark
`CrmP1bDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP1bDark.html) · [PNG](/screens/assistants/png/CrmP1bDark.png)

```text
Try one of these, or ask in your own words.

Find Jordon Le

I could not find Jordon Le. Did you mean Jordan Lee?

Yes, Jordan Lee
No, add a new contact
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Find: no match, light
`CrmP1bLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP1bLight.html) · [PNG](/screens/assistants/png/CrmP1bLight.png)

Same content as `CrmP1b` in the other theme.

### Update: review change, dark
`CrmP2aDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP2aDark.html) · [PNG](/screens/assistants/png/CrmP2aDark.png)

```text
Try one of these, or ask in your own words.

Update Jordan’s preferences to 3 beds

Here is the change. Save it?

Jordan Lee · preferences

Beds
2 → 3
Area
Oak Street · no change
Budget
Under [PRICE] · no change
Save it
Also add a pool
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Update: review change, light
`CrmP2aLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP2aLight.html) · [PNG](/screens/assistants/png/CrmP2aLight.png)

Same content as `CrmP2a` in the other theme.

### Update: saved, dark
`CrmP2bDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP2bDark.html) · [PNG](/screens/assistants/png/CrmP2bDark.png)

```text
Try one of these, or ask in your own words.

Update Jordan’s preferences to 3 beds

Here is the change. Save it?

Jordan Lee · preferences

Beds
2 → 3
Area
Oak Street · no change
Budget
Under [PRICE] · no change

Save it

Saved · Jordan Lee

Saved. I use this when new listings come in.

What else can you do?
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Update: saved, light
`CrmP2bLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP2bLight.html) · [PNG](/screens/assistants/png/CrmP2bLight.png)

Same content as `CrmP2b` in the other theme.

### Draft: review and send, dark
`CrmP3aDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3aDark.html) · [PNG](/screens/assistants/png/CrmP3aDark.png)

```text
Try one of these, or ask in your own words.

Draft a message to Jordan

Here is a draft. Send it, or tell me what to change.

To
Jordan Lee · Text

Hi Jordan, two homes near Oak Street match your budget. Want to tour on Saturday?

Sends from your Radius number
Send
Make it shorter
Send it by email instead
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Draft message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Draft: review and send, light
`CrmP3aLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3aLight.html) · [PNG](/screens/assistants/png/CrmP3aLight.png)

Same content as `CrmP3a` in the other theme.

### Draft: sent, dark
`CrmP3bDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3bDark.html) · [PNG](/screens/assistants/png/CrmP3bDark.png)

```text
Try one of these, or ask in your own words.

Draft a message to Jordan

Here is a draft. Send it, or tell me what to change.

To
Jordan Lee · Text

Hi Jordan, two homes near Oak Street match your budget. Want to tour on Saturday?

Sends from your Radius number
Send

Sent · text to Jordan Lee

Sent and logged in Jordan’s activity.

What else can you do?
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Draft message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Draft: sent, light
`CrmP3bLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP3bLight.html) · [PNG](/screens/assistants/png/CrmP3bLight.png)

Same content as `CrmP3b` in the other theme.

### Follow-up: review, dark
`CrmP4aDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP4aDark.html) · [PNG](/screens/assistants/png/CrmP4aDark.png)

```text
Try one of these, or ask in your own words.

Remind me to call Jordan on Tuesday

Here is the follow-up. Add it?

Call Jordan Lee
Tue, Oct 27 · 10:00 AM
Reminder
15 minutes before
Calendar
Google Calendar
Add it
Make it Wednesday
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Follow-up: review, light
`CrmP4aLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP4aLight.html) · [PNG](/screens/assistants/png/CrmP4aLight.png)

Same content as `CrmP4a` in the other theme.

### Follow-up: added, dark
`CrmP4bDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP4bDark.html) · [PNG](/screens/assistants/png/CrmP4bDark.png)

```text
Try one of these, or ask in your own words.

Remind me to call Jordan on Tuesday

Here is the follow-up. Add it?

Call Jordan Lee
Tue, Oct 27 · 10:00 AM
Reminder
15 minutes before
Calendar
Google Calendar

Add it

Added · Google Calendar

Added. I remind you 15 minutes before.

What else can you do?
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Follow-up: added, light
`CrmP4bLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP4bLight.html) · [PNG](/screens/assistants/png/CrmP4bLight.png)

Same content as `CrmP4b` in the other theme.

### Follow-up: calendar not connected, dark
`CrmP4cDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP4cDark.html) · [PNG](/screens/assistants/png/CrmP4cDark.png)

```text
Try one of these, or ask in your own words.

Remind me to call Jordan on Tuesday

Connect your calendar and I add it there. Until then I keep it in your Mel reminders.

Google Calendar
Not connected

Mel can:

See your events · Add events Mel creates · Send you reminders

Connect
Keep it in Mel reminders
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Follow-up: calendar not connected, light
`CrmP4cLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP4cLight.html) · [PNG](/screens/assistants/png/CrmP4cLight.png)

Same content as `CrmP4c` in the other theme.

### Campaign: review plan, dark
`CrmP5aDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP5aDark.html) · [PNG](/screens/assistants/png/CrmP5aDark.png)

```text
Try one of these, or ask in your own words.

Start a check-in campaign for inactive clients

Here is the plan. Start it?

4-week check-in
12 inactive clients · not contacted in 90 days
Week 1
Text · “Still thinking about a move this year?”
Week 2
Email · new listings near them
Week 3
Text · market update
Week 4
Call reminder for you

Stops for anyone who replies.

Start the campaign
Make it 6 weeks
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Campaign: review plan, light
`CrmP5aLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP5aLight.html) · [PNG](/screens/assistants/png/CrmP5aLight.png)

Same content as `CrmP5a` in the other theme.

### Campaign: started, dark
`CrmP5bDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP5bDark.html) · [PNG](/screens/assistants/png/CrmP5bDark.png)

```text
Try one of these, or ask in your own words.

Start a check-in campaign for inactive clients

Here is the plan. Start it?

4-week check-in
12 inactive clients · not contacted in 90 days
Week 1
Text · “Still thinking about a move this year?”
Week 2
Email · new listings near them
Week 3
Text · market update
Week 4
Call reminder for you

Stops for anyone who replies.

Start the campaign

Started · 12 clients

Started. The first message goes out tomorrow at 9 AM.

What else can you do?
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Campaign: started, light
`CrmP5bLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP5bLight.html) · [PNG](/screens/assistants/png/CrmP5bLight.png)

Same content as `CrmP5b` in the other theme.

### Top buyers: ranked, dark
`CrmP6aDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP6aDark.html) · [PNG](/screens/assistants/png/CrmP6aDark.png)

```text
Try one of these, or ask in your own words.

Show my top buyers this month

Your top buyers this month, by activity:

JL
Jordan Lee
Buyer · 6 listing views
Replied today
PN
Priya Nair
Buyer · 4 listing views
Saved 2 homes
TB
Tom Becker
Buyer · 3 listing views
Tour booked
Draft a message to Jordan
What else can you do?
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Top buyers: ranked, light
`CrmP6aLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP6aLight.html) · [PNG](/screens/assistants/png/CrmP6aLight.png)

Same content as `CrmP6a` in the other theme.

### Top buyers: no activity yet, dark
`CrmP6bDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP6bDark.html) · [PNG](/screens/assistants/png/CrmP6bDark.png)

```text
Try one of these, or ask in your own words.

Show my top buyers this month

Nothing to rank yet. Once clients view listings or reply, I rank them here.

No buyer activity this month

Views, saves and replies show up here.

Show last month instead
MEL
Manage clients
Create posts
Explore listings
Check compliance
Review documents
Speak
```

Accessible labels: MEL message; Your message; Suggested prompts; Back to Radius home; Mel; New chat; More; Mel skills; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message

### Top buyers: no activity yet, light
`CrmP6bLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/assistants/CrmP6bLight.html) · [PNG](/screens/assistants/png/CrmP6bLight.png)

Same content as `CrmP6b` in the other theme.

### BranchApp2DarkR
`BranchApp2DarkR` · 390×844 · [HTML](/screens/assistants/BranchApp2DarkR.html) · [PNG](/screens/assistants/png/BranchApp2DarkR.png)

```text
Yes

Checked 2 things

Let’s bring your contacts together so I can help you manage relationships and follow-ups.

How would you like to add your contacts?

Upload a CSV
Import from another CRM
I’ll add contacts later
MEL
Speak
```

Accessible labels: Your message; MEL message; Suggested prompts; Back to Radius home; Mel; New chat; More; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message; Stop generating

### BranchApp2LightR
`BranchApp2LightR` · 390×844 · [HTML](/screens/assistants/BranchApp2LightR.html) · [PNG](/screens/assistants/png/BranchApp2LightR.png)

Same content as `BranchApp2R` in the other theme.

### IntroAppBDark
`IntroAppBDark` · 390×844 · [HTML](/screens/assistants/IntroAppBDark.html) · [PNG](/screens/assistants/png/IntroAppBDark.png)

```text
Hey, I’m MEL, your AI assistant. I can:

Add and manage your clients
Market a listing
Run follow-up campaigns
Keep clients updated
Check transaction files
Prepare documents

Do you want to start by adding your clients? Reply yes, or pick a number.

MEL
Speak
```

Accessible labels: MEL message; What MEL can do; Mel; Back to Radius home; New chat; More; Message composer; Message MEL; Attachments and connected sources; Dictate message; Speak to MEL; Send message; Stop generating

### IntroAppBLight
`IntroAppBLight` · 390×844 · [HTML](/screens/assistants/IntroAppBLight.html) · [PNG](/screens/assistants/png/IntroAppBLight.png)

Same content as `IntroAppB` in the other theme.
