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
- Write the signup sign in create room endpoint
- Write the middleware that decode the token and gate the create room app
- Decode the token in the websocket server as well.Send the token to the websocket server in a query param for now 
- Initialize a new db package where you write the schema of the project
- Import the db package in http layer and start putting things in the DB