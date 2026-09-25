# Hey World

A lightweight immersive space experience. Hey World opens with a cinematic Mars approach, then invites you through a canvas-rendered portal to all eight planets.

[Live preview](https://howard118008y-commits.github.io/Hey-World/)

Open `index.html` in a modern browser and keep its bundled `assets/` folder beside it, including eight PNG environments and eight six-second MP4 films. No installation, build step, framework, or external JavaScript is required. The exact image-generation prompts and animation method are recorded in [generation notes](assets/generation-notes.json).

Move the pointer to tilt the portal, then click or tap to continue: **Mars → Earth → Venus → Mercury → Jupiter → Saturn → Uranus → Neptune → Mars**. Select any of the eight planet buttons to play that destination's descent or return to an earlier planet. Each descent ends on the frame used as the new background. On phones, open **Menu → Planets** to choose a destination. Buttons support keyboard navigation and disable while a destination loads and plays.

The responsive page includes a video preloader, animated planet facts, a custom desktop cursor, keyboard-accessible controls, and a compact navigation menu. Reduced-motion preferences skip the automatic intro film and animated movement; intentional travel commits directly to the destination.

All environment images and descent videos are bundled locally. Only the geometric logo loads from its original CloudFront URL. Fonts use locally installed SF Pro and Aalto when available, with system fallbacks; no font files or external libraries are requested.

## Sources

All eight descent films (`assets/*-descent.mp4`) combine the credited globe imagery below with AI-generated, straight-down environments in six-second virtual camera descents at normal speed. These are image-based animations. Jupiter, Saturn, Uranus, and Neptune finish inside their cloud atmospheres rather than on solid ground.

八支下降影片結合下列全景素材與 AI 生成的垂直俯視環境圖，製作六秒、原速播放的圖像運鏡動畫；木星、土星、天王星與海王星呈現雲層大氣，不呈現固體地面。

Venus below the clouds is a scientifically informed reconstruction. The giant-planet close-ups are also reconstructed environments, not actual close-range nadir descent photographs. 金星雲下景觀與巨行星近距離俯視雲層均為依科學資料重建的示意環境。

The five added planets use NASA facts. Temperatures for the four outer planets are atmospheric averages at approximately 1 bar, not surface temperatures. The original Mars, Earth, and Venus facts remain as supplied. Fallback backgrounds use the matching bundled AI environment PNGs.

- [Mercury facts](https://science.nasa.gov/mercury/facts/)
- [Jupiter facts](https://science.nasa.gov/jupiter/jupiter-facts/)
- [Saturn facts](https://science.nasa.gov/saturn/facts/)
- [Uranus facts](https://science.nasa.gov/uranus/facts/)
- [Neptune facts](https://science.nasa.gov/neptune/neptune-facts/)
- [NASA temperature definitions and values](https://science.nasa.gov/solar-system/temperatures-across-our-solar-system/)

### Globe imagery and credits

- **Mercury:** [Mercury Globe: 0°N, 180°E, PIA15162](https://science.nasa.gov/photojournal/mercury-globe-0n-180e/) ([image](https://assets.science.nasa.gov/dynamicimage/assets/science/psd/photojournal/pia/pia15/pia15162/PIA15162.jpg?crop=faces%2Cfocalpoint&fit=clip&h=2147&w=2147)). Credit: NASA/Johns Hopkins University Applied Physics Laboratory/Carnegie Institution of Washington.
- **Earth:** [Blue Marble 2007 West](https://science.nasa.gov/image-detail/amf-gsfc_20171208_archive_e002131/) ([image](https://images-assets.nasa.gov/image/GSFC_20171208_Archive_e002131/GSFC_20171208_Archive_e002131~large.jpg)), a multi-source composite. Credit: NASA/Reto Stöckli; producer: NASA Goddard Space Flight Center.
- **Mars:** [Mars at 43 Million Miles From Earth](https://science.nasa.gov/asset/hubble/mars-at-43-million-miles-from-earth/) ([image](https://assets.science.nasa.gov/dynamicimage/assets/science/missions/hubble/releases/2001/07/STScI-01EVVFKC8MVGDMA60XEBJEZ7XR.tif?w=2000)). Credit: NASA and The Hubble Heritage Team (STScI/AURA); acknowledgment: J. Bell (Cornell U.), P. James (U. Toledo), M. Wolff (SSI), A. Lubenow (STScI), J. Neubert (MIT/Cornell).
- **Venus:** [MESSENGER visible-light view](https://www.nasa.gov/technology/nasa-studies-cubesat-mission-to-solve-venusian-mystery/) ([image](https://www.nasa.gov/wp-content/uploads/2017/08/pia10124-1.jpg?w=1024)). Credit: NASA.
- **Jupiter:** [Cassini Jupiter Portrait, PIA04866](https://science.nasa.gov/resource/cassini-jupiter-portrait/) ([image](https://assets.science.nasa.gov/content/dam/science/psd/solar/2023/09/p/i/a/0/PIA04866-1.jpg)), a true-color mosaic. Credit: NASA/JPL/Space Science Institute.
- **Saturn:** [So Far from Home, PIA21345](https://science.nasa.gov/photojournal/so-far-from-home/) ([image](https://science.nasa.gov/wp-content/uploads/2024/03/saturn-farewell-pia21345.jpg)). Credit: NASA/JPL-Caltech/Space Science Institute.
- **Uranus:** [Uranus as seen by NASA's Voyager 2, PIA18182](https://science.nasa.gov/photojournal/uranus-as-seen-by-nasas-voyager-2/) ([image](https://assets.science.nasa.gov/dynamicimage/assets/science/cds/general/images/2024/03/uranus-pia18182-16x9-1.jpg)). Credit: NASA/JPL-Caltech.
- **Neptune:** [Corrected-color comparison](https://ras.ac.uk/news-and-press/research-highlights/new-images-reveal-what-neptune-and-uranus-really-look) ([source graphic](https://ras.ac.uk/sites/default/files/2024-01/Combined_figures_crop.jpg)). Credit: Patrick Irwin/University of Oxford/NASA, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Modification: the bottom-right corrected-color Neptune sphere was cropped from the graphic for the opening.
