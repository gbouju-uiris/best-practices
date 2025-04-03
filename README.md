# Best Pratices - Git Commit

Outils pour aider sur les meilleures pratiques des conventionnels commit

## Pre-commit

[Pre-commit documentation](https://pre-commit.com/#install)

### Installation

Installation du package pre-commit

```bash
pipx install pre-commit
```

### Configuration

Configuration du package commitizen

1. créer un fichier nommé `.pre-commit-config.yaml`
2. Générer une configuration  basique en utilisant la commande

    ```bash
    pre-commit sample-config
    ```

3. Installez les scripts de hook git¶

    ```bash
    pre-commit install
    ```

4. Exécuter sur tous les fichiers

    ```bash
    pre-commit run -a
    ```

## Commitizen

[Commitizen documentation](https://commitizen-tools.github.io/commitizen/#installation)

### Installation

Installation du package commitizen

```bash
pipx install commitizen
```
