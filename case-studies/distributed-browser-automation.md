# Distributed Browser Automation

## Overview

A distributed automation system built to collect and monitor operational data through browser workflows executed across remote agents and coordinated from a central server.

The project had to run reliably over long periods, recover from common browser/session failures and give operators visibility into what each run was doing.

## Problem

A single local script was not enough for the operational requirements. The automation needed centralized control, repeatable runs, concurrency rules, failure recovery and a usable administrative surface.

## My role

I worked on the automation and control flow, including:

- browser automation with Playwright;
- remote Windows execution agents;
- server-side coordination on Ubuntu;
- run scheduling and minimum-interval rules;
- concurrency control;
- session/state recovery;
- operational logging and alerts;
- PostgreSQL persistence;
- administrative panel improvements;
- validation of full collection runs.

## Architecture

### Agent layer

- Python
- Playwright
- Windows execution environment
- browser/session handling

### Control layer

- Django-based administrative/control surface
- Ubuntu server
- PostgreSQL

### Operational concerns

- run state tracking;
- retry/recovery behavior;
- concurrency constraints;
- scheduled execution windows;
- observability through logs and status data.

## Engineering decisions

- Separate the browser worker from the central control surface so collection can continue on dedicated agents.
- Enforce minimum intervals and concurrency rules at the system level rather than relying on operator discipline.
- Persist run information to make failures diagnosable after the fact.
- Treat browser/session recovery as a normal operational case instead of an exceptional one-off fix.

## Stack

`Python` · `Playwright` · `Django` · `PostgreSQL` · `Linux` · `Windows automation`

## Result

The system was able to execute full remote collection runs with centralized visibility and operational controls, replacing a fragile single-machine workflow with a more maintainable distributed setup.

## Privacy

The repository is private because the automation operates against client-specific workflows. This case study intentionally omits target-system details and sensitive operational data.
