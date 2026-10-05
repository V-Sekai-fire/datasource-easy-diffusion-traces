# datasource-easy-diffusion-traces

Planner traces and generated images from sessions that drove an image-diffusion server through a hierarchical task planner.

## What it is for

Each dated directory is one session. Its planning trace is JSON-LD: the domain, the problem and the plan the planner returned, with a civil-time block where wall-clock evidence exists. Beside the trace sit the images the session kept, the probe renders that changed the plan, and the waves a human vetoed, each kind named by a filename prefix. Nothing records which model checkpoint made the images, so the workspace blocklist keeps them out of training corpora.

## Use it

The repository is data; there is nothing to build.

## Licence

The licence is not stated.
