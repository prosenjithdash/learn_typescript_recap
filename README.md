# 🚀 Learn TypeScript Recap

This repository contains my TypeScript recap journey.  
I am revising TypeScript step by step to build a strong foundation for React, Next.js, and Fullstack development.

---

## 📚 Module 1: Write Your First TypeScript Program

### 🎯 Goal
- Set up a TypeScript project
- Compile TypeScript (.ts) into JavaScript (.js)
- Configure TypeScript using tsconfig.json

---

## 📁 Project Structure
learn_typescript_recap/
│
├── module1/
│ └── src/
│ └── index.ts
│
├── dist/
├── tsconfig.json

## 🛠️ Step 1: Create TypeScript File

Path: module1/src/index.ts

```ts
const message: string = "Hello TypeScript 🚀";
console.log(message);

⚙️ Step 2: Compile TypeScript to JavaScript
code: tsc ./module1/src/index.ts
This converts the TypeScript file into JavaScript.


🧠 Step 3: Initialize TypeScript Configuration
Create tsconfig.json file: tsc --init

🔧 Step 4: Configure tsconfig.json
Update compilerOptions:{
  "compilerOptions": {
    "rootDir": "./module1/src",
    "outDir": "./dist",
    "strict": true
  }
}

Explanation:

rootDir → Source TypeScript folder

outDir → Compiled JavaScript output folder

strict → Enable strict type checking


▶️ Run Compiled File

After compilation:

node dist/index.js


-------------------------------------
💡 What I Learned from this part:

Create TypeScript file

Convert .ts to .js using tsc

Initialize tsconfig.json

Configure rootDir and outDir

Understand basic TypeScript setup

-------------------------------------