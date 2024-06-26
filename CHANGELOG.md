## [1.4.6](https://github.com/mob-sakai/UnmaskForUGUI/compare/1.4.1...1.4.2) (2024-03-07)
* Added invoke callback property for us to call any delegate if a unmask component was touched.


## [1.4.5](https://github.com/mob-sakai/UnmaskForUGUI/compare/1.4.1...1.4.2) (2024-03-07)
* Added debug log mode.
* For cross-scene dynamic target finding with target name canvas and target fit name object, now the Unmask component searches for it's own parent canvas for the calculation of the target fit.

## [1.4.4](https://github.com/mob-sakai/UnmaskForUGUI/compare/1.4.1...1.4.2) (2024-02-28)
* Improved UnmaskRaycastFilter to take multiple blockers if needed.
* Unmask now can track a fit target based on the name across the scenes if needed.

## [1.4.2](https://github.com/mob-sakai/UnmaskForUGUI/compare/1.4.1...1.4.2) (2023-10-25)


### Bug Fixes

* UnmaskRaycastFilter not working anymore ([14ab505](https://github.com/mob-sakai/UnmaskForUGUI/commit/14ab505fbfaf1103bbb1869d0e42817bf8830ced)), closes [#29](https://github.com/mob-sakai/UnmaskForUGUI/issues/29)

## [1.4.1](https://github.com/mob-sakai/UnmaskForUGUI/compare/1.4.0...1.4.1) (2023-03-14)


### Bug Fixes

* Fixed error when executing menu item ([9f0afa1](https://github.com/mob-sakai/UnmaskForUGUI/commit/9f0afa19a46bc7b718a80142b02e33ade67fa3b4)), closes [#27](https://github.com/mob-sakai/UnmaskForUGUI/issues/27)

# [1.4.0](https://github.com/mob-sakai/UnmaskForUGUI/compare/1.3.0...1.4.0) (2022-02-17)


### Features

* add edge smoothing option ([c5317de](https://github.com/mob-sakai/UnmaskForUGUI/commit/c5317deafeba575161db8b168dae845d68347236))

# [1.3.0](https://github.com/mob-sakai/UnmaskForUGUI/compare/1.2.0...1.3.0) (2021-06-29)


### Bug Fixes

* fix sample ([2cf7348](https://github.com/mob-sakai/UnmaskForUGUI/commit/2cf734838e380fd16c7f14eb2513346da70415b8))
* only for children option inside a scrollview ([b1e2bcc](https://github.com/mob-sakai/UnmaskForUGUI/commit/b1e2bccd05615df26d2cf69494430f72c6314a45)), closes [#24](https://github.com/mob-sakai/UnmaskForUGUI/issues/24)
* remove component icons ([27cf23b](https://github.com/mob-sakai/UnmaskForUGUI/commit/27cf23b5d275d694bc33357c8d84a26993f49eec))


### Features

* add menu to create template object ([907599c](https://github.com/mob-sakai/UnmaskForUGUI/commit/907599c97273f8ce96d55360d5b52cb42de83c5b))

# [1.2.0](https://github.com/mob-sakai/UnmaskForUGUI/compare/v1.1.3...v1.2.0) (2020-10-07)


### Bug Fixes

* adapt pivot when trying to fit to target ([a39fcef](https://github.com/mob-sakai/UnmaskForUGUI/commit/a39fcefba29beba079ac41d96ebabeaa5e92117e))
* pass camera to check the point in rectangle when camera is not null ([65a0ad0](https://github.com/mob-sakai/UnmaskForUGUI/commit/65a0ad0424edd9093fc9dfdfc0daf3c5aa27a145))


### Features

* add menu to import demo ([74603c5](https://github.com/mob-sakai/UnmaskForUGUI/commit/74603c5e08a4acd6b6fc8b711bf1b195bf7cf366))

# Changelog

## [v1.1.3](https://github.com/mob-sakai/UnmaskForUGUI/tree/v1.1.3) (2019-07-12)

[Full Changelog](https://github.com/mob-sakai/UnmaskForUGUI/compare/v1.1.2...v1.1.3)

**Fixed bugs:**

- There is no asmdef file in this package [\#16](https://github.com/mob-sakai/UnmaskForUGUI/issues/16)

**Closed issues:**

- Separate the demo directory as unitypackage [\#17](https://github.com/mob-sakai/UnmaskForUGUI/issues/17)

## [v1.1.2](https://github.com/mob-sakai/UnmaskForUGUI/tree/v1.1.2) (2019-07-10)

[Full Changelog](https://github.com/mob-sakai/UnmaskForUGUI/compare/v1.1.1...v1.1.2)

**Fixed bugs:**

- Can't install package using UPM [\#15](https://github.com/mob-sakai/UnmaskForUGUI/issues/15)

## [v1.1.1](https://github.com/mob-sakai/UnmaskForUGUI/tree/v1.1.1) (2019-02-07)

[Full Changelog](https://github.com/mob-sakai/UnmaskForUGUI/compare/v1.1.0...v1.1.1)

**Fixed bugs:**

- UnmaskRaycastFilter is not reliable [\#14](https://github.com/mob-sakai/UnmaskForUGUI/issues/14)

## [v1.1.0](https://github.com/mob-sakai/UnmaskForUGUI/tree/v1.1.0) (2019-01-25)

[Full Changelog](https://github.com/mob-sakai/UnmaskForUGUI/compare/1.1.0...v1.1.0)

**Install UnmaskForUGUI with Unity Package Manager!**

Find the manifest.json file in the Packages folder of your project and edit it to look like this:
```js
{
  "dependencies": {
    "com.coffee.unmask": "https://github.com/mob-sakai/UnmaskForUGUI.git#1.1.0",
    ...
  },
}
```
To update the package, change `#1.1.0` to the target version.

**Implemented enhancements:**

- Unmask only for children option [\#11](https://github.com/mob-sakai/UnmaskForUGUI/issues/11)

## [v1.0.0](https://github.com/mob-sakai/UnmaskForUGUI/tree/v1.0.0) (2018-10-18)

[Full Changelog](https://github.com/mob-sakai/UnmaskForUGUI/compare/v0.2.0...v1.0.0)

**Implemented enhancements:**

- Add `Fit On LateUpdate` option [\#10](https://github.com/mob-sakai/UnmaskForUGUI/issues/10)

## [v0.2.0](https://github.com/mob-sakai/UnmaskForUGUI/tree/v0.2.0) (2018-10-16)

[Full Changelog](https://github.com/mob-sakai/UnmaskForUGUI/compare/v0.1.0...v0.2.0)

**Implemented enhancements:**

- Update demo & readme [\#9](https://github.com/mob-sakai/UnmaskForUGUI/issues/9)

## [v0.1.0](https://github.com/mob-sakai/UnmaskForUGUI/tree/v0.1.0) (2018-10-14)

[Full Changelog](https://github.com/mob-sakai/UnmaskForUGUI/compare/987e437b26b83a78d6f54d6cc6778c3181e8e5dc...v0.1.0)

**Implemented enhancements:**

- Add demo [\#5](https://github.com/mob-sakai/UnmaskForUGUI/issues/5)
- Support nesting [\#4](https://github.com/mob-sakai/UnmaskForUGUI/issues/4)
- Following another object [\#3](https://github.com/mob-sakai/UnmaskForUGUI/issues/3)
- Ray through the unmasked rectangle [\#2](https://github.com/mob-sakai/UnmaskForUGUI/issues/2)
- Reverse mask [\#1](https://github.com/mob-sakai/UnmaskForUGUI/issues/1)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*
