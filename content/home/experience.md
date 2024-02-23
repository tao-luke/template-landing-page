---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
    # description: |2-
    #     Responsibilities include:
        
    #     * Analysing
    #     * Modelling
    #     * Deploying
experience:
  - title: Autopilot Core Intern
    company: Tesla
    company_url: 'https://www.tesla.com/'
    company_logo: Tesla1
    location: Palo Alto
    date_start: '2024-01-01'
    date_end: 'Present'
    description: |1-
        * Develop features on SoCs and kernel to enable self-driving vehicles
  - title: Vehicle Simulation Intern
    company: Tesla
    company_url: 'https://www.tesla.com/'
    company_logo: Tesla
    location: Palo Alto
    date_start: '2023-01-17'
    date_end: '2023-04-21'
    description: |1-
        * Engineered time series based assertion algorithms for state-of-the-art SIL vehicle simulation using Rust
  - title: Firmware Engineer Intern
    company: Sibros
    company_url: 'https://www.sibros.tech/'
    company_logo: Sibros
    location: San Jose
    date_start: '2022-09-07'
    date_end: '2022-12-23'
    description: |1-
        * Built RTOS logging features with 100% branch and line unit-test coverage using C, Unity, and Bazel. One of which was a heuristic-based MQTT packet transmission protocol, increasing MTU utilization by at least 204% when averaged over 10,000 independent executions.
  - title: Software Engineer Intern
    company: Huawei Canada
    company_url: 'https://www.huawei.com/ca/'
    company_logo: huawei_icon
    location: Toronto
    date_start: '2021-09-07'
    date_end: '2021-12-24'
    description: |1-
        * Researched state-of-the-art cryptographical methodologies from NIST and implemented various secure, chip-compatible data authentication frameworks integrated in MbedTLS using OpenSSL and C
        
  - title: Systems Engineer Intern
    company: Kaleidescape
    company_url: 'https://www.kaleidescape.com/'
    company_logo: kalei_icon
    location: Toronto
    date_start: '2021-04-01'
    date_end: '2021-09-01'
    description: |1-
        * Developed various system and user-facing features, including a concurrent movie search system in C++11 that provides fast and accessible content navigation on an industry-leading cinema playback system

  - title: Full Stack Developer Intern
    company: Digital Extremes
    company_url: 'https://www.digitalextremes.com/'
    company_logo: digi_icon
    location: Waterloo
    date_start: '2020-05-09'
    date_end: '2020-09-01'
    description: |1-
        * Ironed out the main server data pipeline in MERN stack, using JS and Python, by creating multiple Google Cloud based web scripts to automate news parsing and content deployment, eliminating manual labor throttles in the engineering cycle
design:
  columns: '2'
  view: '1'
---
