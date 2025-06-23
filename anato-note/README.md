# 🧠 AnatoNote

**AnatoNote** is a custom Anki note type designed for anatomy learning — ideal for visual identification of bones, organs, and anatomical structures. It supports images, clean styling, and custom field templates using HTML, CSS, and JavaScript.

## ✅ Usage Instructions: How to Set Up AnatoNote

To use this note type in Anki, follow these steps:

### 1. Open Anki

Launch the Anki desktop app.

### 2. Create a New Note Type

- Go to **Tools → Manage Note Types**.
- Click **Add**.
- Select **“Add: Basic”** as the base model.
- Name the new note type **AnatoNote** (or any name you prefer).
- Click **OK**.

### 3. Configure the Fields

- In the **Manage Note Types** window, select your new note type.
- Click **Fields**.
- Rename the fields as follows:
  - **“Front”** → **Image**
  - **“Back”** → **Answer**
- Click **Save** or **Close**.

### 4. Set Up the Card Templates

- Still in the **Manage Note Types** window, click **Cards...**.
- In the **Front Template**, replace everything with the contents of [`front.html`](./front.html).
- In the **Back Template**, replace everything with the contents of [`back.html`](./back.html).
- In the **Styling** section at the bottom, replace the content with the contents of [`style.css`](./style.css).
- Click **Save** or **Close** when finished.

### ✅ Done!

Your new **AnatoNote** is now ready to use.

When adding a new note:

- Add an **image** (e.g. anatomical diagram) to the **Image** field.
- Type the correct **label or structure name** into the **Answer** field.
