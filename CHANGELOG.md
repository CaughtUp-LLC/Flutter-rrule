# Changelog

All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

<!-- Template:
## NEW · 2021-xx-xx
### ⚠ BREAKING CHANGES
### 🎉 New Features
### ⚡ Changes
### 🐛 Bug Fixes
### 📜 Documentation updates
### 🏗 Refactoring
### 📦 Build & CI
-->

## v0.2.1 · 2021-04-26

### 🐛 Bug Fixes
- disallow invalid recurrence rule field combinations ([2707922](https://github.com/JonasWanke/rrule/commit/2707922bb6b8860c5118be8c896f680e075dd2e5)), closes: [#19](https://github.com/JonasWanke/rrule/issues/19)

## 0.2.0 · 2021-03-26

### ⚠ BREAKING CHANGES

- migrate to null-safety
- Dates and DateTimes no longer use [<kbd>time_machine</kbd>](https://pub.dev/packages/time_machine), but `DateTime` instead.
  All provided `DateTime`s must be in UTC.
- remove `recurrenceRule.weekStart` (Monday is now used everywhere) and `recurrenceRule.weekYearRule`
- remove `RecurrenceSet` as its logic isn't implemented yet


## 0.1.3 · 2021-01-27

### 🎉 New Features
- add `clearUntil`/`clearCount`/`clearInterval` to `recurrenceRule.copyWith(…)`, closes: [#17](https://github.com/JonasWanke/rrule/issues/17)


## 0.1.2 · 2020-11-24

### 🐛 Bug Fixes
- hide new conflicting extension from [<kbd>collection</kbd>](https://pub.dev/packages/collection), closes: [#14](https://github.com/JonasWanke/rrule/issues/14)

### 🎉 New Features
- add `RecurrenceRule.copyWith(…)`


## 0.1.1 · 2020-07-09

### 🎉 New Features
- add `RecurrenceRule.toText()` for conversion to a human-readable string ([#7](https://github.com/JonasWanke/rrule/pull/7)), closes: [#5](https://github.com/JonasWanke/rrule/issues/5)


## 0.1.0 · 2020-05-26

Initial release 🎉
