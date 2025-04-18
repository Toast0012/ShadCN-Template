# ShadCN Template

### **⚠️ This branch shows the code after doing everything below**

Idk about you but I'm gonna be using external css rather than tailwind's inline 💀<br>(don't want my components to look messy)

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
