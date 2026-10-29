# Suggest

Suggestion chips under a Mel reply. Tap sends the chip text at once. shadcn Suggestion shape, DS colours. No script.

```html
<div class="c-suggest">
  <button type="button" class="c-suggest__btn"><span>Send it</span></button>
  <button type="button" class="c-suggest__btn"><span>Make it shorter</span></button>
</div>
```

- **Shape.** 32px chip, `radius-input` (8), 1px `border-card`, `surface-tile` fill, 14px medium. The button is 44pt tall for touch; the chip sits inside it.
- **Row.** Scrolls sideways, bleeds to the screen edge, fades on the right.
- **Versus prompt row.** Chips send; `c-prompt-row` fills the composer. Use one kind per reply.
- **Copy.** Two to four words, a verb first.
- Approved by KJ (chat intimation, 27 October 2026).
