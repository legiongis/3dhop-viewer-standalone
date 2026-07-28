# standalone 3DHOP viewer

This repo is a basic repackaging of the `minimal/3DHOP_all_tools.html` example in https://github.com/cnr-isti-vclab/3DHOP.
It has been modified so that remote 3d models can be passed to the viewer through a
URL parameter, and it is published here through Github pages.

## Example

https://legiongis.github.io/standalone-3dhop-viewer/?model=https://lcai-assets.s3.us-gov-west-1.amazonaws.com/models/LN4232-F1-P1-Top.nxs

## Purpose

The goal is to put this 3DHOP viewer in an iframe while supplying remote data to it.

```
<iframe height="600" width="100%" src="https://legiongis.github.io/standalone-3dhop-viewer/?model=https://lcai-assets.s3.us-gov-west-1.amazonaws.com/models/LN4232-F1-P1-Top.nxs"></iframe>
```
