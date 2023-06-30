`plepis_new.ts` 🦋
-

```ts
/** @type {import('utils').User} */
export const me = {
  name: "Ansis",
  from: "Latvia",
  livesIn: "Sweden",
  hobbies: [
    "Mathematics",
    "Theoretical Physics",
    "Web Development",
    "Speedcubing",
  ],
  workingOn: {
    name: "Pogulum",
    repo: "https://github.com/plepisnew/pogulum_next",
    url: "https://pogulum-next.vercel.app",
  },
  mood: () => Math.random() > 0.15 ? "good" : "mid",
};
```
