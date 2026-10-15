---
name: amazon-image-production
description: Plan, create, adapt, and review Amazon secondary images, Brand Story, and Basic or Premium A+ content from product references and approved claims. Use for a new image stack, an A+ sequence from scratch, or a variant replacement in existing imagery. Enforce product-reference fidelity, distinct A+ module architecture, visual QA, and accessible asset delivery.
---

# Amazon image production

Build product-accurate, useful Amazon visuals. Treat image generation as one production method, not evidence that a rendered product is correct. Read [handoff.md](references/handoff.md) for the input/output contract. Read [aplus-patterns.md](references/aplus-patterns.md) when planning A+ or interpreting an inspiration library. Read [sypen-calibration.md](references/sypen-calibration.md) when working on SyPen or diagnosing the supplied unsuccessful A+ sequence.

## 1. Establish scope and truth

1. Identify the deliverable: secondary stack, A+, Brand Story, variant adaptation, or a combination. Identify whether the page is for one variant, a family, or a collection. Never turn separate products into a bundle or display unoffered options as the contents of one offer.
2. Use `$amazon-listing-research` when available for product intake, research, a fact ledger, supported shopper questions, and proposed copy. Consume its output instead of repeating keyword research. The plugin supplies optional image/A+ copy ideas; this skill owns visual strategy, design, production, and visual QA. If the plugin is unavailable, assemble the same fact/claim handoff from supplied product sources and ask focused questions for vital gaps.
3. Accept the user's latest explicit correction and actual-product source statements as product facts. Separate facts, permitted claims, shopper inferences, and visual ideas. Do not infer a feature from competitor examples or prior generated imagery. Ask concrete questions before using missing information in publish-ready visuals; proceed with independent layout work while awaiting answers.
4. Inventory the product reference images at full resolution. Record shape, parts, proportions, finish, texture, color, logo/label placement, packaging, included pieces, and visible functional details. Distinguish actual product marks from sample customization or supplier placeholder marks. Record views or details that the reference cannot establish. Request additional angles only when essential to the requested view; do not guess the hidden construction.

## 2. Choose the production mode

**From scratch:** Use the actual product reference for product appearance, the approved fact ledger for claims, the brand guide for styling, and the content plan for the scene and layout. Existing stack files are optional. Create a sequence plan before rendering individual images.

**Adapt an existing stack:** Inspect each original scene separately. Its framing, camera, background, lighting, layout, and copy placement are scene references. The new variant's actual-product reference is authoritative for all visible product geometry, components, material, finish, color, logos, and packaging. The old product is never evidence of the new product's construction. The user's stated changes determine what else may change. If the new construction requires a different silhouette, preserve the scene's role and composition while fitting the correct silhouette.

**Source authority for a conflict:** latest user correction and confirmed product facts; actual-product reference for visible construction; approved brand/assets and claims; original scene for adaptation-only composition; inspiration library for design principles. Prior generated output is never a source of product truth.

## 3. Design the sequence before making images

For every asset, write a one-line job, shopper question, supported answer/claim, visual proof, product variant, composition, copy, source reference, and QA risk. Use [handoff.md](references/handoff.md). Show distinct purposes and avoid repeating the same assertion across the stack.

For A+, plan the **whole page** before any individual module. Choose Basic, Premium, or Brand Story based on the account's available modules and the user's request; verify current Amazon module dimensions, text budgets, image requirements, and claim rules in Seller Central or current official guidance. Do not assume a fixed canvas or treat A+ as secondary images widened to a banner ratio. Specify native text versus baked-in text, sequence, visual rhythm, mobile behavior, and the transition between modules. Use technical explanations, steps, comparisons, proof, lifestyle, or brand narrative only when relevant and supported. A collection comparison needs separate products/variants confirmed.

When given an idea library, segment full-page screenshots into actual content modules. Ignore Amazon chrome, carousels, recommendations, and unrelated storefront elements. Annotate each useful example by **module job, layout grammar, image/text hierarchy, product scale, information density, and mobile risk**. Select a small number of relevant structural patterns for the page plan; do not copy another brand's claims, marks, palette, or exact artwork. See [aplus-patterns.md](references/aplus-patterns.md). Flag a proposed sequence whose modules all use the same hero-photo-plus-headline arrangement unless that repetition is a deliberate, justified design choice.

## 4. Render with controlled components

Use image generation for scenes, lighting, context, or visual exploration where appropriate. For a product that must match a photograph precisely, prefer a supplied high-resolution cutout, approved render, or masked composite for the product; use generated context around it. Construct headings, icons, measurements, diagrams, tables, and comparison data in editable layout/code where possible. Do not rely on generated microtext, logos, precise mechanisms, or exact repeated product parts.

Give every image tool input a numbered role: actual product, original scene (adaptation mode only), approved brand assets, and optional layout inspiration. Explicitly state what may change and what must be preserved. Generate one purpose at a time. If a result changes product details, discard or repair it; do not promote an attractive but inaccurate concept to a final asset.

## 5. Verify the product and the page

Inspect every final file at full size against the actual product reference, zooming into each visible product instance. Check silhouettes, count, cap/tip/clip shape, mechanisms, textures, trim colors, engravings, labels, and packaging. Compare copy and numbers to the fact ledger. Run deterministic checks for file format, dimensions, missing assets, and duplicate files where useful. OCR may help find text mistakes but does not replace visual inspection.

Review the assembled secondary stack and A+ page at desktop and mobile scale. Check reading order, copy legibility, crop safety, distinct module jobs, repeated compositions, and whether native text remains accessible. Treat Amazon's Seller Central preview as the final layout validation when available. Report unresolved product fidelity or policy checks clearly; do not mark a concept publication-ready if a critical detail is unverified.

## 6. Deliver accessible files

Save individual final PNGs and editable source or layout files when created, plus a concise manifest with role, source facts, dimensions, and QA status. Keep drafts separate from approved assets. In a GitHub-backed project, put the files on a review branch, link the individual assets and page preview, and verify the committed files open. Do not hand off only a temporary workspace path, a PDF, or an unverified ZIP. Publishing to Amazon requires the user's separate instruction.
