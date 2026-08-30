# Story Weaver Plus

Clone this GitHub project and make it working here

https://github.com/rns420/tale-weaver-pro.git

Remaining



src/lib/useStoryWriter.ts — still dispatches 4 chunks and treats only status !== "done" as pending, so it will loop on skipped chapters. It needs: 12-wide batches, pending = status === "pending", a no-progress guard, and surfacing skipped chapters.

src/lib/stories.functions.ts — the keyIndex validator is capped at max(3); it must accept 0–11.

A typecheck plus one real end-to-end story run to confirm speed and that nothing stalls.



use this https://paraloncloud.com api key for ai:-

make sure paraloncloud api key is with 0 credits so in any condition use only free model Qwen 3.8 27B. make sure use this free model. (free limit 60 request/min). 



api key 1



prlc_9dec184306d8d0dbb7d12c98d6dc22ce35d5ac3feaf2ccb9



Paraloncloud api key 2

prlc_667ae9e467f065c6202fc7e12f07f575a8111b7ad906dd73

Paraloncloud api key 3



prlc_99b14331acd49b119237bef2ecc2e1078ecdd0f3be8a83d7



Paraloncloud api key 4

prlc_a16ea589738ffd489a8c2bb8550facce032e2263922de645



Must use all api keys in parallel to speed up writing process while managing consitancy of story.

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://fast-narrate.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/c579b4da-f5ec-41be-ac0a-7b31ab2571ec).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
