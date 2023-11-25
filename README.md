# Awesome Python Testing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Collection of awesome Python resources for testing and generating test data.

## Contents

- [Assertions](#assertions)
- [Behavior-driven Development](#behavior-driven-development)
- [Code Coverage](#code-coverage)
- [Design by Contract](#design-by-contract)
- [Fake Data](#fake-data)
- [Load Testing](#load-testing)
- [Memory Management](#memory-management)
- [Mock and Stub](#mock-and-stub)
- [Mutation Testing](#mutation-testing)
- [Object Factories](#object-factories)
- [Penetration Testing](#penetration-testing)
- [Property Based Testing](#property-based-testing)
- [Rest API Testing](#rest-api-testing)
- [Speed](#speed)
- [Static Checks](#static-checks)
- [Test Runners](#test-runners)
- [Testing Frameworks](#testing-frameworks)
- [Tools](#tools)
- [UI Testing](#ui-testing)
- [Resources](#resources)
  - [Articles](#articles)
  - [Books](#books)
  - [Related](#related)

## Assertions

- [easycheck](https://github.com/nyggus/easycheck) - A collection of assertion-like functions to be used in code, where assertion themselves should be avoided; `easycheck` includes also function aliases to be used in unit testing.
- [expects](https://github.com/jaimegildesagredo/expects) - Expects is an expressive and extensible TDD/BDD assertion library for Python.
-[expycted](https://github.com/bdsoha/expycted) - Another Python expect pattern implementation. Simple, intuitive and approachable, with ability to plug in to any testing framework that relies on assertions.
- [dirty-equals](https://github.com/samuelcolvin/dirty-equals) - A python library that (mis)uses the `__eq__` method to make python code (generally unit tests) more declarative and therefore easier to read and write.
- [Precisely](https://github.com/mwilliamson/python-precisely) - allows you to write precise assertions so you only test the behaviour you're really interested in.
- [PyHamcrest](https://github.com/hamcrest/PyHamcrest) - is a framework for writing matcher objects, allowing you to declaratively define "match" rules.
- [pytest_cache_assert](https://github.com/kyleking/pytest_cache_assert) - Cache assertion data to simplify regression testing of complex serializable data.
- [sure](https://github.com/gabrielfalcao/sure) - An idiomatic assertion toolkit with human-friendly failure messages, inspired by RSpec Expectations and should.js.

## Behavior-driven Development

- [behave](https://github.com/behave/behave) - is behavior-driven development, Python style.
- [lettuce](https://github.com/gabrielfalcao/lettuce) - Behavior-driven-development tool for python, inspired by Cucumber for Ruby.
- [mamba](http://nestorsalceda.github.io/mamba) - The definitive testing tool for Python. Born under the banner of BDD.

## Code Coverage

- [Coverage.py](https://github.com/nedbat/coveragepy) - is a tool for measuring code coverage of Python programs.
- [coverage-conditional-plugin](https://github.com/wemake-services/coverage-conditional-plugin) - Conditional coverage based on any rules you define.
- [diff_cover](https://github.com/Bachmann1234/diff_cover) - Automatically find diff lines that need test coverage.

## Design by Contract

- [deal](https://github.com/life4/deal) - Design by contract for Python with static checker and test generation.
- [icontract](https://github.com/Parquery/icontract) - Design-by-contract in Python3 with informative violation messages and inheritance.
- [pact-python](https://github.com/pact-foundation/pact-python) - Python version of Pact. Enables consumer driven contract testing, providing a mock service and DSL for the consumer project, and interaction playback and verification for the service provider project.

## Fake Data

- [autofaker](https://github.com/christianhelle/autofaker) - designed to minimize the setup/arrange phase of your unit tests by removing the need to manually write code to create anonymous variables as part of a test cases setup/arrange phase.
- [faker](https://github.com/joke2k/faker) - A Python package that generates fake data.
- [fake2db](https://github.com/emirozer/fake2db) - Fake database generator.
- [genuine-fake](https://github.com/xeroxzen/genuine-fake) - Genuine Fake means an imitation of a (usually) valuable object that is so good that it is, to all intents and purposes, identical.
- [mimesis](https://github.com/lk-geimfari/mimesis) - A Python library that helps you generate fake data.
- [radar](https://pypi.org/project/radar) - Generate random datetime / time.

## Load Testing

- [Dynamic Workload Model](https://github.com/hseera/dynamic-workload-model) - Code to generate dynamic workload model. Useful for testing autoscaling in cloud or mimicking different load profile for different scenario.
- [Grasshopper](https://github.com/alteryx/locust-grasshopper) - A lightweight framework for performing load tests against an environment, primarily against an API. Grasshopper glues Locust, Pytest, some plugins (namely Locust InfluxDBListener ) and some custom code to provide a package that makes authoring load tests simple with very little boilerplate needed.
- [Grizzly](https://github.com/biometria-se/grizzly) - is a framework to be able to easily define load scenarios, and is mainly built on-top of Locust and Behave.
- [Locust](https://github.com/locustio/locust) - Scalable user load testing tool written in Python.
- [pynonymizer](https://github.com/jerometwell/pynonymizer) - is a universal tool for translating sensitive production database dumps into anonymized copies.

## Memory Management

- [filprofiler](https://github.com/pythonspeed/filprofiler) - A Python memory profiler for data processing and scientific computing applications.
- [Guppy 3](https://github.com/zhuyifei1999/guppy3) - a Python programming environment & heap analysis toolset.
- [mem_top](https://github.com/denis-ryzhkov/mem_top) - shows top suspects for memory leaks in your Python program.
- [Pympler](https://github.com/pympler/pympler) - is a development tool to measure, monitor and analyze the memory behavior of Python objects in a running Python application.
- [tracemalloc](https://docs.python.org/3/library/tracemalloc.html) - is a debug tool to trace memory blocks allocated by Python.

## Mock and Stub

- [Aioresponses](https://github.com/pnuckowski/aioresponses) - is a helper for mock/fake web requests in python aiohttp package.
- [Cornell](https://github.com/hiredscorelabs/cornell) - record & replay mock server.
- [doublex](https://pypi.org/project/doublex) - Powerful test doubles framework for Python.
- [Flexmock](https://github.com/flexmock/flexmock) - is a testing library for Python that makes it easy to create mocks, stubs and fakes.
- [freezegun](https://github.com/spulec/freezegun) - Travel through time by mocking the datetime module.
- [httmock](https://github.com/patrys/httmock) - A mocking library for requests for Python 2.6+ and 3.2+.
- [httpretty](https://github.com/gabrielfalcao/HTTPretty) - HTTP request mock tool for Python.
- [Kesha](https://github.com/NUTtech/Kesha) - A web service with a user interface for testing http requests and web hooks.
- [mock](https://docs.python.org/3/library/unittest.mock.html) - (Python standard library) A mocking and patching library.
- [mocket](https://github.com/mindflayer/python-mocket) - A socket mock framework with gevent/asyncio/SSL support.
- [Mockintosh](https://github.com/up9inc/mockintosh) - aims to provide usual HTTP mock service functionality with small resource footprint, making it friendly for microservice applications.
- [moto](https://github.com/spulec/moto) - allows you to easily mock out tests based on AWS infrastructure.
- [Pretend](https://github.com/alex/pretend) - is a library to make stubbing with Python easier.
- [responses](https://github.com/getsentry/responses) - A utility library for mocking out the requests Python library.
- [time-machine](https://github.com/adamchainz/time-machine) - Travel through time in your tests.
- [VCR.py](https://github.com/kevin1024/vcrpy) - Record and replay HTTP interactions on your tests.

## Mutation Testing

- [Cosmic Ray](https://github.com/sixty-north/cosmic-ray) - makes small changes to your source code, running your test suite for each one.
- [Mutatest](https://github.com/EvanKepner/mutatest) - Python mutation testing.
- [Mutmut](https://github.com/boxed/mutmut) - is a mutation testing system for Python, with a strong focus on ease of use.
- [MutPy](https://github.com/mutpy/mutpy) - MutPy is a mutation testing tool for Python 3.x source code
- [xmutant.py](https://github.com/vrthra/xmutant.py) - Python 3.6 bytecode based mutation analysis framework

## Object Factories

- [factory_boy](https://github.com/FactoryBoy/factory_boy) - A test fixtures replacement for Python.
- [mixer](https://github.com/klen/mixer) - Another fixtures replacement. Supports Django, Flask, SQLAlchemy, Peewee and etc.
- [Model Bakery](https://github.com/model-bakers/model_bakery) - offers you a smart way to create fixtures for testing in Django.
- [polyfactory](https://github.com/litestar-org/polyfactory) - A simple and powerful mock data generation library, based around type hints and supporting dataclasses, typed-dicts, pydantic models, msgspec structs and more.

## Penetration Testing

- [fsociety](https://github.com/fsociety-team/fsociety) - A Modular Penetration Testing Framework.
- [python-pentest-tools](https://github.com/dloss/python-pentest-tools) - Python tools for penetration testers.
- [fencer](https://github.com/abunuwas/fencer) - Fencer is an automated API security testing tool. It's an experimental project to see how much of the API security testing process can be automated.

## Property Based Testing

- [Atheris](https://github.com/google/atheris) - is a coverage-guided Python fuzzing engine. It supports fuzzing of Python code, but also native extensions written for CPython.
- [Hypothesis](https://github.com/HypothesisWorks/hypothesis) - is an advanced Quickcheck style property based testing library.

## Rest API Testing

- [behave-restful](https://github.com/behave-restful/behave-restful) - BDD Framework to Test REST Services and APIs.
- [cherrybomb](https://github.com/blst-security/cherrybomb) - CLI tool that helps you avoid undefined user behaviour by auditing your API specifications, validating them and running API security tests.
- [Dredd](https://github.com/apiaryio/dredd) - is a language-agnostic command-line tool for validating API description document against backend implementation of the API.
- [HttpRunner](https://github.com/httprunner/httprunner) - is a simple & elegant, yet powerful HTTP(S) testing framework.
- [hypothesis-graphql](https://github.com/Stranger6667/hypothesis-graphql) - Hypothesis strategies for GraphQL schemas, queries and data.
- [Schemathesis](https://github.com/kiwicom/schemathesis) - A tool for automatic property-based testing of web applications built with Open API / Swagger specifications.
- [SnapshotTest](https://github.com/syrusakbary/snapshottest) - is a way to test your APIs without writing actual test cases.
- [playback](https://github.com/Optibus/playback) - A Python decorator-based framework that lets you "record" and "replay" operations (e.g. API requests, workers consuming jobs from queues).
- [RESTler](https://github.com/microsoft/restler-fuzzer) - is the first stateful REST API fuzzing tool for automatically testing cloud services through their REST APIs and finding security and reliability bugs in these services.
- [Tavern](https://github.com/taverntesting/tavern) - is a pytest plugin, command-line tool and Python library for automated testing of APIs, with a simple, concise and flexible YAML-based syntax.

## Speed

- [Partial Testing](https://github.com/man-group/partialtesting) - Run only the tests that are relevant for your changes.
- [Pytest-incremental](https://github.com/pytest-dev/pytest-incremental) - analyses your project structure and file modifications between test-runs to modify the order tests are executed and de-select tests.
- [pytest-testmon](https://github.com/tarpas/pytest-testmon) - Selects tests affected by changed files. Continuous test runner when used with pytest-watch.
- [Awesome pytest speedup](https://github.com/zupo/awesome-pytest-speedup) - A checklist of best practices to speed up your pytest suite.

## Static Checks

- [awesome-flake8-extensions](https://github.com/DmytroLitvinov/awesome-flake8-extensions) - A curated list of awesome flake8 extensions.
- [awesome-python-typing](https://github.com/typeddjango/awesome-python-typing) - Collection of awesome Python types, stubs, plugins, and tools to work with them.
- [Bandit](https://github.com/PyCQA/bandit) - is a tool designed to find common security issues in Python code.
- [flake8](https://gitlab.com/pycqa/flake8) - is a python tool that glues together pep8, pyflakes, mccabe, and third-party plugins to check the style and quality of python code.
- [pyanalyze](https://github.com/quora/pyanalyze) - A tool for programmatically detecting common mistakes in Python code, such as references to undefined variables and some categories of type mismatches.
- [pyflakes](https://github.com/PyCQA/pyflakes) - A simple program which checks Python source files for errors.
- [Pylint](https://github.com/PyCQA/pylint) - A Python static code analysis tool which looks for programming errors, helps enforcing a coding standard, sniffs for code smells and offers simple refactoring suggestions.
- [Refurb](https://github.com/dosisod/refurb) - A tool for refurbishing and modernizing Python codebases.
- [ruff](https://github.com/charliermarsh/ruff) - An extremely fast Python linter, written in Rust.
- [slotscheck](https://github.com/ariebovenberg/slotscheck) - Find mistakes in your `__slots__` definitions.
- [Typecheckers](https://github.com/ethanhs/python-typecheckers) - A list of Python type checkers.

## Test Runners

- [green](https://github.com/CleanCut/green) - A clean, colorful test runner.
- [Nox](https://github.com/theacodes/nox) - is a command-line tool that automates testing in multiple Python environments, similar to tox. Unlike tox, Nox uses a standard Python file for configuration.
- [tox](https://tox.readthedocs.io/en/latest) - Auto builds and tests distributions in multiple Python versions.

## Testing Frameworks

- [async-asgi-testclient](https://github.com/vinissimus/async-asgi-testclient) - A framework-agnostic library for testing ASGI web applications.
- [awesome-pytest](https://github.com/augustogoulart/awesome-pytest) - A curated list of awesome pytest resources.
- [awesome-robotframework](https://github.com/fkromer/awesome-robotframework) - A curated list of awesome Robot Framework resources and libraries.
- [doctest](https://docs.python.org/3/library/doctest.html) - (Python standard library) The doctest module searches for pieces of text that look like interactive Python sessions, and then executes those sessions to verify that they work exactly as shown.
- [hammett](https://github.com/boxed/hammett) - Fast python test runner, compatible with a subset of pytest.
- [nose2](https://github.com/nose-devs/nose2) - The successor to `nose`, based on `unittest2`.
- [perftester](https://github.com/nyggus/perftester) - A lightweight framework for performance testing of Python functions; allows for testing of performance in terms of execution time and memory usage.
- [promptimize](https://github.com/preset-io/promptimize) - a prompt engineering evaluation and testing toolkit. It accelerates and provides structure around prompt engineering at scale with confidence, bringing some of the ideas behind test-driven development (TDD) to engineering prompts.
- [pytest](https://docs.pytest.org/en/latest) - A mature full-featured Python testing tool.
- [sundew](https://github.com/devenjarvis/sundew/) - Sundew is a testing framework for Python, implementing a new approach to testing. One that combines functional programming concepts and the general best practices for writing tests that we already know, and enforces them in a way that enables some really powerful features that make testing easier, enjoyable, and more effective.
- [Robot Framework](https://github.com/robotframework/robotframework) - A generic test automation framework.
- [testbook](https://github.com/nteract/testbook) - A unit testing framework extension for testing code in Jupyter Notebooks.
- [unittest](https://docs.python.org/3/library/unittest.html) - (Python standard library) Unit testing framework.
- [vedro](https://github.com/vedro-universe/vedro) - Pragmatic testing framework for Python
- [Ward](https://github.com/darrenburns/ward) - is a modern test framework for Python with a focus on productivity and readability.
- [xdoctest](https://github.com/Erotemic/xdoctest) - A rewrite of Python's builtin doctest module (with pytest plugin integration) with AST instead of REGEX.

## Tools

- [ApprovalTests](https://github.com/approvals/ApprovalTests.Python) - work by comparing the test results to a golden master.
- [Auger](https://github.com/laffra/auger) - is a project to automatically generate unit tests for Python code.
- [CrossHair](https://github.com/pschanely/CrossHair) - An analysis tool for Python that blurs the line between testing and type systems.
- [ghostwriter](https://hypothesis.readthedocs.io/en/latest/ghostwriter.html) - Writing tests with Hypothesis frees you from the tedium of deciding on and writing out specific inputs to test.
- [importlab](https://github.com/google/importlab) - A library that automatically infers dependencies for Python files. Importlab's main use case is to work with static analysis tools that process one file at a time, ensuring that a file's dependencies are analysed before it is.
- [Klara](https://github.com/usagitoneko97/klara) - is a static analysis tools to automatic generate test case, based on SMT (z3) solver, with a powerful ast level inference system.
- [Pifpaf](https://github.com/jd/pifpaf) - is a suite of fixtures and a command-line tool that allows to start and stop daemons for a quick throw-away usage. This is typically useful when needing these daemons to run integration testing.
- [Ponicode](https://www.ponicode.com) - AI-powered unit testing interface for VS Code. Write, generate, modify and visualise all kinds of unit tests for JavaScript, TypeScript and Python.
- [Pynguin](https://github.com/se2p/pynguin) - is a tool that allows developers to generate unit tests automatically.
- [pytest-codegen](https://github.com/jeremyschiemann/pytest-codegen) - Pytest-codgen will statically analyze your code to create pytest function stubs.
- [pytestify](https://github.com/dannysepler/pytestify) - Automatically convert unittests to pytest.
- [pytest-mock-generator](https://github.com/pksol/pytest-mock-generator) - A pytest fixture wrapper for `mock_autogen`.
- [teyit](https://github.com/isidentical/teyit) - A static analyzer and a refactoring tool to rewrite your unittest assertions in the right way.

## UI Testing

- [Flybirds](https://github.com/ctripcorp/flybirds) - is a front-end UI automation test framework based on BDD mode, providing a series of out-of-the-box tools and complete documentation.
- [Golem](https://github.com/golemhq/golem) - is a test framework and a complete tool for browser automation. Tests can be written with code in Python, codeless using the web IDE, or both.
- [helium](https://github.com/mherrmann/selenium-python-helium) - is great for web automation. Helium makes it easier to use.
- [Lost Pixel](https://github.com/lost-pixel/lost-pixel) - is an open source visual regression testing tool. Run visual regression tests on your Storybook and Ladle stories and on your application pages.
- [LuluTest](https://github.com/erik-whiting/LuluTest) - is an open source browser automation framework using Python and Selenium.
- [PyAutoGUI](https://github.com/asweigart/pyautogui) - is a cross-platform GUI automation Python module for human beings.
- [pytest-ui-automatic](https://github.com/moyu6027/pytest-ui-automatic) - Playwright Python tool practice pytest pytest-bdd screen-play page-object allure cucumber-report.
- [selene](https://github.com/yashaka/selene) - User-oriented Web UI browser tests in Python (Selenide port).
- [Selenium](https://pypi.org/project/selenium) - Python bindings for [Selenium](http://www.seleniumhq.org/) WebDriver.
- [SeleniumBase](https://github.com/seleniumbase/SeleniumBase) - is an all-in-one Python framework for automated browser testing. Tests are run with "pytest", and use WebDriver APIs for web-page interaction.
- [sixpack](https://github.com/seatgeek/sixpack) - A language-agnostic A/B Testing framework.
- [splinter](https://github.com/cobrateam/splinter) - Open source tool for testing web applications.
- [squape](https://github.com/CyberAlpaca/squish-api-python-extension) - is a package that extends Squish API providing convenience tools for everyday automated test cases development.

## Resources

### Articles

- [Anna-Lena Popkes: "Mocking in Python"](https://alpopkes.com/posts/python/mocking/)
- [async test patterns for Pytest](https://tonybaloney.github.io/posts/async-test-patterns-for-pytest-and-unittest.html) - Learn some handy async examples and patterns for testing in Pytest.
- [How not to footgun yourself when writing tests](https://www.marwansarieddine.com/posts/flaky_tests) - a showcase of flaky tests
- [Stargirl Flowers: “My Python testing style guide”](https://blog.thea.codes/my-python-testing-style-guide) - An attempt to catalog some practices around testing Python projects. It's not meant to be treated as dogma.
- [Test & Code: Python Testing](https://testandcode.com/) - Test & Code is a weekly podcast hosted by Brian Okken. The show covers a wide array of topics including software engineering, development, testing, Python programming, and many related topics.
- [Testing your Python Code with Hypothesis](https://www.inspiredpython.com/course/testing-with-hypothesis/testing-your-python-code-with-hypothesis) - A look at how Hypothesis can help you discover errors in your code.
- [Patterns of flakey Python tests](https://tech.octopus.energy/news/2022/05/23/flakey-python-tests.html) - This post details several patterns that cause flakey Python tests. Being aware of these common causes can help when investigating your own flakey tests.
- [Unit testing Python code in Jupyter notebooks](https://www.wrighters.io/unit-testing-python-code-in-jupyter-notebooks) -  This article covers several options for unit testing Python code in a Jupyter notebook.
- [30 best practices for software development and testing](https://opensource.com/article/17/5/30-best-practices-software-development-and-testing) - These software engineering rules and testing best practices might help save you time and headaches.

### Books

- [Architecture Patterns with Python](https://www.oreilly.com/library/view/architecture-patterns-with/9781492052197) (O'Reilly)
- [Crafting Test-Driven Software with Python](https://www.packtpub.com/product/crafting-test-driven-software-with-python/9781838642655) (Packt)
- [Getting Started With Property-Based Testing in Python With Hypothesis and Pytest](https://semaphoreci.com/blog/property-based-testing-python-hypothesis-pytest)
- [pytest Quick Start Guide](https://www.packtpub.com/product/pytest-quick-start-guide/9781789347562) (Packt)
- [Python Testing with pytest](https://pragprog.com/titles/bopytest2/python-testing-with-pytest-second-edition) (Pragmatic Bookshelf)
- [Python Testing with Selenium](https://link.springer.com/book/10.1007/978-1-4842-6249-8) (Apress)
- [Python Unit Test Automation](https://www.oreilly.com/library/view/python-unit-test/9781484226766) (O'Reilly)
- [Testing In Python](https://www.amazon.com/Testing-Python-Robust-Professionals/dp/B0857CFM17) (Independently published)
- [Testing Python](https://www.amazon.com/Testing-Python-Applying-Unit-Acceptance/dp/1118901223) (Wiley)
- [Test-Driven Development with Python](https://www.oreilly.com/library/view/test-driven-development-with/9781491958698) (O'Reilly)

## Videos

- [PyCon US 2023 - Talk - Shai Geva: 10 Ways To Shoot Yourself In The Foot With Tests](https://youtu.be/Ub31Ae6S1BY)
- [PyCon US 2023 - Tutorial - Zac Hatfield-Dodds, Ryan Soklaski: Introduction to Property-Based Testing](https://youtu.be/YwYIDpze52s)
- [PyCon US 2023 -Talk - Dave Aronson: Kill All Mutants! (Intro to Mutation Testing)](https://youtu.be/G0MbITvWfgY)

### Related

- [Awesome Python](https://github.com/vinta/awesome-python/blob/master/README.md#testing) - A curated list of awesome Python frameworks, libraries, software and resources.
- [Python test automation](https://github.com/atinfo/awesome-test-automation/blob/master/python-test-automation.md) - A comprehensive curated list of python test automation frameworks, tools, libraries and software to help software engineers easily bootstrap test automation on python.
- [commit-check](https://github.com/commit-check/commit-check) - Check commit message formatting, branch naming, commit author, email, and more.
