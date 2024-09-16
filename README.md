# notes-assistant
The project should be a mono repo using bun as the package manager.

the packages in the workspace should be at the root of the repo, not a packages directory.

one package is api which is a honojs backend api with a healthcheck endpoint to start which just returns a 200.

the other package should be a react native app built with expo

the expo app will use over the air updates from expo and eas for building.