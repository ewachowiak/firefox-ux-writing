# Writing for empty states

## What are empty states?

Empty states are moments when there is no information to show. Empty states happen in different scenarios. For example, people will see them when:

- They've never interacted with or are not currently interacting with a feature (for example, they have not saved any bookmarks)

- They've removed or cleared the content that used to be there

- There's simply no data or information to display

Not all empty states are created equal. As with everything, context matters.

- Onboarding and education: Sometimes, empty states can be used to educate people about surfaces and features. When used in this way, they may reinforce or repeat what someone may see in other messaging elements, such as onboarding flows or feature tours. And this repetition is okay. Because empty states are not dismissable, they have a higher chance of reaching users.

- Encouraging interaction: When it makes sense, use empty states to guide people—let them know what they can do to get started or add content.

- Reporting on reality when there's nothing to show: Sometimes, empty states can have a simple job of telling people the empty view they're seeing is accurate, expected, and okay (not an error).

These scenarios often overlap. If an empty state has any onboarding or educational role — even alongside a reporting role — treat it as an onboarding empty state and apply those guidelines. Only use the "reporting on reality" framing for purely transactional surfaces where there is no feature to educate about (for example, an empty search results list).

When used for onboarding, education, or encouraging interaction, empty states can be an opportunity to express our brand personality, with more emotive copy and visuals.

## Anatomy of an empty state

An empty state can optionally include these elements: title, body copy, action, and illustration. Include what is necessary for the context and appropriate for the space. Empty states for an entire page will likely include all elements. Empty states that exist as part of a page alongside other content will likely include fewer elements (for example, just a single string).

Example of empty states that include all 4 parts: illustration, title, body copy, action.

Example of an empty state that includes one part: body copy and illustration only.

## Writing guidelines

> **Avoid "No," "None," or other negative phrases in titles and body copy.** This applies to any empty state with an onboarding or educational role — which is most product empty states. The exception is purely transactional surfaces where there is no feature to educate about (for example, "No results found" on a search page).

### Titles

These general writing rules for titles also apply to titles in empty states:

- Be concise.

- Use sentence case (except on iOS, which uses title case)

- No end punctuation, unless it's a question.

When an empty state is taking on an educational and onboarding role:

- Focus the language on what is possible and the benefits

- Avoid "No" or negative phrases (see callout above)

### Body copy

- Avoid repeating information from the title.

- Keep messages to 1 or 2 sentences.

- Optional, based on context: Include the reason for the empty state and where the person can go next. Keep in mind: sometimes there may not be anything for them to do.

- When linking to other content, like a support article, try to summarize or hint at the additional info that will be available. (Minimize "cold" linking, i.e., linking with minimal context.)

### Action

- Use a primary button if there's an important action for the person to take.

- Lead with a strong verb that encourages action, such as "Try", "Remove", or "Create". To provide enough context, also include a noun.

- Consider a secondary action to dismiss or cancel the suggested action.

These general writing rules for actions also apply to actions in empty states:

- Be clear and predictable.

- Be concise. Avoid unnecessary words and articles such as the, an, or a.

---

## Worked example: borderline case

The Passwords section in Settings shows an empty state when a user has no saved passwords yet. This might feel like a "reporting on reality" situation — after all, there really are no passwords to show. But because Firefox can save passwords and the user may not know that yet, this empty state has an educational role. That means the onboarding guidelines apply.

**Wrong** — reports the empty state as a dead end:

> **No saved passwords**
> You haven't saved any passwords yet.

**Right** — focuses on what's possible and leads with benefit:

> **Save passwords as you browse**
> Firefox can save your passwords so you don't have to remember them.
> [Import from another browser]

The wrong version uses "No" in the title and repeats the same negative idea in the body. The right version tells the user what Firefox can do for them and gives them a path forward.
