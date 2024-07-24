Hexagonal Arch in go
https://www.youtube.com/watch?v=MpFog2kZsHk&list=WL&t=408s

There are 3 primary layers: Domain, Application, Framework.
Domain layer is innermost and framework is outermost.

Then there are driving adapters and driven adapters.

Adapters are like plugs, which can be fitted in ports.

Domain layer is the core and contains business logic.
App layer orchestrates domain layer and bridges between doamin and framework layer.
Framework layer provides logic for the adapters to talk to app layer.

These layers are loosely coupled and talks with each other using ports and adpaters.

All the dependencies are inward i.e. outside layer depends upon inside layer and not the other way.
Domain layer cannot depend upon app layer for anything and app layer cannot depend upon framework layer for anything.
