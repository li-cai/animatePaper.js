# 1.0.1
 * `paper` is now a peerDependency, this should remove unnecessary code from your dependency tree.
 * The `segmentGrow` property and `grow` effect have been removed (this feature was very buggy).
 * When using `rotate` or `scale` properties, you can provide a new setting : `center` (or `rotateCenter`/`scaleCenter`) (default is `item.position`).
 * `Animation` supports a new option `repeat` (defaults to `0`).
 * `settings.complete` callback takes the `Animation`object as 1st argument.