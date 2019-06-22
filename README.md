# lerna 연습

## 설치

```
$ npm i -g lerna
```

## 초기화

```
$ lerna init
```

## 구조

```
└── packages
    ├── alpha
    │   ├── index.js
    │   ├── node_modules
    │   └── package.json
    ├── beta
    │   ├── index.js
    │   ├── node_modules
    │   └── package.json
    └── usage
        ├── index.js
        ├── node_modules
        │   ├── alpha
        │   │   ├── index.js
        │   │   └── package.json
        │   └── beta
        │       ├── index.js
        │       └── package.json
        └── package.json
```
