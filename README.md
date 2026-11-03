# Voxel VFX 3D: product page

The product page and documentation for **Voxel VFX 3D**, 244 pixel-art VFX rebuilt as real 3D voxels for Blender 5.2+:
an asset library you drag from the Asset Browser, every effect one object with one Geometry Nodes modifier.

This repository holds only the description, the media and the docs. The library itself is sold on Superhive and is
not included here.

- Product page: `index.html`, at https://blenderprocedural.github.io/voxel-vfx-3d/
- Documentation: `docs.html`, at https://blenderprocedural.github.io/voxel-vfx-3d/docs.html
- `effects/`: a looping GIF of each of the 244 effects, by category
- `images/`: the store images; `media/`: the promo, the how-to and a scene film
- `assets/`: style and the iframe helper; Inter is bundled in `fonts/`, so the pages make no external requests

## Embedding

Both pages work inside an iframe: links to other pages open in a new tab, and the page posts its height to the
parent window as `{type: "voxelvfx3d-height", height}`.

```html
<iframe src="https://blenderprocedural.github.io/voxel-vfx-3d/" width="100%" height="6000" style="border:0;display:block;" title="Voxel VFX 3D"></iframe>
```

## License

All renders, videos, text and code in this repository are © BlenderProcedural. All rights reserved. The effects are
based on pixelfx (MIT, Patch and Hugo Duprez); see the credits on the page.
