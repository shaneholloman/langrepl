# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.0](https://github.com/shaneholloman/langrepl/compare/v1.4.1...v2.0.0) (2025-11-16)


### ⚠ BREAKING CHANGES

* Major upgrade from LangChain 0.x to 1.x with architectural changes

### Features

* add @ reference completion for file paths ([dc86180](https://github.com/shaneholloman/langrepl/commit/dc86180aacedd3789b08078aa002d1f1624dab5d))
* add @ reference completion for file paths ([3dd5ef0](https://github.com/shaneholloman/langrepl/commit/3dd5ef0c82d759492b768641b16ca1fabd8c88e9))
* Add config and tool_call_id to EditFileInput ([#4](https://github.com/shaneholloman/langrepl/issues/4)) ([e1e250f](https://github.com/shaneholloman/langrepl/commit/e1e250f52164234bfee3a59a1f63f6136753e398))
* add ctrl c key binding for stream cancellation ([#27](https://github.com/shaneholloman/langrepl/issues/27)) ([4e527af](https://github.com/shaneholloman/langrepl/commit/4e527af6311c14ad2dc93b92b41230d06a00178f))
* add model indicators in /model selector ([3dbe31f](https://github.com/shaneholloman/langrepl/commit/3dbe31f8a5d65b9a65bfeeae080df08f6b90b6ae))
* add model switching for subagents ([5e0754f](https://github.com/shaneholloman/langrepl/commit/5e0754f8472ea2ad1a039e27032580d1cccf7ac5))
* add model switching for subagents ([8da512a](https://github.com/shaneholloman/langrepl/commit/8da512acf7e7f1fcc2715623246546260eba0b32))
* add multimodal image support with builder pattern ([#37](https://github.com/shaneholloman/langrepl/issues/37)) ([dc3a94f](https://github.com/shaneholloman/langrepl/commit/dc3a94fbe4d0ac6ce101b813775e2ecebac79071))
* add one-shot mode ([#40](https://github.com/shaneholloman/langrepl/issues/40)) ([43cb1de](https://github.com/shaneholloman/langrepl/commit/43cb1de82de32a2c7c6ac6642f6c3a9d2ef4b44c))
* add repair command for MCP before retrying ([9f7cdd2](https://github.com/shaneholloman/langrepl/commit/9f7cdd27ae4a2df7614394a6428c430441a50bb4))
* add support for zhipuai glm ([15fa1af](https://github.com/shaneholloman/langrepl/commit/15fa1afde131c4b51dab87717b3c9de1f18f33da))
* add support for zhipuai glm ([88815a5](https://github.com/shaneholloman/langrepl/commit/88815a5a95a1fff46909c14fb29a393ea4bdecc8))
* automate version bumping via GitHub Actions ([f995bc8](https://github.com/shaneholloman/langrepl/commit/f995bc84e5bf88bfd623cf8bb099d6306c1fadd3))
* automate version bumping via GitHub Actions ([b55e511](https://github.com/shaneholloman/langrepl/commit/b55e511bb58f6bfd7ad5d8ce32375bc3d89fc05f))
* clean ([70898f9](https://github.com/shaneholloman/langrepl/commit/70898f91cd813fd01c780ecd85177c60ad6a563d))
* improve agent switching with model sync and default persistence ([#5](https://github.com/shaneholloman/langrepl/issues/5)) ([33dd143](https://github.com/shaneholloman/langrepl/commit/33dd143c76de3fe43c55effb96751c5bcb1d99e7))
* improve message rendering with visual indicators and formatting ([#25](https://github.com/shaneholloman/langrepl/issues/25)) ([b88cfdf](https://github.com/shaneholloman/langrepl/commit/b88cfdfb0e3304167f6a1dd75058ef6b942bf4dc))
* migrate to LangChain v1.0 with context-based architecture ([#20](https://github.com/shaneholloman/langrepl/issues/20)) ([d003cce](https://github.com/shaneholloman/langrepl/commit/d003cce49694ce0140249386db96b655dbe58fa0))
* pair tool calls with results in rendering ([#29](https://github.com/shaneholloman/langrepl/issues/29)) ([e2fc941](https://github.com/shaneholloman/langrepl/commit/e2fc94104a4dd7b7714f3720e6075d13774452a1))
* setup workflow ([9cf1738](https://github.com/shaneholloman/langrepl/commit/9cf17386f4d898adb14972c66c3c0112c6f5adc8))


### Bug Fixes

* add cache for approval to prevent duplication ([b99f972](https://github.com/shaneholloman/langrepl/commit/b99f9721ecac55e6c6907767475b6811ad7985dc))
* add missing injected params to EditMemoryFileInput ([9020a5b](https://github.com/shaneholloman/langrepl/commit/9020a5b03cd55b83f463926ab2dd591d97b96d60))
* add missing injected params to EditMemoryFileInput ([73f768c](https://github.com/shaneholloman/langrepl/commit/73f768cfdf8b9fabd1a55b9838505bff5b664223))
* add short content for task tool result ([2e094ad](https://github.com/shaneholloman/langrepl/commit/2e094ad9f6ea22e763d3847cfcc72f1eb4cc554a))
* add TTY check before ANSI escape codes ([585e39d](https://github.com/shaneholloman/langrepl/commit/585e39d60307ed0cce2e0ab7fd36c375cedd5ec9))
* add write permissions to version bump workflow ([66ea456](https://github.com/shaneholloman/langrepl/commit/66ea45685d4b57a6a75948b58025a71ce74755ac))
* add write permissions to version bump workflow ([0700c76](https://github.com/shaneholloman/langrepl/commit/0700c76abc813daa83680d6fa2df5a15d683d71a))
* address code review feedback and security warnings ([be53157](https://github.com/shaneholloman/langrepl/commit/be53157cb5771dc3a633353bf5a0cf93603b5e98))
* allow dirty working directory in version bump workflow ([d48cfd0](https://github.com/shaneholloman/langrepl/commit/d48cfd0d38d339be2145b59c28a812a30ed4f660))
* always return short_content in task tool ([bc1200d](https://github.com/shaneholloman/langrepl/commit/bc1200da099a0c415f78b32b48bfa6970e96aad6))
* correct ToolRuntime context type and auto-approve internal tools ([8d17619](https://github.com/shaneholloman/langrepl/commit/8d176190a4499dd3d66b74d56fda8643154ef623))
* env example ([b2c24ca](https://github.com/shaneholloman/langrepl/commit/b2c24ca65ac6a2e21e8e2503c4e55ae0d117a726))
* handle directory paths with spaces in completion ([b604cae](https://github.com/shaneholloman/langrepl/commit/b604cae770886134d6a27fa62e510c9798ce17f8))
* handle multiple pending interrupts ([#28](https://github.com/shaneholloman/langrepl/issues/28)) ([9cc140f](https://github.com/shaneholloman/langrepl/commit/9cc140f629203596441d183329912c11b7f8f3e3))
* improve tool error handling and replay checkpoint deletion ([f79e580](https://github.com/shaneholloman/langrepl/commit/f79e58070b5eb94ce3ff480a60633b3fc7c9ac4b))
* improve tool error handling and update for LangGraph v2 compatibility ([42a8cf6](https://github.com/shaneholloman/langrepl/commit/42a8cf6f3084c2cc891f6981a1a39eb15341d766))
* input tokens count ([822f45c](https://github.com/shaneholloman/langrepl/commit/822f45ce13a60fe3b751c74eb6cd0098ae2382f4))
* properly rewind conversation thread by deleting checkpoints after replay point ([24b419f](https://github.com/shaneholloman/langrepl/commit/24b419f0cf8ea8af1fc7c6bb6505e5fb23c04db6))
* render interrupt ([ae07b44](https://github.com/shaneholloman/langrepl/commit/ae07b44fc660b53540deb0a41289325da2aca032))
* restore stable state by reverting recent changes ([121d003](https://github.com/shaneholloman/langrepl/commit/121d003dffc8e9574a8ac86189580856fd8368a6))
* tool call/result pairing in live and resume modes ([#30](https://github.com/shaneholloman/langrepl/issues/30)) ([3e5059a](https://github.com/shaneholloman/langrepl/commit/3e5059a7b135e76f570800cd5a0e1ee9998f479c))
* trigger release for refactor changes ([24ab34f](https://github.com/shaneholloman/langrepl/commit/24ab34ff49c7309ea341a90decdbb85d81f68dfe))
* wrap Path.glob() in asyncio.to_thread() to prevent BlockingError in server mode ([9a4f7ee](https://github.com/shaneholloman/langrepl/commit/9a4f7ee766d1a122dfa5096c112e4d37c2788394))


### Performance Improvements

* optimize directory set lookups in completion ([ccb6ea0](https://github.com/shaneholloman/langrepl/commit/ccb6ea08da967a90ff9ba2b5142a5c90a1b815ac))


### Documentation

* update ([af8607d](https://github.com/shaneholloman/langrepl/commit/af8607d00ed4b181e397d905c719490120d8d878))
* update ([4f83edb](https://github.com/shaneholloman/langrepl/commit/4f83edb8422f0a05d3ef279b8f63ada83d8097bb))
* update demo ([799001d](https://github.com/shaneholloman/langrepl/commit/799001dfe87a64e617ce09bec17cf3d4fc21e512))

## [1.4.1](https://github.com/midodimori/langrepl/compare/v1.4.0...v1.4.1) (2025-11-15)


### Bug Fixes

* wrap Path.glob() in asyncio.to_thread() to prevent BlockingError in server mode ([9a4f7ee](https://github.com/midodimori/langrepl/commit/9a4f7ee766d1a122dfa5096c112e4d37c2788394))


### Documentation

* update ([af8607d](https://github.com/midodimori/langrepl/commit/af8607d00ed4b181e397d905c719490120d8d878))

## [1.4.0](https://github.com/midodimori/langrepl/compare/v1.3.0...v1.4.0) (2025-11-11)


### Features

* add one-shot mode ([#40](https://github.com/midodimori/langrepl/issues/40)) ([43cb1de](https://github.com/midodimori/langrepl/commit/43cb1de82de32a2c7c6ac6642f6c3a9d2ef4b44c))


### Documentation

* update ([4f83edb](https://github.com/midodimori/langrepl/commit/4f83edb8422f0a05d3ef279b8f63ada83d8097bb))

## [1.3.0](https://github.com/midodimori/langrepl/compare/v1.2.1...v1.3.0) (2025-11-10)


### Features

* add multimodal image support with builder pattern ([#37](https://github.com/midodimori/langrepl/issues/37)) ([dc3a94f](https://github.com/midodimori/langrepl/commit/dc3a94fbe4d0ac6ce101b813775e2ecebac79071))


### Documentation

* update demo ([799001d](https://github.com/midodimori/langrepl/commit/799001dfe87a64e617ce09bec17cf3d4fc21e512))

## [1.2.1](https://github.com/midodimori/langrepl/compare/v1.2.0...v1.2.1) (2025-11-09)


### Bug Fixes

* add short content for task tool result ([2e094ad](https://github.com/midodimori/langrepl/commit/2e094ad9f6ea22e763d3847cfcc72f1eb4cc554a))
* always return short_content in task tool ([bc1200d](https://github.com/midodimori/langrepl/commit/bc1200da099a0c415f78b32b48bfa6970e96aad6))

## [1.2.0](https://github.com/midodimori/langrepl/compare/v1.1.3...v1.2.0) (2025-11-09)


### Features

* add model indicators in /model selector ([3dbe31f](https://github.com/midodimori/langrepl/commit/3dbe31f8a5d65b9a65bfeeae080df08f6b90b6ae))

## [1.1.3](https://github.com/midodimori/langrepl/compare/v1.1.2...v1.1.3) (2025-11-09)


### Bug Fixes

* add cache for approval to prevent duplication ([b99f972](https://github.com/midodimori/langrepl/commit/b99f9721ecac55e6c6907767475b6811ad7985dc))

## [1.1.2](https://github.com/midodimori/langrepl/compare/v1.1.1...v1.1.2) (2025-11-09)


### Bug Fixes

* restore stable state by reverting recent changes ([121d003](https://github.com/midodimori/langrepl/commit/121d003dffc8e9574a8ac86189580856fd8368a6))

## [1.0.2](https://github.com/midodimori/langrepl/compare/v1.0.1...v1.0.2) (2025-11-07)


### Bug Fixes

* input tokens count ([822f45c](https://github.com/midodimori/langrepl/commit/822f45ce13a60fe3b751c74eb6cd0098ae2382f4))

## [1.0.1](https://github.com/midodimori/langrepl/compare/v1.0.0...v1.0.1) (2025-11-07)


### Bug Fixes

* render interrupt ([ae07b44](https://github.com/midodimori/langrepl/commit/ae07b44fc660b53540deb0a41289325da2aca032))

## [1.0.0](https://github.com/midodimori/langrepl/compare/v0.3.1...v1.0.0) (2025-11-07)


### ⚠ BREAKING CHANGES

* Major upgrade from LangChain 0.x to 1.x with architectural changes

### Features

* migrate to LangChain v1.0 with context-based architecture ([#20](https://github.com/midodimori/langrepl/issues/20)) ([d003cce](https://github.com/midodimori/langrepl/commit/d003cce49694ce0140249386db96b655dbe58fa0))


### Bug Fixes

* correct ToolRuntime context type and auto-approve internal tools ([8d17619](https://github.com/midodimori/langrepl/commit/8d176190a4499dd3d66b74d56fda8643154ef623))

## [0.3.1](https://github.com/midodimori/langrepl/compare/v0.3.0...v0.3.1) (2025-11-05)


### Code Refactoring

* **cli:** reorganize bootstrap layer and expand tests ([#18](https://github.com/midodimori/langrepl/pull/18)) ([7ede2de](https://github.com/midodimori/langrepl/commit/7ede2de6f83cf101df18ab1141b3831ee056c75d))

## [0.3.0] - 2025-11-02

### Features

- Add @ reference completion for file paths ([#16](https://github.com/midodimori/langrepl/pull/16))

## [0.2.4] - 2025-10-31

### Code Refactoring

- Standardize key bindings to use Keys enum constants ([#12](https://github.com/midodimori/langrepl/pull/12))

### Bug Fixes

- Improve tool error handling and replay checkpoint deletion ([#13](https://github.com/midodimori/langrepl/pull/13))

## [0.2.3] - 2025-10-29

### Tests

- Add integration tests for tools ([#11](https://github.com/midodimori/langrepl/pull/11))

## [0.2.2] - 2025-10-29

### Code Refactoring

- Flatten tool parameters ([#10](https://github.com/midodimori/langrepl/pull/10))

## [0.2.1] - 2025-10-29

### Bug Fixes

- Add missing injected params to EditMemoryFileInput ([#9](https://github.com/midodimori/langrepl/pull/9))

## [0.2.0] - 2025-10-29

### Features

- Add model switching for subagents ([#8](https://github.com/midodimori/langrepl/pull/8))

## [0.1.1] - 2025-10-28

### Features

- Add support for zhipuai glm ([#1](https://github.com/midodimori/langrepl/pull/1))
- Automate version bumping via GitHub Actions ([#6](https://github.com/midodimori/langrepl/pull/6))

### Bug Fixes

- Add write permissions to version bump workflow ([#7](https://github.com/midodimori/langrepl/pull/7))

## [0.1.0] - 2025-10-06

Initial release of LangREPL - an interactive terminal CLI for working with LLM agents.

### Features

- ReAct agent pattern with tool execution
- Multi-provider LLM support (OpenAI, Anthropic, Google, AWS Bedrock, Ollama, DeepSeek, Zhipu AI)
- Persistent conversation threads with SQLite checkpointer
- Extensible tool system (filesystem, web, grep, terminal)
- MCP (Model Context Protocol) integration
- Human-in-the-loop tool approval system
- Agent switching and configuration
- Virtual filesystem for document drafting
- Task planning with todo tracking
- LangGraph server mode
