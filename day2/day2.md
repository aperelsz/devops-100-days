# Day 2: Linux User with Expiry Date

---

## English

Created a temporary user with an expiry date on a remote server, connected via SSH.

```bash
sudo useradd -m -e 2027-03-28 mark

# Validate
sudo chage -l mark
```

> `-m` creates the home directory. `-e` sets the account expiry date (YYYY-MM-DD format). `chage -l` displays the password and account aging information.

---

## Español

Creé un usuario temporal con fecha de expiración en un servidor remoto, conectándome por SSH.

```bash
sudo useradd -m -e 2027-03-28 mark

# Validar
sudo chage -l mark
```

> `-m` crea el directorio home. `-e` establece la fecha de expiración de la cuenta (formato YYYY-MM-DD). `chage -l` muestra la información de expiración de la cuenta.

---

## Português

Criei um usuário temporário com data de expiração em um servidor remoto, conectando via SSH.

```bash
sudo useradd -m -e 2027-03-28 mark

# Validar
sudo chage -l mark
```

> `-m` cria o diretório home. `-e` define a data de expiração da conta (formato YYYY-MM-DD). `chage -l` exibe as informações de expiração da conta.
