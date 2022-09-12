# assets
Ramp Network assets.

## Merging assets

Please ask Maciej Bembenista for review and merge once you're ready.

## Optimizing images
Images account for nearly [two-thirds of average webpage bandwidth](https://cloudinary.com/blog/top_10_mistakes_in_handling_website_images_and_how_to_solve_them).
Optimized images make websites and widgets load faster and provide better experience for the user. 

Images from this repository are served "as is", so they should be optimized before they are commited.

[Optimizilla](https://imagecompressor.com/) is example tool that can be used to achieve JPEG, GIF and PNG images optimization. Be warn that sometimes optimized images can lost it quality.
After upload an image you can compare the result with origin on the bottom of this tool webpage. 

SVG images are lesser issue as they are quite small from the beginning.
But optimizing them can still useful. [SVGOptimizer](https://svgoptimizer.com/) is similar tool that can do this. 

WARNING: Using tools above you can optimize only 20 images at once. 

## Crypto Assets

Icons used for displaying crypto assets in UI are divided into two folders:
- `/tokens`
- `/chains`

In the first one, we store icons that are used **ONLY** for **TOKENS**, such as `FEVR` or `BAT`. Naming convention is `{{tokenName}}.svg`.

The second one stores icons that can illustrate **ONLY CHAINS** or **BOTH CHAINS & TOKENS**. The naming convention is `{{tokenName}}-{{chainName}}.svg`
For example, `eth-eth.svg` can be used to both illustrate logo of ETH token and ETH chain. `starknet.svg` on the other hand is used only as a chain logo.

In case that a single icon would represent two or more tokens and chains, their names should be joined based on the aforementioned naming convention, so first token names, then chain names, for example: `token1-token2-chain1-chain2.svg`.