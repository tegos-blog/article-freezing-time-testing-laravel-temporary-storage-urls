# Freezing Time: Testing Laravel Temporary Storage URLs

![Freezing Time: Testing Laravel Temporary Storage URLs](assets/poster.jpg)

This article shows how **freezing time** makes tests for `Storage::temporaryUrl()` reliable and deterministic.

## What You'll Learn

* Why temporary URLs cause flaky tests due to expiration timestamps
* How to fix timestamp mismatches by freezing time
* Using `$this->freezeTime()` and Carbon helpers in Laravel tests
* Testing controllers that generate and redirect to temporary URLs

## Why It Matters

Controlling time removes execution-related inconsistencies and ensures stable assertions for time-sensitive features.

## 📎 Read Full

1. [Testing Temporary URLs in Laravel Storage](https://dev.to/tegos/testing-temporary-urls-in-laravel-storage-20p7)
   - Learn about the challenges of using `Storage::fake` with `temporaryUrl()` and explore solutions like mocking the storage driver or using Laravel's built-in mocking capabilities.
2. [Freezing Time: Testing Laravel Temporary Storage URLs](https://dev.to/tegos/freezing-time-testing-laravel-temporary-storage-urls-13n1)
   - Discover how to handle timing issues in tests by freezing time with features like `$this->freezeTime()` and `Carbon::setTestNow()`.
