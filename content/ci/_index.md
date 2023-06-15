---
title: Status
---

These are the latest results of the Validated Patterns CI test runs.

See pipeline sets: [ [All](/ci/?sets=all) ], [ [GA (default)](/ci/?sets=GA) ], [ [Pre-release](/ci/?sets=early) ]

<p class='ci-status'><b>NOTE:</b> [May 18th] Ansible Edge is known to be broken on OpenShift 4.13 and later due to an unavailable dependency.</p>
<p class='ci-status'><b>NOTE:</b> [June 1st] Some jobs are failing due to a timing issue between Vault and ESO. Watch this space.</p>

  <script type="text/javascript" src="/js/dashboard.js"></script>


  <div class='ci-results'>
    <p id="ci-dataset"> </p>
    <script>
      obtainBadges({ 'target':'ci-dataset' });
    </script>
  </div>
