# 🔁 TurnMarket 🔁

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)

TurnMarket is a plugin that will change items at different defined times. You can buy or sell item. You can all edit the plugin in ``config.yml`` file.

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

> * ``` TURN-TIME ``` - Scheduler feature (Add in your config multiple rotate time. _For example:_ ``"08:00"``)
> * ``` MAX-ITEMS ``` - Max display items on inventory (_Default:_ ``5``)
> * ``` NAME ``` - Shop name (_Example:_ ``"farm"``)
> * ``` DISPLAY-NAME ``` - Shop display name (_Example:_ ``"&7[&e⛃&7] &e&lFarm"``)
> * ``` SIZE ``` - Inventory size (_Default:_ ``5``)
> * ``` ALLOWED-SLOT ``` - Allowed slot in inventory
> * Example
> ```ALLOWED-SLOT:
      - 20
      - 21
      - 22
      - 23
      - 24
      - 25

## Purchase
To purchase the last plugin version, you can click on one of the links below

* **[BuiltByBit](https://builtbybit.com/)**
* **[Spigot](https://spigotmc.com/)**
* **[GroupeZ](https://groupez.dev/resources)**

**🌟 Last version :** 0.0.1

## Autor
The only autor of TurnMarket:
* **[@SYRQL](https://github.com/Syrql_)**


## Contact

* My personal discord ``SYRQL#0139``
* **[Discord Software](https://discord.gg/mK6Q2ddTcy)**

## License

This project is using ``MIT Licence`` - [LICENSE.md](LICENSE) for more informations.

