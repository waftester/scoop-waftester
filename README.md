# Scoop Bucket for WAFtester

[![Latest Version](https://img.shields.io/github/v/release/waftester/waftester?label=version)](https://github.com/waftester/waftester/releases/latest)

Official [Scoop](https://scoop.sh) bucket for [WAFtester](https://waftester.com) — the WAF security testing CLI.

Detect which WAF protects a target, benchmark its rule coverage across OWASP categories, and test bypass techniques — all from a single binary.

## Install

```powershell
scoop bucket add waftester https://github.com/waftester/scoop-waftester
scoop install waftester
```

## Upgrade

```powershell
scoop update waftester
```

## Platforms

| OS      | Architecture |
|---------|-------------|
| Windows | x86_64, arm64 |

## How updates work

This manifest is automatically updated by [GoReleaser](https://goreleaser.com) when a new version of WAFtester is released. No manual maintenance required.

The manifest also includes Scoop's built-in `checkver` and `autoupdate` fields for independent verification.

## Links

- [Website](https://waftester.com)
- [Documentation](https://waftester.com/docs)
- [Main Repository](https://github.com/waftester/waftester)
- [Changelog](https://github.com/waftester/waftester/blob/main/CHANGELOG.md)

## License

WAFtester is licensed under [BSL 1.1](https://github.com/waftester/waftester/blob/main/LICENSE). Community payloads are [MIT](https://github.com/waftester/waftester/blob/main/LICENSE-COMMUNITY).
