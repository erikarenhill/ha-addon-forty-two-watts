# Changelog

## 0.64.0

- Match upstream `forty-two-watts` v0.64.0.
- Includes upstream changes through v0.57.x–v0.64.0: web UI enhancements
  (energy flow, price charts), hot-reload HA bridge with restart-required
  dialog, MPC `pv_limit_w` wired into per-driver curtail dispatch, fuse-blow
  signature via `concurrent_drivers_offline`, plus the v0.62.x bug fixes
  (negative-spot export revenue, MQTT cache invalidation, MQTT connect
  shutdown race).

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
