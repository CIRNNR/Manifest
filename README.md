## Manitfest

This project has a goal to build a CI/CD tool.

the project is composed from 3 parts:
- [Frontend](https://github.com/CIRNNR/ci_web)
- [Runner](https://github.com/CIRNNR/ci_runner)
- [Orchestrator](https://github.com/CIRNNR/CI_Orch)

Orchestrator will communicate with the frontend and also with runners, for the communication between the Orchestrator and the Frontend it will be with GraphQl and the for the one between Runner and Orchestrator it will be in Grpc.
