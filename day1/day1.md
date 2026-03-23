# Day 1: Linux User Setup with Non-Interactive Shell

---

## English

Connected via SSH to a remote server and created a user with a non-interactive shell, preventing interactive logins.

```bash
ssh steve@stapp02
sudo useradd -s /sbin/nologin <username>
```

> `/sbin/nologin` blocks interactive logins while keeping the account active — typical for service accounts.

---

## Español

Me conecté por SSH a un servidor remoto y creé un usuario con shell no interactiva, impidiendo que pueda iniciar sesión.

```bash
ssh steve@stapp02
sudo useradd -s /sbin/nologin <username>
```

> `/sbin/nologin` bloquea el acceso interactivo manteniendo la cuenta activa — típico para cuentas de servicio.

---

## Português

Conectei via SSH a um servidor remoto e criei um usuário com shell não interativo, impedindo logins interativos.

```bash
ssh steve@stapp02
sudo useradd -s /sbin/nologin <username>
```

> `/sbin/nologin` bloqueia logins interativos mantendo a conta ativa — comum para contas de serviço.
