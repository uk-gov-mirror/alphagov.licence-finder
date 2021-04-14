# Licence Finder

Licence Finder is a public facing app that provides the pages that follow https://www.gov.uk/licence-finder (which is served by [frontend][]), specifically starting at https://www.gov.uk/licence-finder/sectors.

[frontend]: https://github.com/alphagov/frontend

## Technical documentation

This is a Ruby on Rails app, and should follow [our Rails app conventions](https://docs.publishing.service.gov.uk/manual/conventions-for-rails-applications.html).

You can use the [GOV.UK Docker environment](https://github.com/alphagov/govuk-docker) to run the application and its tests with all the necessary dependencies. Follow [the usage instructions](https://github.com/alphagov/govuk-docker#usage) to get started.

**Use GOV.UK Docker to run any commands that follow.**

## Before running the app

The first time you run this application in development you will want to populate the search index. This can be done with the following command:

```
bundle exec rake search:index
```

### Running the test suite

```
bundle exec rake
```

## Licence

[MIT License](LICENCE)
