# Old Style Utility Meter Card for Home Assistant
[![hacs_badge](https://img.shields.io/badge/HACS-Custom-41BDF5.svg?style=for-the-badge)](https://github.com/hacs/integration)

Old Style Utility Meter Card for Home Assistant

Customizable Utility Meter Card based on old style (non digital) utility meter box with rotating digits.
This picture does a better job than describing it with words:

![Old Style Utility Meter Card](https://github.com/LuckyG3000/old-style-utility-meter-card/blob/main/imgs/old-style-utility-meter-card.png?raw=true)

This is my first custom card project.

# Configuration

Colors of almost all elements can be set to custom values.
Font of digits can be either default (used by your HA dashboard) or Carlito, which is more resembling the font used on meter boxes.
This card supports visual configuration editor.

![Visual Configuration Editor](https://github.com/LuckyG3000/old-style-utility-meter-card/blob/main/imgs/visual_config.png?raw=true)

![Example YAML configuration](https://github.com/LuckyG3000/old-style-utility-meter-card/blob/main/imgs/yaml_config.png?raw=true)

# Examples

![Example 1](https://github.com/LuckyG3000/old-style-utility-meter-card/blob/main/imgs/example-0.png?raw=true)

![Example 2](https://github.com/LuckyG3000/old-style-utility-meter-card/blob/main/imgs/example-1.png?raw=true)

![Example 3](https://github.com/LuckyG3000/old-style-utility-meter-card/blob/main/imgs/example-2.png?raw=true)

![Example 4](https://github.com/LuckyG3000/old-style-utility-meter-card/blob/main/imgs/example-3.png?raw=true)

![Example 5](https://github.com/LuckyG3000/old-style-utility-meter-card/blob/main/imgs/example-4.png?raw=true)

# Installation

## HACS (recommended) 

This card is available in [HACS](https://hacs.xyz/) (Home Assistant Community Store).

<small>*HACS is a third party community store and is not included in Home Assistant out of the box.*</small>

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=LuckyG3000&repository=old-style-utility-meter-card)


## Manual HACS install:
Use [HACS](https://hacs.xyz/), follow the [instructions for adding a custom repository](https://hacs.xyz/docs/faq/custom_repositories).

- Click on **HACS** in your HA side panel.
- Then click on three dots in upper right corner, choose **Custom repositories**.
- Paste the address of this repository into **Repository** field (`https://github.com/LuckyG3000/old-style-utility-meter-card`)
- Choose **Dashboard** in **Type** dropdown, click **Add**.
- The **Old Style Utility Meter Card** should appear in the list, click the three dots next to it and select **Download**.
- When asked to **Reload**, confirm it.
- Now you can add the card in your dashboard, click **Add card** and scroll to Custom cards. There you'll find the **Old Style Utility Meter Card**.
- In configuration, select the desired entity, optionally change other settings.

# Thanks

I would like to thank to [Elmar Hinz](https://github.com/elmar-hinz) for his [Custom Card Tutorials](https://github.com/home-assistant-tutorials), which helped me a lot when creating this card.
