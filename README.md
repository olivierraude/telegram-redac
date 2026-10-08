# Telegram Rédac

Mini-application de gestion éditoriale (articles, rubriques, rôles journaliste / éditeur),
réalisée pour approfondir Symfony et son écosystème.

## Stack
Symfony 8 · PHP 8.5 · FrankenPHP · Docker (OrbStack) · Doctrine · GitLab CI

## Lancer le projet
```bash
docker compose build --pull
docker compose up --wait
```
Puis ouvrir https://localhost

## Notes techniques
- Basé sur le template [symfony-docker](https://github.com/dunglas/symfony-docker).
- Mercure adapté pour Mercure ≥ 1.0.3 : hub nommé, `protocol_version_compatibility 8`,
  directive `demo` retirée (voir `frankenphp/Caddyfile`).