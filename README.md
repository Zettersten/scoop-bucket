# Shnapp Scoop bucket

This is the owner-maintained [Scoop](https://scoop.sh) bucket for [Shnapp](https://shhnap.com), a Windows screenshot capture and annotation app.

The first manifest will be published here after Shnapp v1.0.0 and its portable ZIP checksums are publicly available.

Once published, install it with:

```powershell
scoop bucket add shnapp https://github.com/Zettersten/scoop-bucket
scoop install shnapp/shnapp
```

Update an installed copy with `scoop update shnapp`. Scoop checks this bucket for a committed manifest update; a new GitHub release alone does not update an existing installation.

The [Excavator workflow](https://github.com/Zettersten/scoop-bucket/actions/workflows/excavator.yml) checks stable GitHub releases every four hours. Review each generated update and its SHA-256 checksum before relying on a new version. Report Shnapp bugs or feature requests in the [application repository](https://github.com/Zettersten/shhnap/issues).
