# Traefik Config
The traefik.toml.example contains the necessary configuration to monitor docker for new containers.

The default port for Traefik's backend is 7080. The username and password combo is admin/admin. I **STRONGLY** suggest changing it. You can generate a new password using the htpasswd utility like so:

```bash
htpasswd -nb admin password
admin:$apr1$Sa.SXDjc$o3IgWm50.gF1cXgoPOtVF.
```

Copy the file, update the password and copy it to traefik.toml
