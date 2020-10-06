# Sass Start!

## install Sass compiler
- node.js 설치 후`npm init -y` 입력 후 `npm i -D parcel-bundler`로 설치!

### 설치 완료 후 package.json 
```json
{
  "name": "soon9_funny_sass",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "parcel-bundler": "^1.12.4"
  }
}

```

- `npx parcel index.html` 명령어로 Sass 컴파일!
```
Server running at http://localhost:1234 
npm WARN soon9_funny_sass@1.0.0 No repository field.
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.13 (node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.13: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})
√  Built in 6.57s.
```
- 위 서버 주소로 접근하면 결과를 볼 수 있음.