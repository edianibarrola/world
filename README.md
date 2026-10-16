# World / First Lives - browser build

Compiled Unity WebGL prototype. Source: https://github.com/edianibarrola/worldcode
Source revision: 102782f462079dab05036ee0bb50b85e43cc22e5

For GitHub Pages, use Settings > Pages > Deploy from a branch > main > / (root).
Then open https://edianibarrola.github.io/world/ once GitHub completes deployment.

The simulation starts paused. Press Play. Select a creature to inspect its learned action values. Choose a resource tool and click land to intervene. Changing Learning mode resets the same starting seed for comparison with random behavior.

This experiment demonstrates basic individual survival learning. Tool invention and culture are not demonstrated. Desktop browser startup is smoke-tested locally. Actual phone performance and touch input remain unvalidated.

To test locally, serve this directory over HTTP (for example: python -m http.server 8765). Opening index.html directly as a local file will not work.
