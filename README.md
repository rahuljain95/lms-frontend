# LMS Frontend

### Setup Instruction

1.

```
git clone https://github.com/rahuljain95/LMS-Frontend.git
```

2. Move into the directory

```
cd lms-frontend-hn
```

3. install dependencies

```
npm i
```

4. run the server

```
npm run dev
```

### Setup instructions for tailwind

[Tailwind official instruction doc](https://tailwindcss.com/docs/installation)

1. Install tailwindcss

```
npm install -D tailwindcss
```

2. Create tailwind config file

```
npx tailwindcss init
```

3. Add file extensions to tailwind config file in the contents property

```
"./src/**/*.{html,js,jsx,ts,tsx}"
```

4. Add the tailwind directives at the top of the `index.css` file

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### Adding plugins and dependencies

```
 npm install @reduxjs/toolkit react-router-dom react-icons react-chartjs-2 chart.js daisyui axios react-hot-toast @tailwindcss/line-clamp
```

### configure auto import sort eslint

1. Install simple import sort

```
npm i -D eslint-plugin-simple-import-sort
```

2. Add rule in `eslint.cjs`

```
'simple-import-sort/imports': 'error'
```

3. Add simple-import-sort plugin in `.eslint.cjs`

```
plugins: [..., 'simple-import-sort']
```

4. To enable auto import sort on file save in vscode

-Open `settings.json`
-add the following config

```
"editor.codeActionsOnSave" : {
    "source.fixAll.eslint": true
}
```

