# React-JUCE

> Write cross-platform native apps with React.js and JUCE


TODO: Reference Yoga and Hermes/Duktape

React-JUCE is a hybrid JavaScript/C++ framework that enables a [React.js](https://reactjs.org/) frontend for a [JUCE](http://juce.com/) application or plugin.

For more information, see the introductory blog post here: [Blueprint: A JUCE Rendering Backend for React.js](https://nickwritesablog.com/blueprint-a-juce-rendering-backend-for-react-js)

## Status

**Approaching Beta**. We hope to announce a beta release in the coming weeks, after which we will aim our focus at stability and completeness on the path
to a 1.0 release.

**Anticipated Breaking Changes**

- ~~`ReactApplicationRoot::evaluate` and `ReactApplicationRoot::evaluateFile` (#115)~~
- ~~Refactoring the hot reloader and decoupling the EcmascriptEngine from ReactApplicationRoot (#65)~~

## Resources

- Documentation: [Docs & Getting Started](https://docs.react-juce.dev)
- Discussions: [GitHub Discussions](https://github.com/JoshMarler/react-juce/discussions)
- Community: [The Audio Programmer Discord Server](https://discord.gg/3H4wwVf49v)
  - Join the `#blueprint` channel and say hi!

## Maintainers

- [@joshmarler](https://github.com/JoshMarler)
- [@nick-thompson](https://github.com/nick-thompson)

## Examples

React-JUCE is a young project, but already it provides the framework on which the entire user interface for [Creative Intent's Remnant](https://www.creativeintent.co/product/remnant) plugin is built.

![Creative Intent Remnant: Screenshot](_media/RemnantScreenShot.jpg)

Besides that, you can check out a selection of example plugins over at [react-juce-examples](https://github.com/JoshMarler/react-juce-examples)

If you have a project written with React-JUCE that you want to share, get in touch! I would love to showcase your work.

## Contributing

See [CONTRIBUTING.md](https://github.com/JoshMarler/react-juce/blob/master/CONTRIBUTING.md)

## License

See [LICENSE.md](https://github.com/JoshMarler/react-juce/blob/master/LICENSE.md)
