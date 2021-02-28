# React Suite Styles

React Suite styles compiler for eases style base customization.

## Structure 📋

```bash
├── README.md
├── LICENCE.md
├── CHANGELOG.md
├── src/
│   ├── components/ # custom variables and components
│   ├── fonts/ # Catamaran font
│   ├── themes/
│   │   ├── dark.less
│   │   └── lights.less
│   ├── dark.less
│   └── light.less # default stylesheet
├── package.json
└── .stylelintrc.json
```

## How To Use 💡

Import stylesheet as usual from package.

```javascript
import '@calvear/rsuite-styles';
import { Button } from 'rsuite';

export default function App()
{
    return (
        <page>
            <h1>Welcome to my App</h1>
            <Button appearance="primary">Press Me</Button>
        </page>
    );
}
```

For dark theme.

```javascript
import '@calvear/rsuite-styles/dist/dark.less';
import { Button } from 'rsuite';

export default function App()
{
    return (
        <page>
            <h1>Welcome to my App</h1>
            <Button appearance="primary">Press Me Dark</Button>
        </page>
    );
}
```

## Linting 🧿

Project uses ESLint, for code formatting and code styling normalizing.

- **stylelint**: CSS, SASS and LESS styles linter.

## Changelog 📄

For last changes see [CHANGELOG.md](CHANGELOG.md) file for details.

## Built with 🛠️

- [React Suite](https://rsuitejs.com/) - marvelous UI framework for React.

## License 📄

This project is licensed under the MIT License - see [LICENSE.md](LICENSE.md) file for details.

---

⌨ by [Alvear Candia, Cristopher Alejandro](https://github.com/calvear93)
