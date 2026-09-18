# 🐳 Docker Templates

A personal collection of Docker Compose templates for self-hosted services I run and maintain.

## 📦 Containers

| Container Name  | Description                              | Port(s)             |
|------------------|-------------------------------------------|----------------------|
| **NPM**          | Nginx Proxy Manager — reverse proxy & SSL | `80`, `443`, `81` (Admin UI) |
| **Dockhand**     | Docker container management UI            | `5500`               |
| **Immich**       | Self-hosted photo & video backup          | `5501`               |
| **PingvinShareX**| File sharing platform                     | `5502`               |
| **StirlingPDF**  | PDF manipulation toolkit                  | `5503`               |
| **Degoog**       | Privacy-focused Google service alternative| `5504`               |

## 🚀 Usage

1. Clone this repo:
   ```bash
   git clone https://github.com/Krak8/containers.git
   cd containers
   ```
2. Pick the service folder you need and review its `docker-compose.yml`.
3. Update environment variables, volumes, and ports as needed.
4. Spin it up:
   ```bash
   docker compose up -d
   ```

## 🗂️ Repo Structure

```
containers/
├── npm/
├── dockhand/
├── immich/
├── pingvinShareX/
├── stirlingPDF/
├── degoog/
└── README.md
```

## ⚠️ Notes

- Ports listed are defaults — adjust them if they conflict with other services on your host.
- Make sure to set strong credentials and secrets before exposing any of these publicly.
- Recommended to run these behind **NPM** (Nginx Proxy Manager) with SSL enabled.

## 🔗 Links

- 💻 GitHub: [Krak8](https://github.com/Krak8/)
- 🌐 My socials & links: [me.krak8.top](https://me.krak8.top)

---

*Feel free to fork, adapt, and use these templates for your own setup.*
