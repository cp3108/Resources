# Skills
- Javascript?

# Projects depended upon
- [Acorn](https://github.com/acornjs/acorn)

A major time-saver, also used by js-slang below. It takes in code and turns it into an Abstract Syntax Tree, saving the tedious and non-trivial parsing of the language.

- [js-slang](https://github.com/source-academy/js-slang)

The current interpreter for _Source_. Many thanks to the developers who have made it what it is today. It has taught me a lot on language implementation, and how for even a comparatively small language it is not at all easy to perfect.

- [_Source_ documentation](https://github.com/source-academy/js-slang/tree/master/doc)

The specifications for _Source_, authored by Prof. Martin Henz, refined relentlessly in pursuit of an approachable yet expressive language.

# Projects depending on this

- Debugger?

I'm not sure what the plans for the debugger are currently, but if it's going to be using the Chrome console hopefully this project can synergise with it to create a seamless debugging experience.

- Source Interpreter, WebAssembly and Sound improvements?

If going native doesn't work out, at least we have the interpreter to fall back on. Work on the interpreter is much appreciated. (Not sure if it's possible or even worth it to have only some parts of the interpreter `eval`ed? Then perhaps we could work together.) Similarly, the sound and curve missions are the main offenders in evaluation time, and if anything can be done to speed those up it would be great.

- Sound Missions.

With a faster implementation of Source, Sound missions can be significantly sped up.
