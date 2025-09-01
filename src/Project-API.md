Project API/SPI for project and worskpaces manipulation.

The API defines `Project` and `Workspace` interface. Most of modules will use these interfaces to watch the application lifecycle. The API therefore define the `WorkspaceListener` interface, which is essential for tracking workspace events. The `ProjectController` service manage the system.

The SPI notably defines how modules can interact more with the worspace lifecyle. See `WorkspacePersistenceProvider` for project saving/loading.

[Javadoc API](http://gephi.org/docs/api/org/gephi/project/api/package-summary.html)

[Javadoc SPI](http://gephi.org/docs/api/org/gephi/project/spi/package-summary.html)