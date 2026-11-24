# vexlo-test

Minimal Node.js hello-world app to test Vexlo Cloud's "Deploy from Public Git URL" flow.

- `server.js` listens on `$PORT` (default 3000) and answers `Hello from Vexlo test`.
- `Dockerfile` builds it with Node 20.
- No dependencies, no database — just proving the Git-based deploy path works.
