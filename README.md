# Shennong Scoop Bucket

Custom [Scoop](https://scoop.sh) bucket for Windows applications.

## Add this bucket

```powershell
scoop bucket add shennong https://github.com/<owner>/shennong-bucket
```

Install an app after its manifest is added:

```powershell
scoop install shennong/<app>
```

## Add an app

Add a Scoop manifest as `bucket/<app>.json`. Each manifest describes an installable app and must use the app name as its filename.

See the [Scoop app manifest guide](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests) for supported fields and examples.

