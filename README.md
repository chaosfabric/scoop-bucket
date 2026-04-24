# chaosfabric Scoop bucket

Scoop manifests for tools maintained under the
[chaosfabric](https://github.com/chaosfabric) umbrella.

## Install

```powershell
scoop bucket add chaosfabric https://github.com/chaosfabric/scoop-bucket
scoop install <manifest>
```

### For example, brainyz:
```powershell
scoop bucket add chaosfabric https://github.com/chaosfabric/scoop-bucket
scoop install brainyz
```

## Manifests
|Manifest|Project|Platform|
|--------|-------|--------|
|brainyz|FavitoX/brainyz|Windows x64|

## Updates
Manifests are pushed automatically by each project's release workflow on stable tags; checkver + autoupdate act as a safety net for any gap.

## License
Manifests are Apache-2.0 (same as upstream).
