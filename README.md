# Emoji Picker for React & Next apps

![emoji-picker](https://github.com/user-attachments/assets/6bf78882-9bde-44bc-bc58-634611ef7552)

A simple and customizable emoji picker component for React and Next applications. This emoji picker is designed to be easy to integrate into your projects by simply copying two files.

## Features

- Easy to use and integrate
- Customizable styles
- Lightweight and no external dependencies aside from [react-icons](https://www.npmjs.com/package/react-icons)
- Works seamlessly in React and Next.js projects
- **Uses Tailwind CSS:** The EmojiPicker is styled using Tailwind CSS. You will need to pre-configure Tailwind in your project to achieve the same styling. Please refer to the [Tailwind CSS installation guide](https://tailwindcss.com/docs/installation) for more details.

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
