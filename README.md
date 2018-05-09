## Generate JSON Schemas

![DemoGif](https://i.gyazo.com/519743fee1ed90371e71dd66767b3a0b.gif)

1. Install dependency
```
npm i
```

2. Paste your JSON response object in `input.json`
3. Run npm script to generate schema
```
npm run gen
```
4. Your schema was generated in `schemas/output.json`

### NOTE
I made this project just to improve the workflow for converting multiple responses. The actual conversion logic and heavy lifting happens within this npm package: [json-schema-generator](https://www.npmjs.com/package/json-schema-generator). All credit to [these guys](https://github.com/krg7880/json-schema-generator/graphs/contributors).
