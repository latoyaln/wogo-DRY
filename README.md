# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/main/packages/create-svelte).



## Componenten design review

### Seijno design: 
[componenten (mobile menu)](https://www.figma.com/design/arBbWMslQCrT2dlf7A9PSj/WOGO?node-id=1-2&node-type=canvas&t=tKON8y3LLFThHrG7-0) </br>
<img width="454" alt="Scherm­afbeelding 2024-11-15 om 14 07 28" src="https://github.com/user-attachments/assets/d9938016-ba12-4d55-b033-a258df2a0a5c">

### Anna-Kyra design: 
[footer component](https://www.figma.com/community/file/1000026521402926606/style-guide-ui-kit) 
> Meer uitleg in [project board](https://github.com/users/latoyaln/projects/7?pane=issue&itemId=86768897&issue=latoyaln%7Cwogo-DRY%7C1) 
> Heb voor de 1e versie gekozen </br>
<img width="701" alt="Scherm­afbeelding 2024-11-14 om 15 55 04" src="https://github.com/user-attachments/assets/ca3fea4e-e28e-4655-995e-2e6661c753f0">

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build

```

You can preview the production build with `npm run preview`.



> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
