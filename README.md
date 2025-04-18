# ShadCN Template

I made this so I won't waste time creating new projects. Follow the steps below to get your repo ready.

1. **Add the Dependencies:**<br>
   ```bash
   npm install
   ```
2. **Add ShadCN:**<br>
   ```bash
   npx shadcn@latest init
   ```
3. **Add your needed components:**<br>

   ```bash
   npx shadcn@latest add [component]
   ```

   and

   ```javascript
   import { Component } from "@/components/ui/[component]";

   function App() {
     return (
       <div>
         <Component></Component>
       </div>
     );
   }
   ```

4. **Run your server:**<br>
   ```bash
   npm run dev
   ```
