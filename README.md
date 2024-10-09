# Emoji Picker for React & Next apps

A simple and customizable emoji picker component for React and Next applications. This emoji picker is designed to be easy to integrate into your projects by simply copying two files.

## Features

- Easy to use and integrate
- Customizable styles
- Lightweight and no external dependencies aside from [react-icons](https://www.npmjs.com/package/react-icons)
- Works seamlessly in React and Next.js projects

## Getting Started

### 1. Install Dependencies

Before using the emoji picker, you need to install [react-icons](https://www.npmjs.com/package/react-icons) in your project. Run the following command:

```bash
npm install react-icons
```

### 2. Copy Files

To use the emoji picker, simply copy the following two files into your project:

- [`EmojiPicker.tsx`](./EmojiPicker.tsx)
- [`emojies.ts`](./emojies.ts)

Place the [`EmojiPicker.tsx`](./EmojiPicker.tsx) file in your desired directory, such as `components/` or `src/`. The [`emojies.ts`](./emojies.ts) file contains a list of emojies and should be placed under `constants/` or `data/`

### 3. Import the Component

In your React or Next.js component, import the EmojiPicker:

```typescript
import EmojiPicker from "./path/to/EmojiPicker";
```
