---
title: Status
---

These are the latest results of the Validated Patterns CI test runs.

**NOTE:** [March 24th] Some jobs are currently failing prior to pattern deployment due to [timeouts while deploying OpenShift](https://issues.redhat.com/browse/OCPBUGS-10439).

**NOTE:** [March 29th] Azure jobs are failing due to a service outage.

Subsequent versions of this page will differentiate between failures prior to pattern installation, and those in the pattern tests.

  <script type="text/javascript" src="/js/dashboard.js"></script>

  <div class='ci-results'>
    <p id="ci-dataset"> </p>
    <script>
      obtainBadges({ 'target':'ci-dataset' });
    </script>
  </div>
