# React typescript buildup

_Some steps before starting a new application using typescript and React_

### 1. CRA
```
yarn create react-app my-app --template typescript
```

### 2. Copy config files from this package to my-app directory

### 3. Install eslint, prettier

```
yarn add eslint-config-airbnb eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks eslint-plugin-sonarjs prettier eslint@^6.6.0 @typescript-eslint/parser @typescript-eslint/eslint-plugin -D
```

### 4. Enzyme test (optional)

* #### 4.1 Remove default testing lib
```
yarn remove @testing-library/jest-dom @testing-library/react @testing-library/user-event
```
* #### 4.2 Copy setupTests.ts to src folder
* #### 4.3 Install enzyme and enzyme-adapter-react-16
```
yarn add enzyme enzyme-adapter-react-16 @types/enzyme-adapter-react-16 @types/enzyme -D
```
