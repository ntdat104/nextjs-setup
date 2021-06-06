# Setup

> Yarn, Nextjs, Typescript, Prettier, Eslint, SCSS, Redux, React-redux, Redux-thunk, Redux-dev-tools, axios...

---

## 1. Một số câu lệnh của yarn

- Cài đặt yarn global
  - `npm install -g yarn`
- Cập nhật phiên bản mới nhất
  - `yarn set version latest`
- Truy cập danh sách các lệnh
  - `yarn help`
- Khởi tạo một project
  - `yarn init`
- Cài đặt tự động các thư viện
  - `yarn`
  - `yarn install`
- Cài đặt một thư viện
  - `yarn add [package]`
  - `yarn add [package]@[version]`
  - `yarn add [package]@[tag]`
  - `yarn add --dev [package]` # _dev dependencies_
  - `yarn add --peer [package]` # _peer dependencies_
- Cập nhật một thư viện
  - `yarn up [package]`
  - `yarn up [package]@[version]`
  - `yarn up [package]@[tag]`
- Xóa một thư viện
  - `yarn remove [package]`
- Chạy yarn CLI trong một thư mục cụ thể
  - `yarn packages/my-new-lib init`

---

## 2. Cài đặt typescript + các gói hỗ trợ typescript

- `echo {}> tsconfig.json`
- `npm install --save-dev typescript @types/react @types/node`
- `yarn add --dev typescript @types/react @types/node`

---

## 3. Cài đặt prettier

- `yarn add --dev prettier`
- `echo {}> .prettierrc.json`
- `"prettier": "npx prettier --config .prettierrc.json --write \"pages/**/*.{tsx,ts}\""`

```js
{
    "bracketSpacing": true,
    "jsxSingleQuote": true,
    "semi": true,
    "singleQuote": true,
    "trailingComma": "none",
    "tabWidth": 2,
    "printWidth": 120
}
```

---

## 4. Cài đặt redux, react-redux, redux-thunk, redux-devtools-extension

- `yarn add redux react-redux redux-thunk`
- `yarn add --dev redux-devtools-extension`

## 5. Cài đặt axios

- `yarn add axios`

## 6. Cài đặt node-sass

- `yarn add --dev node-sass@4.14.1`
