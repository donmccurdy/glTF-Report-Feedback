# glTF-Report-Feedback

Issues, feedback, and feature requests for the https://gltf.report website.

## FAQ

> Which glTF extensions are supported?

The website can open, edit, and export all [extensions supported by glTF-Transform](https://gltf-transform.donmccurdy.com/extensions.html). Some of these extensions will not be shown in the 3D viewport, however, based on [current three.js limitations](https://threejs.org/docs/#examples/en/loaders/GLTFLoader).

> Does glTF Report upload or save my models somewhere?

No. glTF/GLB files opened on the website are not uploaded to a server, and remain on your computer while viewing and editing. The website may collect anonymized analytics (e.g. which glTF extensions are most common?) to improve the glTF ecosystem.

## Source Code

While the source code for the website is not currently open source, its more interesting components already are:

- [donmccurdy/glTF-Transform](https://github.com/donmccurdy/glTF-Transform): glTF JavaScript SDK used for edits, analysis, and optimization.
- [donmccurdy/glTF-Transform-Render](https://github.com/donmccurdy/glTF-Transform-Render/): Experimental rendering API for fast edit/refresh workflows.
- [google/model-viewer](https://github.com/google/model-viewer): Stable glTF viewer that is fast, simple, and lightweight.
- [mrdoob/three.js](https://github.com/mrdoob/three.js/): JavaScript 3D library, used by model-viewer and `@gltf-transform/render`.
- [microsoft/monaco-editor](https://github.com/Microsoft/monaco-editor): Code editor powering VS Code.
- [sveltejs/svelte](https://github.com/sveltejs/svelte): Lightweight, reactive web framework.
- [cocopon/tweakpane](https://github.com/cocopon/tweakpane): Compact GUI for editing and monitoring.

Features and bug fixes in the projects above will eventually make their way to the glTF Report website. If you're interested in the website's source code for a collaboration, commercial projects, or other purposes, reach out to [contact@donmccurdy.com](mailto:contact@donmccurdy.com) to discuss licensing options.
