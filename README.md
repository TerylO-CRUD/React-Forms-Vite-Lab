# Shopping List App
A simple React app for keeping a shopping list. You can search for items, filter them by category, and add new items.

## Functionality

 **Search:** The list updates as you type in the search box.
- **Filter:** Choose a category (Produce, Dairy or Dessert) to see only those items.
- **Add an item:** Type a name, pick a category and click "Add to List". The new item shows up in the list.

## Controlled Form

The search box and the new item form are controlled components. This means React keeps the value of each input in state.

- When you type, the state updates.
- The input always shows the value stored in state.
- When the form is submitted, `preventDefault()` stops the page from reloading.
- The form creates a new item `{ id, name, category }` and sends it to `App`.
- `App` adds the new item to the list.

## Setup

```bash
npm install
npm run dev
```

Then open the link shown in the terminal (for example http://localhost:5173).

## Running the Tests

```bash
npm test
```