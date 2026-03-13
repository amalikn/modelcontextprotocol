# Model Context Protocol (MCP)

_Just heard of MCP and not sure where to start? Check out our [documentation website](https://modelcontextprotocol.io)._

This repo contains the:

- MCP specification
- MCP protocol schema
- Official MCP documentation

The schema is [defined in TypeScript](schema/2025-11-25/schema.ts) first, but
[made available as JSON Schema](schema/2025-11-25/schema.json) as well, for wider
compatibility.

The official MCP documentation is built using Mintlify and available at
[modelcontextprotocol.io](https://modelcontextprotocol.io).

## Authors

The Model Context Protocol was created by David Soria Parra ([@dsp](https://github.com/dsp)) and Justin Spahr-Summers ([@jspahrsummers](https://github.com/jspahrsummers)).

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Local Customization Tracking
- Local machine-specific integration, client wiring, and operational state are tracked under the external data root.
- Local metadata path: `/Volumes/Data/_ai/_mcp/mcp-data/<name>/meta`
- Repo-side capability contract is in `docs/local-capability/`.
- Secrets are never stored in repo docs; only variable names and loading locations are documented.

## Local Enhancements Capture (2026-03-13)
- Captured current local changes, configuration updates, and operational enhancements for GitHub publication.
- Includes synchronization with sub-repo link updates where applicable.
- Cross-reference local docs and capability notes added in this repository.
