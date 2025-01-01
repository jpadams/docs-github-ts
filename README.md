```
Error logs:

✘ .daggerOrganization: GithubOrganization! 2.7s
could not find module entrypoint: class Github from import. Class should be exported to benefit fr
 all features.
missing export in class Github at /src/src/index.ts:32:0 but it's used by the module.
missing export in class Account at /src/src/index.ts:2:0 but it's used by the module.
! failed to collect IDs: failed to convert field "repositories": expected string, got map[string]interface {}

Full trace at https://dagger.cloud/dagger/traces/75df68b392655e44b27b424e1341f3a4
```
