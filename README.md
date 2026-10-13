<div align="center">

# Advanced Web Tools </br>
Tools for building, extending, and maintaining web applications. </br>
PHP Framework · Application packages · CMS · Developer tools
Explore repositories · Documentation
</div>

About the organization
Advanced Web Tools (AWT) develops a connected ecosystem of web development projects: an application runtime, reusable packages, content management tools, rendering infrastructure, and developer tooling.
The organization brings these projects together while keeping their responsibilities distinct. Some repositories provide the foundations applications run on. Others add features, define integration contracts, or support the workflow of building and distributing packages.
The goal is to make it easier to develop software that can grow through extensions, reuse functionality across projects, and keep application code organized as requirements change.
What we build
Area	Focus
Application infrastructure	Runtime behavior and the foundations needed to execute and connect packages.
Framework packages	Reusable capabilities and controllers that extend the runtime.
Content management	Packages for managing content, themes, and administration interfaces.
Developer tools	Tools that support package development, builds, and distribution.
Templates and examples	Starting points that demonstrate package structure and integration.


Design principles
These principles guide the ecosystem:
- Clear responsibilities. Each project has a defined role and exposes the interfaces other projects need.
- Extension through packages. New functionality belongs in packages, allowing applications to evolve without editing the framework core.
- Interoperability through contracts. Shared interfaces, events, resources, and data formats provide integration points between independently developed packages.
- Server-side rendering where appropriate. Generate HTML on the server while using browser-side behavior for interactions that benefit from it.
- Developer control. Provide structure for integration while leaving room for developers to choose how they implement their applications.
- A connected development workflow. Support the work around application code, including package structure, building, and distribution.
Repository directory
Application runtime
Repository	Purpose
AWT Framework	The PHP application runtime and foundation for executing, connecting, and extending AWT packages.


Framework packages
Repository	Purpose
URPC	Universal Rendering Pipeline Contract: a rendering controller that coordinates rendering through shared contracts and block formats.


CMS packages
Repository	Purpose
ThemeEngine	Theme management and integration with the public rendering pipeline.
Dashboard	An extensible administration dashboard with widgets supplied by packages.


Developer tools and templates
Repository	Purpose
Package Build Environment	Tooling for building and packaging AWT packages for distribution.
TemplatePackage	A starting structure for developing packages and organizing their runtime, routes, controllers, views, and assets.


Browse all repositories →
How the projects fit together
The runtime executes packages and provides their integration mechanisms. Framework packages add reusable capabilities. CMS packages use those foundations to provide content and administration features. Developer tools and templates support the process of creating and distributing those packages.
Dependencies and compatibility requirements belong to each individual project. Start with the repository that matches your goal and follow its documentation for the components it requires.
Find your starting point
- Build an application: explore the AWT Framework and its documentation.
- Develop a package: start with TemplatePackage and explore the Package Build Environment.
- Integrate rendering: explore URPC and its rendering contracts.
- Work on themes or administration: explore ThemeEngine and Dashboard.
Check each repository for installation instructions, supported versions, dependencies, releases, and licensing.
Contribute
Contributions can include code, bug reports, documentation, examples, and developer experience improvements.
- Report a bug: open an issue in the relevant repository with reproduction steps, expected behavior, actual behavior, and the versions involved.
- Suggest an improvement: explain the problem it solves and which project should own the behavior.
- Improve documentation: clarify setup instructions, explain an integration point, or add a practical example.
- Submit a change: follow the repository's contribution guidance. Discuss larger architectural changes in an issue before implementing them.
For questions about a particular component, use its repository so the discussion stays close to the relevant code and documentation.
Releases and licensing
Projects have their own release cycles and compatibility requirements. Consult the relevant repository and release notes before upgrading components.
Licensing is defined per repository. Review each project's license before using, modifying, or distributing its code.
Created and maintained by Stefan Crkvenjakov.
