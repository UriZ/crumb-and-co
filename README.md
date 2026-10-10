# Crumb & Co. Bakeshop

A cozy five-stage cookie-baking game built with three.js. No build step, no install.

**Play it: https://uriz.github.io/crumb-and-co/**

## The five stages
1. **Dough** — drag flour, eggs, butter, milk and sugar into the bowl. Toss in strawberries, chocolate, coconut, matcha or caramel to flavour the dough, or a food-colouring bottle to tint it. Mix by hand with the spoon, or dock the bowl under the pink stand mixer.
2. **Mix-ins** — portion six treats in four shapes (classic, big cookie, donut, bear claw) and sprinkle from a 23-crate topping bar. Dye a single cookie or a whole crate.
3. **Bake** — set the dial, slide the tray in, pull it out while the doneness marker sits in the golden window. Four outcomes, from pale to charcoal.
4. **Frosting** *(optional)* — melt a base plus milk in the saucepan, then swirl or drizzle. The topping bar rolls along, so sprinkles still work here.
5. **Pack** — arrange the cookies in a compartment box, then choose box colour, ribbon, sticker, gift tag and glitter.

Step **back** between stations at any time. Before the tray goes in the oven, and before the bow is tied, going back lets you genuinely edit your work again; elsewhere it is a look-around that changes nothing.

## Run locally
ES modules need http, not `file://`:

```sh
python3 -m http.server 8000
# open http://localhost:8000/
```

## Notes
- `three.module.js` is three.js r160, vendored so the page is self-contained.
- Desktop, or a phone in landscape.
