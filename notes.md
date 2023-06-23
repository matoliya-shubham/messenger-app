Blocker: To see suggetion of tailwind css classes cmd+shift+p and setting.json paste
"editor.quickSuggestions": {
"strings": true
}
initial screen should show authentication page
(site) folder will be equivalent to index.js
in Atuhform component we 'use client' is written to indicate next js that it is client component hence dont use serverside methods in it
\*\* rsc for stateless functional component extention:Reactjs code snippets
import Input from "@/app/components/inputs/input" this type of import is due to we install alias while installing nextjs
for forms npm i @tailwindcss/forms and in tailwind.config file in plugins paste this
plugins: [
require("@tailwindcss/forms")({
strategy: "class",
}),
],
with clsx we can write dynamic classes either in backticks or dbl quotes and dynamic classes are provided by strategy: "class" which we imported in tailwindcss.config file
In mongodb connection url 3 things should be take care of username, password and database name at the end
\*\* after creating modals in prisma run "npx prisma db push"
npm install next-auth@latest @prisma/client @next-auth/prisma-adapter bcrypt
npm i -D @types/bcrypt
