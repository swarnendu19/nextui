# @nextui-org/input-otp

## 2.1.7

### Patch Changes

- [#4338](https://github.com/nextui-org/nextui/pull/4338) [`2f55ecb`](https://github.com/nextui-org/nextui/commit/2f55ecb4b2e61fb9d9a91df9f4d7c1eff6b7b05e) Thanks [@macci001](https://github.com/macci001)! - Change ensures that the input value does not accept any disallowed characters when the value prop contains them (#4329)

- Updated dependencies [[`77206bc`](https://github.com/nextui-org/nextui/commit/77206bc62596894d038b9715e40b361fec286c10)]:
  - @nextui-org/shared-utils@2.1.2
  - @nextui-org/form@2.1.7
  - @nextui-org/react-utils@2.1.2

## 2.1.6

### Patch Changes

- [#4314](https://github.com/nextui-org/nextui/pull/4314) [`5598806`](https://github.com/nextui-org/nextui/commit/5598806216166dc9fff36cafd9112412486b747f) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix build

- Updated dependencies []:
  - @nextui-org/form@2.1.6

## 2.1.5

### Patch Changes

- [#4296](https://github.com/nextui-org/nextui/pull/4296) [`1485eca`](https://github.com/nextui-org/nextui/commit/1485eca48fce8a0acc42fe40590b828c1a90ff48) Thanks [@macci001](https://github.com/macci001)! - Fixing the autofocus functionality in input-otp component(#4250)

- Updated dependencies []:
  - @nextui-org/form@2.1.5

## 2.1.4

### Patch Changes

- [#4258](https://github.com/nextui-org/nextui/pull/4258) [`1031e98`](https://github.com/nextui-org/nextui/commit/1031e985b71e69b8a7189ea049b9616257f820b3) Thanks [@wingkwong](https://github.com/wingkwong)! - sync with upstream RA versions

- Updated dependencies [[`b16291b`](https://github.com/nextui-org/nextui/commit/b16291b2200229f0d0a9ea910e38f3f100f7931f), [`1031e98`](https://github.com/nextui-org/nextui/commit/1031e985b71e69b8a7189ea049b9616257f820b3)]:
  - @nextui-org/form@2.1.4

## 2.1.3

### Patch Changes

- [#4255](https://github.com/nextui-org/nextui/pull/4255) [`6a94a12`](https://github.com/nextui-org/nextui/commit/6a94a125d4836b0a18d9cd2cb521c85a6bfa9050) Thanks [@wingkwong](https://github.com/wingkwong)! - fixed incorrect peerDependencies for theme and system package (#4254)

- Updated dependencies [[`6a94a12`](https://github.com/nextui-org/nextui/commit/6a94a125d4836b0a18d9cd2cb521c85a6bfa9050)]:
  - @nextui-org/form@2.1.3

## 2.1.2

### Patch Changes

- [#4247](https://github.com/nextui-org/nextui/pull/4247) [`551ab18`](https://github.com/nextui-org/nextui/commit/551ab184060b24b2c3a89598f84d4c18599649d0) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Fix peerDeps & core package client on export \*

- Updated dependencies [[`551ab18`](https://github.com/nextui-org/nextui/commit/551ab184060b24b2c3a89598f84d4c18599649d0)]:
  - @nextui-org/form@2.1.2

## 2.1.1

### Patch Changes

- [`d6eee4a`](https://github.com/nextui-org/nextui/commit/d6eee4a8767556152f47f06dcf04940951abc5af) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - v2.6.2

- Updated dependencies [[`d6eee4a`](https://github.com/nextui-org/nextui/commit/d6eee4a8767556152f47f06dcf04940951abc5af)]:
  - @nextui-org/form@2.1.1
  - @nextui-org/react-utils@2.1.1
  - @nextui-org/shared-utils@2.1.1

## 2.1.0

### Minor Changes

- [`5786897`](https://github.com/nextui-org/nextui/commit/5786897b9950d95c12351dacd2fb41bb1e298201) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - This release includes several improvements and bug fixes:

  - Updated react-aria version across all components
  - Improved Drawer styles and transitions
  - Fixed missing peer dependencies for framer-motion
  - Fixed menu item classNames functionality
  - Added isClearable prop to Textarea component
  - Fixed label placement issues in Input and Select components
  - Improved table keyboard navigation with new isKeyboardNavigationDisabled prop
  - Fixed UI sliding issues with helper wrapper in Input and Select
  - Updated use-image hook to avoid Next.js hydration issues
  - Replaced RTL-specific styles with logical properties
  - Fixed textarea label squish issue
  - Bumped tailwind-merge version
  - Applied tw nested group fixes
  - Fixed fullWidth variant in input and select components
  - Moved circular-progress tv to progress
  - Changed ListboxItem key to optional
  - Fixed autocomplete clear button behavior
  - Updated Select label placement logic
  - Added missing framer-motion peer dependencies
  - Removed layoutNode prop from Table due to react-aria update
  - Virtualization added to Autocomplete

### Patch Changes

- [#4224](https://github.com/nextui-org/nextui/pull/4224) [`26e478d`](https://github.com/nextui-org/nextui/commit/26e478dd937dedcaf41110171d971a8a3cf2ff52) Thanks [@jrgarciadev](https://github.com/jrgarciadev)! - Added form support to input-otp, change default validationBehavior to "native" to avoid breaking changes, and fix select with form

- Updated dependencies [[`26e478d`](https://github.com/nextui-org/nextui/commit/26e478dd937dedcaf41110171d971a8a3cf2ff52), [`6c0213d`](https://github.com/nextui-org/nextui/commit/6c0213dfc805aa3c793763c0b25f53b2b80c24dc), [`5786897`](https://github.com/nextui-org/nextui/commit/5786897b9950d95c12351dacd2fb41bb1e298201)]:
  - @nextui-org/form@2.1.0
  - @nextui-org/react-utils@2.1.0
  - @nextui-org/shared-utils@2.1.0

## 2.0.1-beta.0

### Patch Changes

- [#4052](https://github.com/nextui-org/nextui/pull/4052) [`1d5b2b6c1`](https://github.com/nextui-org/nextui/commit/1d5b2b6c1f8672e7339a6f9dc66f0244d7bb2789) Thanks [@macci001](https://github.com/macci001)! - Adding new input-otp component.

- Updated dependencies [[`1d5b2b6c1`](https://github.com/nextui-org/nextui/commit/1d5b2b6c1f8672e7339a6f9dc66f0244d7bb2789)]:
  - @nextui-org/theme@2.3.0-beta.17
