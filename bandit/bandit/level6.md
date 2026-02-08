# Bandit – Level 6

## Objective
Find the password stored somewhere on the server.

## Key concepts
- File permissions
- Ownership
- Search constraints

## Commands used
```bash
find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
