This 24 bit art has been incorporated into a development build of the game. Known existing issues are elaborated on below. 

#### Anti-Alias Issue
Some unit images don't anti-alias to a transparent background. Instead, they anti-alias to a "noisy" (i.e. various shades) grey background which has such low alpha values that is hardly noticed in most cases. Art with this issue:
- artillery
- hq
- hrc
- itank
- miner
- mobilehq
- mtank
- proc
- reactor
- research
- tmac
- troc
- warehouse

#### Missing Art
Missing bitmap and building art has been substituted with art from art824. Missing unit art has been substituted with solid colored blue (or black) images. These substitutions are for development purposes and most should be replaced with "real" 24 bit art before production. Below follows a list of the missing/substitued art:
- Animation art:
    - activator
    - andyshot
    - bullet
    - movetarget
    - proc_smoke
    - ricochet
    - rocket
    - tankshot
    - upgrades
    - vacuum
- Arrowhead art:
    - arrowheaddown.png
    - arrowheadleft.png
    - arrowheadright.png
    - arrowheadup.png
- Building Art:
    - vts
    - replicator
- Miscellaneous
    - All cut scene images
- Scenery art:
    - bitmaps/RocketArtifact.png
    - bitmaps/rocks.png
    - bitmaps/plant.png
    - bitmaps/plant1.png
    - bitmaps/plant2.png
    - bitmaps/plant3.png
    - bitmaps/plant4.png
    - bitmaps/plant5.png
- Scroll art:
    - bitmaps/scrolldowndown.png
    - bitmaps/scrolldownup.png
    - bitmaps/scrollupdown.png
    - bitmaps/scrollupup.png
- Unit art:
    - All andy_jog_x_x, most andy_idle_x_x, and some andy_fire_x_x
    - ltank_fire_04_xx through ltank_fire_15_xx
    - sri\sri_idle_9_0.png (currently substituted with black_sri_idle_9_0.png which is not missing)

*Note: side-specific art listed above is also missing its black frame unless otherwise noted.*

#### Shadows
Unit shadows do not visually coordinate with terrain shadows. In fact, most unit shadows have such a low alpha that they are scarcely visible in-game. Aside from that, hrc is missing a shadow altogether. Also note that any art substituted from art824 will have shadows facing in the opposite direction.


