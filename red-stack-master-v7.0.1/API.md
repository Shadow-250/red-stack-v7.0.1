RED-Stack Modules
---

RED-Stack provides a set of node modules that implement different parts of the
application.

Module | Description
-------|-------
[red-stack](red-stack) | the main module that pulls together all of the internal modules and provides the executable version of RED-Stack
[@red-stack/editor-api](@red-stack_editor-api) | an Express application that serves the RED-Stack editor and provides the Admin HTTP API
[@red-stack/runtime](@red-stack_runtime) | the core runtime of RED-Stack
[@red-stack/util](@red-stack_util) | common utilities for the RED-Stack runtime and editor modules
[@red-stack/registry](@red-stack_registry) | the internal node registry
[@red-stack/nodes](@red-stack_nodes) | the default set of core nodes
[@red-stack/editor-client](@red-stack_editor-client) | the client-side resources of the RED-Stack editor application
