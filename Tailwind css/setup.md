## How to set up Tailwind CSS

1) Run the following Command :-
```
npm install -D tailwindcss
npx tailwindcss init
```

2) Update tailwind.config.js file to include this line:-
```
content:["*.html"]
```

3) Create src/input.css to include:-
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

4) Include the src/output.css file to your html

5) Run the following Command :-
```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```