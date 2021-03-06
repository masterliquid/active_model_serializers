## How can I help?

Everyone is encouraged to open issues that are affecting you: bugs, ideas, performance problems – everything helps!

The first place to start is by looking at our [GitHub Issues](https://github.com/rails-api/active_model_serializers/issues).

The vast majority of development is happening under the `master` branch, currently slated for release as `0.10.x`. This is where we would suggest you start.

Fixing bugs is extraordinarily helpful and requires the least familiarity with AMS. Look for issues labeled [**Needs Bug Verification**](https://github.com/rails-api/active_model_serializers/labels/Needs%20Bug%20Verification) and [**Bug**](https://github.com/rails-api/active_model_serializers/labels/bug).

We are also actively working to identify tasks under the label [**Good for New Contributors**](https://github.com/rails-api/active_model_serializers/labels/Good%20for%20New%20Contributors). Some bugs are expressly not good for new contributors, so don't expect 100% overlap between the two.

If you want to work on new feature development, look for the label [**Feature**](https://github.com/rails-api/active_model_serializers/labels/Feature).

We are also encouraging comments to substantial changes (larger than bugfixes and simple features) under an "RFC" (Request for Comments) process before we start active development. Look for the [**RFC**](https://github.com/rails-api/active_model_serializers/labels/RFC) label.

## Issue Labeling

AMS uses a subset of [StandardIssueLabels](https://github.com/wagenet/StandardIssueLabels) for Github Issues. You can [see our labels here](https://github.com/rails-api/active_model_serializers/labels).

## Contributing

1. Fork it ( https://github.com/rails-api/active_model_serializers/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Write tests for your feature, or regression tests highlighting a bug
4. Write the feature itself, or fix your bug
5. Commit your changes (`git commit -am 'Add some feature'`)
6. Push to the branch (`git push origin my-new-feature`)
7. Create a new Pull Request
8. Update [CHANGELOG.md](https://github.com/rails-api/active_model_serializers/blob/master/CHANGELOG.md)
with a brief description of any breaking changes, fixes, features, or
miscellaneous changes under the proper version section.
9. Iterate on feedback given by the community (fix syntax, modify bits of code, add
tests), pushing the new commits to the PR each time

Remember to squash your commits and rebase off `master`.

### Running tests

#### Running with Rake

The easiest way to run the unit tests is through Rake. The default task runs
the entire test suite for all classes. For more information, checkout the
full array of rake tasks with "rake -T"

Rake can be found at http://docs.seattlerb.org/rake/.

To run a single test suite

   rake test TEST=path/to/test.rb

which can be further narrowed down to one test:

   rake test TEST=path/to/test.rb TESTOPTS="--name=test_something"
