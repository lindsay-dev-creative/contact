# Contact

`inquiries.html` — project inquiry form for Lindsay Dev Creative.

- Responsive, self-contained single file (dark `#0A0A0A` + gold `#D4A85A` LDC theme).
- Typography: PP Editorial New (headers, bundled in `/fonts`) + Inter (body, Google Fonts). Font sizing in `rem`.
- Submits via `mailto:` — on submit it validates, builds a formatted email, and opens the visitor's mail client to `lindsay@lindsaydevcreative.com`.

### Conditional logic
- **Service → Other** reveals a free-text field.
- **Referral → Other** reveals a free-text field.
- Selecting **Full Brand Identity** or **Website Development** hides the **Under $1,000** budget option.
- **My timeline is flexible** removes the required target-date.

### Notes
- `fonts/PPEditorialNew-*.otf` are bundled so the file renders correctly when served. PP Editorial New is a licensed typeface — keep this repo private if license terms require it.
