# Module 2 - Activity 3 - State, Events, and Lists

> **Builds on Activity 2.** The new idea is **state**, so take it slowly. You
> are **done when `npm test` is all green**.

Now your components come alive. You will add **state** (data that changes),
**event handlers** (responding to clicks and typing), **conditional rendering**
(showing things based on a condition), and **lists** (rendering an array).

## Read first

The concepts for this activity live in your **course workspace repo**:

- `content/m2-react/README.md` -> **Activity 3** section
- `content/react-theory/04-hooks-mental-model.md` (state, the rules of hooks)
- `content/react-theory/02-virtual-dom-and-rendering.md` (why lists need keys)

## What to do

### 1. Fill in your details

Open [`student.json`](student.json) and fill in every field (keep it identical
to your other activities; `classCode` must match your repo name).

### 2. Implement the components

Each file in [`src/components/`](src/components/) describes its concept and the
exact requirement. Replace each `// TODO` (and the `return null`) so the tests
pass.

| File | Builds | Concept |
| --- | --- | --- |
| [`Counter.jsx`](src/components/Counter.jsx) | a +/- counter | `useState` + events |
| [`Toggle.jsx`](src/components/Toggle.jsx) | a show/hide message | conditional rendering |
| [`TodoList.jsx`](src/components/TodoList.jsx) | add items to a list | controlled input + lists |

Do not change file names or the `export default`s.

## Set up your repo

1. **Use this template -> Create a new repository**, owner **`HAU-6APSI`**.
2. Name it `m2a3-<classcode>-yourname`, **Private**.
3. Clone your copy and `npm install`.

```bash
git clone https://github.com/HAU-6APSI/m2a3-<classcode>-yourname.git
cd m2a3-<classcode>-yourname
npm install
```

## Running the app and the tests

```bash
npm run dev          # see it in the browser (http://localhost:5173)
npm test             # run the tests once (each passing test is a point)
npm run test:watch   # re-run on every save
```

> **Write your code in `src/` only.** The files in `test/` are how your work is
> graded.

## Submit

Pushing is submitting:

```bash
git add -A
git commit -m "✨ Activity 3 complete"
git push
```

Then open the **Actions** tab, open the latest **Autograde** run, and confirm
the green check, the "N / N tests passed" summary, and the linked screenshot of
your running app.

## 💻 Work in a Codespace (recommended)

A **Codespace** is a complete dev environment that runs in the cloud, so you do
not have to install Node, Dart, or anything else on your own laptop. This repo is
already configured: open a Codespace and everything you need is ready.

**Open one:** click the green **Code** button → **Codespaces** tab → **Create
codespace on main**. The first launch takes a minute to set up; after that it is
instant. Then run the activity from its terminal exactly as described below.

**Use it in VS Code (recommended).** It works in the browser, but it is nicer in
the desktop app: install the **GitHub Codespaces** extension in VS Code, or from
the running Codespace click the menu (☰) → **Open in VS Code Desktop**. Same
environment, your own editor.

### ⏱️ Make your free hours last (please read)
Your GitHub Education account includes a generous but limited monthly Codespaces
allowance. Three habits keep you from wasting it:

1. **Set your idle timeout to 10 minutes.** Go to
   **github.com/settings/codespaces → Default idle timeout → 10 minutes → Save.**
   A Codespace keeps running (and spending your hours) when you walk away; this
   makes it auto-stop after 10 idle minutes.
2. **Stop it when you finish - don't just close the tab.** Closing the browser
   leaves it running. Stop it at **github.com/codespaces → ••• → Stop
   codespace**, or from inside the editor open the **Command Palette**
   (`Ctrl`/`Cmd`+`Shift`+`P`, or **F1**) and run
   *Codespaces: Stop Current Codespace*.
3. **Delete the Codespace once you've submitted this activity.** Every activity
   gets its own Codespace, so old ones pile up and use your storage. After your
   final push: **github.com/codespaces → ••• → Delete.** You can always recreate
   it later from the green **Code** button.
