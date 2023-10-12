---
title: Directories
layout: mirador
---
  <script type="text/javascript">
    var mirador = Mirador.viewer({
      id: "viewer",
      catalog: [
         { manifestId: "/iiif/ark:/12148/bpt6k62929887/manifest.json"},
       ],
      window: {
        sideBarPanel: "annotations",
        sideBarOpen: true,
        highlightAllAnnotations: true,
        workspaceControlPanel: {
          enabled: false,
        },
      },
      windows: [{
        loadedManifest: "/iiif/ark:/12148/bpt6k62929887/manifest.json",
        view: 'single',
        thumbnailNavigationPosition: 'far-bottom'
      }]
    });
  </script>
