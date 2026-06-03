# Changelog

## 0.112.0

- Match upstream `forty-two-watts` v0.112.0.

## 0.110.0

- Match upstream `forty-two-watts` v0.110.0.

## 0.109.0

- Match upstream `forty-two-watts` v0.109.0.

## 0.106.0

- Match upstream `forty-two-watts` v0.106.0.

## 0.102.3

- Match upstream `forty-two-watts` v0.102.3.

## 0.90.1

- Match upstream `forty-two-watts` v0.90.1.

## 0.81.2

- Match upstream `forty-two-watts` v0.81.2.

## 0.80.4

- Match upstream `forty-two-watts` v0.80.4.

## 0.79.0

- Match upstream `forty-two-watts` v0.79.0.

## 0.78.1

- Match upstream `forty-two-watts` v0.78.1.

## 0.75.1

- Match upstream `forty-two-watts` v0.75.1.

## 0.74.0

- Match upstream `forty-two-watts` v0.74.0.

## 0.73.0

- Match upstream `forty-two-watts` v0.73.0.

## 0.71.0

- Match upstream `forty-two-watts` v0.71.0.

## 0.70.0

- Match upstream `forty-two-watts` v0.70.0.

## 0.69.5

- Match upstream `forty-two-watts` v0.69.5.

## 0.69.4

- Match upstream `forty-two-watts` v0.69.4.

## 0.69.1

- Match upstream `forty-two-watts` v0.69.1.

## 0.68.1

- Match upstream `forty-two-watts` v0.68.1.

## 0.65.0

- Match upstream `forty-two-watts` v0.65.0.
- Adds `solaredge_legacy.lua` driver for SolarEdge K-series display
  inverters.

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
