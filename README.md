```
[95m1   : [0m[90;2m[0mdagger-organization
[95m2   : [0m[90;2m│ [0mconnect
[95m3   : [0m[90;2m│ │ [0mstarting engine
[95m4   : [0m[90;2m│ │ │ [0mcreate
[95m5   : [0m[90;2m│ │ │ │ [0mexec docker ps -a --no-trunc --filter name=^/dagger-engine- --format {{.Names}}
[95m5   : [0m[90;2m│ │ │ │ [0m[90m[0.1s] [0m[90m|[0m dagger-engine-v0.15.1
[95m5   : [0m[90;2m│ │ │ │ [0mexec docker ps -a --no-trunc --filter name=^/dagger-engine- --format {{.Names}}[32m DONE[0m[90m [0.1s][0m
[95m6   : [0m[90;2m│ │ │ │ [0mexec docker start dagger-engine-v0.15.1
[95m6   : [0m[90;2m│ │ │ │ [0m[90m[0.0s] [0m[90m|[0m dagger-engine-v0.15.1
[95m6   : [0m[90;2m│ │ │ │ [0mexec docker start dagger-engine-v0.15.1[32m DONE[0m[90m [0.0s][0m
[95m4   : [0m[90;2m│ │ │ [0mcreate[32m DONE[0m[90m [0.1s][0m
[95m3   : [0m[90;2m│ │ [0mstarting engine[32m DONE[0m[90m [0.1s][0m
[95m7   : [0m[90;2m│ │ [0mconnecting to engine
[95m7   : [0m[90;2m│ │ [0m[90m[0.2s] [0m[90m|[0m engine [2mname=[0mfb9ca13827e9 [2mversion=[0mv0.15.1 [2mclient=[0ml6rd4cb4b2zzqk0wslinreeqt
[95m7   : [0m[90;2m│ │ [0m[90m[0.2s] [0m[90m|[0m cloud [2murl=[0mhttps://dagger.cloud/dagger/traces/98b7a6f0c0be11cc74c41db41b51ca6d
[95m7   : [0m[90;2m│ │ [0mconnecting to engine[32m DONE[0m[90m [0.2s][0m
[95m8   : [0m[90;2m│ │ [0mstarting session
[95m8   : [0m[90;2m│ │ [0mstarting session[32m DONE[0m[90m [0.1s][0m

[95m9   : [0m[90;2m[0mconsuming /v1/traces

[95m1   : [0m[90;2m[0mdagger-organization
[95m2   : [0m[90;2m│ [0mconnect[32m DONE[0m[90m [0.5s][0m
[95m10  : [0m[90;2m│ [0mload module
[95m11  : [0m[90;2m│ │ [0mfinding module configuration

[95m9   : [0m[90;2m[0mconsuming /v1/traces[32m DONE[0m[90m [0.1s][0m

[95m12  : [0m[90;2m[0mconsuming /v1/logs
[95m12  : [0m[90;2m[0mconsuming /v1/logs[32m DONE[0m[90m [0.0s][0m

[95m13  : [0m[90;2m[0mconsuming /v1/metrics
[95m13  : [0m[90;2m[0mconsuming /v1/metrics[32m DONE[0m[90m [0.0s][0m

[95m1   : [0m[90;2m[0mdagger-organization
[95m10  : [0m[90;2m│ [0mload module
[95m14  : [0m[90;2m│ │ [0minitializing module

[95m15  : [0m[90;2m[0m[1mmoduleSource[0m([36mrefString:[0m [33m"."[0m)[2m: ModuleSource![0m
[95m15  : [0m[90;2m[0m[1mmoduleSource[0m[32m DONE[0m[90m [0.0s][0m

[95m16  : [0m[90;2m[0mModuleSource.[1mkind[0m[2m: ModuleSourceKind![0m
[95m16  : [0m[90;2m[0mModuleSource.[1mkind[0m[32m DONE[0m[90m [0.0s][0m

[95m17  : [0m[90;2m[0mModuleSource.[1mresolveContextPathFromCaller[0m[2m: String![0m
[95m17  : [0m[90;2m[0mModuleSource.[1mresolveContextPathFromCaller[0m[32m DONE[0m[90m [0.0s][0m

[95m18  : [0m[90;2m[0mModuleSource.[1mresolveFromCaller[0m[2m: ModuleSource![0m

[95m19  : [0m[90;2m[0moci-layout://dagger/import@sha256:a9094b30a283913a597639adf649cb179351feaf782eb90b52c3aaf9003a9686
[95m19  : [0m[90;2m[0moci-layout://dagger/import@sha256:a9094b30a283913a597639adf649cb179351feaf782eb90b52c3aaf9003a9686[32m DONE[0m[90m [0.0s][0m

[95m20  : [0m[90;2m[0minitialize dependencies
[95m20  : [0m[90;2m[0minitialize dependencies[32m DONE[0m[90m [0.0s][0m

[95m21  : [0m[90;2m[0mbuild module

[95m18  : [0m[90;2m[0mModuleSource.[1mresolveFromCaller[0m[2m: ModuleSource![0m
[95m22  : [0m[90;2m│ [0mupload /Users/jeremyadams/src/docs-github-ts from qhq2l5qub0za2y0v2llozndz4 (client id: l6rd4cb4b2zzqk0wslinreeqt, session id: s59gg427vnipqatveva8pbozh) (include: dagger.json, ./**/*) (exclude: **/.git)
[95m22  : [0m[90;2m│ [0mupload /Users/jeremyadams/src/docs-github-ts from qhq2l5qub0za2y0v2llozndz4 (client id: l6rd4cb4b2zzqk0wslinreeqt, session id: s59gg427vnipqatveva8pbozh) (include: dagger.json, ./**/*) (exclude: **/.git)[32m DONE[0m[90m [0.0s][0m
[95m18  : [0m[90;2m[0mModuleSource.[1mresolveFromCaller[0m[32m DONE[0m[90m [0.4s][0m

[95m21  : [0m[90;2m[0mbuild module[32m DONE[0m[90m [0.3s][0m

[95m23  : [0m[90;2m[0moci-layout://dagger/import@sha256:3f7f8e0063344ac9b21fecfe00ea3cc350d8170b54d73c9e424f336529fbd4c1
[95m23  : [0m[90;2m[0moci-layout://dagger/import@sha256:3f7f8e0063344ac9b21fecfe00ea3cc350d8170b54d73c9e424f336529fbd4c1[32m DONE[0m[90m [0.0s][0m

[95m24  : [0m[90;2m[0mModuleSource.[1masModule[0m[2m: Module![0m

[95m25  : [0m[90;2m[0minitialize dependencies
[95m25  : [0m[90;2m[0minitialize dependencies[32m DONE[0m[90m [0.0s][0m

[95m26  : [0m[90;2m[0mbuild module

[95m1   : [0m[90;2m[0mdagger-organization
[95m10  : [0m[90;2m│ [0mload module
[95m14  : [0m[90;2m│ │ [0minitializing module[32m DONE[0m[90m [0.6s][0m
[95m27  : [0m[90;2m│ │ [0minspecting module metadata
[95m27  : [0m[90;2m│ │ [0minspecting module metadata[32m DONE[0m[90m [0.1s][0m
[95m28  : [0m[90;2m│ │ [0mloading type definitions

[95m24  : [0m[90;2m[0mModuleSource.[1masModule[0m[32m DONE[0m[90m [0.2s][0m

[95m26  : [0m[90;2m[0mbuild module[32m DONE[0m[90m [0.2s][0m

[95m29  : [0m[90;2m[0mModule.[1minitialize[0m[2m: Module![0m
[95m30  : [0m[90;2m│ [0mModule.[1mwithObject[0m(
[95m30  : [0m[90;2m│ │ │ [0m[36mobject:[0m TypeDef.[1mwithFunction[0m(
[95m30  : [0m[90;2m│ │ │ │ [0m[36mfunction:[0m Function.[1mwithDescription[0m([36mdescription:[0m [33m""[0m)[2m: Function![0m
[95m30  : [0m[90;2m│ │ │ [0m)[2m: TypeDef![0m
[95m30  : [0m[90;2m│ │ [0m)[2m: Module![0m
[95m31  : [0m[90;2m│ │ [0mTypeDef.[1mwithObject[0m([36mdescription:[0m [33m""[0m, [36mname:[0m [33m"Github"[0m)[2m: TypeDef![0m
[95m31  : [0m[90;2m│ │ [0mTypeDef.[1mwithObject[0m[32m DONE[0m[90m [0.0s][0m
[95m32  : [0m[90;2m│ │ [0mTypeDef.[1mwithFunction[0m(
[95m32  : [0m[90;2m│ │ │ │ [0m[36mfunction:[0m Function.[1mwithDescription[0m([36mdescription:[0m [33m""[0m)[2m: Function![0m
[95m32  : [0m[90;2m│ │ │ [0m)[2m: TypeDef![0m
[95m33  : [0m[90;2m│ │ [0m[1mfunction[0m(
[95m33  : [0m[90;2m│ │ │ │ [0m[36mname:[0m [33m"daggerOrganization"[0m
[95m33  : [0m[90;2m│ │ │ │ [0m[36mreturnType:[0m TypeDef.[1mwithObject[0m([36mname:[0m [33m"Organization"[0m)[2m: TypeDef![0m
[95m33  : [0m[90;2m│ │ │ [0m)[2m: Function![0m
[95m34  : [0m[90;2m│ │ [0mTypeDef.[1mwithObject[0m([36mname:[0m [33m"Organization"[0m)[2m: TypeDef![0m
[95m34  : [0m[90;2m│ │ [0mTypeDef.[1mwithObject[0m[32m DONE[0m[90m [0.0s][0m
[95m33  : [0m[90;2m│ │ [0m[1mfunction[0m[32m DONE[0m[90m [0.0s][0m
[95m35  : [0m[90;2m│ │ [0mFunction.[1mwithDescription[0m([36mdescription:[0m [33m""[0m)[2m: Function![0m
[95m35  : [0m[90;2m│ │ [0mFunction.[1mwithDescription[0m[32m DONE[0m[90m [0.0s][0m
[95m32  : [0m[90;2m│ │ [0mTypeDef.[1mwithFunction[0m[32m DONE[0m[90m [0.0s][0m
[95m30  : [0m[90;2m│ [0mModule.[1mwithObject[0m[32m DONE[0m[90m [0.0s][0m
[95m36  : [0m[90;2m│ [0mModule.[1mwithObject[0m(
[95m36  : [0m[90;2m│ │ │ [0m[36mobject:[0m TypeDef.[1mwithField[0m(
[95m36  : [0m[90;2m│ │ │ │ [0m[36mdescription:[0m [33m""[0m
[95m36  : [0m[90;2m│ │ │ │ [0m[36mname:[0m [33m"members"[0m
[95m36  : [0m[90;2m│ │ │ │ [0m[36mtypeDef:[0m TypeDef.[1mwithListOf[0m(
[95m36  : [0m[90;2m│ │ │ │ │ [0m[36melementType:[0m TypeDef.[1mwithObject[0m([36mname:[0m [33m"Account"[0m)[2m: TypeDef![0m
[95m36  : [0m[90;2m│ │ │ │ [0m)[2m: TypeDef![0m
[95m36  : [0m[90;2m│ │ │ [0m)[2m: TypeDef![0m
[95m36  : [0m[90;2m│ │ [0m)[2m: Module![0m
[95m37  : [0m[90;2m│ │ [0mTypeDef.[1mwithObject[0m([36mdescription:[0m [33m"Organization has no specific methods, only exposed fields so\nwe can define it with `type` instead of `class` to\navoid the boilerplate of defining a constructor."[0m, [36mname:[0m [33m"Organization"[0m)[2m: TypeDef![0m
[95m37  : [0m[90;2m│ │ [0mTypeDef.[1mwithObject[0m[32m DONE[0m[90m [0.0s][0m
[95m38  : [0m[90;2m│ │ [0mTypeDef.[1mwithField[0m(
[95m38  : [0m[90;2m│ │ │ │ [0m[36mdescription:[0m [33m""[0m
[95m38  : [0m[90;2m│ │ │ │ [0m[36mname:[0m [33m"url"[0m
[95m38  : [0m[90;2m│ │ │ │ [0m[36mtypeDef:[0m TypeDef.[1mwithKind[0m([36mkind:[0m [33mSTRING_KIND[0m)[2m: TypeDef![0m
[95m38  : [0m[90;2m│ │ │ [0m)[2m: TypeDef![0m
[95m38  : [0m[90;2m│ │ [0mTypeDef.[1mwithField[0m[32m DONE[0m[90m [0.0s][0m
[95m39  : [0m[90;2m│ │ [0mTypeDef.[1mwithField[0m(
[95m39  : [0m[90;2m│ │ │ │ [0m[36mdescription:[0m [33m""[0m
[95m39  : [0m[90;2m│ │ │ │ [0m[36mname:[0m [33m"repositories"[0m
[95m39  : [0m[90;2m│ │ │ │ [0m[36mtypeDef:[0m TypeDef.[1mwithListOf[0m(
[95m39  : [0m[90;2m│ │ │ │ │ [0m[36melementType:[0m TypeDef.[1mwithObject[0m([36mname:[0m [33m"GitRepository"[0m)[2m: TypeDef![0m
[95m39  : [0m[90;2m│ │ │ │ [0m)[2m: TypeDef![0m
[95m39  : [0m[90;2m│ │ │ [0m)[2m: TypeDef![0m
[95m40  : [0m[90;2m│ │ [0mTypeDef.[1mwithListOf[0m(
[95m40  : [0m[90;2m│ │ │ │ [0m[36melementType:[0m TypeDef.[1mwithObject[0m([36mname:[0m [33m"GitRepository"[0m)[2m: TypeDef![0m
[95m40  : [0m[90;2m│ │ │ [0m)[2m: TypeDef![0m
[95m41  : [0m[90;2m│ │ [0mTypeDef.[1mwithObject[0m([36mname:[0m [33m"GitRepository"[0m)[2m: TypeDef![0m
[95m41  : [0m[90;2m│ │ [0mTypeDef.[1mwithObject[0m[32m DONE[0m[90m [0.0s][0m
[95m40  : [0m[90;2m│ │ [0mTypeDef.[1mwithListOf[0m[32m DONE[0m[90m [0.0s][0m
[95m39  : [0m[90;2m│ │ [0mTypeDef.[1mwithField[0m[32m DONE[0m[90m [0.0s][0m
[95m42  : [0m[90;2m│ │ [0mTypeDef.[1mwithField[0m(
[95m42  : [0m[90;2m│ │ │ │ [0m[36mdescription:[0m [33m""[0m
[95m42  : [0m[90;2m│ │ │ │ [0m[36mname:[0m [33m"members"[0m
[95m42  : [0m[90;2m│ │ │ │ [0m[36mtypeDef:[0m TypeDef.[1mwithListOf[0m(
[95m42  : [0m[90;2m│ │ │ │ │ [0m[36melementType:[0m TypeDef.[1mwithObject[0m([36mname:[0m [33m"Account"[0m)[2m: TypeDef![0m
[95m42  : [0m[90;2m│ │ │ │ [0m)[2m: TypeDef![0m
[95m42  : [0m[90;2m│ │ │ [0m)[2m: TypeDef![0m
[95m43  : [0m[90;2m│ │ [0mTypeDef.[1mwithListOf[0m(
[95m43  : [0m[90;2m│ │ │ │ [0m[36melementType:[0m TypeDef.[1mwithObject[0m([36mname:[0m [33m"Account"[0m)[2m: TypeDef![0m
[95m43  : [0m[90;2m│ │ │ [0m)[2m: TypeDef![0m
[95m44  : [0m[90;2m│ │ [0mTypeDef.[1mwithObject[0m([36mname:[0m [33m"Account"[0m)[2m: TypeDef![0m
[95m44  : [0m[90;2m│ │ [0mTypeDef.[1mwithObject[0m[32m DONE[0m[90m [0.0s][0m
[95m43  : [0m[90;2m│ │ [0mTypeDef.[1mwithListOf[0m[32m DONE[0m[90m [0.0s][0m
[95m42  : [0m[90;2m│ │ [0mTypeDef.[1mwithField[0m[32m DONE[0m[90m [0.0s][0m
[95m36  : [0m[90;2m│ [0mModule.[1mwithObject[0m[32m DONE[0m[90m [0.0s][0m
[95m45  : [0m[90;2m│ [0mModule.[1mwithObject[0m(
[95m45  : [0m[90;2m│ │ │ [0m[36mobject:[0m TypeDef.[1mwithConstructor[0m(
[95m45  : [0m[90;2m│ │ │ │ [0m[36mfunction:[0m Function.[1mwithArg[0m(
[95m45  : [0m[90;2m│ │ │ │ │ [0m[36mdescription:[0m [33m""[0m
[95m45  : [0m[90;2m│ │ │ │ │ [0m[36mname:[0m [33m"email"[0m
[95m45  : [0m[90;2m│ │ │ │ │ [0m[36mtypeDef:[0m TypeDef.[1mwithKind[0m([36mkind:[0m [33mSTRING_KIND[0m)[2m: TypeDef![0m
[95m45  : [0m[90;2m│ │ │ │ [0m)[2m: Function![0m
[95m45  : [0m[90;2m│ │ │ [0m)[2m: TypeDef![0m
[95m45  : [0m[90;2m│ │ [0m)[2m: Module![0m
[95m46  : [0m[90;2m│ │ [0mTypeDef.[1mwithObject[0m([36mdescription:[0m [33m""[0m, [36mname:[0m [33m"Account"[0m)[2m: TypeDef![0m
[95m46  : [0m[90;2m│ │ [0mTypeDef.[1mwithObject[0m[32m DONE[0m[90m [0.0s][0m
[95m47  : [0m[90;2m│ │ [0mTypeDef.[1mwithFunction[0m(
[95m47  : [0m[90;2m│ │ │ │ [0m[36mfunction:[0m Function.[1mwithDescription[0m([36mdescription:[0m [33m""[0m)[2m: Function![0m
[95m47  : [0m[90;2m│ │ │ [0m)[2m: TypeDef![0m
[95m48  : [0m[90;2m│ │ [0m[1mfunction[0m(
[95m48  : [0m[90;2m│ │ │ │ [0m[36mname:[0m [33m"url"[0m
[95m48  : [0m[90;2m│ │ │ │ [0m[36mreturnType:[0m TypeDef.[1mwithKind[0m([36mkind:[0m [33mSTRING_KIND[0m)[2m: TypeDef![0m
[95m48  : [0m[90;2m│ │ │ [0m)[2m: Function![0m
[95m48  : [0m[90;2m│ │ [0m[1mfunction[0m[32m DONE[0m[90m [0.0s][0m
[95m49  : [0m[90;2m│ │ [0mFunction.[1mwithDescription[0m([36mdescription:[0m [33m""[0m)[2m: Function![0m
[95m49  : [0m[90;2m│ │ [0mFunction.[1mwithDescription[0m[32m DONE[0m[90m [0.0s][0m
[95m47  : [0m[90;2m│ │ [0mTypeDef.[1mwithFunction[0m[32m DONE[0m[90m [0.0s][0m
[95m50  : [0m[90;2m│ │ [0mTypeDef.[1mwithField[0m(
[95m50  : [0m[90;2m│ │ │ │ [0m[36mdescription:[0m [33m""[0m
[95m50  : [0m[90;2m│ │ │ │ [0m[36mname:[0m [33m"username"[0m
[95m50  : [0m[90;2m│ │ │ │ [0m[36mtypeDef:[0m TypeDef.[1mwithKind[0m([36mkind:[0m [33mSTRING_KIND[0m)[2m: TypeDef![0m
[95m50  : [0m[90;2m│ │ │ [0m)[2m: TypeDef![0m
[95m50  : [0m[90;2m│ │ [0mTypeDef.[1mwithField[0m[32m DONE[0m[90m [0.0s][0m
[95m51  : [0m[90;2m│ │ [0mTypeDef.[1mwithField[0m(
[95m51  : [0m[90;2m│ │ │ │ [0m[36mdescription:[0m [33m""[0m
[95m51  : [0m[90;2m│ │ │ │ [0m[36mname:[0m [33m"email"[0m
[95m51  : [0m[90;2m│ │ │ │ [0m[36mtypeDef:[0m TypeDef.[1mwithKind[0m([36mkind:[0m [33mSTRING_KIND[0m)[2m: TypeDef![0m
[95m51  : [0m[90;2m│ │ │ [0m)[2m: TypeDef![0m
[95m51  : [0m[90;2m│ │ [0mTypeDef.[1mwithField[0m[32m DONE[0m[90m [0.0s][0m
[95m52  : [0m[90;2m│ │ [0mTypeDef.[1mwithConstructor[0m(
[95m52  : [0m[90;2m│ │ │ │ [0m[36mfunction:[0m Function.[1mwithArg[0m(
[95m52  : [0m[90;2m│ │ │ │ │ [0m[36mdescription:[0m [33m""[0m
[95m52  : [0m[90;2m│ │ │ │ │ [0m[36mname:[0m [33m"email"[0m
[95m52  : [0m[90;2m│ │ │ │ │ [0m[36mtypeDef:[0m TypeDef.[1mwithKind[0m([36mkind:[0m [33mSTRING_KIND[0m)[2m: TypeDef![0m
[95m52  : [0m[90;2m│ │ │ │ [0m)[2m: Function![0m
[95m52  : [0m[90;2m│ │ │ [0m)[2m: TypeDef![0m
[95m53  : [0m[90;2m│ │ [0m[1mfunction[0m(
[95m53  : [0m[90;2m│ │ │ │ [0m[36mname:[0m [33m""[0m
[95m53  : [0m[90;2m│ │ │ │ [0m[36mreturnType:[0m TypeDef.[1mwithField[0m(
[95m53  : [0m[90;2m│ │ │ │ │ [0m[36mdescription:[0m [33m""[0m
[95m53  : [0m[90;2m│ │ │ │ │ [0m[36mname:[0m [33m"email"[0m
[95m53  : [0m[90;2m│ │ │ │ │ [0m[36mtypeDef:[0m TypeDef.[1mwithKind[0m([36mkind:[0m [33mSTRING_KIND[0m)[2m: TypeDef![0m
[95m53  : [0m[90;2m│ │ │ │ [0m)[2m: TypeDef![0m
[95m53  : [0m[90;2m│ │ │ [0m)[2m: Function![0m
[95m53  : [0m[90;2m│ │ [0m[1mfunction[0m[32m DONE[0m[90m [0.0s][0m
[95m54  : [0m[90;2m│ │ [0mFunction.[1mwithArg[0m(
[95m54  : [0m[90;2m│ │ │ │ [0m[36mdescription:[0m [33m""[0m
[95m54  : [0m[90;2m│ │ │ │ [0m[36mname:[0m [33m"username"[0m
[95m54  : [0m[90;2m│ │ │ │ [0m[36mtypeDef:[0m TypeDef.[1mwithKind[0m([36mkind:[0m [33mSTRING_KIND[0m)[2m: TypeDef![0m
[95m54  : [0m[90;2m│ │ │ [0m)[2m: Function![0m
[95m54  : [0m[90;2m│ │ [0mFunction.[1mwithArg[0m[32m DONE[0m[90m [0.0s][0m
[95m55  : [0m[90;2m│ │ [0mFunction.[1mwithArg[0m(
[95m55  : [0m[90;2m│ │ │ │ [0m[36mdescription:[0m [33m""[0m
[95m55  : [0m[90;2m│ │ │ │ [0m[36mname:[0m [33m"email"[0m
[95m55  : [0m[90;2m│ │ │ │ [0m[36mtypeDef:[0m TypeDef.[1mwithKind[0m([36mkind:[0m [33mSTRING_KIND[0m)[2m: TypeDef![0m
[95m55  : [0m[90;2m│ │ │ [0m)[2m: Function![0m
[95m55  : [0m[90;2m│ │ [0mFunction.[1mwithArg[0m[32m DONE[0m[90m [0.0s][0m
[95m52  : [0m[90;2m│ │ [0mTypeDef.[1mwithConstructor[0m[32m DONE[0m[90m [0.0s][0m
[95m45  : [0m[90;2m│ [0mModule.[1mwithObject[0m[32m DONE[0m[90m [0.0s][0m
[95m29  : [0m[90;2m[0mModule.[1minitialize[0m[32m DONE[0m[90m [0.0s][0m

[95m56  : [0m[90;2m[0mModule.[1mserve[0m[2m: Void[0m
[95m56  : [0m[90;2m[0mModule.[1mserve[0m[32m DONE[0m[90m [0.0s][0m

[95m57  : [0m[90;2m[0mModuleSource.[1mresolveFromCaller[0m[2m: ModuleSource![0m
[95m57  : [0m[90;2m[0mModuleSource.[1mresolveFromCaller[0m[32m DONE[0m[90m [0.0s][0m

[95m58  : [0m[90;2m[0mModuleSource.[1masString[0m[2m: String![0m
[95m58  : [0m[90;2m[0mModuleSource.[1masString[0m[32m DONE[0m[90m [0.0s][0m

[95m59  : [0m[90;2m[0mModule.[1mname[0m[2m: String![0m
[95m59  : [0m[90;2m[0mModule.[1mname[0m[32m DONE[0m[90m [0.0s][0m

[95m60  : [0m[90;2m[0mModule.[1mdependencies[0m[2m: [Module!]![0m
[95m60  : [0m[90;2m[0mModule.[1mdependencies[0m[32m DONE[0m[90m [0.0s][0m

[95m61  : [0m[90;2m[0mModule.[1mdescription[0m[2m: String![0m
[95m61  : [0m[90;2m[0mModule.[1mdescription[0m[32m DONE[0m[90m [0.0s][0m

[95m1   : [0m[90;2m[0mdagger-organization
[95m10  : [0m[90;2m│ [0mload module
[95m11  : [0m[90;2m│ │ [0mfinding module configuration[32m DONE[0m[90m [1.1s][0m
[95m28  : [0m[90;2m│ │ [0mloading type definitions[32m DONE[0m[90m [0.1s][0m
[95m10  : [0m[90;2m│ [0mload module[32m DONE[0m[90m [1.1s][0m
[95m62  : [0m[90;2m│ [0mparsing command line arguments
[95m62  : [0m[90;2m│ [0mparsing command line arguments[32m DONE[0m[90m [0.0s][0m
[95m63  : [0m[90;2m│ [0m[1mgithub[0m[2m: Github![0m
[95m63  : [0m[90;2m│ [0m[1mgithub[0m[32m DONE[0m[90m [0.0s][0m
[95m64  : [0m[90;2m│ [0m[35mGithub[0m.[1mdaggerOrganization[0m[2m: GithubOrganization![0m
[95m64  : [0m[90;2m│ [0m[90m[2.7s] [0m[90m|[0m could not find module entrypoint: class Github from import. Class should be exported to benefit from all features.
[95m64  : [0m[90;2m│ [0m[90m[2.7s] [0m[90m|[0m missing export in class Github at /src/src/index.ts:32:0 but it's used by the module.
[95m64  : [0m[90;2m│ [0m[90m[2.7s] [0m[90m|[0m missing export in class Account at /src/src/index.ts:2:0 but it's used by the module.
[95m1   : [0m[90;2m[0mdagger-organization
[95m1   : [0m[90;2m[0m[90m[4.5s] [0m[90m|[0m Error: input: github.daggerOrganization failed to collect IDs: failed to convert field "repositories": expected string, got map[string]interface {}
[95m1   : [0m[90;2m[0m[90m[4.5s] [0m[90m|[0m 
[95m64  : [0m[90;2m│ [0m[35mGithub[0m.[1mdaggerOrganization[0m[33m ERROR[0m[90m [2.8s][0m
[95m64  : [0m[90;2m│ [0m[33m! failed to collect IDs: failed to convert field "repositories": expected string, got map[string]interface {}[0m
[95m1   : [0m[90;2m[0mdagger-organization[33m ERROR[0m[90m [4.5s][0m
[95m1   : [0m[90;2m[0m[33m! exit code 1[0m


[1mFull trace at [0mhttps://dagger.cloud/dagger/traces/98b7a6f0c0be11cc74c41db41b51ca6d


Error: input: github.daggerOrganization failed to collect IDs: failed to convert field "repositories": expected string, got map[string]interface {}
```
