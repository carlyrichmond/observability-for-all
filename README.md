# Observability for All!

Slides and Resources for several holistic observability talks, given at several conferences including:

1. [Observability for All! @ Devoxx UK 2025](https://www.devoxx.co.uk/talk/?id=13326)
2. [Observability-is-not-just-for-Backend! @ JNation 2025](https://jnation.pt/)
3. [Berlin Buzzwords](https://2025.berlinbuzzwords.de/)

## Slides

Slides for each conference, including sample screenshots from the live demos, are available in PDF [here](./slides).

## Example repos

Check out the below code examples covered as part of the talk:

1. [OTel Record Store](https://github.com/carlyrichmond/otel-record-store): a sample Java and Svelte + TS full stack web application instrumented with [OpenTelemetry JavaScript SDK](https://opentelemetry.io/docs/languages/js/) (specifically the [Web Provider for Browser](https://opentelemetry.io/docs/languages/js/getting-started/browser/)), [Elastic RUM](https://www.elastic.co/docs/solutions/observability/apm/real-user-monitoring-rum) and [Web Vitals JavaScript library](https://www.npmjs.com/package/web-vitals).
2. [Synthetics Replicatr](https://github.com/carlyrichmond/synthetics-replicator): an example Svelte application showcasing project based browser monitors using [Elastic Synthetics](https://www.elastic.co/docs/solutions/observability/synthetics) and [Playwright JS](https://playwright.dev/).

## Useful Resources

### Real User Monitoring

1. [Elastic User Experience Overview](https://www.elastic.co/guide/en/observability/current/user-experience.html)
3. [Elastic RUM Agent](https://www.elastic.co/guide/en/apm/agent/rum-js/current/index.html)
4. [Google Core Web Vitals](https://web.dev/explore/learn-core-web-vitals)

### OpenTelemetry

1. [Open Telemetry](https://opentelemetry.io/)
2. [OpenTelemetry Web SDK](https://opentelemetry.io/docs/languages/js/getting-started/browser/)
3. [OpenTelemetry Java SDK](https://opentelemetry.io/docs/languages/java/getting-started/)
4. [GitHub: EDOT](https://github.com/elastic/opentelemetry)
5. [Revealing unknowns in your tracing data with inferred spans in OpenTelemetry | Elastic Observability Labs](https://www.elastic.co/observability-labs/blog/tracing-data-inferred-spans-opentelemetry)
6. [Announcing GA of Elastic distribution of the OpenTelemetry Java Agent | Elastic Observability Labs](https://www.elastic.co/observability-labs/blog/elastic-distribution-opentelemetry-java-agent)

### Synthetic Monitoring

1. [GitHub: Synthetics Replicatr](https://github.com/carlyrichmond/synthetics-replicator)
1. [Elastic Blog: Synthetic Monitoring & E2E Testing- Two Sides of the Same Coin](https://ela.st/synthetics-replicator-blog)
2. [Elastic Advent Calendar: Authentication with Synthetic Monitoring](https://ela.st/synthetics-auth-advent)
3. [USENIX :login; magazine: Synthetic Monitoring & E2E Testing- Two Sides of the Same Coin](https://www.usenix.org/publications/loginonline/synthetic-monitoring-e2e-testing-two-sides-same-coin)
4. [Semaphore Blog: Synthetic Monitoring](https://semaphoreci.com/blog/synthetic-monitoring)