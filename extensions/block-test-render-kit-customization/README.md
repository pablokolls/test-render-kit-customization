### Notes
  - En los snippets si importamos el archivo CSS luego no se lee al hacer un render dentro de otro snippet o block porque shopify unicamente lee el CSS de los block porque los inserta en el head del HTML. Por eso estamos usando para componentes chicos el CSS de los snippets dentro de las etiquetas `<style>`.
### Snippets
#### Components
- [] Kit Media (Render)
- [] Kit Customization 
    - [] Kit Equipment (Products)
        - [] Equipment Item
        - [] Mock Products
    - [] Kit Sizes
        - [] Size Item
        - [] Mock Sizes
        - [] Modal Sizes Guide
    - [] Kit Personalization
        - [] Player list
        - [] Custom Player
        - [] Mock Player Options
    - [] Kit Competitions
        - [] Mock Competitions
    - [] Kit Add to Cart
#### Utils
- [] Titles (H1, H2, H3, H4, H5, H6) 
- [] Toggle Switch 
    - [] Default Radio Selector 
        - [] Disabled Style and Bell Icon
    - [] Personalization Double Options 
- [] Selector
- [] Input text
- [] Input number
- [] Price Text (option format example: "132,98 €", "+20€")