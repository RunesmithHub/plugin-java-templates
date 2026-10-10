# Java templates for Runesmith

The official Java project templates for [Runesmith](https://github.com/RunesmithHub/Runesmith), `runesmith.java-templates`. **File ›
New Project** offers:

| Template | What it creates |
| --- | --- |
| Application | A `Main` class with a `main` method, and a test for it |
| Library | A public class named after the project, and its test |
| Compact source file | One Java 25 file with a `void main()` and no class or build, run with `java File.java` |
| Multi-module project | A `lib` module and an `app` module that uses it, built with Maven or Gradle |

Each can be built with Maven, Gradle (Kotlin or Groovy DSL) or no build system, for Java 8, 11, 17, 21 or 25, with JUnit tests, a
module declaration and sample code as options. The templates write their files directly and download nothing.

Editing, building and running Java come from the [Java plugin](https://github.com/RunesmithHub/plugin-java).

## Capabilities

| Capability | Why |
| --- | --- |
| `filesystem` | Writes the new project's files into the folder you choose. |

## Install

Install **Java templates** from the plugin manager in Runesmith, or from [the plugin hub](https://hub.runesmith.dev).

## Build and test

You need the .NET SDK version in `global.json`.

```sh
dotnet build plugin-java-templates.slnx -warnaserror
dotnet test --solution plugin-java-templates.slnx
```

`dotnet build src/Runesmith.Java.Templates -t:InstallPlugin` installs your build into your Runesmith plugins folder; restart Runesmith to
load it.

## Documentation

[Java templates](https://docs.runesmith.dev/plugins/java#templates) in the
[Runesmith documentation](https://docs.runesmith.dev/) describes every template and option.

## License

Apache-2.0. See [LICENSE](LICENSE) and [NOTICE](NOTICE).
