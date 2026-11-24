# Tech Stock

A phone-friendly inventory for everything electronic at home: network gear, PoE cameras and NVRs, computers, game consoles, video games, TV and A/V, smart home, cables and batteries. Sister app to [Home Stock](https://github.com/mcgillpreston-glitch/shopping) and [Garage Stock](https://github.com/mcgillpreston-glitch/garage).

Live: https://mcgillpreston-glitch.github.io/tech/

- **Departments** modeled on an electronics store: Networking, Security Cameras & NVR, Computers, Phones & Tablets, Gaming, Video Games (by platform), TV & Home Theater, Audio, Smart Home, Cameras & Drones, Movies & Music, Power & Batteries, Cables & Adapters, Install & Repair.
- **Barcode scanning** of boxes and game cases (looked up on UPCitemdb and Open Products Facts), plus **serial number and MAC address scanning** from device labels (Code 128, Code 39, QR, Data Matrix).
- **Network & power** on any device: IP, MAC, hostname, firmware, what it's plugged into and which port, PoE it draws or can supply, and which NVR channel records a camera.
- **Network tab**: connection tree, PoE budget per switch, NVR channel grid, sorted IP list (copy to a spreadsheet), and warnings for duplicate IPs or MACs, ports used twice, switches over their PoE budget, and cameras on the same NVR channel.
- **Consoles and games**: gaming gear is a Console or Other; consoles are picked from a list of 38 (NES to Switch 2, Game Boy to PS Vita, original Xbox to Series X|S, Sega, Atari, PC, VR). Each game has its console, and the Gaming and Video Games views show a By console tree with every console's games as a branch, including older games it can play (PS4 on PS5, Switch on Switch 2, GameCube on Wii…).
- **Games and discs**: format (disc, cartridge, digital, code), which of your consoles it plays on, and loans with due dates.
- **Warranties**: shown on each device, flagged 30 days out, listed on the Network tab.
- **Places and rooms**: rack, TV stand, desk, shelves and bins in each room, with printable QR asset tags (Avery 5160/5163 or plain paper).
- **Floor plan**: Rooms → Arrange → Configure layout draws your home from above, floor by floor: rooms (rectangles, L-shapes, hallways or any polygon), building outlines and outdoor areas. Rooms lock together at corners and walls like puzzle pieces, walls and corners can be dragged, and each wall's length can be typed in feet and inches. Tap a room on the plan to go into it and see its places and things. The plan syncs like everything else (`shapes`).
- **Pick for me**: a button on the Tech tab asks what you're trying to do. Watch a movie, play a game or listen to music picks a random title you own that's home and playable, with its picture, where it is and what to play it on. Start a project suggests ideas for gear marked as spare (home server, ad blocker, access point, wall panel…), ways to get more from gear in use, and loose ends in your records.
- **Supplies** (batteries, cables, ink) with low levels feed the shopping list.
- **Insurance list**: Settings → Download insurance list (CSV) with brand, model, serial, price, date, store and warranty.
- **Private sync** through the same Cloudflare storage as the other apps (`/data/tech`). A new device unlocks once with the household key or the invite link from Settings.
