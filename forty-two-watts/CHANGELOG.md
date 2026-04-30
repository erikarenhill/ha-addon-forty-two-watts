# Changelog

## 0.56.2

- Match upstream `forty-two-watts` v0.56.2.
- Add Home Assistant Ingress support so the forty-two-watts web UI appears
  as "42 Watts" in the HA sidebar.

## 0.56.1

- Match upstream `forty-two-watts` v0.56.1.

## 0.1.0

- Initial community add-on packaging of forty-two-watts.
- Wraps `ghcr.io/frahlg/forty-two-watts:latest`, redirects config and
  state to Supervisor's `/data` volume.
- Web UI exposed on port 8080; first launch runs the setup wizard.
