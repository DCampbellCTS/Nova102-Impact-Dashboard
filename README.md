# Nova102 Impact Dashboard

Static, self-contained HTML dashboard (Project Nova / NOVA102 BIM coordination).
Tracks daily Revit model change volume, the current field punch-list status, and
open WP Register gaps, so the construction team can see the impact of the changes
they're asking the BIM team to make.

The page is a single index.html snapshot rebuilt from the Revit Daily Change Log
and the latest field punch-list review each time it's updated -- there is no
backend and no live data connection, so it reflects whatever was baked in at
last publish.

To publish an update: replace index.html with a new build and push to main --
once this repo is linked to a Netlify site for continuous deployment, that push
triggers the live redeploy automatically.
