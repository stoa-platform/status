# STOA Platform Status

> Public status page for [STOA Platform](https://gostoa.dev) — the European Agent Gateway.

**Live**: [status.gostoa.dev](https://status.gostoa.dev)

## Monitored Services

| Service           | Endpoint                           | Criticality |
| ----------------- | ---------------------------------- | ----------- |
| API Gateway       | `mcp.gostoa.dev/health`            | Critical    |
| Control Plane API | `api.gostoa.dev/health/live`       | Critical    |
| Console           | `console.gostoa.dev`               | High        |
| Developer Portal  | `portal.gostoa.dev`                | High        |
| Authentication    | `auth.gostoa.dev` (OIDC discovery) | Critical    |
| Documentation     | `docs.gostoa.dev`                  | Low         |
| Landing Page      | `gostoa.dev`                       | Low         |

## How It Works

- Powered by [Upptime](https://upptime.js.org) (MIT License)
- GitHub Actions checks every 5 minutes
- Hosted on GitHub Pages
- Incident history tracked via GitHub Issues
- Zero server cost, fully GitOps

## Disclaimer

Uptime figures displayed on this page are **observed metrics**, not contractual SLA commitments.
STOA Platform provides technical capabilities that support regulatory compliance efforts (NIS2, DORA).
This does not constitute a service level agreement.

## License

MIT — see [LICENSE](LICENSE).
