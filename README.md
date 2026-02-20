# role-quiz

Rôle Ansible pour déployer l'application **quiz-ansible** (Node.js).

## Plateformes supportées

- Ubuntu / Debian
- Rocky Linux / RedHat

## Variables

| Variable    | Défaut                                                  | Description               |
|-------------|---------------------------------------------------------|---------------------------|
| `quiz_repo` | `https://gitlab.com/ftutorials-labs/quiz-ansible.git`   | URL du dépôt Git          |
| `quiz_dest` | `/quiz-ansible`                                         | Répertoire d'installation |

## Exemple d'utilisation

```yaml
- hosts: all
  roles:
    - role-quiz
```
