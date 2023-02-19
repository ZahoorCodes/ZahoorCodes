[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://GitHub.com/xahurs/xahurs)
name: 📅 Isometric commit calendar
category: github
description: |
  This plugin displays an isometric view of a user commit calendar along with a few additional statistics like current streak and average number of commit per day.
examples:
  +full year calendar: https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.isocalendar.fullyear.svg
  half year calendar: https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.isocalendar.svg
index: 0
supports:
  - user
scopes:
  - public_access
inputs:

  plugin_isocalendar:
    description: |
      Enable isocalendar plugin
    type: boolean
    default: no

  plugin_isocalendar_duration:
    description: |
      Time range

      - `half-year`: 180 days
      - `full-year`: 1 year
    type: string
    default: half-year
    values:
      - half-year
      - full-year
