# Awesome Python Testing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
Collection of awesome Python resources for testing and generating test data.

## Contents

- [Testing Frameworks](#testing-frameworks)
- [Test Runners](#test-runners)
- [Property Based Testing](#property-based-testing)
- [Mutation Testing](#mutation-testing)
- [Behavior-driven Development](#behavior-driven-development)
- [UI Testing](#ui-testing)
- [Rest API Testing](#rest-api-testing)
- [Load Testing](#load-testing)
- [Mock](#mock)
- [Assertions](#assertions)
- [Object Factories](#object-factories)
- [Fake Data](#fake-data)
- [Design by Contract](#design-by-contract)
- [Code Coverage](#code-coverage)
- [Static Checks](#static-checks)
- [Articles](#articles)
- [Tools](#tools)
- [Related](#related)

## Testing Frameworks

- [pytest](https://docs.pytest.org/en/latest/) - A mature full-featured Python testing tool.
- [awesome-pytest](https://github.com/augustogoulart/awesome-pytest) - A curated list of awesome pytest resources.
- [hammett](https://github.com/boxed/hammett) - Fast python test runner, compatible with a subset of pytest.
- [unittest](https://docs.python.org/3/library/unittest.html) - (Python standard library) Unit testing framework.
- [doctest](https://docs.python.org/3/library/doctest.html) - (Python standard library) The doctest module searches for pieces of text that look like interactive Python sessions, and then executes those sessions to verify that they work exactly as shown.
- [nose2](https://github.com/nose-devs/nose2) - The successor to `nose`, based on `unittest2`.
- [Robot Framework](https://github.com/robotframework/robotframework) - A generic test automation framework.
- [awesome-robotframework](https://github.com/fkromer/awesome-robotframework) - A curated list of awesome Robot Framework resources and libraries.
- [testbook](https://github.com/nteract/testbook) - A unit testing framework extension for testing code in Jupyter Notebooks.
- [ward](https://github.com/darrenburns/ward) - Ward is a modern test framework for Python with a focus on productivity and readability.

## Test Runners

- [green](https://github.com/CleanCut/green) - A clean, colorful test runner.
- [tox](https://tox.readthedocs.io/en/latest/) - Auto builds and tests distributions in multiple Python versions.
- [nox](https://github.com/theacodes/nox) - Nox is a command-line tool that automates testing in multiple Python environments, similar to tox. Unlike tox, Nox uses a standard Python file for configuration.

## Property Based Testing

- [hypothesis](https://github.com/HypothesisWorks/hypothesis) - Hypothesis is an advanced Quickcheck style property based testing library.
- [Atheris](https://github.com/google/atheris) - Atheris is a coverage-guided Python fuzzing engine. It supports fuzzing of Python code, but also native extensions written for CPython.

## Mutation Testing

- [mutmut](https://github.com/boxed/mutmut) - Mutmut is a mutation testing system for Python, with a strong focus on ease of use.
- [Cosmic Ray](https://github.com/sixty-north/cosmic-ray) - Cosmic Ray is a mutation testing tool for Python 3. It makes small changes to your source code, running your test suite for each one.

## Behavior-driven Development

- [mamba](http://nestorsalceda.github.io/mamba/) - The definitive testing tool for Python. Born under the banner of BDD.
- [behave](https://github.com/behave/behave) - BDD, Python style.
- [lettuce](https://github.com/gabrielfalcao/lettuce) - Behavior-driven-development tool for python, inspired by Cucumber for Ruby.

## UI Testing

- [PyAutoGUI](https://github.com/asweigart/pyautogui) - PyAutoGUI is a cross-platform GUI automation Python module for human beings.
- [Selenium](https://pypi.org/project/selenium/) - Python bindings for [Selenium](http://www.seleniumhq.org/) WebDriver.
- [SeleniumBase](https://github.com/seleniumbase/SeleniumBase) - SeleniumBase is an all-in-one Python framework for automated browser testing. Tests are run with "pytest", and use WebDriver APIs for web-page interaction.
- [sixpack](https://github.com/seatgeek/sixpack) - A language-agnostic A/B Testing framework.
- [splinter](https://github.com/cobrateam/splinter) - Open source tool for testing web applications.
- [helium](https://github.com/mherrmann/selenium-python-helium) - Selenium-python is great for web automation. Helium makes it easier to use.
- [LuluTest](https://github.com/erik-whiting/LuluTest) - LuluTest is an open source browser automation framework using Python and Selenium. It is relatively lightweight in that it mostly provides wrappers for 3rd party library methods that make browser automation and testing more intuitive.

## Rest API Testing

- [Schemathesis](https://github.com/kiwicom/schemathesis) - A tool for automatic property-based testing of web applications built with Open API / Swagger specifications.
- [hypothesis-graphql](https://github.com/Stranger6667/hypothesis-graphql) - Hypothesis strategies for GraphQL schemas, queries and data.
- [tavern](https://github.com/taverntesting/tavern) - Tavern is a pytest plugin, command-line tool and Python library for automated testing of APIs, with a simple, concise and flexible YAML-based syntax.
- [SnapshotTest](https://github.com/syrusakbary/snapshottest) - Snapshot testing is a way to test your APIs without writing actual test cases.
- [playback](https://github.com/Optibus/playback) - A Python decorator-based framework that lets you "record" and "replay" operations (e.g. API requests, workers consuming jobs from queues).
- [behave-restful](https://github.com/behave-restful/behave-restful) - BDD Framework to Test REST Services and APIs.

## Load Testing

- [locust](https://github.com/locustio/locust) - Scalable user load testing tool written in Python.
- [dynamic-workload-model](https://github.com/hseera/dynamic-workload-model) - Code to generate dynamic workload model. Useful for testing autoscaling in cloud or mimicking different load profile for different scenario.
- [pynonymizer](https://github.com/jerometwell/pynonymizer) - Pynonymizer is a universal tool for translating sensitive production database dumps into anonymized copies. This can help you support GDPR/Data Protection in your organization without compromizing on quality testing data.

## Mock

- [doublex](https://pypi.org/project/doublex/) - Powerful test doubles framework for Python.
- [freezegun](https://github.com/spulec/freezegun) - Travel through time by mocking the datetime module.
- [time-machine](https://github.com/adamchainz/time-machine) - Travel through time in your tests.
- [httmock](https://github.com/patrys/httmock) - A mocking library for requests for Python 2.6+ and 3.2+.
- [httpretty](https://github.com/gabrielfalcao/HTTPretty) - HTTP request mock tool for Python.
- [mock](https://docs.python.org/3/library/unittest.mock.html) - (Python standard library) A mocking and patching library.
- [mocket](https://github.com/mindflayer/python-mocket) - A socket mock framework with gevent/asyncio/SSL support.
- [responses](https://github.com/getsentry/responses) - A utility library for mocking out the requests Python library.
- [VCR.py](https://github.com/kevin1024/vcrpy) - Record and replay HTTP interactions on your tests.
- [moto](https://github.com/spulec/moto) - A library that allows you to easily mock out tests based on AWS infrastructure.
- [Mockintosh](https://github.com/up9inc/mockintosh) - Mockintosh aims to provide usual HTTP mock service functionality with small resource footprint, making it friendly for microservice applications. You can have tens of mocks at once, inside moderate laptop or single Docker container.
- [flexmock](https://github.com/flexmock/flexmock) - Flexmock is a testing library for Python that makes it easy to create mocks, stubs and fakes.
- [cornell](https://github.com/hiredscorelabs/cornell) - Cornell: record & replay mock server.

## Assertions

- [Precisely](https://github.com/mwilliamson/python-precisely) - Precisely allows you to write precise assertions so you only test the behaviour you're really interested in. This makes it clearer to the reader what the expected behaviour is, and makes tests less brittle.
- [sure](https://github.com/gabrielfalcao/sure) - An idiomatic assertion toolkit with human-friendly failure messages, inspired by RSpec Expectations and should.js.

## Object Factories

- [factory_boy](https://github.com/FactoryBoy/factory_boy) - A test fixtures replacement for Python.
- [mixer](https://github.com/klen/mixer) - Another fixtures replacement. Supports Django, Flask, SQLAlchemy, Peewee and etc.
- [model_bakery](https://github.com/model-bakers/model_bakery) - Model Bakery offers you a smart way to create fixtures for testing in Django. With a simple and powerful API you can create many objects with a single line of code.

## Fake Data

- [fake2db](https://github.com/emirozer/fake2db) - Fake database generator.
- [faker](https://github.com/joke2k/faker) - A Python package that generates fake data.
- [mimesis](https://github.com/lk-geimfari/mimesis) - A Python library that helps you generate fake data.
- [radar](https://pypi.org/project/radar/) - Generate random datetime / time.
- [genuine-fake](https://github.com/xeroxzen/genuine-fake) - Genuine Fake means an imitation of a (usually) valuable object that is so good that it is, to all intents and purposes, identical.

## Design by Contract

- [icontract](https://github.com/Parquery/icontract) - Design-by-contract in Python3 with informative violation messages and inheritance.
- [deal](https://github.com/life4/deal) - Design by contract for Python with static checker and test generation.

## Code Coverage

- [coverage](https://pypi.org/project/coverage/) - Code coverage measurement.
- [coverage-conditional-plugin](https://github.com/wemake-services/coverage-conditional-plugin/) - Conditional coverage based on any rules you define.
- [diff_cover](https://github.com/Bachmann1234/diff_cover) - Automatically find diff lines that need test coverage.

## Static Checks

- [pyflakes](https://github.com/PyCQA/pyflakes) - A simple program which checks Python source files for errors.
- [pylint](https://github.com/PyCQA/pylint) - Pylint is a Python static code analysis tool which looks for programming errors, helps enforcing a coding standard, sniffs for code smells and offers simple refactoring suggestions.
- [pyanalyze](https://github.com/quora/pyanalyze) - A tool for programmatically detecting common mistakes in Python code, such as references to undefined variables and some categories of type mismatches.
- [bandit](https://github.com/PyCQA/bandit) - Bandit is a tool designed to find common security issues in Python code.
- [flake8](https://gitlab.com/pycqa/flake8) - flake8 is a python tool that glues together pep8, pyflakes, mccabe, and third-party plugins to check the style and quality of python code.
- [awesome-flake8-extensions](https://github.com/DmytroLitvinov/awesome-flake8-extensions) - A curated list of awesome flake8 extensions.
- [Typecheckers](https://github.com/ethanhs/python-typecheckers) - A list of Python type checkers.
- [awesome-python-typing](https://github.com/typeddjango/awesome-python-typing) - Collection of awesome Python types, stubs, plugins, and tools to work with them.

## Articles

- [30 best practices for software development and testing](https://opensource.com/article/17/5/30-best-practices-software-development-and-testing) - These software engineering rules and testing best practices might help save you time and headaches.
- [Stargirl Flowers: “My Python testing style guide”](https://blog.thea.codes/my-python-testing-style-guide/) - An attempt to catalog some practices around testing Python projects. It's not meant to be treated as dogma.
- [Test & Code: Python Testing](https://testandcode.com/) - Test & Code is a weekly podcast hosted by Brian Okken. The show covers a wide array of topics including software engineering, development, testing, Python programming, and many related topics.
- [Unit testing Python code in Jupyter notebooks](https://www.wrighters.io/unit-testing-python-code-in-jupyter-notebooks/) -  This article covers several options for unit testing Python code in a Jupyter notebook.

## Tools

- [Pynguin](https://github.com/se2p/pynguin) - Pynguin, the PYthoN General UnIt test geNerator, is a tool that allows developers to generate unit tests automatically.
- [Ponicode](https://www.ponicode.com/) - AI-powered unit testing interface for VS Code. Write, generate, modify and visualise all kinds of unit tests for JavaScript, TypeScript and Python.
- [Auger](https://github.com/laffra/auger) - Auger is a project to automatically generate unit tests for Python code.
- [ApprovalTests](https://github.com/approvals/ApprovalTests.Python) - Approvals work by comparing the test results to a golden master.
- [pytest-codegen](https://github.com/jeremyschiemann/pytest-codegen) - Pytest-codgen will statically analyze your code to create pytest function stubs.
- [teyit](https://github.com/isidentical/teyit) - A static analyzer and a refactoring tool to rewrite your unittest assertions in the right way.
- [pifpaf](https://github.com/jd/pifpaf) - Pifpaf is a suite of fixtures and a command-line tool that allows to start and stop daemons for a quick throw-away usage. This is typically useful when needing these daemons to run integration testing.
- [mock_autogen](https://github.com/pksol/mock_autogen) - A tool to auto generate the basic mocks and asserts for faster unit testing using the AAA pattern.
- [ghostwriter](https://hypothesis.readthedocs.io/en/latest/ghostwriter.html) - Writing tests with Hypothesis frees you from the tedium of deciding on and writing out specific inputs to test. Now, the hypothesis.extra.ghostwriter module can write your test functions for you too!

## Related

- [Awesome Python](https://github.com/vinta/awesome-python/blob/master/README.md#testing) - A curated list of awesome Python frameworks, libraries, software and resources.
- [Python test automation](https://github.com/atinfo/awesome-test-automation/blob/master/python-test-automation.md) - A comprehensive curated list of python test automation frameworks, tools, libraries and software to help software engineers easily bootstrap test automation on python.
