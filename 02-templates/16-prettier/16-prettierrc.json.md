# Prettier (JSON Configuration)

```json
{
  "arrowParens": "avoid",
  "bracketSpacing": true,
  "endOfLine": "lf",
  "printWidth": 80,
  "semi": false,
  "singleQuote": true,
  "tabWidth": 2,
  "trailingComma": "none",
  "plugins": ["@ianvs/prettier-plugin-sort-imports"],
  "importOrder": [
    "^react$",
    "<BUILTIN_MODULES>",
    "<THIRD_PARTY_MODULES>",
    "^types$",
    "^@types",
    "^@[a-zA-Z0-9-]+/",
    "^@/.*$",
    "^\\w+/",
    "^\\.\\.?.*$",
    "\\.css$"
  ]
}
```

Related Reference:

- Prettier vs. Linters [16-prettier.md](/01-references/16-prettier.md)
- Prettier (YAML or YML Configuration)
  [16-prettierrc.yaml.md](./16-prettierrc.yaml.md)
- Prettier (TypeScript Configuration)
  [16-prettier.config.ts.md](16-prettier.config.ts.md)
