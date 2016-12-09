# Symfony console application with DI

A simple Symfony console application skeleton. Uses Symfony DI container.

## Motivation

I wanted a Symfony console application skeleton that uses DI container to manage commands, services and parameters without using the whole Symfony framework bundle.

## How does it work

- The commands are automatically registered, when tagged with `console.command` in container.
- The dependencies of comand are resolved automatically without injecting the whole container like with `ContainerAwareCommand`.
- YAML configuration is the default, with separate config files for commands, services and parameters.

## Inspiration

- https://github.com/bkielbasa/symfony-console-di
- https://github.com/box-project/console

Thanks!
