## Draft 1.1

* Clarify values in `channels` and `channelsOrNull`.

* Throw an error if construction space can not be determined.

* Remove `alpha` from list of deprecated getters.

* Rename types: `ColorSpaceLAB` to `ColorSpaceLab`, `ChannelNameLAB` to
  `ChannelNameLab`.

* Use `Exclude<>` instead of `Omit<>` for union types.

* Make procedure for determining space backwards compatible when using `change`
  for legacy colors.

* Fix channel names for `change` with `oklch` and `lch`.

## Draft 1

* Initial draft