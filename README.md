# docker-cloudflared-arm-build

Use Docker to make a cloudflared arm build. This is useful for the non-64bit
Raspberry Pi.

## How to use

Clone this repo and then use one of the options below.

```sh
# Build the latest available version
./build

# Build a specific version
./build <version/git-tag>
```

After a successful build, you should have your compiled `cloudflared` binary in
the root directory. Just copy this over to its destination (e.g., use `scp`).

## Other

After following this [Pi-hole guide][pi-hole-doh], some useful scripts to copy
over are available in the `scripts` directory.

<!-- Referes -->
[pi-hole-doh]: https://docs.pi-hole.net/guides/dns/cloudflared/
