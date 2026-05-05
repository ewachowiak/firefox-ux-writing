# Conversion Messaging: Best Practices

## About this document

This document gives Claude surface-specific guidance for writing copy that drives four high-impact conversion actions: set default browser (desktop), set default browser (mobile), sync Firefox data, and import data.

**When to apply:** Apply this guidance automatically whenever the copy task involves one of these four actions, regardless of how the user frames the request.

**Override rule:** This document is more specific than general Firefox writing guidelines. Where it conflicts, this document takes precedence for these four actions specifically:
- Mobile default: direct action language overrides general "lead with value" guidance and Mina persona guidance
- Sync/accounts: privacy/security as reassurance only overrides Felt Privacy instincts
- Import: same override as sync applies

---

## Set default browser (desktop)

**Why this matters:** On desktop, setting Firefox as the default browser is one of the most reliable activation signals we've seen. People who set Firefox as default are less likely to churn over a 3-month period.

### Quick copy recommendations

| Use | Be cautious with |
|-----|-----------------|
| **Early lifecycle (install, first-run, early days):** "Make Firefox your go-to browser." / "Choose Firefox as your primary browser." / "Open my links with Firefox." | "Default browser" by itself (without outcome framing), outside of a CTA |
| **Re-engagement surfaces (resurrected or lapsed users):** Lead with a specific, personal privacy benefit before the default ask. "We don't track where you browse." / "Firefox blocks trackers automatically. No setup needed." | Abstract or aspirational language as the primary argument: "A better internet," "Backed by a non-profit," "Independent browser" |
| "Default browser" is fine in CTAs across both contexts. In headline and body copy, pair with an outcome ("so links open in Firefox," "so Firefox is your everyday browser"). | Overinvesting in CTA wording when the framing hasn't been resolved. On re-engagement surfaces, equivalent framing with different CTAs produces equivalent default rates. |
| **Privacy and security messaging** works well when tied to a specific, personal outcome. More effective than values-first language for driving default adoption. "Firefox blocked thousands of trackers this month. Make it your default." | Privacy messaging used as a retention argument. Evidence supports it for default adoption |

### Messaging checklist

- Is the timing right? Is this shown early (install, first run, early days)? If shown post-onboarding, is the action tied to a clear moment of value (e.g. sign-in, import, autofill success)?
- Is the action clear? Does the copy clearly explain what setting default means in practice (e.g. links opening in Firefox)?
- Are we leading with outcomes, not abstractions? Is the primary argument about what changes for the user, not about who we are as a brand? Habit and outcome framing should carry the message. Values and philosophy should reinforce the decision, not replace the core benefit.
- Is the tone encouraging, not enforcing? Does the message feel like a friendly, helpful suggestion rather than a system warning or obligation?
- Are we keeping the ask focused? Is this message primarily about setting Firefox as default, without bundling multiple actions? (Applies outside of first run onboarding)
- Is the prompt lightweight and respectful? If this is a follow-up, is it dismissible and not interrupting a task?

### Key insights

1. **Ask early in the lifecycle:** Prioritize prominent asks during install and first-run onboarding; consider additional prompts during early-days moments and if there are “new device” signals (e.g. early sign-in, import, backup restore). Post-onboarding prompts should be tied to moments of value (e.g. submitting a form with autofilled data, 10,000th tracker blocked).
2. **Concrete outcomes over values and technical terms:** 
Lead with phrases that describe what the user will do and experience, like “go-to browser / primary browser / open links with Firefox.” 
“Default browser” is fine to use for CTAs, but in headline and body copy, make sure to pair with language about the everyday outcomes and benefits (e.g. links opening in Firefox, Firefox being the everyday browser).
Privacy and security messaging can also work well when tied to a concrete, personal outcome ("Firefox blocks trackers automatically. No setup needed.") rather than an abstract value. 
Be cautious about leading with abstract values-based or philosophical messaging (e.g. “a better internet,” “backed by a non-profit,” open-source positioning) — unless translated into a concrete user benefit (e.g. “You’re in safe paws”)
On re-engagement surfaces specifically, the framing around privacy is an effective conversion lever. CTA wording matters less than previously assumed at these surfaces, and the bigger drop-off tends to happen at the OS prompt step, not the message.
3. **For early-day reminders, prefer friendly, emotive tone + visuals:** If they didn’t set default during first run, re-ask with a reminder that feels human. Avoid copy that feels like a system warning, enforcement, or obligation.

---

## Set default browser (mobile)

**Why this matters:** On mobile, "set to default" is an OS-mediated task, and what works on desktop doesn't reliably translate. It's also platform-dependent: on Android, users can change their default browser via a system prompt in one step, while on iOS users are required to leave the app and navigate system settings (multiple steps). As such, message strategies will need to vary by platform.

**Override note:** On mobile, direct action language ("Set Firefox as your default browser") outperforms benefit descriptions, emotive framing, and values-led language. This overrides general Mina persona guidance to lead with the human problem, and general guidance to lead with value. Use explicit default browser language instead.

### Quick copy recommendations

| Use | Be cautious with |
|-----|-----------------|
| "Set Firefox as your default browser" | Habit language like "go-to browser" / "everyday browser" |
| "Make Firefox your default browser" | Values/brand-led language when paired with system instructions |
| Short, explicit references to "default browser settings" | Euphemisms that obscure what OS setting is changing |

### Messaging checklist

- Are we being explicit about the action and avoiding euphemisms? Say "Set Firefox as default browser," and avoid euphemisms like "go-to browser" or values-led language. On mobile, habit/emotional language can add ambiguity during an OS-setting task; tests of emotive/values copy didn't show impact.
- Are we matching the platform's reality (Android vs iOS)? Android can be a one-step ask via a system prompt; iOS requires leaving the app to go to Settings + multiple steps — so the copy needs to prepare people for that.
- If they skip, will they get another chance later — and is the re-prompt tied to a good moment? Post-onboarding surfaces are limited, so treat default as repeatable when you do have a surface — ideally after a "success" moment like sharing a link or saving a password.

### Key insights

1. **Make set to default the first onboarding priority**: On mobile, set to default performs best when it comes as close to the beginning of onboarding as possible. It should not be buried behind general customization steps, feature education, or value statements.
2. **Use explicit "default browser" language and system prompts, NOT benefit descriptions:**
Name the action directly (“Set Firefox as default browser”) rather than relying on euphemistic, habit-based, or values-led language (e.g. “go-to browser”). 
On Android, use the Android system prompt during first run onboarding; this is proven more effective than our own messaging. 
On iOS, show clear instructions before sending users to Settings.
3. **Treat default as a repeatable opportunity, not a one-shot ask:** Re-prompt users who skipped default during onboarding with contextual reminders — ideally tied to a moment of success (e.g., after completing a task) or differentiation over other browsers (speed/performance, features, etc.).

---

## Sync Firefox data (desktop)

**Why this matters:** Accounts and sync correlate with deeper, more committed Firefox use: most surveyed sync users say they use it daily, and over 80% report having Firefox synced across all their devices. At the same time, experiments show that while targeted campaigns can increase Firefox Account sign-ins, they do not necessarily produce measurable gains in DAU or retention. Sign-in messaging primarily drives account adoption — not guaranteed usage lift for Firefox usage.

The content challenge: awareness of "Sync" (and what it actually does) is low. So our job is to make "sign in" feel like a helpful next step that keeps things consistent across devices — without adding uncertainty or sounding like compliance.

**Override note:** For sync, accounts, and sign-in copy, privacy and security language should be used to reassure, not as the primary hook. This overrides Felt Privacy guidance to make privacy felt and concrete. Lead with backup and continuity outcomes instead.

### Quick copy recommendations

| Use | Be cautious with |
|-----|-----------------|
| Cite specific data types: "Back up your [bookmarks, passwords, etc.]," "Sync your [bookmarks, passwords, etc.]" | "Create an account" |
| "Sign in" | "Sign in/up" or "Sign up" |
| "Restore your Firefox info on another device" | Mentions of encryption, account privacy, or security as the main hook |
| "Pick up where you left off" | Abstract benefit language without a clear user outcome |
| "Your synced data is encrypted" (only when it adds reassurance without making the message harder to understand — keep it short, secondary, and tied to a clear user benefit) | Heavy emphasis on sensitive data (like passwords or financial info) unless the moment clearly calls for it |
| "Your data is encrypted, so only you can see it." (same conditions as above) | "Sync" by itself, if the user may not know what it means. Prefer naming the thing that sync does over "sync" by itself |

### Messaging checklist

- What does signing in unlock right now, in this moment? If you can't answer in one sentence, the copy will probably feel generic.
- Did the user just do something that makes sync feel relevant? Saved a bookmark, imported data, changed settings, etc. If not, reconsider the timing.
- Are we leading with a concrete outcome, not an account concept? Is the message about backing up, keeping, restoring, or continuing something the user cares about right now — not just about having an account or using sync? Would a person who doesn't already know what "sync" means understand what will happen?
- If we mention privacy/security, does it clarify something real for the user? If we mention encryption, are we keeping it short and positive? Explain what data is involved, where it applies, what the user controls, and what the protection means in practice. Avoid trust-building words like "secure," "private," or "encrypted" unless the meaning is clear from the context. When you mention encryption, keep it brief. Avoid long explanations, technical detail, or negative, threat-heavy language unless the context clearly calls for it.
- Are we keeping the action simple? Lead with compelling benefits about backing up or syncing data across devices instead of language about creating an account. Research shows reluctance to manage another account; keeping CTAs short (e.g. "Sign in") may reduce perceived friction.
- Will they get another chance later if they skip? Multiple lightweight opportunities beat one "big decision."

### Key insights

1. **Introduce accounts in context, tied to an immediate outcome:** Show sign-in messaging when the user has clear intent or investment (onboarding, importing, saving a bookmark), and lead with the near-term outcome: keep what you’ve done, avoid losing it, continue elsewhere.
2. **Lead with backup & continuity, not abstract benefits:** Lead with backup, continuity, and preservation of important data or progress (e.g., saving bookmarks, restoring data on another device, continuing where you left off). If you use security or privacy language, use it to reassure and clarify — not as the main hook. Avoid leading with abstract ideas like encryption, account privacy, or general security claims unless the user is already thinking about security and the benefit is explained in plain language.
3. **Use security/privacy to reassure, not carry the message:**
Use account security or privacy language to make syncing feel clearer and safer, not as the main reason to sign in. 
Don’t rely on trust or security words like “secure” or “encrypted” unless the user can quickly tell what they mean. Explain the benefit in plain language instead. If you mention encryption, don’t assume more explanation will help. 
When possible, be clear about what data is involved, where it applies (this device or others), and what the user controls (like choosing what to sync).
TL;DR: In most cases, backup or continuity language should lead the headline or first sentence. Privacy and security language works better as supporting text.
4. **Give repeated, low-friction chances to sign in during onboarding**: Don’t treat sign-in as a one-shot decision. Use multiple lightweight, skippable CTAs across onboarding so people can act when they’re ready
5. **Keep CTAs short; let "Sign in" do the heavy lifting:** Keep CTA language short and benefit-focused, using a brief “sign in” as opposed to longer phrases like “sign up/in” or “create an account.”

---

## Import data to Firefox

**Why this matters:** Import makes switching browsers feel less like starting over by bringing your bookmarks, passwords, and browsing history with you. Some people want import early so they can get back to saved logins and familiar sites and start browsing "right from the start." Others hesitate during first run because import feels like it involves personal info, and they want to try Firefox first before deciding.

Import by itself isn't a strong standalone predictor of DAU or retention. Import works more like a supporting activation step: it lowers switching cost, restores familiar workflows, and can create a natural moment to introduce bigger actions like set default or sign in.

**Override note:** For import copy, do not lead with privacy or security themes. This overrides Felt Privacy guidance. Heavy privacy/security framing raises perceived stakes at the moment of action and increases hesitation. Position import as a routine convenience step instead.

### Quick copy recommendations

| Use | Be cautious with |
|-----|-----------------|
| "Import your bookmarks, passwords, and history" | Vague phrases like "your stuff" or "your information" without clarification and more precise language elsewhere |
| "Import my data" | Overloaded reassurance in the CTA (e.g., "Safely import your private data") |
| "Import to Firefox" | Heavy privacy and security themes as the primary message (can raise perceived stakes at the moment of action) |
| "Bring your bookmarks and passwords" | Language that implies obligation or finality (e.g., "You'll need to import now") |
| "You can import this later" / "Not now" (where applicable) | |

### Messaging checklist

- Is the action clear and lightweight? Are we naming what will be imported (bookmarks, passwords, history) with short, action-forward language — without cramming reassurance into the CTA?
- Does this respect user readiness and control? Is it obvious import is optional and can happen later ("Not now"), instead of sounding urgent or final?
- Are we building trust without making it feel scary? Don't lead with heavy privacy/security selling points here, as it can lead to more hesitation at this step; instead, position import as a routine convenience step.
- Is this the right moment to ask? Is the prompt placed where it fits the journey (early setup, returning user, recovery context) without competing with higher-priority actions?

### Key insights

1. **Be explicit about what will be imported:** Always name the specific data types (bookmarks, passwords, history). Avoid vague “your stuff / your data” without clarification. 
2. **Keep the CTA short; put reassurance in supporting text:**
Use short, action CTAs (“Import my data,” “Import to Firefox”). 
If you need reassurance (reversibility, ease, etc.), put it in supporting copy — not inside the CTA. 
Warm language like “Make yourself at home” is fine, but it should be paired with concrete import language, not replace it. 
3. **Frame import as a normal setup step, not a big decision:** Position import as a routine part of getting started. The vibe should be “this is what people often do when setting up,” not “you must decide this right now.”
