---
title: 'Managing resource conflicts'
taxonomy:
    category:
        - docs
visible: true
---

The resource accepts appointments even if there are conflicts unless either the number of conflicts reaches the maximum allowed or the maximum percentage of conflicts allowed is reached.  If you try to schedule an appointment with the resource and the number of times the resource is unavailable exceeds the rule, the entire appointment is rejected. If you set both fields, the resource declines appointments whenever either of the conditions is met.

For example, if the maximum allowed conflicts is 3 and you try to schedule an appointment with a resource and more than 3 conflicting dates are found, the entire recurring appointment is rejected.

When a resource is invited to a single-instance appointment, if the resource scheduling policy is configured to auto decline, the single instance is always declined. The conflict rules do not apply.