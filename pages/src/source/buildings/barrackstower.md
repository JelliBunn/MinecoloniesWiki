---
type: building
building: barrackstower
layout: building
---
{% infobox_building %}
The Barracks Towers will employ and house one Guard for every level built (unlike the normal {% building_link guardtower %}, which can only have 1 Guard at a time). Each new Guard will need a bed in a house in order to spawn. However, once they are hired at the Barracks Tower, that becomes their new residence and the bed in the house will open up for another new citizen (child or recruit).

| Barracks Tower Level | Max # of Guards |
|----------------------|-----------------|
| 1                    | 1               |
| 2                    | 2               |
| 3                    | 3               |
| 4                    | 4               |
| 5                    | 5               |

The Barracks Tower locations are predetermined by the {% building_link barracks %} that you choose. They are placed in specific locations to fit within the Barracks. 

| Barracks Level | Max # of Barracks Towers | Max Level of Barracks Towers |
|----------------|--------------------------|------------------------------|
| 1              | 1                        | 1                            |
| 2              | 2                        | 2                            |
| 3              | 3                        | 3                            |
| 4              | 4                        | 4                            |
| 5              | 4                        | 5                            |

Guard(s) will patrol a set distance around their tower, which is based on their tower's level.

| Tower Level | Max Patrol Distance |
|-------------|---------------------|
| 1           | 80 blocks           |
| 2           | 110 blocks          |
| 3           | 140 blocks          |
| 4           | 170 blocks          |
| 5           | 200 blocks          |

**Note:** If you place Barracks/Barracks Towers near your colony border and level them up, your border will [expand](../../source/systems/border).
{% endinfobox_building %}

## {% building %} GUI

{% building_gui_content_block_main order=1 %}
{% building_gui_content_block_stock order=2 %}
{% building_gui_content_block_custom order=3 header="selection tools" image_key="guardtool" image_alt="Guard tool" %}
Click the <strong>Obtain Tools</strong> button to get the Guard Scepter. Right-clicking on a block with the Guard Scepter will set it as a guard spot or a patrol point.
{% endbuilding_gui_content_block_custom %}
{% building_gui_content_block_hostiles order=4 %}
{% building_gui_content_block_settings order=5 %}