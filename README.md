# glTF-Report-Feedback

✨ **UPDATE:** Feedback for glTF Report (https://gltf.report) has been moved to https://gltf-report.canny.io/.

## FAQ

> Which glTF extensions are supported?

The website can open, edit, and export all [extensions supported by glTF-Transform](https://gltf-transform.donmccurdy.com/extensions.html). Some of these extensions will not be shown in the 3D viewport, however, based on [current three.js limitations](https://threejs.org/docs/#examples/en/loaders/GLTFLoader).

> Does glTF Report upload or save my models somewhere?

No. glTF/GLB files opened on the website are not uploaded to a server, and remain on your computer while viewing and editing. The website may collect anonymized analytics (e.g. which glTF extensions are most common?) to improve the glTF ecosystem.

## Source Code

The glTF Report website is [open core](https://en.wikipedia.org/wiki/Open-core_model), but not [open source](https://en.wikipedia.org/wiki/Open_source). Much of its functionality — excluding the user interface — is provided by the projects below, available under MIT License:

- [donmccurdy/glTF-Transform](https://github.com/donmccurdy/glTF-Transform): glTF JavaScript SDK used for edits, analysis, and optimization.
- [donmccurdy/glTF-Transform-View](https://github.com/donmccurdy/glTF-Transform-View/): Experimental rendering API for fast edit/refresh workflows.

Other important dependencies used by this project include:

- [three.js](https://github.com/mrdoob/three.js/): JavaScript 3D library.
- [Svelte](https://github.com/sveltejs/svelte): Lightweight, reactive web framework.
- [Monaco](https://github.com/Microsoft/monaco-editor): Code editor powering VS Code.
- [Tweakpane](https://github.com/cocopon/tweakpane): Compact GUI for editing and monitoring.

Features and bug fixes in the projects above will eventually make their way to the glTF Report website.
