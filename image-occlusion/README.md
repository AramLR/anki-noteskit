# 📷 Better‑Styled **Image Occlusion** Note

_A drop‑in facelift for Anki’s native **Image Occlusion** note type._

## ⚡ Quick‑Start (≈ 2 min)

1. **Open Anki Desktop**
2. **(Recommended) Clone the native note type**
   _Tools → Manage Note Types →_ select **“Image Occlusion”** → **Clone** → give it a name (e.g. _Image Occlusion — Clean_).
   _(Cloning keeps the original untouched in case you want to revert.)_
3. **Open the card editor** for your (cloned) note type
   In _Manage Note Types_ choose it → **Cards…**
4. **Replace the templates**

   | Section            | Paste                        |
   | ------------------ | ---------------------------- |
   | **Front Template** | everything from `front.html` |
   | **Back Template**  | everything from `back.html`  |
   | **Styling**        | everything from `style.css`  |

5. **Save → Close.** Done! Create Image Occlusion cards as usual.

## ⚠️ Known Caveats / Warnings

1. **Native only** — This makeover targets Anki’s _built‑in_ **Image Occlusion** note type. It **has not been tested** with the _Image Occlusion Enhanced_ add‑on and will probably break there.
2. **Speed‑run styling** — The CSS was written in <30 minutes. Expect rough edges—especially on AnkiDroid / AnkiMobile where viewport quirks differ. PRs welcome!

## 🛠️ Tweaking

Feel free to fork the CSS (especially media queries) to suit your deck colours or phone layout.

Happy occluding & good luck with your studies! 🧠
