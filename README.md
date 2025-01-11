### Steps performed 

- Initialized empty turborepo
- Deleted docs app
- Added http-server, ws-server
- Added package.json in both places
- Added tsconfig.json in both places and imported it from @repo/typescript-config/base.json
- Added @repo/typescript-config as a dependency in both ws-backend and http-backend
- Added a build,dev and start script to both the projects
- Update the turbo-config in both projects
- Initialize a http-server initialize a websocket server