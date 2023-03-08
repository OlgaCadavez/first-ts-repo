# Passos para replicar este projeto

## 1. Setup Node.js package.json
npm init -y

## 2. Initialize a npm package
npm install typescript --save-dev

## 3. Install ambient Node.js types for TypeScript
npm install @types/node --save-dev

## 4. Configure TypeScript
npx tsc --init --rootDir src --outDir build --esModuleInterop --resolveJsonModule --lib es6 --module commonjs --allowJs true --noImplicitAny true

## 5. Create a Simple TypeScript Hello World App
Create the src/app.ts file and type:

console.log("Ola mundo");

## 6. Compile the typescript files
Open the VS Code Terminal or Command-line and type:

npx tsc

## 7. Execute the Application
Inside the Terminal or Command-line type:

node build/app.js

