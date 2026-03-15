# Install

## Requirements

- Node.js
- Git

## Steps to Install

1. Clone the repository:
    ```bash
git clone https://github.com/gaumondp/superpowers-kiro.git
```

2. Navigate to the project folder:
    ```bash
cd superpowers-kiro
```

3. Install the dependencies:
    ```bash
npm install
```

4. Run the application:
    ```bash
npm start
```

## Manual Installation (Kiro Skills Setup)

⚠️ **Important**: This section should NOT be removed. Follow these steps if you need to manually install Kiro skills.

1. Clone Superpowers:
    ```bash
git clone https://github.com/obra/superpowers.git ~/.kiro/superpowers
```

2. Copy each skill into Kiro's skills directory:
    ```bash
mkdir -p ~/.kiro/skills
for skill in ~/.kiro/superpowers/skills/*/; do
  cp -R "$skill" ~/.kiro/skills/"$(basename "$skill")"
done
```

3. Restart Kiro from the installation

## Additional Resources

For more information, please refer to:
- The [documentation](https://github.com/gaumondp/superpowers-kiro/docs) for further setup instructions.
- The [issue tracker](https://github.com/gaumondp/superpowers-kiro/issues) for bug reports and feature requests.