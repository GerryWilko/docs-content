---
title: Month Input
description: A native HTML month picker.
---

::InputPageHero
---
type: "Month"
---
::

:PageToc

The `month` input uses HTML's [native month picker](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/month) to allow users to easily select a month.

::Callout
---
type: "danger"
label: "Compatibility warning"
---
Month inputs are not currently supported in FireFox or Safari.
::

## Basic example

::Example
---
name: "Month input"
file: "_content/_examples/month/month.vue"
---
::

::Callout
---
type: "warning"
label: "Formatting"
---
The internal format of all native month pickers is <code>YYYY-MM</code>. This is true
even though the format of the month displayed to the user may be different. For example, U.S. based browsers display the month format as <code>Month Name YYYY</code>.
::

## Accessibility

All FormKit inputs are designed with the following accessibility considerations in mind. Help us continually improve accessibility for all by filing accessibility issues [here](https://github.com/formkit/formkit/issues/new?assignees=&labels=%F0%9F%90%9B+bug-report%2C%E2%9B%91+Needs+triage&projects=&template=bug-report.yml): 

:AccessibilityChecks

## Props & Attributes

The `month` input has no unique props but can make use of the following universal
FormKit props.

:ReferenceTable

## Sections

:SectionKeysIntro

::FormKitInputDiagram
---
label-content: "Month you met your significant other"
prefix-icon-content: "📅"
input-icon-content: "2010-05"
suffix-content: "❤️"
help-content: "We'll divide groups based on how long you've been together."
message-content: "Month is required."
---
::

::ReferenceTable
---
type: "sectionKeys"
primary: "section-key"
---
::

