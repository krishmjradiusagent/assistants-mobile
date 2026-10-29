# Mel voice mode

Mel voice mode on mobile: full-screen voice, edge states, cards in voice, minimised bubble across tabs, concept A background, and iOS background states (Dynamic Island, Live Activity, widgets). Light and dark.

Screens: 128. Each screen has a static HTML page (`/screens/voice/<File>.html`), a PNG (`/screens/voice/png/<File>.png`) and its raw design source (`/source/voice/<File>.dc.html`).
Tokens and components: see `/design-system/README.md`. Copy shown is real UI copy unless it says placeholder.

## Voice mode · mobile

Designer notes:

- **Prototype · tap the green voice button to restart**
- **Happy path**
- **Edge states, voice asks, dictation**
- **CRM by voice · cards in voice**
- **Minimised across tabs · floating bubble**
- NEW (KJ, 28 Oct)
  
  · Bubble replaces the pill everywhere, chat included.
  · Tap = back to voice. Drag = move, snaps to the side. Drop on the cross = End.
  · Needs you: bubble turns attention + label. Mel also says it.
  · Dashboard and Clients are grey skeletons, not real pages.
  
  Copy not from Biju: "Draft ready", "Drop to end".
  
  Prototype: tap minimise, tap Dashboard or Clients in the nav, drag the bubble. After 6s Mel flags the draft.

### Prototype, dark
`Main` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/voice/Main.html) · [PNG](/screens/voice/png/Main.png)

```text
Mel Voice

Follow up with Sarah Reynolds
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, listening; Follow up with Sarah Reynolds about 412 Marina Blvd; Mute microphone; Switch to typing; End voice

### Prototype, light
`VoiceProtoLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/voice/VoiceProtoLight.html) · [PNG](/screens/voice/png/VoiceProtoLight.png)

```text
Mel Voice

Follow up
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, listening; Follow up with Sarah Reynolds about 412 Marina Blvd; Mute microphone; Switch to typing; End voice

### 1. Connecting, dark
`VHConnectingDark` · 390×844 · [HTML](/screens/voice/VHConnectingDark.html) · [PNG](/screens/voice/png/VHConnectingDark.png)

```text
Mel Voice

Connecting

Say what you need
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, ready; Mute microphone; Switch to typing; End voice

### 2. Listening, dark
`VHListeningDark` · 390×844 · [HTML](/screens/voice/VHListeningDark.html) · [PNG](/screens/voice/png/VHListeningDark.png)

```text
Mel Voice

Follow up with Sarah Reynolds about
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, listening; Follow up with Sarah Reynolds about 412 Marina Blvd; Mute microphone; Switch to typing; End voice

### 3. Working, dark
`VHWorkingDark` · 390×844 · [HTML](/screens/voice/VHWorkingDark.html) · [PNG](/screens/voice/png/VHWorkingDark.png)

```text
Mel Voice

Checking Sarah’s last email

Follow up with Sarah Reynolds about 412 Marina Blvd
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, working; Follow up with Sarah Reynolds about 412 Marina Blvd; Mute microphone; Switch to typing; End voice

### 4. Speaking, dark
`VHSpeakingDark` · 390×844 · [HTML](/screens/voice/VHSpeakingDark.html) · [PNG](/screens/voice/png/VHSpeakingDark.png)

```text
Mel Voice

Sarah hasn’t replied in 5 days. I drafted
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Interrupt Mel; Mel, speaking; Sarah hasn’t replied in 5 days. I drafted a short follow-up.; Mute microphone; Switch to typing; End voice

### 5. Interrupt, you talk over Mel, dark
`VHInterruptDark` · 390×844 · [HTML](/screens/voice/VHInterruptDark.html) · [PNG](/screens/voice/png/VHInterruptDark.png)

```text
Mel Voice

I drafted a short follow-up…

Wait, add the open
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, listening; Wait, add the open house on Saturday; Mute microphone; Switch to typing; End voice

### 6. Needs you, draft to send, dark
`VHNeedsDark` · 390×844 · [HTML](/screens/voice/VHNeedsDark.html) · [PNG](/screens/voice/png/VHNeedsDark.png)

```text
Mel Voice

Here’s the draft.

Sarah Reynolds · Email

Re: 412 Marina Blvd

Hi Sarah, checking in on 412 Marina Blvd. The open house is Saturday, 1 to 4 PM. Want me to save you a time to walk through?

Sends from your Radius email
Send
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, needs you; Here’s the draft. Say send, or tap Send.; Email draft to Sarah Reynolds; Mute microphone; Switch to typing; End voice

### 7. Done, sent, dark
`VHDoneDark` · 390×844 · [HTML](/screens/voice/VHDoneDark.html) · [PNG](/screens/voice/png/VHDoneDark.png)

```text
Mel Voice

Sent to Sarah. Anything
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, done; Sent to Sarah. Anything else?; Mute microphone; Switch to typing; End voice

### 8. Ended, back in chat, dark
`VHEndedDark` · 390×844 · [HTML](/screens/voice/VHEndedDark.html) · [PNG](/screens/voice/png/VHEndedDark.png)

```text
Voice chat · 1:12

Follow up with Sarah Reynolds about 412 Marina Blvd

Sarah hasn’t replied in 5 days. I drafted a short follow-up.

Wait, add the open house on Saturday

Added the open house. Here’s the draft.

Sarah Reynolds · Email

Re: 412 Marina Blvd

Hi Sarah, checking in on 412 Marina Blvd. The open house is Saturday, 1 to 4 PM. Want me to save you a time to walk through?

Sends from your Radius email
Sent

Sent to Sarah. Anything else?

Remind me if Sarah doesn’t reply
Check in with Grace Lee
K
Mel
```

Accessible labels: Your message; MEL message; Email draft to Sarah Reynolds; Suggested prompts; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 1. Connecting, light
`VHConnectingLight` · 390×844 · [HTML](/screens/voice/VHConnectingLight.html) · [PNG](/screens/voice/png/VHConnectingLight.png)

Same content as `VHConnecting` in the other theme.

### 2. Listening, light
`VHListeningLight` · 390×844 · [HTML](/screens/voice/VHListeningLight.html) · [PNG](/screens/voice/png/VHListeningLight.png)

```text
Mel Voice

Follow up with Sarah Reynolds
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, listening; Follow up with Sarah Reynolds about 412 Marina Blvd; Mute microphone; Switch to typing; End voice

### 3. Working, light
`VHWorkingLight` · 390×844 · [HTML](/screens/voice/VHWorkingLight.html) · [PNG](/screens/voice/png/VHWorkingLight.png)

Same content as `VHWorking` in the other theme.

### 4. Speaking, light
`VHSpeakingLight` · 390×844 · [HTML](/screens/voice/VHSpeakingLight.html) · [PNG](/screens/voice/png/VHSpeakingLight.png)

```text
Mel Voice

Sarah hasn’t replied
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Interrupt Mel; Mel, speaking; Sarah hasn’t replied in 5 days. I drafted a short follow-up.; Mute microphone; Switch to typing; End voice

### 5. Interrupt, you talk over Mel, light
`VHInterruptLight` · 390×844 · [HTML](/screens/voice/VHInterruptLight.html) · [PNG](/screens/voice/png/VHInterruptLight.png)

```text
Mel Voice

I drafted a short follow-up…

Wait, add the
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, listening; Wait, add the open house on Saturday; Mute microphone; Switch to typing; End voice

### 6. Needs you, draft to send, light
`VHNeedsLight` · 390×844 · [HTML](/screens/voice/VHNeedsLight.html) · [PNG](/screens/voice/png/VHNeedsLight.png)

Same content as `VHNeeds` in the other theme.

### 7. Done, sent, light
`VHDoneLight` · 390×844 · [HTML](/screens/voice/VHDoneLight.html) · [PNG](/screens/voice/png/VHDoneLight.png)

```text
Mel Voice

Sent to Sarah.
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, done; Sent to Sarah. Anything else?; Mute microphone; Switch to typing; End voice

### 8. Ended, back in chat, light
`VHEndedLight` · 390×844 · [HTML](/screens/voice/VHEndedLight.html) · [PNG](/screens/voice/png/VHEndedLight.png)

Same content as `VHEnded` in the other theme.

### 1. Muted, dark
`VEMutedDark` · 390×844 · [HTML](/screens/voice/VEMutedDark.html) · [PNG](/screens/voice/png/VEMutedDark.png)

```text
Mel Voice

Muted

Tap the mic to talk again
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, paused; Unmute microphone; Switch to typing; End voice

### 2. Mic permission denied, dark
`VEDeniedDark` · 390×844 · [HTML](/screens/voice/VEDeniedDark.html) · [PNG](/screens/voice/png/VEDeniedDark.png)

```text
Mel Voice

Microphone off

Mel needs your microphone to talk.

Open Settings
Type instead
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, paused; Mel needs your microphone to talk.; Mute microphone; Switch to typing; End voice

### 3. Can’t hear you, dark
`VECantHearDark` · 390×844 · [HTML](/screens/voice/VECantHearDark.html) · [PNG](/screens/voice/png/VECantHearDark.png)

```text
Mel Voice

Still there?

I didn’t catch that.
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, ready; I didn’t catch that. Try again.; Mute microphone; Switch to typing; End voice

### 4. Network dropped, dark
`VENetworkDark` · 390×844 · [HTML](/screens/voice/VENetworkDark.html) · [PNG](/screens/voice/png/VENetworkDark.png)

```text
Mel Voice

Connection lost

Lost connection. Your chat is saved.

Try again
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, paused; Lost connection. Your chat is saved.; Mute microphone; Switch to typing; End voice

### 1. Muted, light
`VEMutedLight` · 390×844 · [HTML](/screens/voice/VEMutedLight.html) · [PNG](/screens/voice/png/VEMutedLight.png)

Same content as `VEMuted` in the other theme.

### 2. Mic permission denied, light
`VEDeniedLight` · 390×844 · [HTML](/screens/voice/VEDeniedLight.html) · [PNG](/screens/voice/png/VEDeniedLight.png)

Same content as `VEDenied` in the other theme.

### 3. Can’t hear you, light
`VECantHearLight` · 390×844 · [HTML](/screens/voice/VECantHearLight.html) · [PNG](/screens/voice/png/VECantHearLight.png)

Same content as `VECantHear` in the other theme.

### 4. Network dropped, light
`VENetworkLight` · 390×844 · [HTML](/screens/voice/VENetworkLight.html) · [PNG](/screens/voice/png/VENetworkLight.png)

Same content as `VENetwork` in the other theme.

### 9. Minimised, bubble in chat, dark
`VHMinimisedDark` · 390×844 · [HTML](/screens/voice/VHMinimisedDark.html) · [PNG](/screens/voice/png/VHMinimisedDark.png)

```text
Follow up with Sarah Reynolds about 412 Marina Blvd

K
Mel
```

Accessible labels: Your message; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Dictate message; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox; Back to Mel Voice. Drag to move, drop on the cross to end.; Mel, listening

### 9. Minimised, bubble in chat, light
`VHMinimisedLight` · 390×844 · [HTML](/screens/voice/VHMinimisedLight.html) · [PNG](/screens/voice/png/VHMinimisedLight.png)

Same content as `VHMinimised` in the other theme.

### 5. Change voice by asking, dark
`VEVoiceChangeDark` · 390×844 · [HTML](/screens/voice/VEVoiceChangeDark.html) · [PNG](/screens/voice/png/VEVoiceChangeDark.png)

```text
Mel Voice

Use a calmer voice

Switched to Sage.
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Interrupt Mel; Mel, speaking; Switched to Sage. Say “change voice” anytime.; Mute microphone; Switch to typing; End voice

### 5. Change voice by asking, light
`VEVoiceChangeLight` · 390×844 · [HTML](/screens/voice/VEVoiceChangeLight.html) · [PNG](/screens/voice/png/VEVoiceChangeLight.png)

Same content as `VEVoiceChange` in the other theme.

### 6. Captions off by asking, dark
`VECaptionsOffDark` · 390×844 · [HTML](/screens/voice/VECaptionsOffDark.html) · [PNG](/screens/voice/png/VECaptionsOffDark.png)

```text
Mel Voice

Captions off
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Interrupt Mel; Mel, speaking; Mute microphone; Switch to typing; End voice

### 6. Captions off by asking, light
`VECaptionsOffLight` · 390×844 · [HTML](/screens/voice/VECaptionsOffLight.html) · [PNG](/screens/voice/png/VECaptionsOffLight.png)

Same content as `VECaptionsOff` in the other theme.

### 7. Dictating in chat, dark
`VEDictatingDark` · 390×844 · [HTML](/screens/voice/VEDictatingDark.html) · [PNG](/screens/voice/png/VEDictatingDark.png)

```text
Voice chat · 1:12

Follow up with Sarah Reynolds about 412 Marina Blvd

Sarah hasn’t replied in 5 days. I drafted a short follow-up.

Wait, add the open house on Saturday

Added the open house. Here’s the draft.

Sarah Reynolds · Email

Re: 412 Marina Blvd

Hi Sarah, checking in on 412 Marina Blvd. The open house is Saturday, 1 to 4 PM. Want me to save you a time to walk through?

Sends from your Radius email
Send
K
Mel
```

Accessible labels: Your message; MEL message; Email draft to Sarah Reynolds; Profile; Notifications, new; Message composer; Attachments and connected sources; Message MEL; Stop dictating; Speak to MEL; Send message; Stop generating; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox

### 7. Dictating in chat, light
`VEDictatingLight` · 390×844 · [HTML](/screens/voice/VEDictatingLight.html) · [PNG](/screens/voice/png/VEDictatingLight.png)

Same content as `VEDictating` in the other theme.

### CRM by voice, prototype, dark
`VCProtoDark` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/voice/VCProtoDark.html) · [PNG](/screens/voice/png/VCProtoDark.png)

```text
Mel Voice

Pull up Sarah Reynolds

Here’s Sarah.

Sarah Reynolds

Buyer · 412 Marina Blvd

Last touch 5 days
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Interrupt Mel; Mel, speaking; Here’s Sarah. You last talked 5 days ago.; Sarah Reynolds; Mute microphone; Switch to typing; End voice

### 1. Find contact, result card, dark
`VCFindDark` · 390×844 · [HTML](/screens/voice/VCFindDark.html) · [PNG](/screens/voice/png/VCFindDark.png)

```text
Mel Voice

Pull up Sarah Reynolds

Here’s Sarah. You

Sarah Reynolds

Buyer · 412 Marina Blvd

Last touch 5 days
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Interrupt Mel; Mel, speaking; Here’s Sarah. You last talked 5 days ago.; Sarah Reynolds; Mute microphone; Switch to typing; End voice

### 2. Add note, result card, dark
`VCNoteDark` · 390×844 · [HTML](/screens/voice/VCNoteDark.html) · [PNG](/screens/voice/png/VCNoteDark.png)

```text
Mel Voice

Add a note, she wants 3 beds under 900K

Saved to Sarah’s notes.

Note saved

Sarah Reynolds

“Wants 3 beds under 900K”
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Interrupt Mel; Mel, speaking; Saved to Sarah’s notes.; Note saved; Mute microphone; Switch to typing; End voice

### 3. Set follow-up, result card, dark
`VCRemindDark` · 390×844 · [HTML](/screens/voice/VCRemindDark.html) · [PNG](/screens/voice/png/VCRemindDark.png)

```text
Mel Voice

Remind me to call her tomorrow at 10

Done. I’ll

Reminder

Call Sarah Reynolds

Tomorrow, 10:00 AM
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Interrupt Mel; Mel, speaking; Done. I’ll remind you tomorrow at 10 AM.; Reminder; Mute microphone; Switch to typing; End voice

### 4. Open profile, link card, dark
`VCOpenDark` · 390×844 · [HTML](/screens/voice/VCOpenDark.html) · [PNG](/screens/voice/png/VCOpenDark.png)

```text
Mel Voice

Open her profile

Here’s Sarah in your CRM.

Sarah Reynolds
Radius CRM
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Interrupt Mel; Mel, speaking; Here’s Sarah in your CRM.; Open Sarah Reynolds in Radius CRM; Mute microphone; Switch to typing; End voice

### 5. No match, dark
`VCNoneDark` · 390×844 · [HTML](/screens/voice/VCNoneDark.html) · [PNG](/screens/voice/png/VCNoneDark.png)

```text
Mel Voice

Find Mike Torres

No Mike Torres in
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Interrupt Mel; Mel, speaking; No Mike Torres in your contacts. Want me to add him?; Mute microphone; Switch to typing; End voice

### 6. Two matches, pick card, dark
`VCTwoDark` · 390×844 · [HTML](/screens/voice/VCTwoDark.html) · [PNG](/screens/voice/png/VCTwoDark.png)

```text
Mel Voice

Call Sarah

You have two Sarahs.

Sarah Reynolds
Sarah Kim
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, needs you; You have two Sarahs. Reynolds or Kim?; Pick a contact; Mute microphone; Switch to typing; End voice

### 7. Gmail not connected, connector card, dark
`VCGmailDark` · 390×844 · [HTML](/screens/voice/VCGmailDark.html) · [PNG](/screens/voice/png/VCGmailDark.png)

```text
Mel Voice

Email Sarah the listing

I need Gmail to

Gmail

Google

Send email
Read replies
Connect
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, needs you; I need Gmail to send that. Connect it and I’ll send.; Connect Gmail; Mute microphone; Switch to typing; End voice

### CRM by voice, prototype, light
`VCProtoLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/voice/VCProtoLight.html) · [PNG](/screens/voice/png/VCProtoLight.png)

Same content as `VCProto` in the other theme.

### 1. Find contact, result card, light
`VCFindLight` · 390×844 · [HTML](/screens/voice/VCFindLight.html) · [PNG](/screens/voice/png/VCFindLight.png)

```text
Mel Voice

Pull up Sarah Reynolds

Here’s Sarah.

Sarah Reynolds

Buyer · 412 Marina Blvd

Last touch 5 days
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Interrupt Mel; Mel, speaking; Here’s Sarah. You last talked 5 days ago.; Sarah Reynolds; Mute microphone; Switch to typing; End voice

### 2. Add note, result card, light
`VCNoteLight` · 390×844 · [HTML](/screens/voice/VCNoteLight.html) · [PNG](/screens/voice/png/VCNoteLight.png)

Same content as `VCNote` in the other theme.

### 3. Set follow-up, result card, light
`VCRemindLight` · 390×844 · [HTML](/screens/voice/VCRemindLight.html) · [PNG](/screens/voice/png/VCRemindLight.png)

```text
Mel Voice

Remind me to call her tomorrow at 10

Done. I’ll remind

Reminder

Call Sarah Reynolds

Tomorrow, 10:00 AM
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Interrupt Mel; Mel, speaking; Done. I’ll remind you tomorrow at 10 AM.; Reminder; Mute microphone; Switch to typing; End voice

### 4. Open profile, link card, light
`VCOpenLight` · 390×844 · [HTML](/screens/voice/VCOpenLight.html) · [PNG](/screens/voice/png/VCOpenLight.png)

Same content as `VCOpen` in the other theme.

### 5. No match, light
`VCNoneLight` · 390×844 · [HTML](/screens/voice/VCNoneLight.html) · [PNG](/screens/voice/png/VCNoneLight.png)

```text
Mel Voice

Find Mike Torres

No Mike Torres in your contacts.
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Interrupt Mel; Mel, speaking; No Mike Torres in your contacts. Want me to add him?; Mute microphone; Switch to typing; End voice

### 6. Two matches, pick card, light
`VCTwoLight` · 390×844 · [HTML](/screens/voice/VCTwoLight.html) · [PNG](/screens/voice/png/VCTwoLight.png)

Same content as `VCTwo` in the other theme.

### 7. Gmail not connected, connector card, light
`VCGmailLight` · 390×844 · [HTML](/screens/voice/VCGmailLight.html) · [PNG](/screens/voice/png/VCGmailLight.png)

```text
Mel Voice

Email Sarah the listing

I need Gmail to send

Gmail

Google

Send email
Read replies
Connect
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, needs you; I need Gmail to send that. Connect it and I’ll send.; Connect Gmail; Mute microphone; Switch to typing; End voice

### 1. Voice live, tap minimise, dark
`VMVoiceDark` · 390×844 · [HTML](/screens/voice/VMVoiceDark.html) · [PNG](/screens/voice/png/VMVoiceDark.png)

```text
Mel Voice

Follow up with Sarah Reynolds about
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, listening; Follow up with Sarah Reynolds about 412 Marina Blvd; Mute microphone; Switch to typing; End voice

### 2. Dashboard, bubble listening, dark
`VMHomeDark` · 390×844 · [HTML](/screens/voice/VMHomeDark.html) · [PNG](/screens/voice/png/VMHomeDark.png)

```text
K
Dashboard
```

Accessible labels: Dashboard, page content; Profile; Notifications, new; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox; Back to Mel Voice. Drag to move, drop on the cross to end.; Mel, listening

### 3. Clients, bubble speaking, dark
`VMClientsDark` · 390×844 · [HTML](/screens/voice/VMClientsDark.html) · [PNG](/screens/voice/png/VMClientsDark.png)

```text
K
Clients
```

Accessible labels: Clients, page content; Profile; Notifications, new; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox; Back to Mel Voice. Drag to move, drop on the cross to end.; Mel, speaking

### 4. Dragged, snaps to the side, dark
`VMSnapDark` · 390×844 · [HTML](/screens/voice/VMSnapDark.html) · [PNG](/screens/voice/png/VMSnapDark.png)

```text
K
Clients
```

Accessible labels: Clients, page content; Profile; Notifications, new; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox; Back to Mel Voice. Drag to move, drop on the cross to end.; Mel, listening

### 5. Needs you, Draft ready, dark
`VMNeedsDark` · 390×844 · [HTML](/screens/voice/VMNeedsDark.html) · [PNG](/screens/voice/png/VMNeedsDark.png)

```text
K
Clients
Draft ready
```

Accessible labels: Clients, page content; Profile; Notifications, new; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox; Back to Mel Voice. Drag to move, drop on the cross to end.; Mel, needs you

### 6. Tap bubble, back to voice with the card, dark
`VMBackDark` · 390×844 · [HTML](/screens/voice/VMBackDark.html) · [PNG](/screens/voice/png/VMBackDark.png)

```text
Mel Voice

Here’s the draft.

Sarah Reynolds · Email

Re: 412 Marina Blvd

Hi Sarah, checking in on 412 Marina Blvd. The open house is Saturday, 1 to 4 PM. Want me to save you a time to walk through?

Sends from your Radius email
Send
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, needs you; Here’s the draft. Say send, or tap Send.; Email draft to Sarah Reynolds; Mute microphone; Switch to typing; End voice

### 7. Drag onto the cross to end, dark
`VMEndDark` · 390×844 · [HTML](/screens/voice/VMEndDark.html) · [PNG](/screens/voice/png/VMEndDark.png)

```text
K
Dashboard
Drop to end
```

Accessible labels: Dashboard, page content; Profile; Notifications, new; Chat with Mel; Mel; Main; Dashboard; Clients; Transactions; Inbox; Back to Mel Voice. Drag to move, drop on the cross to end.; Mel, listening

### 1. Voice live, tap minimise, light
`VMVoiceLight` · 390×844 · [HTML](/screens/voice/VMVoiceLight.html) · [PNG](/screens/voice/png/VMVoiceLight.png)

```text
Mel Voice

Follow up with Sarah Reynolds
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, listening; Follow up with Sarah Reynolds about 412 Marina Blvd; Mute microphone; Switch to typing; End voice

### 2. Dashboard, bubble listening, light
`VMHomeLight` · 390×844 · [HTML](/screens/voice/VMHomeLight.html) · [PNG](/screens/voice/png/VMHomeLight.png)

Same content as `VMHome` in the other theme.

### 3. Clients, bubble speaking, light
`VMClientsLight` · 390×844 · [HTML](/screens/voice/VMClientsLight.html) · [PNG](/screens/voice/png/VMClientsLight.png)

Same content as `VMClients` in the other theme.

### 4. Dragged, snaps to the side, light
`VMSnapLight` · 390×844 · [HTML](/screens/voice/VMSnapLight.html) · [PNG](/screens/voice/png/VMSnapLight.png)

Same content as `VMSnap` in the other theme.

### 5. Needs you, Draft ready, light
`VMNeedsLight` · 390×844 · [HTML](/screens/voice/VMNeedsLight.html) · [PNG](/screens/voice/png/VMNeedsLight.png)

Same content as `VMNeeds` in the other theme.

### 6. Tap bubble, back to voice with the card, light
`VMBackLight` · 390×844 · [HTML](/screens/voice/VMBackLight.html) · [PNG](/screens/voice/png/VMBackLight.png)

Same content as `VMBack` in the other theme.

### 7. Drag onto the cross to end, light
`VMEndLight` · 390×844 · [HTML](/screens/voice/VMEndLight.html) · [PNG](/screens/voice/png/VMEndLight.png)

Same content as `VMEnd` in the other theme.

## Voice concepts

Designer notes:

- **Voice concept A (approved) · speaking**

### A · Dot field, dark
`VoiceConcept` · 390×844 · [HTML](/screens/voice/VoiceConcept.html) · [PNG](/screens/voice/png/VoiceConcept.png)

```text
Mel Voice

Sarah hasn’t replied in 5 days. I drafted a short follow-up.
```

Accessible labels: Mel voice mode, speaking; Voice settings; Mel, speaking; Sarah hasn’t replied in 5 days. I drafted a short follow-up.; Mute microphone; Switch to typing; End voice

### A · Dot field, light
`VoiceConceptALight` · 390×844 · [HTML](/screens/voice/VoiceConceptALight.html) · [PNG](/screens/voice/png/VoiceConceptALight.png)

```text
Mel Voice

Sarah hasn’t replied in 5 days. I drafted a short follow-up.
```

Accessible labels: Mel voice mode, speaking; Voice settings; Mel, speaking; Sarah hasn’t replied in 5 days. I drafted a short follow-up.; Mute microphone; Switch to typing; End voice

## Background states · iOS

Designer notes:

- **Background states · prototype**
- NEW (KJ, 28 Oct) · iOS only
  
  Prototype: island starts live. Tap island = expand. Tap wallpaper = collapse. Mute toggles. End = Voice ended, then hides. Talk to Mel widget = start again. After ~9s Mel needs you; Open goes to the voice prototype.
  
  · Mel Brand Guidelines only (KJ, 28 Oct): marks = 07 Mel in motion per state (listening, working, speaking, done, needs you = Deep Teal + mint, paused = grey). Open / Open chat / Try again = 08 Accent button (green, Deep Teal label). Mute = brand outline/secondary. End stays red (approved earlier, not in brand file). No skill teal.
  · ↳ rows in widgets: tap = open chat + send.
  · Mini Dot field in the island: out = speaking, in = listening, slow = working.
  · Lock screen widgets render monochrome on iOS, so no green there.
  · App icons + dock are grey skeletons.
  
  Copy not from Biju: Draft ready, Voice ended, Reconnecting, Stopped, 42/120, 120 added, Importing clients, Checking for duplicates, Import stopped, Row 65 has no name or email…, 120 clients added, Import done, Open, Open chat, Try again, Ask Mel, Opens chat, Talk to Mel, Starts voice, Mel suggests, 3 clients need a follow-up today, Nothing due today, Ask me anything, or talk to me, 2 follow-ups today, all widget ↳ prompts.
- **Dynamic Island · voice**
- **Dynamic Island · chat task (Mel works while you're out)**
- **Lock screen · Live Activity**
- **Widgets · home + lock**
- **Edge states**
- **Flow · leave the app mid voice**

### Prototype, dark
`Bg` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/voice/Bg.html) · [PNG](/screens/voice/png/Bg.png)

```text
Ask Mel

Opens chat

Talk to Mel

Starts voice

Ask anything
Follow up with Sarah Reynolds
Show my top buyers this week
```

Accessible labels: Home screen; Ask Mel, opens chat; Talk to Mel, starts voice; Dictate; Talk to Mel; Mel voice

### Prototype, light
`BgProtoLight` · 390×844 · interactive prototype (snapshot) · [HTML](/screens/voice/BgProtoLight.html) · [PNG](/screens/voice/png/BgProtoLight.png)

```text
Ask Mel

Opens chat

Talk to Mel

Starts voice

Ask anything
Follow up with Sarah Reynolds
Show my top buyers this week
```

Accessible labels: Home screen; Ask Mel, opens chat; Talk to Mel, starts voice; Dictate; Talk to Mel; Mel voice

### 1. Compact, listening, dark
`BGA1Dark` · 390×844 · [HTML](/screens/voice/BGA1Dark.html) · [PNG](/screens/voice/png/BGA1Dark.png)

Accessible labels: Home screen; Mel voice, listening

### 2. Compact, speaking, dark
`BGA2Dark` · 390×844 · [HTML](/screens/voice/BGA2Dark.html) · [PNG](/screens/voice/png/BGA2Dark.png)

Accessible labels: Home screen; Mel voice, speaking

### 3. Compact, working, dark
`BGA3Dark` · 390×844 · [HTML](/screens/voice/BGA3Dark.html) · [PNG](/screens/voice/png/BGA3Dark.png)

Accessible labels: Home screen; Mel voice, working

### 4. Compact, muted, dark
`BGA4Dark` · 390×844 · [HTML](/screens/voice/BGA4Dark.html) · [PNG](/screens/voice/png/BGA4Dark.png)

```text
Muted
```

Accessible labels: Home screen; Mel voice, muted

### 5. Compact, needs you, draft ready, dark
`BGA5Dark` · 390×844 · [HTML](/screens/voice/BGA5Dark.html) · [PNG](/screens/voice/png/BGA5Dark.png)

```text
Draft ready
```

Accessible labels: Home screen; Mel needs you, draft ready

### 6. Expanded, long press, speaking, dark
`BGA6Dark` · 390×844 · [HTML](/screens/voice/BGA6Dark.html) · [PNG](/screens/voice/png/BGA6Dark.png)

```text
Mel

Speaking

Sarah hasn’t replied in 5 days. I drafted a short follow-up.

End
```

Accessible labels: Home screen; Mel, expanded; Mute microphone

### 7. Expanded, needs you, Open, dark
`BGA7Dark` · 390×844 · [HTML](/screens/voice/BGA7Dark.html) · [PNG](/screens/voice/png/BGA7Dark.png)

```text
Mel

Needs you

Here’s the draft. Say send, or tap Send.

Hi Sarah, checking in on 412 Marina Blvd. The open house is Saturday, 1 to 4 PM. Want me to save you a time to walk through?

Open
End
```

Accessible labels: Home screen; Mel, expanded

### 8. Minimal, shared with another app, dark
`BGA8Dark` · 390×844 · [HTML](/screens/voice/BGA8Dark.html) · [PNG](/screens/voice/png/BGA8Dark.png)

```text
4:12
```

Accessible labels: Home screen; Timer, 4 minutes 12 seconds; Mel voice, speaking

### 1. Compact, listening, light
`BGA1Light` · 390×844 · [HTML](/screens/voice/BGA1Light.html) · [PNG](/screens/voice/png/BGA1Light.png)

Same content as `BGA1` in the other theme.

### 2. Compact, speaking, light
`BGA2Light` · 390×844 · [HTML](/screens/voice/BGA2Light.html) · [PNG](/screens/voice/png/BGA2Light.png)

Same content as `BGA2` in the other theme.

### 3. Compact, working, light
`BGA3Light` · 390×844 · [HTML](/screens/voice/BGA3Light.html) · [PNG](/screens/voice/png/BGA3Light.png)

Same content as `BGA3` in the other theme.

### 4. Compact, muted, light
`BGA4Light` · 390×844 · [HTML](/screens/voice/BGA4Light.html) · [PNG](/screens/voice/png/BGA4Light.png)

Same content as `BGA4` in the other theme.

### 5. Compact, needs you, draft ready, light
`BGA5Light` · 390×844 · [HTML](/screens/voice/BGA5Light.html) · [PNG](/screens/voice/png/BGA5Light.png)

Same content as `BGA5` in the other theme.

### 6. Expanded, long press, speaking, light
`BGA6Light` · 390×844 · [HTML](/screens/voice/BGA6Light.html) · [PNG](/screens/voice/png/BGA6Light.png)

Same content as `BGA6` in the other theme.

### 7. Expanded, needs you, Open, light
`BGA7Light` · 390×844 · [HTML](/screens/voice/BGA7Light.html) · [PNG](/screens/voice/png/BGA7Light.png)

Same content as `BGA7` in the other theme.

### 8. Minimal, shared with another app, light
`BGA8Light` · 390×844 · [HTML](/screens/voice/BGA8Light.html) · [PNG](/screens/voice/png/BGA8Light.png)

Same content as `BGA8` in the other theme.

### 1. Compact, importing, dark
`BGB1Dark` · 390×844 · [HTML](/screens/voice/BGB1Dark.html) · [PNG](/screens/voice/png/BGB1Dark.png)

```text
42/120
```

Accessible labels: Home screen; Mel importing clients, 42 of 120

### 2. Expanded, progress, dark
`BGB2Dark` · 390×844 · [HTML](/screens/voice/BGB2Dark.html) · [PNG](/screens/voice/png/BGB2Dark.png)

```text
Importing clients

42 of 120

Checking for duplicates

Open chat
```

Accessible labels: Home screen; Mel, expanded

### 3. Compact, done, dark
`BGB3Dark` · 390×844 · [HTML](/screens/voice/BGB3Dark.html) · [PNG](/screens/voice/png/BGB3Dark.png)

```text
120 added
```

Accessible labels: Home screen; Mel import done, 120 clients added

### 4. Compact, stopped, dark
`BGB4Dark` · 390×844 · [HTML](/screens/voice/BGB4Dark.html) · [PNG](/screens/voice/png/BGB4Dark.png)

```text
Stopped
```

Accessible labels: Home screen; Mel import stopped

### 5. Expanded, stopped, Open chat, dark
`BGB5Dark` · 390×844 · [HTML](/screens/voice/BGB5Dark.html) · [PNG](/screens/voice/png/BGB5Dark.png)

```text
Import stopped

64 of 120 added

Row 65 has no name or email. Tell me how to fix it.

Open chat
```

Accessible labels: Home screen; Mel, expanded

### 1. Compact, importing, light
`BGB1Light` · 390×844 · [HTML](/screens/voice/BGB1Light.html) · [PNG](/screens/voice/png/BGB1Light.png)

Same content as `BGB1` in the other theme.

### 2. Expanded, progress, light
`BGB2Light` · 390×844 · [HTML](/screens/voice/BGB2Light.html) · [PNG](/screens/voice/png/BGB2Light.png)

Same content as `BGB2` in the other theme.

### 3. Compact, done, light
`BGB3Light` · 390×844 · [HTML](/screens/voice/BGB3Light.html) · [PNG](/screens/voice/png/BGB3Light.png)

Same content as `BGB3` in the other theme.

### 4. Compact, stopped, light
`BGB4Light` · 390×844 · [HTML](/screens/voice/BGB4Light.html) · [PNG](/screens/voice/png/BGB4Light.png)

Same content as `BGB4` in the other theme.

### 5. Expanded, stopped, Open chat, light
`BGB5Light` · 390×844 · [HTML](/screens/voice/BGB5Light.html) · [PNG](/screens/voice/png/BGB5Light.png)

Same content as `BGB5` in the other theme.

### 1. Voice live, dark
`BGC1Dark` · 390×844 · [HTML](/screens/voice/BGC1Dark.html) · [PNG](/screens/voice/png/BGC1Dark.png)

```text
Wednesday 28 October

9:41

Mel

Speaking

Sarah hasn’t replied in 5 days. I drafted a short follow-up.

End
```

Accessible labels: Mel live activity; Mute microphone

### 2. Voice needs you, draft ready, dark
`BGC2Dark` · 390×844 · [HTML](/screens/voice/BGC2Dark.html) · [PNG](/screens/voice/png/BGC2Dark.png)

```text
Wednesday 28 October

9:41

Mel

Needs you

Here’s the draft. Say send, or tap Send.

Hi Sarah, checking in on 412 Marina Blvd. The open house is Saturday, 1 to 4 PM. Want me to save you a time to walk through?

Open
End
```

Accessible labels: Mel live activity

### 3. Chat task, progress, dark
`BGC3Dark` · 390×844 · [HTML](/screens/voice/BGC3Dark.html) · [PNG](/screens/voice/png/BGC3Dark.png)

```text
Wednesday 28 October

9:41

Importing clients

42 of 120

Checking for duplicates
```

Accessible labels: Mel live activity

### 4. Chat task, done, dark
`BGC4Dark` · 390×844 · [HTML](/screens/voice/BGC4Dark.html) · [PNG](/screens/voice/png/BGC4Dark.png)

```text
Wednesday 28 October

9:41

120 clients added

Import done

Open chat
```

Accessible labels: Mel live activity

### 1. Voice live, light
`BGC1Light` · 390×844 · [HTML](/screens/voice/BGC1Light.html) · [PNG](/screens/voice/png/BGC1Light.png)

Same content as `BGC1` in the other theme.

### 2. Voice needs you, draft ready, light
`BGC2Light` · 390×844 · [HTML](/screens/voice/BGC2Light.html) · [PNG](/screens/voice/png/BGC2Light.png)

Same content as `BGC2` in the other theme.

### 3. Chat task, progress, light
`BGC3Light` · 390×844 · [HTML](/screens/voice/BGC3Light.html) · [PNG](/screens/voice/png/BGC3Light.png)

Same content as `BGC3` in the other theme.

### 4. Chat task, done, light
`BGC4Light` · 390×844 · [HTML](/screens/voice/BGC4Light.html) · [PNG](/screens/voice/png/BGC4Light.png)

Same content as `BGC4` in the other theme.

### 1. Home, small x2 + medium, dark
`BGD1Dark` · 390×844 · [HTML](/screens/voice/BGD1Dark.html) · [PNG](/screens/voice/png/BGD1Dark.png)

```text
Ask Mel

Opens chat

Talk to Mel

Starts voice

Ask anything
Follow up with Sarah Reynolds
Show my top buyers this week
```

Accessible labels: Home screen; Ask Mel, opens chat; Talk to Mel, starts voice; Dictate; Talk to Mel

### 2. Home, large, Mel suggests, dark
`BGD2Dark` · 390×844 · [HTML](/screens/voice/BGD2Dark.html) · [PNG](/screens/voice/png/BGD2Dark.png)

```text
Mel suggests

3 clients need a follow-up today.

Follow up with Sarah Reynolds
Remind me to call Mike at 4 PM
Show my top buyers this week
Draft a just-listed email
Ask anything
```

Accessible labels: Home screen; Dictate; Talk to Mel

### 3. Lock screen, circular + rectangular + inline, dark
`BGD3Dark` · 390×844 · [HTML](/screens/voice/BGD3Dark.html) · [PNG](/screens/voice/png/BGD3Dark.png)

```text
2 follow-ups today

9:41

Ask Mel
Sarah hasn’t replied in 5 days
```

Accessible labels: Talk to Mel; Ask Mel, Sarah has not replied in 5 days; Ask Mel, opens chat

### 1. Home, small x2 + medium, light
`BGD1Light` · 390×844 · [HTML](/screens/voice/BGD1Light.html) · [PNG](/screens/voice/png/BGD1Light.png)

Same content as `BGD1` in the other theme.

### 2. Home, large, Mel suggests, light
`BGD2Light` · 390×844 · [HTML](/screens/voice/BGD2Light.html) · [PNG](/screens/voice/png/BGD2Light.png)

Same content as `BGD2` in the other theme.

### 3. Lock screen, circular + rectangular + inline, light
`BGD3Light` · 390×844 · [HTML](/screens/voice/BGD3Light.html) · [PNG](/screens/voice/png/BGD3Light.png)

Same content as `BGD3` in the other theme.

### 1. Connection lost, lock screen, dark
`BGE1Dark` · 390×844 · [HTML](/screens/voice/BGE1Dark.html) · [PNG](/screens/voice/png/BGE1Dark.png)

```text
Wednesday 28 October

9:41

Mel

Connection lost

Lost connection. Your chat is saved.

Try again
End
```

Accessible labels: Mel live activity

### 2. Reconnecting, island, dark
`BGE2Dark` · 390×844 · [HTML](/screens/voice/BGE2Dark.html) · [PNG](/screens/voice/png/BGE2Dark.png)

```text
Reconnecting
```

Accessible labels: Home screen; Mel voice, reconnecting

### 3. Mic denied, from a widget tap, dark
`BGE3Dark` · 390×844 · [HTML](/screens/voice/BGE3Dark.html) · [PNG](/screens/voice/png/BGE3Dark.png)

```text
Mel Voice

Microphone off

Mel needs your microphone to talk.

Open Settings
Type instead
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, paused; Mel needs your microphone to talk.; Mute microphone; Switch to typing; End voice

### 4. Widget, nothing due, dark
`BGE4Dark` · 390×844 · [HTML](/screens/voice/BGE4Dark.html) · [PNG](/screens/voice/png/BGE4Dark.png)

```text
Mel suggests

Nothing due today.

Ask me anything, or talk to me.

Ask anything
```

Accessible labels: Home screen; Dictate; Talk to Mel

### 1. Connection lost, lock screen, light
`BGE1Light` · 390×844 · [HTML](/screens/voice/BGE1Light.html) · [PNG](/screens/voice/png/BGE1Light.png)

Same content as `BGE1` in the other theme.

### 2. Reconnecting, island, light
`BGE2Light` · 390×844 · [HTML](/screens/voice/BGE2Light.html) · [PNG](/screens/voice/png/BGE2Light.png)

Same content as `BGE2` in the other theme.

### 3. Mic denied, from a widget tap, light
`BGE3Light` · 390×844 · [HTML](/screens/voice/BGE3Light.html) · [PNG](/screens/voice/png/BGE3Light.png)

Same content as `BGE3` in the other theme.

### 4. Widget, nothing due, light
`BGE4Light` · 390×844 · [HTML](/screens/voice/BGE4Light.html) · [PNG](/screens/voice/png/BGE4Light.png)

Same content as `BGE4` in the other theme.

### 1. Voice live, swipe home, dark
`BGF1Dark` · 390×844 · [HTML](/screens/voice/BGF1Dark.html) · [PNG](/screens/voice/png/BGF1Dark.png)

```text
Mel Voice

Sarah hasn’t replied
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Interrupt Mel; Mel, speaking; Sarah hasn’t replied in 5 days. I drafted a short follow-up.; Mute microphone; Switch to typing; End voice

### 2. Island compact, Mel keeps talking, dark
`BGF2Dark` · 390×844 · [HTML](/screens/voice/BGF2Dark.html) · [PNG](/screens/voice/png/BGF2Dark.png)

Accessible labels: Home screen; Mel voice, speaking

### 3. Long press, expanded, dark
`BGF3Dark` · 390×844 · [HTML](/screens/voice/BGF3Dark.html) · [PNG](/screens/voice/png/BGF3Dark.png)

```text
Mel

Speaking

Sarah hasn’t replied in 5 days. I drafted a short follow-up.

End
```

Accessible labels: Home screen; Mel, expanded; Mute microphone

### 4. Mel needs you, island flags it, dark
`BGF4Dark` · 390×844 · [HTML](/screens/voice/BGF4Dark.html) · [PNG](/screens/voice/png/BGF4Dark.png)

```text
Draft ready
```

Accessible labels: Home screen; Mel needs you, draft ready

### 5. Tap island, back to voice with the draft, dark
`BGF5Dark` · 390×844 · [HTML](/screens/voice/BGF5Dark.html) · [PNG](/screens/voice/png/BGF5Dark.png)

```text
Mel Voice

Here’s the draft.

Sarah Reynolds · Email

Re: 412 Marina Blvd

Hi Sarah, checking in on 412 Marina Blvd. The open house is Saturday, 1 to 4 PM. Want me to save you a time to walk through?

Sends from your Radius email
Send
```

Accessible labels: Mel voice mode; Minimise to chat, voice stays on; Mel; Mel, needs you; Here’s the draft. Say send, or tap Send.; Email draft to Sarah Reynolds; Mute microphone; Switch to typing; End voice

### 6. End, island says Voice ended, then hides, dark
`BGF6Dark` · 390×844 · [HTML](/screens/voice/BGF6Dark.html) · [PNG](/screens/voice/png/BGF6Dark.png)

```text
Voice ended
```

Accessible labels: Home screen; Mel voice ended

### 1. Voice live, swipe home, light
`BGF1Light` · 390×844 · [HTML](/screens/voice/BGF1Light.html) · [PNG](/screens/voice/png/BGF1Light.png)

Same content as `BGF1` in the other theme.

### 2. Island compact, Mel keeps talking, light
`BGF2Light` · 390×844 · [HTML](/screens/voice/BGF2Light.html) · [PNG](/screens/voice/png/BGF2Light.png)

Same content as `BGF2` in the other theme.

### 3. Long press, expanded, light
`BGF3Light` · 390×844 · [HTML](/screens/voice/BGF3Light.html) · [PNG](/screens/voice/png/BGF3Light.png)

Same content as `BGF3` in the other theme.

### 4. Mel needs you, island flags it, light
`BGF4Light` · 390×844 · [HTML](/screens/voice/BGF4Light.html) · [PNG](/screens/voice/png/BGF4Light.png)

Same content as `BGF4` in the other theme.

### 5. Tap island, back to voice with the draft, light
`BGF5Light` · 390×844 · [HTML](/screens/voice/BGF5Light.html) · [PNG](/screens/voice/png/BGF5Light.png)

Same content as `BGF5` in the other theme.

### 6. End, island says Voice ended, then hides, light
`BGF6Light` · 390×844 · [HTML](/screens/voice/BGF6Light.html) · [PNG](/screens/voice/png/BGF6Light.png)

Same content as `BGF6` in the other theme.
