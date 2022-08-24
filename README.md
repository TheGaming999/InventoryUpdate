# InventoryUpdate
(**You need [ReflectionUtils](https://github.com/CryptoMorin/XSeries/blob/7477ef5c434c40c89b9a6f4e180f4d5d69672e2f/src/main/java/com/cryptomorin/xseries/ReflectionUtils.java)**)

This fork fixes an issue with CHAT_MESSAGE constructor for 1.15- versions and also made some small modifications such as removing JavaPlugin parameter from the update method, following *static final* order, and tiny optimizations.

With this resource, you can update the title of almost every inventory (some limitations, read below) without the need of reopening the inventory or resetting the cursor.

Some limitations / notes:
* You can't change the title from a beacon, creative, or player inventory. (any version).
* You can't change the title from an anvil or workbench if you're developing 1.13 or below.
* There's a visual glitch when updating a shulker box (barely noticeable), the inventory get a bit bigger, nothing to worry about though. I'ts fixed in 1.14+.
* Of couse you can use colors, but you need to pass it already translated. I didn't add it because maybe you have your own method to translate colors if you're using 1.16 with HEX colors.

https://www.spigotmc.org/threads/change-inventory-title-reflection-1-8-1-16.489966/
