# 🔁 TurnMarket 🔁

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)

TurnMarket is a plugin that will change items at different defined times. You can buy or sell item. You can all edit the plugin in ``config.yml`` file.
Each time the market runs, new items are selected and displayed in a menu. It is therefore possible to buy and resell objects.
The interfaces are all modifiable, at each rotation, new items are randomly selected from the ``config.yml`` file.

## Synopsis

To start, you have to use your brain to read this documentation.

### Requirements

You have to follow the instructions below.

- 💸 Economy plugin (Vault) _(depend)_
- 💙 PlaceHolderAPI _(softdepend)_

### Plugin Installation

After buying the plugin, just put into your plugins folder the .jar, and dont forget to use an Economy plugin.

_Config_: You can easily edit Config by using ``config.yml`` file [...]

## PlaceHolderAPI

How to use [PlaceHolderAPI](https://www.spigotmc.org/resources/placeholderapi.6245) implementation?

* ``%turnmarket_shop_name/<shopName>%`` -  Replace ``<shopName>`` by your custom shop name. Return the custom display name of a shop.
* ``%turnmarket_shop_time-left/<shopName>%`` -  Replace ``<shopName>`` by your custom shop name. Return the timeleft before next rotation
* ``%turnmarket_shop_next-rotate/<shopName>%`` -  Replace ``<shopName>`` by your custom shop name. Return the time of the next rotation

## Config

* You can manually add in ``config.yml`` file multiple addons for use better the plugin.

## **Shop & Inventory**

### Default config keys

* ``` TURN-TIME ``` - Scheduler feature (Add in your config multiple rotate time. _For example:_ ``"08:00"``)
* ``` MAX-ITEMS ``` - Max display items on inventory (_Default:_ ``5``)
* ``` NAME ``` - Shop name (_Example:_ ``"farm"``)
* ``` DISPLAY-NAME ``` - Shop display name (_Example:_ ``"&7[&e⛃&7] &e&lFarm"``)
* ``` SIZE ``` - Inventory size (_Default:_ ``5``)
* ``` ALLOWED-SLOT ``` - Allowed slot in inventory (where item will be place)

```java    
    ALLOWED-SLOT:
      - 20
      - 21
      - 22
      - 23
      - 24
      - 25
```

### Items

```java
      1:
        MATERIAL: "STONE" (Item type)
        NAME: "&7Stone" (Item name)
        LORE: (Item lore)
          - " "
          - "&aBuy: &e%buy-price% &a(Right-Click)"
          - "&cSell: &e%sell-price% &c(Left-click)"
        PRICE: 50 (Item buy price. Set -1 value if it's not possible to buy)
        SELL: 10 (Item sell price. Set -1 value if it's not possible to sell)
        QUANTITY: 1 (Item quantity)
```

## Increment Items

```java

    1:
      NAME: "&a(+) &eAdd &6&l1"
      QUANTITY: 1
      MATERIAL: "INK_SACK"
      MATERIAL-ID: 10
      SLOT: 15
      TYPE: "I_ADD"
```
## Decrement Items

```java

    4:
      NAME: "&c(-) &eSet to &6&l1"
      QUANTITY: 1
      MATERIAL: "INK_SACK"
      MATERIAL-ID: 1
      SLOT: 29
      TYPE: "D_SET"
```

### Config keys

* ``` I_ADD ``` Increment item by using ``QUANTITY``
* ``` I_SET ``` Set item amount by using ``QUANTITY``
* ``` D_REMOVE ``` Decrement item by using ``QUANTITY``
* ``` D_SET ``` Set item amount by using ``QUANTITY``

### Custom config key

* ``` COMMAND ``` Add this key in Item section _Example:_ ``COMMAND: "give %player% diamond %amount%"``

## Purchase
To purchase the last plugin version, you can click on one of the links below

* **[BuiltByBit](https://builtbybit.com/)**
* **[Spigot](https://spigotmc.com/)**
* **[GroupeZ](https://groupez.dev/resources)**

**🌟 Last version :** 0.0.1

## Autor
The only autor of TurnMarket:
* **[@SYRQL](https://github.com/Syrql)**


## Contact

* My personal discord ``SYRQL#0139``
* **[Discord Software](https://discord.gg/mK6Q2ddTcy)**

## License

This project is using ``MIT Licence`` - [LICENSE.md](LICENSE) for more informations.

