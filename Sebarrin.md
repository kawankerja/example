# Sebarr.in - Template 3
Template 3 merupakan sebuah tema undangan online untuk kebutuhan bisnis sebarr.in.

## Tech Stack
- TailwindCSS CLI (npx)
- Font: Luxurious Script
- JQuery CDN

## Structure Folder
```
├── assets/
│   ├── img/
│   └── js/
│       └── index.js
├── dist/
│   └── output.css
├── src/
│   └── input.css
├── .gitignore
├── README.md
├── index.html
├── invitation.html
├── package-lock.json
├── package.json
└── tailwind.config.js
```

## Build
### Generate Output CSS from Source
Cara generate css dari src ke dist dengan perintah:

```bash
npx tailwindcss -i ./src/input.css -o ./dist/output.css 
```

File dari `src/input.css` akan di generate ke `dist/output.css`.

## Deployment
### How to Deploy on Vercel
- Add new Project.
- Select repository git.
- Framework Preset: `Others`.
- Root Directory: `./`.
- Deploy.

## Contributing 
- [Kawan Kerja](https://github.com/kawankerja)
