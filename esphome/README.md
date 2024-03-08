# Gaggia Cortex ESPHome

## Build

- install esphome, or if you use Nix, run `nix develop`
- copy `secrets.example.yaml` to `secrets.yaml` and adjust accordingly
- create a new config like `gaggia-example.yaml`
- build it with `esphome compile gaggia-example.yaml`
- flash according to your config

## References

- https://esphome.io/guides/getting_started_command_line.html
