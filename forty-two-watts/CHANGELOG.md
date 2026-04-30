# Changelog

## 0.56.2.1

- Add an "Open Web UI" button on the add-on dashboard (via `webui:`).
  A proper HA sidebar entry via Ingress will follow once the upstream web
  UI supports reverse-proxy base paths; for now, port 8080 is reached
  directly through the dashboard button.

## 0.56.2

- Match upstream `forty-two-watts` v0.56.2.

## 0.56.1

- Match upstream `forty-two-watts` v0.56.1.

## 0.1.0

- Initial community add-on packaging of forty-two-watts.
- Wraps `ghcr.io/frahlg/forty-two-watts:latest`, redirects config and
  state to Supervisor's `/data` volume.
- Web UI exposed on port 8080; first launch runs the setup wizard.
