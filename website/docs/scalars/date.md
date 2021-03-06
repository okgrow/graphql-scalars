---
id: date
title: Date
sidebar_label: Date
---

A date string, such as 2007-12-03, compliant with the `full-date` format outlined in section 5.6 of the [RFC 3339](./rfc3339.txt) profile of the ISO 8601 standard for representation of dates and times using the Gregorian calendar.

This scalar is a description of the date, as used for birthdays for example. It cannot represent an instant on the time-line.

**Result Coercion**

Javascript Date instances are coerced to an RFC 3339 compliant date string. Invalid Date instances raise a field error.

**Input Coercion**

When expected as an input type, only RFC 3339 compliant date strings are accepted. All other input values raise a query error indicating an incorrect type.

