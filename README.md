# Orí Jewellery & Objects
Original responsive jewellery storefront built from supplied visual references. Mobile uses persistent bottom navigation, compact browsing and single-column product screens. Desktop uses an editorial hero and multi-column catalogue and product layouts.

## Reference influences
- Lawmi: ivory and terracotta palette, mobile hierarchy and saved/product controls.
- Gemia: serif display typography and image-led editorial layout.
- Celesse: layered-necklace imagery, considered spacing and brand storytelling.
- Aureli: product detail hierarchy, material controls and care information.
- Jewelry shop and custom builder references: mobile shopping, product choices, custom concepts.
- K.Stores: catalogue recommendations and bag/checkout structure.
No reference screenshots or copied interfaces are included in the published site.

## Behaviour
Search, category filtering, sorting, product finish/size/quantity, saved products, bag editing and totals, custom concept builder, account preferences, and demo checkout. Data stays in browser localStorage. No server account, subscription, payment, order submission, inventory, or fulfilment integration. Prices, names and descriptions are demonstration content. Photos illustrate styles rather than exact purchasable inventory.

## Assets
Original AI-generated imagery created for Orí with the built-in image-generation tool: campaign portrait, twisted gold hoops, oval crystal ring, pearl strand. Saved in dist/assets/ori-campaign.webp, ori-twist-hoops.webp, ori-vow-ring.webp, ori-heirloom-pearls.webp. Prompts: fictional adult Nigerian woman with layered gold necklaces and ivory linen; twisted gold hoop pair on travertine; oval crystal gold ring on ivory stone; organic pearl strand with gold spacers on linen. Shared art direction: warm daylight, ivory, terracotta, realistic texture, no lettering or branding. Stock photos removed. Icons: Tabler Icons v3.35.0 (MIT). Fonts: Cormorant Garamond and DM Sans (OFL).

## Verification
JavaScript syntax checked. Script-level interaction checks cover navigation, category/search, wishlist toggling, bag quantities and totals, custom choices, checkout behaviour and localStorage. Browser visual QA unavailable in this session; responsive styles inspected in source.

## Client revision: editorial storefront
Rebuilt the homepage and responsive design after client feedback. Upright Cormorant Garamond Medium display font replaces the mistakenly italic font file. Header now uses centred ORÍ wordmark, clear desktop navigation and mobile app navigation. Burgundy controls follow the supplied Aureli reference. Campaign portrait uses restrained studio lighting, with distinct original stud and pendant images replacing repeated catalogue photographs. All six listings have distinct imagery. Decorative seals, on-image marketing labels and empty promotional sections removed. Product information uses sans-serif type, clear prices, gold-tone finish, product-specific fit and US ring sizes. Saved bag records migrate to current catalogue names and imagery. Existing search, filtering, sorting, saved products, custom concepts, bag and demo checkout preserved.

Additional generated image files: assets/ori-editorial.webp, assets/ori-sol-studs.webp, assets/ori-lumi-pendant.webp. Prompts: authentic Nigerian adult model in chocolate silk, softly lit neutral studio; folded petal gold studs on pale gray paper; delicate gold oval pendant necklace on pale gray paper. Created with built-in image-generation tool. These remain generated concept images, not photographs of real client inventory.

Mobile review page: /review-mobile.html embeds the actual responsive storefront in a 390px viewport for desktop review. It does not change the layout served to phone visitors.

Live visual review identified and corrected shared desktop content-edge alignment, campaign portrait head crop, and mobile purchase action placement. Mobile product pages use a persistent Add to bag bar with quantity-adjusted total; normal bottom navigation is replaced only on product pages. Single-photo products omit redundant thumbnails.

### October 9 photography and controls update
Two new fictional model portraits generated with the built-in image generator replace the previous campaign/styling images. Prompt direction: authentic editorial studio shoot, natural visible skin texture and tonal variation, restrained makeup and retouching, realistic jewellery and fabric, soft directional light, no CGI/beauty-filter effect. Assets: `dist/assets/ori-editorial-v2.webp` and `dist/assets/ori-styling-v2.webp`.

Downloaded button reference: https://github.com/shadcn-ui/next-template/blob/main/components/ui/button.tsx . Original source and MIT license retained under `vendor/`. Filled, outlined, focus, disabled, and alignment patterns adapted to the existing vanilla HTML/CSS application; no React runtime dependency added. No arrow-based calls to action or decorative underlines remain. Header, campaign, catalogue, styling and footer use a common 1440px maximum width and responsive gutters.

### Lookbook carousel
Added three original editorial images (`ori-carousel-gold.webp`, `ori-carousel-pearls.webp`, `ori-carousel-details.webp`) and a six-image scrolling lookbook between the campaign and catalogue. The continuous 65-second loop pauses on hover, keyboard focus within its viewport, or the labelled Pause control. Repeated loop items are inert and hidden from assistive technology. Reduced-motion users receive a stationary horizontally scrollable photo strip without duplicated items. Prompts use realistic Nigerian adult models, natural skin and fabric texture, warm studio light, and gold/pearl jewellery detail photography.

### Expanded shopping catalogue
Expanded from six to 24 products: six each in Rings, Necklaces, Earrings, and Beads. The homepage now displays all four categories with their six individual cards, and each new product has a distinct original studio image, price, details, sizing or fit, wishlist control, and bag action. Related items stay within the current category. The 18 product-image prompts specify complete isolated jewellery designs on warm ivory paper, diffused studio lighting, and clear construction, without people or campaign props. Catalogue data and imagery remain demonstration concepts rather than verified stock.
