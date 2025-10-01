# sh25-intro-react-convex

1. npm create vite@latest


Installing Convex
https://docs.convex.dev/quickstart/react
https://docs.convex.dev/functions/mutation-functions

1. Ensure terminal in current root of folder 
   1. cd sh25-intro-react-convex
2. npm install convex
3. npx convex dev
4. add guestbookData.jsonl
5. npx convex import --table guestbook guestbookData.jsonl
6. add convex/schema.ts
7. add convex/tasks.ts
8. Connect backend in src/main.tsx
9. Display data in src/components/GuestbookSection.tsx