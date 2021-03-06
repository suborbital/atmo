![logo_transparent cropped](https://user-images.githubusercontent.com/5942370/97611488-a10ea580-19ec-11eb-9178-a6b17c151230.png)

Building web services should be simple. Atmo makes it easy to create a powerful server application wihout needing to worry about scalability, infrastructure, or complex networking.

Atmo lets you write small self-contained functions called Runnables using a variety of languages, and define the business logic of your API by declaratively composing them. Atmo then scales out a flat network of instances to handle traffic using its meshed message bus and embedded job scheduler. Atmo can handle request-based traffic, and soon will be able to handle events sourced from various systems like Kafka or EventBridge.

## Get started

**✨ To start building with Atmo, visit the [Atmo guide](https://atmo.suborbital.dev) ✨**

Atmo uses a declarative file called the [Directive](https://atmo.suborbital.dev/concepts/the-directive) where you describe your application's behaviour. Because the Directive can describe everything you need to make your application work (including routes, logic, and more), there is no need to write boilerplate ever again.

With Atmo, you only need to do three things:
1. Write self-contained, composable functions
2. Declare how you want Atmo to handle requests by creating a "Directive"
3. Build and deploy your Runnable bundle

Atmo is not just a framework, but also a self-hosted platform that uses a bundle containing your Runnables and Directive to automatically run your application.

## Background

Atmo is designed to embody the [SUFA design pattern](https://blog.suborbital.dev/building-a-better-monolith) (Simple, Unified, Function-based Applications). This means you can build your project into a single deployable unit, and Atmo will take care of the server, scaling out its job scheduler, and meshing together auto-scaled instances.

## Contributing

Please read the [contributing guide](./CONTRIBUTING.md) to learn about how you can contribute to Atmo! We welcome all types of contribution.

## Status
Atmo is currently in **beta**, and is the flagship project in the Suborbital Development Platform.

Atmo is built atop [Vektor](https://github.com/suborbital/vektor), [Grav](https://github.com/suborbital/grav), and [Reactr](https://github.com/suborbital/reactr).

Copyright Suborbital contributors 2021.
