# NEED_TO_DO

Recovery of sovereignag.com rebuilt from the archive.org snapshot of May 10, 2026. Live at https://sovereignag.vercel.app

## Open items

1. Replace stand-in photos with the originals. The archive did not save the site's photos, so every missing image is currently a fitted agricultural stand-in image (and the real logo where a logo was used). If Ken (Avalanche Marketing) can provide the original photos, replace the files under site/_assets/sovereignag.com/wp-content/uploads/ using the same file names.

2. Point the live domain. When approved, connect sovereignag.com to the Vercel project (or connect the GitHub repo CalTech-Web/sovereignag for auto deploys) so it serves on the client's normal address.

3. Interior page fine styling. Six interior pages (Who We Are, What We Do, Investors, Partner With Us, Sell Your Business, Preserving Our Heritage) were missing their per-page Elementor stylesheets in the archive. They render fully and look complete on global styling, but spacing may differ slightly from the original. Optional to fine tune.

4. Entrance animations. The archive did not include the Elementor animation stylesheets (fade and slide effects, aos, lightgallery). Sections that used a reveal-on-scroll animation are forced visible so nothing is hidden, but the animations themselves do not play. Optional to restore.

5. Contact form is a static copy and does not submit anywhere yet. If the client needs it working, register the domain in the CalTech Web forms service and wire the form to it.
