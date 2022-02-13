

## Template Node + TS project

### requirements

  - node
  - git
  - yarn (optional)

- chore: init node project

      git init
      touch .gitignore

        - check .gitignore content

      yarn init
      npm init

- chore: add commit linter

      yarn add -D git-commit-msg-linter
      npm i -D git-commit-msg-linter

- chore: add typescript

      yarn add -D typescript @types/node ts-node-dev
      npm i -D typescript @types/node ts-node-dev

      yarn tsc --init --outDir dist --target es2020
      npx tsc --init --outdir dist --target es2020

      - check tsconfig.json content
