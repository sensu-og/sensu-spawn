# Change Log

## [Unreleased](https://github.com/sensu/sensu-spawn/tree/HEAD)

[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v2.4.1...HEAD)

**Merged pull requests:**

- Include stop error message in timeout output [\#25](https://github.com/sensu/sensu-spawn/pull/25) ([portertech](https://github.com/portertech))

## [v2.4.1](https://github.com/sensu/sensu-spawn/tree/v2.4.1) (2018-04-18)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v2.4.0...v2.4.1)

**Merged pull requests:**

- Pin FFI version on load \(as well as install\) [\#28](https://github.com/sensu/sensu-spawn/pull/28) ([portertech](https://github.com/portertech))

## [v2.4.0](https://github.com/sensu/sensu-spawn/tree/v2.4.0) (2018-04-18)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v2.3.0...v2.4.0)

**Merged pull requests:**

- Revert "Revert "Only enable posix spawn on x86\_64 and i386"" [\#27](https://github.com/sensu/sensu-spawn/pull/27) ([portertech](https://github.com/portertech))
- Pin FFI at 1.9.21, newer versions segfault on CentOS [\#26](https://github.com/sensu/sensu-spawn/pull/26) ([portertech](https://github.com/portertech))
- Revert "Only enable posix spawn on x86\_64 and i386" [\#24](https://github.com/sensu/sensu-spawn/pull/24) ([portertech](https://github.com/portertech))

## [v2.3.0](https://github.com/sensu/sensu-spawn/tree/v2.3.0) (2018-04-12)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v2.2.2...v2.3.0)

**Merged pull requests:**

- Only enable posix spawn on x86\_64 and i386 [\#23](https://github.com/sensu/sensu-spawn/pull/23) ([portertech](https://github.com/portertech))

## [v2.2.2](https://github.com/sensu/sensu-spawn/tree/v2.2.2) (2018-03-08)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v2.2.1...v2.2.2)

**Merged pull requests:**

- Sign the sensu-spawn Ruby gem [\#22](https://github.com/sensu/sensu-spawn/pull/22) ([portertech](https://github.com/portertech))
- Implement automated changelog generation [\#21](https://github.com/sensu/sensu-spawn/pull/21) ([cwjohnston](https://github.com/cwjohnston))

## [v2.2.1](https://github.com/sensu/sensu-spawn/tree/v2.2.1) (2016-09-12)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v2.2.0...v2.2.1)

**Merged pull requests:**

- Only include necessary gem files [\#19](https://github.com/sensu/sensu-spawn/pull/19) ([amdprophet](https://github.com/amdprophet))

## [v2.2.0](https://github.com/sensu/sensu-spawn/tree/v2.2.0) (2016-05-27)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v2.1.0...v2.2.0)

**Merged pull requests:**

- Fixed child process large STDIN writes [\#17](https://github.com/sensu/sensu-spawn/pull/17) ([portertech](https://github.com/portertech))

## [v2.1.0](https://github.com/sensu/sensu-spawn/tree/v2.1.0) (2016-05-26)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v2.0.0...v2.1.0)

**Closed issues:**

- Command with large output \( larger than STDOUT buffer\) times out if any timeout is set [\#14](https://github.com/sensu/sensu-spawn/issues/14)

**Merged pull requests:**

- Replace poll\_for\_exit with stdlib Timeout to fix large output deadlock [\#15](https://github.com/sensu/sensu-spawn/pull/15) ([tbriggs-curse](https://github.com/tbriggs-curse))

## [v2.0.0](https://github.com/sensu/sensu-spawn/tree/v2.0.0) (2016-05-17)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v1.8.0...v2.0.0)

**Merged pull requests:**

- Configurable spawn child process limit [\#16](https://github.com/sensu/sensu-spawn/pull/16) ([portertech](https://github.com/portertech))

## [v1.8.0](https://github.com/sensu/sensu-spawn/tree/v1.8.0) (2016-03-10)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v1.7.0...v1.8.0)

**Merged pull requests:**

- Moved FFI require into load error rescue block, fixing AIX build [\#13](https://github.com/sensu/sensu-spawn/pull/13) ([portertech](https://github.com/portertech))

## [v1.7.0](https://github.com/sensu/sensu-spawn/tree/v1.7.0) (2016-03-01)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v1.6.0...v1.7.0)

**Closed issues:**

- childprocess posix\_spawn does not support freebsd [\#9](https://github.com/sensu/sensu-spawn/issues/9)

**Merged pull requests:**

- Only enable POSIX Spawn for Linux & OS X [\#10](https://github.com/sensu/sensu-spawn/pull/10) ([portertech](https://github.com/portertech))

## [v1.6.0](https://github.com/sensu/sensu-spawn/tree/v1.6.0) (2015-11-13)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v1.5.0...v1.6.0)

**Merged pull requests:**

- Fix Windows job handle leak [\#8](https://github.com/sensu/sensu-spawn/pull/8) ([portertech](https://github.com/portertech))

## [v1.5.0](https://github.com/sensu/sensu-spawn/tree/v1.5.0) (2015-09-16)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v1.4.0...v1.5.0)

**Merged pull requests:**

- Remove sensu-em as a dependency, let Sensu core determine which em to use [\#7](https://github.com/sensu/sensu-spawn/pull/7) ([portertech](https://github.com/portertech))

## [v1.4.0](https://github.com/sensu/sensu-spawn/tree/v1.4.0) (2015-09-09)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v1.3.0...v1.4.0)

**Merged pull requests:**

- Use a mutex for childprocess posix spawn [\#6](https://github.com/sensu/sensu-spawn/pull/6) ([portertech](https://github.com/portertech))

## [v1.3.0](https://github.com/sensu/sensu-spawn/tree/v1.3.0) (2015-07-09)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v1.2.0...v1.3.0)

**Merged pull requests:**

- Bump childprocess to latest available \(0.5.6\) [\#5](https://github.com/sensu/sensu-spawn/pull/5) ([darix](https://github.com/darix))

## [v1.2.0](https://github.com/sensu/sensu-spawn/tree/v1.2.0) (2015-05-29)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v1.1.0...v1.2.0)

**Merged pull requests:**

- Require POSIX spawn libs immediately [\#4](https://github.com/sensu/sensu-spawn/pull/4) ([portertech](https://github.com/portertech))

## [v1.1.0](https://github.com/sensu/sensu-spawn/tree/v1.1.0) (2014-09-15)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v1.0.0...v1.1.0)

**Merged pull requests:**

- use a spec asset for testing output larger than 64KB \(ascii\) [\#3](https://github.com/sensu/sensu-spawn/pull/3) ([portertech](https://github.com/portertech))
- lock java-jars for travis-ci jruby build [\#2](https://github.com/sensu/sensu-spawn/pull/2) ([portertech](https://github.com/portertech))
- Parent should not wait for child before closing its write end of pipe [\#1](https://github.com/sensu/sensu-spawn/pull/1) ([nlim](https://github.com/nlim))

## [v1.0.0](https://github.com/sensu/sensu-spawn/tree/v1.0.0) (2014-06-12)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v0.0.3...v1.0.0)

## [v0.0.3](https://github.com/sensu/sensu-spawn/tree/v0.0.3) (2014-05-24)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v0.0.2...v0.0.3)

## [v0.0.2](https://github.com/sensu/sensu-spawn/tree/v0.0.2) (2014-05-24)
[Full Changelog](https://github.com/sensu/sensu-spawn/compare/v0.0.1...v0.0.2)

## [v0.0.1](https://github.com/sensu/sensu-spawn/tree/v0.0.1) (2014-05-19)


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*