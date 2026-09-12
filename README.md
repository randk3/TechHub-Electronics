# TechHub Electronics Class Website

Upload this folder’s contents to the repository root, then choose Settings → Pages → Deploy from a branch → main → / (root). No installation or build required. Preserve any existing CNAME file if your repository has a custom domain.

## Interactive assignment features
- Seven category cards preserve the original layout, colors, Arial, original logo and current photos.
- Shop & Compare Devices opens two fictional TechHub models per category with individual prices and specifications. Select both to compare side by side and add devices to the bag.
- Secure Checkout Demo includes customer details, fulfillment, conditional delivery address, test payment methods, order totals, student savings and an order confirmation. Order references work in Order Tracking during the current session.
- Student verification collects a school, .edu email and enrollment declaration, followed by a six-digit demo code (430202). Successful completion applies 10% off the bag and checkout.
- Support scheduling offers two-hour arrival windows and prevents duplicate session bookings. Customer Support provides an on-site message form; Chat With Support provides automated responses.

## Demonstration scope
Checkout is a simulation, not an actual secure payment processor. No card details are requested, no charge occurs and no information is sent to a payment service. Student verification is also simulated: no email is sent and enrollment is not independently verified. TechHub device models, specifications and prices are fictional assignment data; brand lists and category stock photos are separate from those fictional models. All state resets on reload. Production operation would require hosted payment processing, shared order and booking records, and a real student-verification provider.

## Validation
JavaScript syntax and local flow checks passed for device comparison, bag, verification errors and success, 10% discount calculations, checkout, tracking and empty-bag handling. Photos and local asset references checked. Visual browser testing remains outstanding because the local file URL was blocked by browser policy.

Photo credits appear in IMAGE-CREDITS.md.
