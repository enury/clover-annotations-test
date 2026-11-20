# Clover annotations test

A live example of [Clover](https://clover.iiif.library.northwestern.edu)'s `<clover-viewer>` web component showing annotations exported from liiive.now beside a Yale Peabody Museum Manifest.

- Page: [`index.html`](index.html), live at https://mathewjordan.github.io/clover-annotations-test/
- Annotations: [`assets/annotations/test-annotations.json`](assets/annotations/test-annotations.json), an AnnotationPage with a `FragmentSelector` rectangle and an `SvgSelector` ellipse

```html
<script src="https://cdn.jsdelivr.net/npm/@nulib/clover/dist/web-components/index.umd.js"></script>

<clover-viewer
  iiif-content="https://manifests.collections.yale.edu/ypm/nat/6299"
  template="default"
  items="grid"
  header="false"
  annotations="assets/annotations/test-annotations.json"
>
</clover-viewer>
```
