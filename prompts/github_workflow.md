# Creating a github workflow

Create a new github workflow or update existing one as follows.

Read the file //GEMINI.md if it exists.

Be sure to read the file //README.md if it exists.

* Add a github action which runs `bazel build //...`.

* The action must run on every pull request into `main`, on every merge into
  main, as well as once a week at any time on `main` branch itself.

* Add a rule that allows caching build artifacts.

* Ensure that the caching is keyed so that the cache expires in 24 hours.
