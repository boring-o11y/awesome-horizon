# Awesome Horizon [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome Laravel Horizon-related resources

- [Horizon official web site](https://laravel.com/docs/horizon)
- [Skyline](https://boring-observability.dev/skyline) - A commercial drop-in replacement with better visibility and operational controls.

## Blog posts
- [A Series of Unfortunate Jobs](https://oussama-mater.tech/laravel-queue-gotchas/) - Laravel queue gotchas
- [Extending the Horizon Dashboard: Adding a UI to a Compiled Vue Bundle](https://boring-observability.dev/blog/extending-the-horizon-dashboard)
- [Laravel Background Jobs: 12 Best Practices for Production Queues](https://boring-observability.dev/blog/laravel-background-jobs-best-practices)
- [Laravel Cloud Managed Queues vs Horizon: What You Give Up and What You Get](https://hafiz.dev/blog/laravel-cloud-managed-queues-vs-horizon)
- [Laravel Horizon Alerting: What Horizon Sends on Its Own and What Prometheus Adds](https://boring-observability.dev/blog/laravel-horizon-alerting)
- [Laravel Horizon production patterns I trust before queues go quiet](https://maniruzzaman.me/article/laravel-horizon-production-patterns-i-trust/)
- [Laravel Horizon Queue Balancing: Idle Workers vs. Starved Queues](https://boring-observability.dev/blog/laravel-horizon-queue-balancing-tradeoffs)
- [Laravel Interruptible Jobs: interrupted(), SIGALRM and horizon:terminate](https://boring-observability.dev/blog/laravel-interruptible-jobs)
- [Laravel Job timeout vs retry_after: The Ordering Rule Nothing Enforces](https://boring-observability.dev/blog/laravel-queue-timeout-retry-after)
- [Laravel ShouldBeUnique: What Breaks Under Real Traffic](https://boring-observability.dev/blog/laravel-job-uniqueness-controls)
- [Logarithmic auto-scaling for Laravel Horizon](https://gummibeer.dev/blog/2026/logarithmic-auto-scaling-laravel-horizon)
- [Rate-Limited APIs and Laravel Queues: One Request at a Time, Without Starving the Rest](https://boring-observability.dev/blog/laravel-queue-rate-limiting-concurrency)
- [Scaling Laravel queues in production: Horizon, Redis, and multi-server workers](https://richdynamix.com/articles/scaling-laravel-queues-production-guide)


## Videos
- [Laravel Queues: 11 Must-Know Advanced Tips](https://www.youtube.com/watch?v=PeDiswbjLq8)

## Queue drivers
- [kafka-queue](https://github.com/laravel-tool/kafka-queue) - Laravel Kafka Queue connection with Horizon support.
- [laravel-queue-rabbitmq](https://github.com/vyuldashev/laravel-queue-rabbitmq) - RabbitMQ driver for Laravel Queue with Horizon support.
- [horizon-database](https://github.com/pocketarc/horizon-database) - Run Laravel Horizon on a relational database instead of Redis.

## Dashboards and dashboard improvements
- [deck](https://github.com/getdeckapp/deck) - Job-class observability and safe cancellation for Laravel apps running Horizon.
- [horizon-delayed-jobs](https://github.com/boring-o11y/horizon-delayed-jobs) - Delayed jobs view (scheduled / retries) for Laravel Horizon.
- [horizon-worker-stats](https://github.com/boring-o11y/horizon-worker-stats) - Display memory and CPU stats of the workers.
- [Horizon new dawn](https://github.com/nckrtl/horizon-new-dawn) - A React and Inertia interface for Laravel Horizon.
- [zenith](https://github.com/devaction-labs/zenith) - The operator console and orchestration layer for Laravel Horizon, built with React and Inertia.
- [Horizon hub](https://github.com/enegalan/horizonhub) - Centralized dashboard for monitoring Laravel Horizon jobs across multiple services.
- [horizonflow](https://github.com/nsumbadze/horizonflow)) - An unofficial Laravel Horizon fork with queue-flow visualization and code-driven dashboard configuration
- [laravel-queue-insights](https://github.com/SanderMuller/laravel-queue-insights) - Self-hosted, driver-agnostic queue observability for Laravel.
- [laravel-queue-metrics](https://github.com/cboxdk/laravel-queue-metrics) - Production-ready Laravel queue monitoring with metrics, analytics, and insights.
- [laravel-horizon-running-jobs](https://github.com/ashiqfardus/laravel-horizon-running-jobs) - Monitor currently running jobs in Laravel Horizon.
- [laravel-horizon-job-output](https://github.com/knobik/laravel-horizon-job-output) - Give a queued job the same output API an Artisan command has, and watch it live on the Horizon job details page.
- [laravel-horizon-tag-search-in-pending-and-completed-jobs](https://github.com/mvd81/laravel-horizon-tag-search-in-pending-and-completed-jobs) - Allows searching in pending and completed jobs.
- [horizon-ui](https://github.com/negoziator/horizon-ui) - Fully-featured Horizon dashboard
- [horizon-config-tags](https://github.com/mustorze/horizon-config-tags) - Allows to configure monitored tags in the code.
- [Grafana dashboard for Horizon](https://grafana.com/grafana/dashboards/11034-laravel-horizon/)
- [eloquage/filament-horizon](https://github.com/eloquage/filament-horizon) - Horizon queue monitoring pages and widgets for Filament

## Horizon alternatives
- [laravel-zenith](https://github.com/smwks/laravel-zenith) - Laravel Horizon for database-backed queues — real-time dashboard and worker management for the database queue driver.
- [JobWarden](https://github.com/kpconnell/laravel-jobwarden) - A database-backed alternative to Horizon.
- [Moox jobs](https://github.com/mooxphp/jobs) - Filament plugin for managing job queues, failed jobs and batches.
- [station](https://github.com/ojbaeza/station) - A Laravel Horizon alternative with RabbitMQ support, multi-driver architecture, advanced job recovery capabilities, and a modern Vue 3 dashboard.
- [periscope](https://github.com/maherelgamil/periscope) - Universal queue monitor and manage for Laravel — a driver-agnostic alternative to Horizon. Redis, database, SQS, Beanstalkd.
- [Laravel Queue Monitor](https://github.com/romanzipp/Laravel-Queue-Monitor) - Monitoring Laravel Jobs with your Database

## AI 
- [laravel-horizon-advanced](https://github.com/neuraliq/laravel-horizon-advanced) - AI skill for configuring jobs and queues.
- [laravel-queues-skill](https://github.com/ludoguenet/laravel-queues-skill) - Production-grade Laravel queue engineering guidance for AI coding agents.

## Other  
- [laravel-balanced-queue](https://github.com/YanGusik/laravel-balanced-queue) - A Laravel package for queue management with load balancing between partitions (user groups). Perfect for scenarios where you need fair job distribution and concurrency control per user/tenant.
- [laravel-horizon-cluster](https://github.com/daison12006013/laravel-horizon-cluster) - Laravel Horizon - Redis Cluster Support.
- [horizon-cluster-scaling](https://github.com/deniscsz/horizon-cluster-scaling) - Makes Laravel Horizon cluster-aware by dynamically adjusting minProcesses and maxProcesses based on the number of active master supervisors across your server cluster.
- [laravel-dynamic-horizon](https://github.com/smskin/laravel-dynamic-horizon) - Dynamic supervisors(consumers) & queues for the laravel horizon.
- [horizon-telemetry](https://github.com/worksome/horizon-telemetry) - An Opentelemetry instrumentation for Laravel Horizon.
- [horizon-prometheus-exporter](https://github.com/boring-o11y/horizon-prometheus-exporter) - Per job prometheus exporter for Laravel Horizon.
- [queue-prefork](https://github.com/tevkert/queue-prefork) - Cut the memory of Laravel queue workers by up to 80 %: queue:work and Horizon workers fork from one template that shares compiled code.
- [laravel-unique-job-locks](https://github.com/MohannadElemary/laravel-unique-job-locks) - Find out why a ShouldBeUnique job won't dispatch: list and explain the unique-job locks held in your Laravel Redis cache store.

## Discontinued projects
- [horizon-extended-dashboard](https://github.com/VincentBean/horizon-extended-dashboard) - An extended dashboard for Laravel Horizon written using Livewire.
