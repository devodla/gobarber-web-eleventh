# gobarber-web-eleventh
{
  "name": "06-gobarber-web",
  "version": "0.1.0",
  "private": true,
  "dependencies": {
    "@testing-library/jest-dom": "^4.2.4",
    "@testing-library/react": "^9.3.2",
    "@testing-library/user-event": "^7.1.2",
    "@types/jest": "^24.0.0",
    "@types/node": "^12.0.0",
    "@types/react": "^16.9.0",
    "@types/react-dom": "^16.9.0",
    "@unform/core": "^2.1.0",
    "@unform/web": "^2.1.0",
    "axios": "^0.21.2",
    "date-fns": "^2.15.0",
    "polished": "^3.6.5",
    "react": "^16.13.1",
    "react-day-picker": "^7.4.8",
    "react-dom": "^16.13.1",
    "react-icons": "^3.10.0",
    "react-router-dom": "^5.2.0",
    "react-scripts": "3.4.0",
    "react-spring": "^8.0.27",
    "styled-components": "^5.1.1",
    "typescript": "~3.7.2",
    "uuidv4": "^6.1.0",
    "yup": "^0.29.1"
  },
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "test:coverage": "react-scripts test --coverage --watchAll false",
    "eject": "react-scripts eject"
  },
  "jest": {
    "collectCoverageFrom": [
      "src/pages/**/*.tsx",
      "src/components/**/*.tsx",
      "src/hooks/*.tsx",
      "!src/hooks/index.tsx"
    ]
  },
  "browserslist": {
    "production": [
      ">0.2%",
      "not dead",
      "not op_mini all"
    ],
    "development": [
      "last 1 chrome version",
      "last 1 firefox version",
      "last 1 safari version"
    ]
  },
  "devDependencies": {
    "@commitlint/cli": "^9.1.1",
    "@commitlint/config-conventional": "^9.1.1",
    "@testing-library/react-hooks": "^3.4.1",
    "@types/react-router-dom": "^5.1.5",
    "@types/styled-components": "^5.1.0",
    "@types/yup": "^0.29.3",
    "@typescript-eslint/eslint-plugin": "^3.2.0",
    "@typescript-eslint/parser": "^3.2.0",
    "axios-mock-adapter": "^1.18.2",
    "cz-conventional-changelog": "3.2.0",
    "eslint": "6.8.0",
    "eslint-config-airbnb": "^18.1.0",
    "eslint-config-prettier": "^6.11.0",
    "eslint-import-resolver-typescript": "^2.0.0",
    "eslint-plugin-import": "^2.20.1",
    "eslint-plugin-jsx-a11y": "^6.2.3",
    "eslint-plugin-prettier": "^3.1.3",
    "eslint-plugin-react": "^7.19.0",
    "eslint-plugin-react-hooks": "^2.5.0",
    "husky": "^4.2.5",
    "prettier": "^2.0.5",
    "react-test-renderer": "^16.13.1"
  },
  "husky": {
    "hooks": {
      "prepare-commit-msg": "exec < /dev/tty && git cz --hook || true",
      "commit-msg": "commitlint -E HUSKY_GIT_PARAMS"
    }
  },
  "config": {
    "commitizen": {
      "path": "./node_modules/cz-conventional-changelog"
    }
  }
}
