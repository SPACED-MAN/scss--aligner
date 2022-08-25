# Aligner
SCSS Mixin that aligns anything relative to its container vertically, horizontally and more.

## Usage

```scss
.parent {
	position: relative;
}
.child-1 {
	@include aligner; // Vertically and horizontally center this content inside of .parent
}
.child-2 {
	@include aligner("right", "bottom"); // Place this content in the bottom right corner of .parent
}
```

## Donations

You might find that this saves you time and/or money. A donation of any amount would be very kind and will ensure this is actively maintained. Donations can be made here: <https://www.paypal.com/donate/?hosted_button_id=9YRXRN6EJA2DN> -- Thank you!

## TO DO

- Add 'Demo' section in README, complete with links to working examples (e.g. Codepen)
- Add 'Getting Started' section, with npm/yarn install instructions
- Provide better documentation
- Support percentage and unit-based adjustments as alignment arguments