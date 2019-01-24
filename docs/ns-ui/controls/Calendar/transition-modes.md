---
title: Calendar transition modes
page_title: RadCalendar transition modes | Progress NativeScript UI Documentation
description: A transition modes usage guide page for RadCalendar for NativeScript.
slug: calendar-transition-modes
tags: radcalendar, transition, modes, calendar
position: 6
publish: true
previous_url: controls/calendar/transition-modes
---

# Transitions: Overview
- {% typedoc_link classes:RadCalendar %} supports different animations when switching between months, weeks or years. These are also called *transitions*. Defining a transition is done by setting the - {% typedoc_link classes:RadCalendar,member:transitionMode %} property to one of the values enlisted by the `CalendarTransitionModes` enum.

## Available transition modes:
- {% typedoc_link modules:CalendarTransitionMode,member:None %} - Transitions with gestures are disabled and no animation is applied when transitioning programmatically. Available in iOS and Android.
- {% typedoc_link modules:CalendarTransitionMode,member:Slide %} - Slide animation is applied when transitioning between views in *RadCalendar*. Available in iOS and Android.
- {% typedoc_link modules:CalendarTransitionMode,member:Stack %} -  Stack animation is applied when transitioning between views in *RadCalendar*. Available in iOS and Android.
- {% typedoc_link modules:CalendarTransitionMode,member:Flip %} -  Flip animation is applied when transitioning between views in *RadCalendar*. Available only in iOS.
- {% typedoc_link modules:CalendarTransitionMode,member:Fold %} -  Fold animation is applied when transitioning between views in *RadCalendar*. Available only in iOS.
- {% typedoc_link modules:CalendarTransitionMode,member:Float %} -  Float animation is applied when transitioning between views in *RadCalendar*. Available only in iOS.
- {% typedoc_link modules:CalendarTransitionMode,member:Rotate %} -  Rotate animation is applied when transitioning between views in *RadCalendar*. Available only in iOS.
- {% typedoc_link modules:CalendarTransitionMode,member:Plain %} -  Allows non inertial scrolling between views in *RadCalendar*. Available only in Android.
- {% typedoc_link modules:CalendarTransitionMode,member:Free %} -  Allows inertial scrolling between views in *RadCalendar*. Available only in Android.
- {% typedoc_link modules:CalendarTransitionMode,member:Combo %} -  Applies inertial slide animation when transitioning between views in *RadCalendar*. Available only in Android.
- {% typedoc_link modules:CalendarTransitionMode,member:Overlap %} -  Views overlap when transitioning in *RadCalendar*. Available only in Android.

## References
Want to see this scenario in action?
Check our SDK examples repo on GitHub. You will find this and many other practical examples with NativeScript UI.

* [Transition Modes Example](https://github.com/telerik/nativescript-ui-samples/tree/master/calendar/app/calendar/transition-modes)
