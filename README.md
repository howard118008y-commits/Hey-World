# Hey World

A lightweight immersive space experience. Hey World opens with a cinematic Mars approach, then invites you through a canvas-rendered portal to all eight planets.

[Live preview](https://howard118008y-commits.github.io/Hey-World/)

Open `index.html` in a modern browser and keep its bundled `assets/` folder beside it, including the five PNG artworks and five six-second MP4 films. No installation, build step, framework, or external JavaScript is required. The exact five image-generation prompts and animation method are recorded in [generation notes](assets/generation-notes.json).

Move the pointer to tilt the portal, then click or tap to continue: **Mars → Earth → Venus → Mercury → Jupiter → Saturn → Uranus → Neptune → Mars**. Select any of the eight planet buttons to play that destination's descent or return to an earlier planet. Each descent ends on the frame used as the new background. On phones, open **Menu → Planets** to choose a destination. Buttons support keyboard navigation and disable while a destination loads and plays.

The responsive page includes a video preloader, animated planet facts, a custom desktop cursor, keyboard-accessible controls, and a compact navigation menu. Reduced-motion preferences skip the automatic intro film and animated movement; intentional travel commits directly to the destination.

An internet connection is required for the original CloudFront videos, Mercury image, geometric logo, and the official NASA images of Jupiter, Saturn, Uranus, and Neptune. The original CloudFront URLs remain as supplied; the four added planet images are from NASA. Fonts use locally installed SF Pro and Aalto when available, with system fallbacks; no font files or external libraries are requested.

## Sources

The five added descent films (`assets/*-descent.mp4`) animate AI-generated environment artwork into six-second cinematic approaches; they are illustrative camera animations, not spacecraft recordings or physically simulated landings. Mercury finishes near its rocky surface. Jupiter, Saturn, Uranus, and Neptune finish inside their cloud atmospheres, not on solid ground. The original Mars, Earth, and Venus films are preserved.

新增五支下降影片以 AI 生成環境圖製作六秒電影式運鏡，屬藝術示意；水星接近岩石地表，木星、土星、天王星與海王星則進入雲層大氣，不呈現固體地面。

The five added planets use NASA facts and fallback imagery. Temperatures for the four outer planets are atmospheric averages at approximately 1 bar, not surface temperatures. The original Mars, Earth, and Venus facts remain as supplied.

- [Mercury facts](https://science.nasa.gov/mercury/facts/)
- [Jupiter facts](https://science.nasa.gov/jupiter/jupiter-facts/) · [NASA image](https://science.nasa.gov/wp-content/uploads/2024/03/jupiter-marble-pia22946-16x9-1.jpg?resize=900,506)
- [Saturn facts](https://science.nasa.gov/saturn/facts/) · [NASA image](https://science.nasa.gov/wp-content/uploads/2024/03/saturn-farewell-pia21345.jpg?resize=900,466)
- [Uranus facts](https://science.nasa.gov/uranus/facts/) · [NASA image](https://assets.science.nasa.gov/dynamicimage/assets/science/cds/general/images/2024/03/uranus-pia18182-16x9-1.jpg?w=900&h=506&fit=crop&crop=faces%2Cfocalpoint)
- [Neptune facts](https://science.nasa.gov/neptune/neptune-facts/) · [NASA image](https://science.nasa.gov/wp-content/uploads/2024/03/pia01492-neptune-full-disk-16x9-1.jpg?resize=900,506)
- [NASA temperature definitions and values](https://science.nasa.gov/solar-system/temperatures-across-our-solar-system/)

Jupiter image credit: Enhanced image by Kevin M. Gill (CC-BY) based on images provided courtesy of NASA/JPL-Caltech/SwRI/MSSS. [Original image and credit](https://science.nasa.gov/photojournal/jupiter-marble/).

Mercury's full-disk opening uses [Mercury Globe: 0°N, 180°E](https://science.nasa.gov/photojournal/mercury-globe-0n-180e/) ([source image](https://assets.science.nasa.gov/dynamicimage/assets/science/psd/photojournal/pia/pia15/pia15162/PIA15162.jpg?crop=faces%2Cfocalpoint&fit=clip&h=2147&w=2147)). Credit: NASA/Johns Hopkins University Applied Physics Laboratory/Carnegie Institution of Washington.
