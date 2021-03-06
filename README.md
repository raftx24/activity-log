# Activity Log

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/0f8e148c3247407cab601e3460967a2e)](https://www.codacy.com/app/laravel-enso/activity-log?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=laravel-enso/activity-log&amp;utm_campaign=Badge_Grade)
[![StyleCI](https://github.styleci.io/repos/144374422/shield?branch=master)](https://github.styleci.io/repos/144374422)
[![License](https://poser.pugx.org/laravel-enso/activity-log/license)](https://packagist.org/packages/laravel-enso/activity-log)
[![Total Downloads](https://poser.pugx.org/laravel-enso/activity-log/downloads)](https://packagist.org/packages/laravel-enso/activity-log)
[![Latest Stable Version](https://poser.pugx.org/laravel-enso/activity-log/version)](https://packagist.org/packages/laravel-enso/activity-log)

Activity logger dependency for [Laravel Enso](https://laravel-enso.com).

This package works exclusively within the [Enso](https://github.com/laravel-enso/Enso) ecosystem.

The front end assets that utilize this api are present in the [ui](https://github.com/enso-ui/ui) package.

For live examples and demos, you may visit [laravel-enso.com](https://www.laravel-enso.com)

[![Watch the demo](https://laravel-enso.github.io/activity-log/screenshots/bulma_051_thumb.png)](https://laravel-enso.github.io/activity-log/videos/bulma_activity_log.mp4)

<sup>click on the photo to view a short demo in compatible browsers</sup>

## Installation

Comes pre-installed in Enso.

## Features

- friendly interface for viewing user activity in the application
- available by default only to users with the Administrator role
- events are presented in an useful manner
- allows the filtering of data depending on a date interval, the roles of the users, the users or the type of events
- supports create, update, delete and custom event types
- the models whose changes need to represented, need only to use the `LogsActivity` trait. Optionally, 
you may set additional configuration attributes on the model to further fine tune the way data is logged/represented
- the logger will not attempt to persist data when there is no authenticated user - this avoids issues when 
using seeder / playing in tinker, etc.

### Configuration & Usage

Be sure to check out the full documentation for this package available at [docs.laravel-enso.com](https://docs.laravel-enso.com/backend/activity-log.html)

### Contributions

are welcome. Pull requests are great, but issues are good too.

### License

This package is released under the MIT license.
