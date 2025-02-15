![karafka logo](https://raw.githubusercontent.com/karafka/misc/master/logo/karafka_logotype_transparent2.png)

[![Build Status](https://github.com/karafka/karafka/actions/workflows/ci.yml/badge.svg)](https://github.com/karafka/karafka/actions/workflows/ci.yml)
[![Gem Version](https://badge.fury.io/rb/karafka.svg)](http://badge.fury.io/rb/karafka)
[![Join the chat at https://slack.karafka.io](https://raw.githubusercontent.com/karafka/misc/master/slack.svg)](https://slack.karafka.io)

Karafka is a Ruby and Rails efficient Kafka processing framework.

Karafka allows you to capture everything that happens in your systems in large scale, without having to focus on things that are not your business domain. 

## Why Choose Karafka?

Karafka is a Ruby and Rails multi-threaded efficient Kafka processing framework that:

- Has a built-in [Web UI](https://karafka.io/docs/Web-UI-Features/) providing a convenient way to monitor and manage Karafka-based applications.
- Supports parallel processing in [multiple threads](https://karafka.io/docs/Concurrency-and-multithreading) (also for a [single topic partition](https://karafka.io/docs/Pro-Virtual-Partitions) work) and [processes](https://karafka.io/docs/Swarm-Multi-Process).
- [Automatically integrates](https://karafka.io/docs/Integrating-with-Ruby-on-Rails-and-other-frameworks#integrating-with-ruby-on-rails) with Ruby on Rails
- Has [ActiveJob backend](https://karafka.io/docs/Active-Job) support (including [ordered jobs](https://karafka.io/docs/Pro-Enhanced-Active-Job#ordered-jobs))
- Has a seamless [Dead Letter Queue](https://karafka.io/docs/Dead-Letter-Queue/) functionality built-in
- Supports in-development [code reloading](https://karafka.io/docs/Auto-reload-of-code-changes-in-development)
- Is powered by [librdkafka](https://github.com/edenhill/librdkafka) (the Apache Kafka C/C++ client library)
- Has an out-of the box [AppSignal](https://karafka.io/docs/Monitoring-and-Logging/#appsignal-metrics-and-error-tracking) and [StatsD/DataDog](https://karafka.io/docs/Monitoring-and-Logging/#datadog-and-statsd-integration) monitoring with dashboard templates.

## Getting started

![karafka web ui](https://raw.githubusercontent.com/karafka/misc/master/printscreens/web-ui.png)

If you're entirely new to the subject, you can start with our "Kafka on Rails" articles series, which will get you up and running with the terminology and basic ideas behind using Kafka:

- [Kafka on Rails: Using Kafka with Ruby on Rails – Part 1 – Kafka basics and its advantages](https://mensfeld.pl/2017/11/kafka-on-rails-using-kafka-with-ruby-on-rails-part-1-kafka-basics-and-its-advantages/)
- [Kafka on Rails: Using Kafka with Ruby on Rails – Part 2 – Getting started with Rails and Kafka](https://mensfeld.pl/2018/01/kafka-on-rails-using-kafka-with-ruby-on-rails-part-2-getting-started-with-ruby-and-kafka/)

If you want to get started with Kafka and Karafka as fast as possible, then the best idea is to visit our [Getting started](https://karafka.io/docs/Getting-Started) guides and the [example apps repository](https://github.com/karafka/example-apps).

We also maintain many [integration specs](https://github.com/karafka/karafka/tree/master/spec/integrations) illustrating various use-cases and features of the framework.

## Want to Upgrade? LGPL is not for you? Want to help?

I also sell Karafka Pro subscriptions. It includes a commercial-friendly license, priority support, architecture consultations, enhanced Web UI, and high throughput data processing-related features (virtual partitions, long-running jobs, and more).

Help me provide high-quality open-source software. Please see the Karafka [homepage](https://karafka.io/#become-pro) for more details.

## Support

Karafka has [Wiki pages](https://karafka.io/docs) for almost everything and a pretty decent [FAQ](https://karafka.io/docs/FAQ). It covers the installation, setup, and deployment, along with other useful details on how to run Karafka.

If you have questions about using Karafka, feel free to join our [Slack](https://slack.karafka.io) channel.

Karafka has [priority support](https://karafka.io/docs/Pro-Support) for technical and architectural questions that is part of the Karafka Pro subscription.
