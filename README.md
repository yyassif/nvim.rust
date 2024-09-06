## @yyassif's Nvim Configurations based on NvChad for Rust & Next.js development.

### Issues Encountered

In order to start the development for NextJS and NodeJS in general you'll need to install the following langauage servers `Typescript`, `Tailwind` & `Eslint` to not encounter any inssues in the future.

Go ahead an run the following npm command line.

```bash
sudo npm install -g typescript typescript-language-server tailwindcss-language-server vscode-langservers-extracted
```

Or, using yarn.

```bash
sudo yarn global add typescript typescript-language-server tailwindcss-language-server vscode-langservers-extracted
```

**This repo is supposed to used as config by NvChad users!**

- The main nvchad repo (NvChad/NvChad) is used as a plugin by this repo.
- So you just import its modules , like `require "nvchad.options" , require "nvchad.mappings"`
- So you can delete the .git from this repo ( when you clone it locally ) or fork it :)

# Credits

1) Lazyvim starter https://github.com/LazyVim/starter as nvchad's starter was inspired by Lazyvim's . It made a lot of things easier!

