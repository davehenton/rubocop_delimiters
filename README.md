From terminal:

```
bundle install

$ rubocop test_delimiters.rb

Inspecting 1 file
.

1 file inspected, no offenses detected

$ codeclimate analyze test_delimiters.rb

Starting analysis
Running brakeman: Done!
Running bundler-audit: Done!
Running csslint: Done!
Running duplication: Done!
Running eslint: Done!
Running fixme: Done!
Running rubocop: Done!

== test_delimiters.rb (2 issues) ==
1: `%i`-literals should be delimited by `(` and `)`. [rubocop]
2: `%w`-literals should be delimited by `(` and `)`. [rubocop]

Analysis complete! Found 2 issues.
```
